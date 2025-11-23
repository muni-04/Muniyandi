# INITIAL SETUP

-Open the n8n website in the mobile/lab environment.

-Sign up or log in to your n8n account.

-Create a new workflow inside the n8n editor.

# WORKFLOW STRUCTURE
-On form submission (Trigger)
          ↓
-Append row in sheet (Action)


-This workflow listens for a form submission and automatically adds the submitted data into a spreadsheet.

# NODES DESCRIPTION
# 1. On form submission (Trigger Node)

-Starts the workflow when a user submits the form.

-Captures all form fields and passes them to the next node.

-Icon shows a form symbol with a lightning bolt (indicating a trigger).

# 2. Append row in sheet (Action Node)

-Takes the incoming form data.

-Appends a new row into the connected spreadsheet.

-Each submission creates one new row.

# SCREENSHOT DESCRIPTION

<img width="1032" height="959" alt="▶️ My workflow 2 - n8n - Google Chrome 23-11-2025 10_49_07 AM" src="https://github.com/user-attachments/assets/d5521066-f83b-43eb-99cd-da2b40f709aa" />



# HOW IT WORKS

-A user submits a form connected to the workflow.

-The On form submission trigger fires.

-Data flows into the Append row in sheet node.

-The spreadsheet receives a new row with the submission details.

-Workflow completes automatically.
