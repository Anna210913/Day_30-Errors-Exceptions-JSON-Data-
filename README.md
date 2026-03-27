# Day_30-Errors-Exceptions-JSON-Data-
Enhancing the Password Manager GUI app.

Day 30 focused on making the Password Manager **(Day 29)** more robust, reliable, and user-friendly by introducing proper error handling and improving how data is stored and accessed. Rather than building a new project, this day was all about refining and strengthening the existing application.

## ⚙️Improvements Made to the Password Manager 
🔍 Search Functionality
    Users can now search for saved credentials by website
    Results are displayed using a pop-up dialog box
⚠️ Exception Handling
  Prevents the program from crashing when the data file doesn’t exist a website     is not found in the saved data.
📁 Improved JSON Data Management
  Reading existing data from the JSON file
  Updating it with new entries
  Writing the updated data back safely
🧹 Better User Experience
  Clearing input fields after saving
  Clear and helpful pop-up messages


## What I Learned That Day
- Using the try, except, else, and finally pattern
- Handling specific errors like FileNotFoundError, KeyError, IndexError
- Understanding how and when to raise your own errors
- Working with JSON Data:
    Reading data using json.load()
    Writing data using json.dump()
    Updating existing data structures instead of overwriting
- Writing code that anticipates and handles potential issues
- Searching for specific entries in stored data
- Handling cases where data may not exist


Day 30 was all about leveling up from "it works" to "it works well." By adding proper error handling and improving data management, the Password Manager became a much more realistic and production-ready application.

📌**These improvements are already included in the Day 29 Password Manager project.**
