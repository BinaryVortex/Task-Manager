# Task-Manager (TaskBuddy)

A lightweight, responsive Task Manager built with plain HTML, CSS and JavaScript. Add tasks to your "My Day", mark them as complete (with a satisfying sound and animation), delete tasks, and switch the app theme color.

![App screenshot](./Screenshot%202024-09-13%20091336.png)

## Demo
Open `index.html` in any modern browser to try the app locally.

## Features
- Add tasks with a single press of Enter
- Mark tasks complete with animation and a completion sound
- Delete tasks
- Choose from multiple theme colors
- App info modal with version and author credit
- Responsive layout that works on mobile and desktop

Note: Tasks are stored only in the current page session (no persistence across reloads).

## Files
- `index.html` — app structure and markup
- `style.css` — styling and responsive rules
- `script.js` — app behaviour (add, complete, delete tasks, theme switching)
- `calender-image.svg` — welcome illustration
- `task-complete.mp3` — completion sound
- `Screenshot 2024-09-13 091336.png` — screenshot used above

## Usage
1. Clone the repository:

   git clone https://github.com/BinaryVortex/Task-Manager.git

2. Open `index.html` in your browser:

   - Double-click the file, or
   - Serve it from a static server (recommended for best results):
     - Python 3: `python -m http.server 8000`
     - Node (http-server): `npx http-server`

3. Start typing a task and press Enter to add it.

## Customization
- Change theme: open the menu (ellipsis) in the header and pick a color.
- Change the title text by editing the header in `index.html`.

## Contributing
Contributions, suggestions and improvements are welcome. If you'd like to:
- Open an issue for bugs or feature requests
- Fork the repo, make changes, and submit a pull request

Please keep changes small and provide a short description of what you changed.

## Author & Credits
- Repository owner: BinaryVortex
- App originally created by Disandu Perera (credited inside the app info modal in `index.html`)

## License
This repository does not contain a license file. If you want to share or reuse the code, consider adding a license (for example, the MIT License) by adding a `LICENSE` file.

---

If you want, I can also:
- Add a short demo GIF
- Improve accessibility (keyboard navigation / ARIA)
- Add task persistence using localStorage
- Add a project license file (MIT)
