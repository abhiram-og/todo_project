ToDo Web App

A modern, "Domain Expansion" themed ToDo list application built with Django and customized with a premium dark aesthetic. Feel your cursed energy grow as you check off tasks!

## Features
- **Add & Manage Tasks**: Simple, fast workflow to add, edit, and delete ToDo items.
- **Glassmorphism UI**: Beautiful, frosted-glass containers that blur the background dynamically.
- **Jujutsu Kaisen Theme**:
  - Deep Purple and Crimson Red "cursed energy" gradients.
  - Floating dark energy background shapes.
  - Custom background image integration.
- **Smooth Animations**: Micro-interactions on buttons, hover elements, and task state changes.
- **Responsive Design**: Adapts gracefully to all screen sizes.

## Tech Stack
- **Backend**: Python, Django 6.0
- **Frontend**: HTML5, Modern CSS (Variables, Flexbox, Animations), Phosphor Icons
- **Database**: SQLite3

## Prerequisites
- Python 3.10+
- Django 6.0+

## Local Setup

1. **Activate the Virtual Environment**
Ensure you are in the project root directory (`ToDo webapp`) and activate the environment:
```bash
# Windows
.\venv\Scripts\activate
```

2. **Navigate into the project folder**
```bash
cd todo_project
```

3. **Run Database Migrations** (For first-time setup)
```bash
python manage.py makemigrations
python manage.py migrate
```

4. **Start the Development Server**
```bash
python manage.py runserver
```

5. **View the Application**  
Open your web browser and navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Customization

### Background Image
To swap out the background image for a different character or scene, replace the existing image located at:
`todo_project/static/images/bg.png`
(Ensure your new file is named exactly `bg.png`!)

### Color Theme
If you wish to adjust the core "Cursed Energy" colors, edit the CSS Variables located in the `:root` pseudo-class at the top of:
`todo_project/static/css/style.css`

---
_A stylish, cursed way to stay organized._
