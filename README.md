# Web Technologies — Practical Test (Starter)

**State University of Zanzibar (SUZA) · School of Computing, Communication and Media Studies**
**Course:** Web Technologies — BSc Computer Science / BITAM
**Lecturer:** Masoud Hamad
**Covers:** Lecture 4 (HTML & CSS Basics) and Lecture 5 (CSS Layout)

This is the **single starter project** that every student forks for the practical test.
Each student is assigned **one question** (Q001–Q120) from the document **`QUESTIONS.docx`**
distributed by the lecturer.

---

## 📁 What's inside

```
web-tech-practical-test-starter/
├── README.md          ← this file
├── index.html         ← starter HTML — edit this with your solution
├── styles.css         ← starter CSS — edit this with your solution
├── assets/
│   └── images/        ← shared images you may use (or upload your own)
│       ├── logo.svg
│       ├── banner.svg
│       ├── hero.svg
│       ├── profile.svg
│       ├── product.svg
│       └── placeholder.svg
└── .gitignore
```

---

## 🚀 Workflow (each student does this once)

### 1. Fork this repository

On GitHub, click the **Fork** button (top right) on the lecturer's repo:
`https://github.com/<lecturer-username>/web-tech-practical-test-starter`

This creates **your own copy** under your GitHub account.

### 2. Clone YOUR fork to your computer

```bash
git clone https://github.com/<your-username>/web-tech-practical-test-starter.git
cd web-tech-practical-test-starter
```

### 3. Identify your assigned question

Open the file **`QUESTIONS.docx`** (provided separately by the lecturer)
and find the row matching your **registration number / student ID**.
Copy your question title and full task description.

### 4. Fill in your identity

Edit the top comments inside `index.html` AND `styles.css` and replace
`[YOUR NAME]`, `[YOUR REG NO]`, `Q[XXX]`, and the task statement with
your assigned question's details.

### 5. Build your solution

Edit `index.html` and `styles.css` ONLY. Build the UI component described
in your question.

**Mandatory for every solution:**

- ✅ Valid semantic HTML5
- ✅ All styling in `styles.css` (no inline styles, no `<style>` tags)
- ✅ Use **Flexbox or CSS Grid** for layout
- ✅ At least **2 images** (use `assets/images/` or your own under that folder)
- ✅ At least **2 working links** (internal or external)
- ✅ Hover effects on interactive elements
- ✅ Looks fine on mobile (at least one `@media` query)
- ❌ No JavaScript

### 6. Test in your browser

Open `index.html` directly (or use Live Server in VS Code). Check the
console — there must be no errors. Check on mobile width (DevTools).

### 7. Commit and push to YOUR fork

```bash
git add .
git commit -m "Qxxx: <Your Name> — <Question Title>"
git push origin main
```

### 8. Submit on GitHub Classroom

Submit the URL of your forked repository in the assignment submission
form on Moodle / GitHub Classroom **before the deadline**.

The lecturer's autograder will:

1. Pull your repo,
2. Validate HTML,
3. Check that your file contains your name, reg no, and question number,
4. Confirm presence of images and links,
5. Run a Lighthouse pass for basic accessibility.

---

## 📋 Marking rubric (10 marks total)

| Criterion | Marks |
|---|---|
| Valid HTML5 (no validator errors) | 2 |
| Question task correctly addressed | 4 |
| At least 2 images, present and rendering | 1 |
| At least 2 working links | 1 |
| Clean CSS in external stylesheet, Flexbox/Grid used | 2 |
| **Total** | **10** |

---

## ⚠️ Academic integrity

- This is an **individual** practical test.
- Each student has a **different question** — no copy-paste between students.
- Plagiarism (including copying from past years or AI tools without disclosure)
  will be detected and result in zero marks.

---

## 🆘 Help

- HTML reference: https://developer.mozilla.org/en-US/docs/Web/HTML
- CSS reference: https://developer.mozilla.org/en-US/docs/Web/CSS
- Course site: https://massoudhamad.github.io/web-technologies/index.html

Good luck!
