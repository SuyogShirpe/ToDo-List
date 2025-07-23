
# 📝 ToDo List Web App

A simple, fast, and responsive **ToDo list** app built with **HTML**, **CSS**, and **JavaScript** – with **no frameworks**!  
Tasks are stored in your browser using `localStorage` for seamless offline access.


---

## 🚀 Features

- [x] Add tasks with due dates  
- [x] Delete tasks individually  
- [x] Data persists using `localStorage`  
- [x] Clean, light UI  
- [ ] Edit tasks *(coming soon)*  
- [ ] Mark tasks as completed *(coming soon)*

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
<button onclick="addToDo()" class="addBtn">add</button>
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


## 🙋‍♂️ Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---


