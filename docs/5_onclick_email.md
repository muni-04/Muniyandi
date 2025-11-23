# INITIAL SETUP

- Open the official n8n website in the lab/mobile environment.

- Create a new n8n account or log in.

- Go to the Workflow Editor and create a new workflow.

# WORKFLOW STRUCTURE
- On form submission (Trigger)
          ↓
- Append row in sheet (Action)


- This workflow listens for a form submission and automatically adds the submitted form data into a sheet.

# NODES DESCRIPTION
 # 1. On form submission (Trigger Node)

- Activates when a form is submitted.

- Collects all the form fields.

- Passes the data to the next node.

- Seen in the screenshot as a blue form icon with a lightning symbol.

# 2. Append row in sheet (Action Node)

- Takes the incoming form data.

- Appends a new row into a Google Sheet / spreadsheet.

- Runs every time a form is submitted.

- Shown in the screenshot with a green sheet icon.

# SCREENSHOT DESCRIPTION

<img width="976" height="903" alt="image" src="https://github.com/user-attachments/assets/7c456fc0-1dcd-4ba9-af97-23cca0daf7c8" />


# HOW IT WORKS

- User submits the form.

- The On form submission trigger fires.

- Data flows into Append row in sheet.

- The sheet receives a new row automatically.

- Workflow completes.
