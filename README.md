# rag_with_n8n

# Installtion

You need to install Node.js Node.js version that satisfies the following version range: >=18.17 <= 22

Then inside the project folder, run this command:

>> npm install n8n

After instal n8n successfully, run this command to start n8n locally:

>> n8n

# Build the workflow

**Prerequisite:**

If you attempt to integrate with Google, OpenAI, HuggingFace or Gemini, you must create the API Key of them.

*Google:*

- Create a Google Cloud account and create a workspace.

- Go to this link https://console.cloud.google.com/apis/api/drive.googleapis.com/ to create and enable API Key.

*HuggingFace:*

- Go to this page https://huggingface.co/settings/tokens to create an API key.

*Gemini:*

- Go to Google AI Studio, create one API Key.

**How to import workflow:**

Note: The project is in developing progress so it does not UI yet.

- Open n8n, click the (...) button on the top right and choose "Import from File"

- Choose the core_flow.json. This is the first flow to ask a pdf which uploaded from Google Drive. You can type the input in Text section:

![image](https://github.com/user-attachments/assets/ab2d59b9-1785-4bf6-ac38-6ecfad18bdd7)

- The 

