
# 📝 ToDo List Web App

A simple, fast, and responsive **ToDo list** app built with **HTML**, **CSS**, and **JavaScript** – with **no frameworks**!  
Tasks are stored in your browser using `localStorage` for seamless offline access.

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Built with JavaScript](https://img.shields.io/badge/Built%20with-JavaScript-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Live Demo](https://img.shields.io/badge/Demo-Open%20index.html%20in%20browser-brightgreen)](#live-demo)

---

## 🚀 Features

- [x] Add tasks with due dates  
- [x] Delete tasks individually  
- [x] Data persists using `localStorage`  
- [x] Clean, dark UI  
- [ ] Edit tasks *(coming soon)*  
- [ ] Mark tasks as completed *(coming soon)*

---

## 📸 Preview

<details>
  <summary>Click to expand screenshot</summary>

  ![screenshot](https://via.placeholder.com/800x400?text=ToDo+List+Preview)

</details>

---

## 📂 Project Structure

```
📁 todo-list/
├── index.html      # Main file containing HTML, CSS & JS
└── README.md       # You’re reading it!
```

---

## 💻 Live Demo

> 💡 Open the file directly in your browser:
```bash
# Simply open the file
double-click index.html
```

Or drag and drop `index.html` into your browser window.

---

## 🧪 Sample Code Usage

```html
<input placeholder="enter task" class="taskInput" />
<input type="date" class="dueDateInput" />
<button onclick="addToDo()">add</button>
```

```js
toDoList.push({
  task: task,
  dueDate: dueDate,
});
localStorage.setItem('toDoList', JSON.stringify(toDoList));
```

---

## 📅 Future Enhancements

- [ ] ✅ Task completion toggle
- [ ] 🔄 Sort tasks by due date
- [ ] 📱 Responsive mobile UI
- [ ] 🔁 Sync with cloud/local backup

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

### 🔗 Connect

Let me know if you'd like your social links (LinkedIn/GitHub/Portfolio) added here!
