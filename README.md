# KSketch

I developed a side project called KSketch to enhance my skills. It’s an Excalidraw clone built with React and TypeScript, featuring a sketchy, hand-drawn style using Rough.js.

## 📦 Technologies Used
- Vite
- React.js
- TypeScript
- Vitest
- Cypress
- Testing Library
- Rough.js
- CSS

## 🦄 Features
KSketch offers a variety of tools and functionalities:

- **Choose a Tool:** Select from pencils, lines, rectangles, and text tools to start creating.
- **Draw and Move:** Click and drag on the canvas to draw. Move elements by selecting and dragging them. Resize elements by dragging the corners (applicable to rectangles and lines only).
- **Edit Text:** Click on the canvas to add text and edit existing text.
- **Zoom:** Use Ctrl + Scroll or zoom buttons to zoom in or out.
- **Pan:** Hold the Space bar and drag, or use the middle mouse button to navigate around the canvas.

## 🎯 Keyboard Shortcuts
Enhance productivity with these shortcuts:

- **Canvas Navigation:** Hold the Space bar and drag or use the middle mouse button.
- **Undo:** Ctrl + Z.
- **Redo:** Ctrl + Y or Ctrl + Shift + Z.
- **Zoom In:** Ctrl + Plus.
- **Zoom Out:** Ctrl + Minus.

## 📚 Lessons Learned
This project enhanced my skills and understanding in several areas:

- **useHistory Hook:** Improved logical thinking through managing actions like saving, undoing, and redoing.
- **Coordinates and Measurements:** Gained precision in working with shapes and points, enhancing my math skills.
- **Discovering Rough.js:** Explored a new tool that creates hand-drawn graphics.
- **Deep Dive into Functions:** Understood complex functions like `getSvgPathFromStroke`, which smooths drawing movements.
- **Managing Points and Drawing:** Learned to manage and use points from drawings.
- **React Hooks and Rendering:** Gained knowledge about `useLayoutEffect` for handling screen updates before rendering changes.
- **Advanced Event Handling:** Worked with the wheel event listener for zooming and panning features, enhancing user interaction.

## 🚦 Running the Project
To run the project locally:

1. Clone the repository to your local machine.
2. Run `npm install` or `yarn` in the project directory to install dependencies.
3. Run `npm run start` or `yarn start` to start the project.
4. Open [http://localhost:5173](http://localhost:5173) (or the address shown in your console) in your web browser to view the app.
