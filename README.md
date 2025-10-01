# Task 6: Contact Form with Validation

## 🎯 Objective
Build a simple **Contact Form** with client-side validation for Name, Email, and Message using HTML, CSS, and JavaScript.

---

## 🛠 Tools Used
- **VS Code** (to write the code)
- **Chrome Browser** (to test)
- **HTML + CSS + JavaScript** (technologies)

---

## 📋 Features
✅ Form fields: Name, Email, Message  
✅ Inline error messages if input is invalid  
✅ Regex validation for email format  
✅ Prevents form submission if invalid  
✅ Shows success message on valid submission  
✅ Clears form after successful submission  

---

## 🚀 How to Run
1. Open **VS Code**.
2. Create a file named `index.html`.
3. Copy the code from this repo into `index.html`.
4. Open `index.html` in your **Chrome browser**.
5. Try submitting the form.

---

## 🧪 Testing (Edge Cases)
- Leave fields empty → should show error messages.
- Enter invalid email (e.g., `abc@xyz`, `abc.com`) → error appears.
- Enter special characters in name → still works (no restriction).
- Enter valid details (e.g., Name = "John", Email = "john@gmail.com", Message = "Hello") → shows **success message**.

---

## 📸 Example Behavior
- **Empty form** → shows red error messages.
- **Invalid email** → "Enter a valid email."
- **Valid form** → "Form submitted successfully!" in green.

---

## ✅ Deliverables
- `index.html` file with form, CSS, and JavaScript validation.
- `README.md` (this file) explaining setup, usage, and testing.
