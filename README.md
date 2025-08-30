Codemate -An Ai powered DSA Practice Environment

An interactive web-based environment to practice Data Structures & Algorithms (DSA) problems in Python, Java, and C++.
It comes with a built-in code editor, timer, test case evaluator, hints, and AI-powered feedback system.

🚀 Features

🎯 Difficulty Levels – Choose between Easy, Medium, and Hard challenges.

💻 Multi-language Support – Solve problems in Python, Java, or C++ with preloaded templates.

✍️ Code Editor – Integrated with CodeMirror
 for syntax highlighting and a smooth coding experience.

✅ Automatic Test Cases – Each problem comes with predefined test cases to validate your solution.

⏱️ Countdown Timer – Encourages time-bound problem solving.

💡 Hints & Feedback –

Get cryptic hints related to the problem.

Receive periodic AI-powered feedback on your code.

Get success feedback with time complexity suggestions once all test cases pass.

⚡ Code Execution – Uses Judge0 API
 to compile and run code across multiple languages.

🤝 AI Assistance (Optional) – Connects to a local Ollama
 server for generating hints and solution feedback.

📂 Project Structure
├── codemate.html   # Main application (UI + logic + API calls)
├── questions.js    # DSA problems categorized into Easy, Medium, Hard

🛠️ Setup Instructions
1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2. Open in Browser

Simply open codemate.html in your browser to start solving problems.

⚙️ Dependencies

The project relies on:

Frontend Libraries

Bootstrap 5
 – UI styling

CodeMirror
 – Code editor

APIs

Judge0
 – Online compiler & execution environment

Ollama
 (optional) – For AI hints & feedback

🔑 Configuration

Judge0 API Key: Replace the placeholder key inside codemate.html:

"X-RapidAPI-Key": "YOUR_API_KEY"


You can get a free key from RapidAPI Judge0
.

Ollama Model (optional):
Ensure you have an Ollama server running locally:

OLLAMA_ORIGINS=* ollama serve


You can change the model in codemate.html:

const OLLAMA_MODEL = "gemma3:1b"; // or "codellama"

📘 Usage

Select a difficulty level (Easy/Medium/Hard).

Read the problem statement & example test cases.

Write your code in Python, Java, or C++.

Run your code → outputs & test results will be displayed.

Use Get Clue or wait for feedback if stuck.

If all test cases pass → you’ll receive success feedback with potential optimizations.

🎯 Example Problems

Easy: Two Sum, Palindrome Number, Merge Two Sorted Lists

Medium: Longest Substring Without Repeating Characters, 3Sum, Coin Change

Hard: Trapping Rain Water, Median of Two Sorted Arrays, N-Queens

(See questions.js for the full list of problems.)
