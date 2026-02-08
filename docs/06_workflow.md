- Start with “When clicking ‘Execute workflow’” – this trigger starts the workflow manually.
- The workflow reads all rows from your Google Sheet using Get row(s) in sheet.
- The IF node checks a condition (example: row number, age, name, etc.).
- If the condition is true, the data goes to the Append row in sheet node and gets added to Sheet-1.
- If the condition is false, the data goes to Append row in sheet1 and gets added to another sheet.
- Click Execute Workflow to test — the output shows how many rows went to the True branch and False branch.
# screenshot
<img width="1538" height="840" alt="Screenshot 2026-02-08 105210" src="https://github.com/user-attachments/assets/51838a32-f2ad-4207-a59e-5f153754c36f" />

