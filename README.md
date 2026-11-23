# Online Examination Website

A clean, responsive, single-page Online Examination portal built using semantic HTML5 and CSS3 (Flexbox). This project is designed for a first-year college Web Development Activity assignment.

---

## 🔗 Live Demo
Live Demo: <paste link here>

---

## 📖 Description
This project simulates an online examination interface for college students. It provides a structured test environment featuring an exam header, student information details, examination instructions, a countdown timer display, a 5-question multiple choice test, an interactive question navigator palette, and an exam submission section.

---

## ✨ Features
- **Semantic HTML5 Structure**: Uses proper semantic tags such as `<header>`, `<main>`, `<section>`, `<aside>`, `<form>`, `<fieldset>`, `<legend>`, and `<footer>`.
- **Student Details Card**: Displays student name, roll number, branch, exam date, and duration.
- **Rules & Instructions**: Clearly lists 6 exam guidelines.
- **Timer Display**: Displays an exam countdown timer badge (`Time Left: 30:00`).
  > **Note on Timer:** The timer is currently **display-only** using HTML and CSS. A functional countdown timer can be implemented in future iterations by integrating JavaScript.
- **5 Multiple-Choice Questions (MCQs)**: Formatted with standard `<fieldset>`, `<legend>`, `<input type="radio">`, and `<label>` pairs. Only one radio option can be chosen per question.
- **Question Navigation Palette**: A side panel listing buttons Q1 to Q5 built with Flexbox. Clicking any question number instantly scrolls the page to that specific question.
- **Submission Area**: Features a review reminder notice and a distinct "Submit Exam" button wrapped in a `<form>`.
- **Responsive Design**: Designed with CSS Flexbox and includes a `@media (max-width: 768px)` breakpoint to smoothly stack the question palette beneath the questions on mobile screens.
- **Clean Academic Theme**: Styled with a professional color palette, hover effects, and comfortable padding/spacing.

---

## 🛠️ Technologies Used
- **HTML5**: For semantic page structure and form inputs.
- **CSS3 (Flexbox only)**: For layout, styling, spacing, color scheme, and responsiveness.
- **GitHub Pages**: For free static website hosting.

---

## 📁 Project Structure
```text
online-exam-website/
├── index.html   # Main webpage with all exam sections and semantic tags
├── style.css    # External stylesheet (Reset, Layout, Components, Responsive)
└── README.md    # Project documentation and deployment guide
```

---

## 🚀 Step-by-Step GitHub Pages Deployment Guide

Follow these simple steps to deploy your website online for free:

### Step 1: Create a GitHub Repository
1. Log in to [GitHub](https://github.com).
2. Click the **+** (plus) icon in the top-right corner and select **New repository**.
3. Name your repository (e.g., `online-exam-website`).
4. Ensure the repository visibility is set to **Public**.
5. Do not check "Add a README file" if you already have this folder ready.
6. Click **Create repository**.

### Step 2: Upload Project Files
1. On your newly created repository page, click the **uploading an existing file** link.
2. Drag and drop all 3 files (`index.html`, `style.css`, and `README.md`) into the upload area.
3. In the "Commit changes" box at the bottom, type: `Initial commit: Online exam portal`.
4. Click **Commit changes**.

### Step 3: Enable GitHub Pages
1. In your GitHub repository, click on the **Settings** tab (gear icon at the top menu).
2. On the left sidebar menu under the "Code and automation" section, click **Pages**.
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` (or `master`) from the dropdown.
   - **Folder**: Ensure `/ (root)` is selected.
4. Click **Save**.

### Step 4: Access and Test Your Live Site
1. Wait 1 to 2 minutes for GitHub to build and publish your site.
2. Refresh the **Pages** settings screen. You will see a banner:
   > *"Your site is live at `https://<your-username>.github.io/<repository-name>/`"*
3. Click the link to view your live website!
4. Copy that URL and paste it into the `Live Demo: <paste link here>` section in your `README.md`.
