# User Registration Form

## 📌 Project Description
This project is a **User Registration Form** built using **semantic HTML5**.  
The form demonstrates best practices in structuring inputs, accessibility, validation, and user interaction.  
It collects personal details, contact information, preferences, and feedback from users in a structured and user-friendly manner.

---

## 🎯 Purpose of the Form
The purpose of this form is to:
- Collect user **personal details** (name, age, date of birth, gender, profile photo).
- Capture **contact and address information** (email, phone, country, city, ZIP code).
- Understand user **preferences and interests** (colors, hobbies, education, experience level).
- Allow users to provide **feedback and suggestions**.
- Ensure **account security** with a password + confirmation.
- Provide **submission actions** (`Register` and `Clear Form`).

---

## 📂 File Structure

---

## ⚙️ Implementation Notes
- **HTML5 Semantic Structure**: Used `<fieldset>`, `<legend>`, `<label>`, and proper input types for accessibility.  
- **Validation**:  
  - Name fields accept only letters, 2–30 characters.  
  - Date of birth ensures the user is at least 18 years old.  
  - Phone number requires a **10-digit format**.  
  - Password requires **8–20 characters**, including uppercase, lowercase, and a number.  
- **Unique IDs**: Each input has a unique `id` for proper label association.  
- **Accessibility**: ARIA attributes (`aria-required`, `aria-describedby`) used for improved screen reader support.  
- **Form Controls**:  
  - `type="reset"` clears the form.  
  - `type="submit"` submits the form.  

---

## 🚀 How to Use / View the Form
1. Clone or download the repository:
   ```bash
   git clone <your-repo-url>
