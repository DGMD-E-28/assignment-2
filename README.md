# Tic Tac Toe - Part 1

## Assignment Overview
This project is the first part of building a **Tic Tac Toe** game as a web application using **HTML, CSS, and JavaScript**. The assignment focuses on creating the visual structure of the board and preparing it for interactive functionality in the next phase.

## Requirements
You may use the following technologies:
- **HTML** for structure
- **CSS** for styling
- **JavaScript** for board generation and initial placement of marks
- **jQuery is allowed**

### 🚨 Ground Rules
- **Do not look up solutions online.** Use techniques covered in class.
- **Host the project online.** You may use any platform for deployment.
- **Enhancements are welcome,** but first, meet the basic requirements.

---

## 📌 Tasks
### 🔹 Version 1: `ttt1.html` [ttt1.html](https://bizzyk.github.io/DGMD-E-28-assignment-2/ttt1.html)
- Create a **3×3 Tic Tac Toe board** using **HTML and CSS**.
- Each square should be a `<div>` element.
- **Hardcode** two `X` and one `O` in different squares to test positioning.
- Add a **hover effect** to highlight squares when the mouse is over them.
- Use an **internal CSS style sheet**.
- **Save the file as** `ttt1.html`.

### 🔹 Version 2: `ttt2.html` [ttt2.html](https://bizzyk.github.io/DGMD-E-28-assignment-2/ttt2.html)
- Recreate the board using **JavaScript** instead of static HTML.
- Use the following JavaScript code (cannot be modified) to generate the squares:

  ```js
  const NUM_SQUARES = 9;
  for (let i = 0; i < NUM_SQUARES; i++) {
      let id = "sq" + i;
      document.write("<div class='square' id='" + id + "'></div>");
  }
  ```
- Add a **title** above the board.
- Add a `<div>` to indicate whose turn it is (X or O) with a visible border.
- Add another `<div>` section to **display a win condition** (to be used in the next phase).
- Use **JavaScript to place two X's and one O** in the same positions as in `ttt1.html`.
- **Save the file as** `ttt2.html`.

---

## 🚀 Deliverables
- **Files to submit:** `ttt1.html` and `ttt2.html`
- **Live Deployment URL** (host your project online and provide the link)
- **Answer the question:** Identify an area of CSS where you feel confident and explain why.

---

## 📌 Rubric
| Criteria | Points |
|----------|--------|
| Creativity & Effort | 20 |
| Meets Requirements | 50 |
| Overall Quality & Technical Proficiency | 30 |
| **Total** | **100** |

---

## 🔗 Useful Resources
- [How JavaScript works](https://computer.howstuffworks.com/javascript.htm)
- [JavaScript beginner tutorial](https://htmldog.com/guides/javascript/beginner/)
- [Javascript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Happy Coding! 🎉
