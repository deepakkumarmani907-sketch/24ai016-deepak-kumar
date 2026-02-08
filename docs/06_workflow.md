- Start with “When clicking ‘Execute workflow’” – this trigger starts the workflow manually.
- The workflow reads all rows from your Google Sheet using Get row(s) in sheet.
- The IF node checks a condition (example: row number, age, name, etc.).
- If the condition is true, the data goes to the Append row in sheet node and gets added to Sheet-1.
- If the condition is false, the data goes to Append row in sheet1 and gets added to another sheet.
- Click Execute Workflow to test — the output shows how many rows went to the True branch and False branch.
# screenshot
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/bc06bf66-070a-4583-89e3-850f01fdaf7f" />
