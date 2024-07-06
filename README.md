Gemini Explorer

Mission Scenario
Using Streamlit, we created a chat interface that integrates with Google's state-of-the-art big language model, Gemini. This platform makes it easy to explore and showcase the potential of sophisticated language model applications!


Mission Workflow:
Task 1:  Enable Google Cloud
Task 2:  Google Cloud Initialization
Task 3:  Setting up Google Gemini
Task 4:  Streamlit Integration
Task 5:  Adding Initial System Messages
Task 6:  Preparing Submission


Task 1: Enabling Google Cloud

Go to the Google Cloud Platform and Select "Get Started for free".
Sign in using your Google Account and then provide the necessary details and complete the billing requirments.
Accept the terms and conditions.
Complete the payment process to initialize your Google Cloud Account.
Create a new project (for instance "RadicalX - Gemini Explorer").
Access the Google Cloud Console.
Navigation -> Artificial Intelligence -> Vertex AI -> Enable All Recommended APIs

<img width="952" alt="radical1" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/86a6b56d-9b61-4ee8-946c-438846a76a48">


Task 2: Google Cloud Initialization
Install the Google SDK using this Link.
Run the following command to initialize the SDK:
gcloud init
Sign in using your Google Account credentials.
Select an existing project or Create a new project
Set default compute region and zone (Optional Step)

<img width="739" alt="radical 2" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/2c21c4d5-092e-46d1-a640-ea85752eeb68">


Task 3: Setting up Google Gemini
Install the streamlit framework
pip install streamlit
In the project, we are using Google's Gemini Pro LLM.
Use the project ID instead of the project name, like this: project = "project_id". This helps avoid encountering a permission denied error.


<img width="947" alt="radical 3" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/c2249dee-2cd5-4096-8766-a742cd848890">


Task 4: Streamlit Integration
Implement the steps given in the mission.
Run the python file streamlit run filename.py.

<img width="581" alt="radical 4" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/4f9742ed-1ce5-44c2-a912-912c8db61bea">



Task 5: Adding Initial System Messages

<img width="592" alt="radical 5" src="https://github.com/kowshik2019/Gemini-Explorer/assets/91105162/dbf49a0d-ac25-4373-99d0-77aa8380b359">



Task 6: Preparing Submission
A GitHub repository for the project containing all the project files.
Loom Video representing the overall approach. Loom Link

Issues Faced
Permission Denied Error: Check if you have provided project_id rather than project name in your code or if the service account is activated.

