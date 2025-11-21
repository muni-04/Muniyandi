# INITIAL SETUP

  Visit The Official Websites In Our Mobile/Labs
 - To Create An Account In N8N
  -  Login / Sign Up In A Account

# WORKFLOW STRUCTURE
         + Button (onClick)
                ↓
        Right Side Chat Panel
                ↓
        When Chat Message Received
                ↓
             AI Agent
                ↓
        Google Gemini Chat Model
                ↓
        AI Response to Chat Box
   
# NODES DESCRIPTION 

      
## 1. UI Button (+ Icon)

 - Event: `onClick`
 - Action: Opens Chat Panel On Right Side.
 - Used To Trigger The Agent Workflow.

## 2. Right Side Chat Panel

  -  Displays Chat Interface.
  - Accepts User Messages.
  - Connected to: **When Chat Message Received** Node.
 
 ##     3. When Chat Message Received

  - Triggers Whenever User Sends a Message.
  - Passes Message to AI Agent.

 ##     4. AI Agent Node

  - Core Logic Handler.
  - Connected To Google Gemini Chat Model.
  - Uses Memory And Tools If Required.

 ##     5. Google Gemini Chat Model

  - Processes text with Gemini API.
  - Returns intelligent responses.

 ##     6. Output to Chat Panel

  - Sends AI response back to the user.

 ## SCREENSHOT
 <img width="1878" height="962" alt="New File at _ · muni-04_Muniyandi - Google Chrome 21-11-2025 11_57_55" src="https://github.com/user-attachments/assets/e3ce9b01-e689-4f02-94f9-25504c19b1c0" />


 ## HOW IT WORKS 

1.  User clicks the **+ button**.
2.  Chat panel slides from the right.
3.  User types a message.
4.  Message goes to **AI Agent**.
5.  AI Agent invokes **Google Gemini Chat Model**.
6.  Response appears in chat panel.

       
