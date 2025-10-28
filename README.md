# Guess My Number!

A simple interactive **JavaScript DOM project** that demonstrates how to manipulate and update the DOM dynamically.  
Built as part of my practice to strengthen **core JavaScript concepts** like event handling, DOM selection, state updates, and UI feedback.

---

##  **Live Demo**
🕹️ [Play it on GitHub Pages](https://bosubose132.github.io/Guess-my-number-js/)

---

##  **About the Project**
This project is a small browser-based game where the player has to guess a hidden number between **1 and 20**.  
Each wrong guess decreases the score, and the UI updates in real-time to reflect the player’s progress.

The main purpose of this project is to **apply and demonstrate DOM concepts** in a clean, structured way — not to use frameworks or libraries.

---

##  **Concepts & JavaScript Features Used**

| Concept | Description |
|----------|--------------|
| **DOM Selection & Manipulation** | Used `document.querySelector()` to select and update HTML elements dynamically (messages, score, number). |
| **Event Handling** | Added click events (`.check` button) and keyboard events (`Enter` key) using `addEventListener()`. |
| **Dynamic Styling** | Modified CSS properties via JS (`.style.width`, `.classList.add('win')`) for visual feedback. |
| **State Management** | Managed `score`, `highscore`, and `secretNumber` variables to control game flow. |
| **Conditional Logic** | Used `if/else` statements to handle win/loss and hint messages (“Too high!”, “Too low!”). |
| **Reset Functionality** | Implemented `.again` button to fully reset the game state and UI. |
| **Responsive & Accessible UI** | Designed using semantic HTML and keyboard interactions (Enter key support). |

---

##  **Core Files**
| File | Description |
|------|--------------|
| `index.html` | Main structure and layout of the game |
| `style.css` | UI styling, layout, animations, and responsive design |
| `script.js` | Game logic, DOM interactions, event listeners, and UI updates |

---

##  **Gameplay Summary**
- Enter a number between **1–20** and click **Check!** or press **Enter**.  
- The app updates the message:  
  - “Too high!”  
  - “Too low!”  
  - “Correct Number!” (glows green )  
- The **score** decreases with each wrong guess.  
- Click **Play Again** to reset and start a new round.

---

## ⚙️ **Tech Used**
- **HTML5** – structure  
- **CSS3** – layout, styling, and animations  
- **Vanilla JavaScript (ES6)** – DOM manipulation, events, and game logic  

---

## 🎓 **Learning Outcome**
This project strengthened my understanding of:
- DOM tree traversal and element manipulation  
- Event-driven programming  
- UI state synchronization using JavaScript variables  
- Clean separation between logic (JS) and presentation (CSS)

---

##  **Author**
**Bosu Bose**  
📍 Fort Wayne, Indiana, USA  
🔗 [GitHub](https://github.com/bosuBose132)

---
