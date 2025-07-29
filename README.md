# TodoFlow

A beautiful, modern todo application built with React, TypeScript, and Tailwind CSS. TodoFlow combines elegant design with powerful functionality to help you organize your tasks efficiently.

![TodoFlow Screenshot](https://images.pexels.com/photos/3727464/pexels-photo-3727464.jpeg?auto=compress&cs=tinysrgb&w=1200&h=600&fit=crop)

## ✨ Features

- **Intuitive Task Management**: Add, edit, delete, and mark tasks as complete with smooth animations
- **Smart Filtering**: View all tasks, only active tasks, or completed tasks
- **Persistent Storage**: Your todos are automatically saved to local storage
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Keyboard Shortcuts**: 
  - `Enter` to add a new todo
  - `Enter` to save edits
  - `Escape` to cancel editing
- **Bulk Actions**: Clear all completed tasks at once
- **Visual Feedback**: Hover states, transitions, and micro-interactions
- **Accessibility**: Screen reader friendly with proper ARIA labels

## 🚀 Demo

You can see TodoFlow in action by running it locally or deploying it to your favorite hosting platform.

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/todoflow.git
   cd todoflow
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the app running.

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom animations
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Development**: ESLint for code quality
- **Storage**: Browser localStorage for data persistence

## 📱 Usage

### Adding Tasks
1. Type your task in the input field at the top
2. Press `Enter` or click the "Add" button
3. Your task will appear in the list below

### Managing Tasks
- **Complete**: Click the circle next to a task to mark it as complete
- **Edit**: Click the edit icon (pencil) to modify a task
- **Delete**: Click the trash icon to remove a task permanently

### Filtering Tasks
Use the filter buttons to view:
- **All**: Show all tasks
- **Active**: Show only incomplete tasks
- **Completed**: Show only completed tasks

### Bulk Actions
- **Clear Completed**: Remove all completed tasks at once using the "Clear completed" button

## 🎨 Design Features

- **Glass-morphism Effects**: Modern translucent design elements
- **Gradient Backgrounds**: Beautiful color transitions
- **Micro-interactions**: Smooth hover states and animations
- **Typography**: Clean, readable fonts with proper hierarchy
- **Color System**: Consistent color palette with semantic meanings
- **Responsive Layout**: Optimized for all screen sizes

## 🏗️ Project Structure

```
src/
├── components/
│   └── TodoApp.tsx         # Main todo application component
├── App.tsx                 # Root application component
├── main.tsx               # Application entry point
├── index.css              # Global styles and Tailwind imports
└── vite-env.d.ts          # Vite type definitions
```

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## 🚀 Deployment

### Netlify
1. Build the project: `npm run build`
2. Upload the `dist` folder to Netlify
3. Your app is live!

### Vercel
1. Connect your repository to Vercel
2. Vercel will automatically detect it's a Vite project
3. Deploy with one click

### GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json:
   ```json
   "homepage": "https://yourusername.github.io/todoflow",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Run: `npm run deploy`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

### Code Style
- Use TypeScript for type safety
- Follow the existing code style (ESLint configured)
- Add comments for complex logic
- Keep components focused and reusable

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons provided by [Lucide React](https://lucide.dev/)
- Styling powered by [Tailwind CSS](https://tailwindcss.com/)
- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)

## 📞 Support

If you have any questions or need help, please:
1. Check the [Issues](https://github.com/your-username/todoflow/issues) page
2. Create a new issue if your problem isn't already addressed
3. Provide as much detail as possible in your issue report

---

**Made with ❤️ and React**