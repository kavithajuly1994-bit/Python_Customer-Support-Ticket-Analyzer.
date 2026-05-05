📘 Python_Customer-Support-Ticket-Analyzer.
To analyze customer support data and extract meaningful insights that help improve service quality, response time, and customer satisfaction

📌 Project Overview
* Built a Python-based Ticket Analysis System to store, clean, and analyze customer support tickets.
* Implemented data cleaning, keyword analysis, and priority insights to identify common issues and
improve service quality.

🎯 Project Objective
* To analyze customer support data and extract meaningful insights that help improve service quality,
response time, and customer satisfaction.

🗂️ Dataset
The data set is organized in a structured format (dictionary/tabular form) with the following fields:
* Ticket_No: unique identifier assigned to each support ticket.
* Customer_Name: The name of the customer who raised the issue.
* Issue_Description: A textual description of the problem reported by the customer. This field contains
unstructured text data, which is later cleaned and analyzed.
* Priority: Ticket priority categorized as: (High/Medium/Low)
  
🛠️ Tools & Technologies Used
* Python - Core programming and logic implementation
* Built-in Libraries - String methods (.lower(), .replace(), .split(), .strip()) for text processing
* Google Colab
  
🧹 Data Cleaning Process
* Converted all issue descriptions to lowercase for consistency
* Replaced informal words (e.g., "ok" → "okay") for standardization
* Removed punctuation marks (., ! ? -) to clean the text
* Eliminated multiple spaces and converted them into a single space
* Trimmed leading and trailing spaces to improve readability
* Prepared clean and structured text data for accurate analysis

📊 Challenges Faced
* Handling unstructured text data in issue descriptions with inconsistent formatting
* Cleaning data with punctuation, extra spaces, and mixed case text
* Dealing with slang and informal words affecting analysis accuracy
* Managing errors like KeyError and TypeError during data processing
* Understanding differences between .loc and .iloc for data selection
  
📊 Code Implementation
* Created a dictionary-of-lists (ticket_data) to store ticket details.
* Added new tickets dynamically using loops, user input, and auto-increment logic.
* Cleaned issue descriptions using string methods (lower(), replace(), split(), strip()).
* Built a function for keyword-based search to analyze common issues.
* Performed priority counting and insights generation using loops and conditions

💡 Final Insights
* High-priority tickets (6) are highest, indicating more critical issues than others.
* Medium-priority tickets (5) are second highest, showing moderate issue volume.
* Low-priority tickets (4) are lowest, meaning fewer minor issues.
* Keywords like “slow” and “poor” highlight performance and service issues. "slow" → 2 tickets "poor" → 2 tickets
* Positive terms like “good” and “excellent” indicate some customer satisfaction. "good" → 2 tickets
"excellent" → 1 ticket
* Ticket No: 2 (Meera) Issue: slow response, very poor service Longer descriptions indicate strong
dissatisfaction. These tickets need priority investigation
* Majority of complaints are related to system performance and reliability
* Support team shows strong communication and resolution skills
* 53 unique words indicate diverse customer issues, not a single dominant problem.

💡 Recommendation
* Focus on reducing response time and resolving high-priority technical issues to significantly improve
overall customer satisfaction.
* Prioritize high-priority tickets
* Provide technical training for support agents
* Improve communication quality with customers

📚 Conclusion
* The Ticket Analysis System successfully identified key patterns in customer issues, highlighting that
high-priority and performance-related problems (slow response, technical failures) are the main
concerns.
* While customers appreciate support quality in some cases, improving response time and system
reliability is essential to enhance overall customer satisfaction
