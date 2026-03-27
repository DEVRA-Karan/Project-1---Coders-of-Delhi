🚀 CodeBook: The Social Media Data Science Project
Welcome to your Data Science Internship at CodeBook! 🇮🇳 Based in Delhi, this platform is the go-to network for developers. Your mission is to move from a raw data dump to a fully functional recommendation engine using Pure Python (no Pandas, no NumPy—just logic!).

📊 Project Overview
You are tasked with handling the "CodeBook" backend data. The system revolves around two main entities:

Users 👤: Each has a unique ID, name, list of friends, and liked pages.

Pages 📄: Specialized hubs like "Python Developers" or "AI & ML Community".

The goal is to prove your skills and land that ₹10 LPA job by completing four critical milestones.

🛠️ Key Milestones
1. Data Ingestion & Exploration 🔍
The journey starts with raw JSON. You built a robust loader to peek into the data structure.

Tooling: Used the built-in json module to parse files.

Functionality: Created a structured display to map out user IDs against their specific connections.

2. Data Cleaning & Sanitization 🧹
Raw data is often "messy." You implemented a pipeline to ensure high data integrity:

Name Validation: Automatically strips whitespace and removes users with missing names.

Deduplication: Uses Python set() logic to clean up duplicate friend entries.

Activity Filter: Removes "ghost" users who have zero friends and zero liked pages.

Page Integrity: Ensures every Page ID in the system is unique.

3. "People You May Know" Algorithm 🤝
This is the heart of social growth! You built a recommendation engine based on Mutual Connections.

The Logic: It scans your friends' lists to find people you aren't connected with yet.

Ranking: Suggestions are prioritized based on the highest number of mutual friends.

4. Smart Page Recommendations 💡
To keep users engaged, you developed an interest-based suggestion system.

Shared Interests: The algorithm finds "look-alike" users who like the same pages as you.

Scoring: It suggests new pages based on a similarity score—calculated by the overlap in your liked pages.

📈 The Workflow
Load 📥: Import the massive_data.json file.

Clean 🧼: Run the sanitization script to fix errors.

Analyze 🧪: Apply collaborative filtering logic.

Recommend ✨: Output the top suggested friends and pages.

🚀 How to Use
Since we are sticking to the basics, no heavy installations are required!

Environment: Python 3.12+.

Execution: Run the notebooks in sequence (01 through 04) to see the data transform from a messy dictionary into a powerful recommendation tool.
