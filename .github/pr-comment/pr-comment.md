# 🌈 Simple Markdown Playground

Click, expand and explore! 👇

---

## 🎨 Coloured Text

$\color{red}{\textsf{Red}}$ · $\color{orange}{\textsf{Orange}}$ · $\color{gold}{\textsf{Yellow}}$ · $\color{limegreen}{\textsf{Green}}$ · $\color{deepskyblue}{\textsf{Blue}}$ · $\color{blueviolet}{\textsf{Purple}}$ · $\color{hotpink}{\textsf{Pink}}$

---

## 🚦 Coloured Alerts

> [!NOTE]
> 🔵 Useful information.

> [!TIP]
> 🟢 A helpful tip.

> [!WARNING]
> 🟡 Pay attention to this.

> [!CAUTION]
> 🔴 Risky, be careful.

---

## 🟥🟩 Red / Green Lines

```diff
- 🔴 Removed line
+ 🟢 Added line
! 🟠 Highlighted line
```

---

## 🖱️ Click to Expand

<details>
<summary>🔴 What is GitHub Actions?</summary>

<br>

An automation tool built into GitHub that runs jobs when events happen, like a push or a pull request. 🤖

</details>

<details>
<summary>🟡 What is <code>uses:</code>?</summary>

<br>

It runs a ready-made action:

```yaml
- uses: actions/checkout@v4
```

</details>

<details>
<summary>🟢 What is <code>run:</code>?</summary>

<br>

It runs a shell command:

```yaml
- run: echo "Hello!"
```

</details>

---

## 🧠 Quick Quiz

**Which keyword decides *when* a workflow runs?**

<details>
<summary>👉 Show answer</summary>

✅ `on:`

</details>

---

## ✅ Checklist

- [ ] 🔴 Create a repository
- [ ] 🟠 Add a workflow file
- [ ] 🟡 Trigger it with a push
- [ ] 🟢 Use `uses:` and `run:`
- [ ] 🔵 Check the Actions tab

---

## 📊 Colour Table

| Colour | Meaning |
|:---:|:---|
| 🔴 | Failed |
| 🟡 | Running |
| 🟢 | Success |
| 🟣 | Merged |

---

🎉 Keep learning! 🔴 🟠 🟡 🟢 🔵 🟣