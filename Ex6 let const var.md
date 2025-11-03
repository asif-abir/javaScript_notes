# 🧠 JavaScript Variables

Variable মানে হলো কোনো ডাটা স্টোর করার জায়গা।

---

## 🔹 তিন ধরনের Variable
1. `var` – পুরনো, function scoped  
2. `let` – আধুনিক, block scoped  
3. `const` – constant value, পরিবর্তন করা যায় না  

---

### 🧩 উদাহরণ:
```js
var name = "Asif";
let age = 22;
const country = "Bangladesh";

console.log(name, age, country);



---

## 📘 functions.md

```markdown
# ⚙️ JavaScript Functions

Function হলো নির্দিষ্ট কাজের জন্য লেখা পুনঃব্যবহারযোগ্য কোড ব্লক।

---

### 🧩 উদাহরণ:
```js
function greet(user) {
  return `Hello, ${user}!`;
}

console.log(greet("Asif"));
