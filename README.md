This project is a simple UiPath automation that checks whether a person is eligible to vote based on their age. It uses basic decision-making logic to determine eligibility, making it a great beginner-friendly project to understand how UiPath handles input, conditions, and user interaction.

🎯 Features
Takes age input from the user.

Verifies if the person is eligible to vote (age ≥ 18).

Displays an appropriate message:

✅ "You are eligible to vote."

❌ "You are not eligible to vote."

🔧 Prerequisites
UiPath Studio (Community or Enterprise Edition)

Basic understanding of sequences and flowcharts in UiPath

🛠️ How It Works
Input Dialog: Prompts the user to enter their age.

If Activity: Checks if the entered age is greater than or equal to 18.

Message Box:

If eligible: Shows a success message.

If not eligible: Shows a warning message.

🚀 How to Run
Open UiPath Studio.

Clone or download this repository.

Open the project .xaml file in UiPath.

Run the workflow.

Enter your age when prompted and view the result.

📚 Concepts Used
Input Dialog

If/Else Condition

Message Box

Integer Parsing and Validation

📦 Use Cases
Demonstrating basic RPA concepts to beginners.

Training module for age-based automation.

Can be extended to more complex eligibility checks (e.g., nationality, registration status).

✅ Output Examples
Input: 22 → Output: "You are eligible to vote."

Input: 16 → Output: "You are not eligible to vote."

