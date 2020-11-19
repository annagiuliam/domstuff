# domstuff

# example of usage

# addNewListener

this function makes you add a new listener to an element in your DOM.

```js
addNewListener("#edit-btn", "click", function () {
  editTask(task, taskTitle);
});
```

# createDomEle

```js
createDomEle(
  `#${taskTitle}`,
  "div",
  { class: ["class-1", "class-2"], id: "id" }, // id or any attribute
  "this is the text content of the div"
);
```
