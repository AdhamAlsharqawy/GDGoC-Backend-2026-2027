# Task 03 – HTML Form Questions

## 1. What is the difference between `placeholder` and `value`?

| | `placeholder` | `value` |
|---|---|---|
| Purpose | Hint text that shows the user what to type | Actual data of the input |
| Disappears? | Yes, once the user starts typing | No, it stays until the user changes it |
| Submitted with the form? | No | Yes |
| Example | `<input placeholder="Enter your name">` | `<input value="Ahmed">` |

## 2. What is the purpose of the `required` attribute?

The `required` attribute makes a field **mandatory**. The browser will not submit the form until the user fills it in, and it shows a validation message if the field is empty.

```html
<input type="text" name="username" required>
```

## 3. What is the difference between `radio` and `checkbox`?

| | `radio` | `checkbox` |
|---|---|---|
| Selection | Only **one** option from a group | **One or more** options |
| Grouping | Options must share the same `name` | Can have the same or different `name` |
| Use case | Gender, payment method | Skills, hobbies, terms agreement |
| Can be unselected by clicking again? | No | Yes |
