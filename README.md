# ✅ Todo App

A sleek, modern to-do list application with a beautiful dark theme UI, progress tracking, and confetti celebrations when all tasks are completed.

<https://i.imgur.com/ISEywzF.gif>

## 🚀 Features

- **Clean, Modern UI** with a dark theme and subtle gradients
- **Task Management**
  - Add new tasks
  - Mark tasks as complete/incomplete
  - Edit existing tasks
  - Delete tasks
- **Progress Tracking** with a visual progress bar
- **Persistent Storage** using localStorage to save your tasks between sessions
- **Celebration Animation** with confetti when all tasks are completed
- **Fully Responsive** design that works on all device sizes

## 📋 Usage

1. Enter a task in the input field
2. Click the "+" button or press Enter to add the task
3. Check the checkbox to mark a task as complete
4. Click the edit icon to modify a task
5. Click the bin icon to delete a task
6. Watch the progress bar and counter update as you complete tasks
7. Complete all tasks to see a confetti celebration!

## 🔧 Technology Stack

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript
- LocalStorage API for data persistence
- [tsParticles Confetti](https://github.com/tsparticles/tsparticles) for celebration animations

## 💻 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo-app
   ```

3. Open `index.html` in your browser:
   ```bash
   open index.html
   ```

## 🎨 Customization

The app uses CSS variables that can be easily customized in the `styles.css` file:

```css
:root {
    --background: #000430;
    --secondaryBackground: #171c48;
    --text: #fff;
    --purple: #828dff;
    --teal: #24feee;
}
```

Change these values to create your own color scheme!

## 🔄 How It Works

The application uses vanilla JavaScript to:
- Manage a task array with task objects containing text and completion status
- Save and retrieve tasks from localStorage
- Update the UI dynamically as tasks are added, edited, completed, or deleted
- Calculate completion percentage to update the progress bar
- Trigger a confetti animation when all tasks are completed

## 📱 Browser Compatibility

- Chrome
- Firefox
- Safari
- Edge
- Opera

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Confetti animation powered by [tsParticles](https://particles.js.org/)
