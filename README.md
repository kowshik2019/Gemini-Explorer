# Gemini-Explorer

MISSION WORKFLOW!
Task 1: Enable Google Cloud
Task 2: Google Cloud Initialization
Task 3: Setting up Google Gemini
Task 4: Streamlit Integration
Task 5: Adding Initial System Messages
Task 6: Conclusion


Mission Scenario
Using Streamlit, we created a chat interface that integrates with Google's state-of-the-art big language model, Gemini. This platform makes it easy to explore and showcase the potential of sophisticated language model applications.


TASK 1: ENABLE GOOGLE CLOUD!
Go to the Google Cloud Platform and Select "Get Started for free".
Sign in using your Google Account and then provide the necessary details and complete the billing requirments.
Complete the payment process to initialize your Google Cloud Account.
Create a new project (for instance "RadicalX - Gemini Explorer").
Access the Google Cloud Console.
Navigation -> Artificial Intelligence -> Vertex AI -> Enable All Recommended APIs

<img width="952" alt="radical1" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/807eb7ce-2e8f-4e7c-b5bc-b653439aef1a">


TASK 2: GOOGLE CLOUD INITIALIZATION!
Install google Cloud SDK
Run the following command to initialize the SDK:
gcloud init
Initialize SDK.
Sign in and select/create a project
Set default compute region and zone(optional step)

<img width="739" alt="radical 2" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/89bb58a6-164f-4c73-923e-e2368b16330a">


TASK 3: SETTING UP GOOGLE GEMINI!
Install Streamlit
pip install streamlit
Integrating the Gemini Pro LLM.Note: Use Project ID Instead of name to avoid permission errors.
Use the project ID instead of the project name, like this: project = "project_id". This helps avoid encountering a 403 permission denied error.

<img width="947" alt="radical 3" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/f7739a23-650c-4a53-8544-aa1681da5405">


TASK 4: STREAMLIT INTEGRATION!
Defined a function to handle chat Interactions
Implement features to send and receive changes.
Incorporate Logic to process user Input and Generate responses.
Integrate the chat functionality.

<img width="581" alt="radical 4" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/197946f8-3926-4d65-9e1b-3d05a24ed951">


TASK 5: ADDING INITIAL SYSTEM MESSAGES!
Customize System messages for User Interaction!

<img width="592" alt="radical 5" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/7f8bcfaa-c102-47e3-b85e-e240f4b0bc98">


TASK 6: CONCLUSION!
A GitHub repository for the project containing all the project files.
Loom Video representing the overall approach. Loom Link 
https://www.loom.com/share/0c53bcc5b2744f29a04684c1c0a5b379?sid=7b248cb7-54a6-4531-812c-f3bd23f903cc

Issues Faced
Permission Denied Error: Check if you have provided project_id rather than project name in your code or if the service account is activated.







