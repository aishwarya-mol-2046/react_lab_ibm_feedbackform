# 📝 Feedback Form Lab

## 🌟 Overview
This lab demonstrates how to create a **React functional component** for collecting user feedback. It focuses on **form handling, state management, and form submission** using React Hooks.

The component `FeedbackForm` allows users to:

- 🧑 Enter their **name**  
- 📧 Enter their **email**  
- ✏️ Provide **text feedback**  
- ⭐ Give a **rating** from 1 to 5  

---

## ⚡ Features

- ✅ **Controlled Inputs** – All form fields are controlled using `useState`.  
- 🔄 **Dynamic State Updates** – The `handleChange` function updates form data in real time.  
- 💬 **Form Confirmation** – On submission, a confirmation dialog displays the entered information.  
- 🧹 **Reset on Submit** – After submission, the form resets to empty fields.  
- 🖥 **Console Logging** – Feedback data is logged in the console for testing purposes.  

---

## 🏗 Component Structure

- **`formData` state** – Stores all input values (`name`, `email`, `feedback`, `rating`).  
- **`handleChange` function** – Updates state when a user types or selects a rating.  
- **`handleSubmit` function** – Prevents default submission, shows confirmation, logs data, and resets the form.  
- **Radio Buttons for Rating** – Allows users to rate between 1–5.  

---


## 🖼 Example Preview

Tell Us What You Think
---------------------

We'd Love to Hear From You!
Please share your feedback with us.

[Name Input]
[Email Input]
[Feedback Textarea]

Rate Us: (1 2 3 4 5)

[Submit Feedback Button]

## 💻 Tech Stack
React (Functional Components + Hooks)

JavaScript ES6+

CSS for styling (FeedbackForm.css)

---

## Live Site
site-url : https://aishwarya-mol-2046.github.io/react_lab_ibm_feedbackform/
