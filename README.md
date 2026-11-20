# Todo List

A clean, responsive todo list that runs entirely in the browser. Tasks are saved automatically in `localStorage`, so they remain available after a refresh.

## Features

- Add and delete tasks
- Mark tasks as active or completed
- Filter by All, Active, or Completed
- Clear all completed tasks
- Persist tasks locally in the browser
- Responsive layout for desktop and mobile

## Run locally

Open `index.html` directly in a browser, or start a small local server:

```bash
# From the repository root
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

- `index.html` - page structure and todo template
- `styles.css` - responsive visual design
- `script.js` - task interactions and browser storage
