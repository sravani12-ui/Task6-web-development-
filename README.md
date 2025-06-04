

✅ Task 6 - Form Handling & Validation

📌 Objective

Implement a basic HTML form with JavaScript validation that ensures user input is correct before allowing submission. No data is actually sent — this task focuses purely on validation and user feedback.


🎯 Goals & Outcomes

✅ Learn how to handle form inputs

✅ Validate input fields using JavaScript

✅ Use regular expressions (regex) for email format validation

✅ Prevent form submission if validation fails

✅ Show real-time error and success messages

✅ Test and handle edge cases like empty inputs and invalid emails





🛠️ Technologies Used

HTML

CSS (optional for styling)

JavaScript



📂 File Structure

task6-form-validation/
├── index.html      # Main HTML form with embedded JS
└── README.md       # Documentation (this file)




🔍 Validation Rules

Field	Validation

Name	Required (non-empty)
Email	Required and must match regex


🧪 Edge Cases to Test

1. Empty name and email – should show required field errors


2. Invalid email (e.g., user@, @gmail.com) – should show format error


3. Special characters in name – allowed unless restricted


4. Valid inputs – shows success message, clears the form





🧾 Example Test Case: Sravani

Field	Input

Name	Sravani
Email	n190121@rguktn.ac.in


✅ Result: Form submits successfully and shows a success message.
![IMG_20250604_105526](https://github.com/user-attachments/assets/808aff84-a34f-4c87-b8a3-c529549ff02d)
![IMG_20250604_105518](https://github.com/user-attachments/assets/e7b18bda-93b4-4406-a86b-3b05b66222af)
![Screenshot_2025-06-04-10-54-28-07_e3c1f266f17b29c7b40472751f031275](https://github.com/user-attachments/assets/1b511bfe-ac65-4666-831b-18ff70b92f4e)




📋 How to Run

1. Open index.html in a web browser.


2. Fill out the form.


3. Click Submit.


4. Observe validation messages below inputs.


5. On success, see a green confirmation message.

🚫 No External Libraries Used

Everything is done using vanilla JavaScript, making this a great learning example for beginners.

