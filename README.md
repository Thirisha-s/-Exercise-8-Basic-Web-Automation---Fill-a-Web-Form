# -Exercise-8-Basic-Web-Automation---Fill-a-Web-Form
```
Name: THIRISHA S
Reg No: 212222230160
```
# Aim:
To automate the process of filling out a web form using the Application/Browser activity in UiPath Studio.

# Equipment Required:
UiPath Studio installed on your computer.
Web Browser (e.g., Chrome, Edge, with UiPath extensions installed).
Computer with:
Minimum 4 GB RAM.
Minimum 2.0 GHz CPU.
Windows operating system.
A Web Form to be automated.

# Procedure:
# Create a New Project in UiPath Studio:
Open UiPath Studio and create a new project by selecting Process under the New Project tab.
Name the process (e.g., Web Form Automation Using Application/Browser) and click Create.

# Install the Browser Extension:
# To interact with a web browser, install the necessary UiPath browser extension:
Go to the Tools section in UiPath Studio.
Install the extension for the browser you will use (e.g., Chrome or Edge).

# Use Application/Browser Activity:
Instead of using the Open Browser activity, we will use the Use Application/Browser activity.
In the Activities panel, search for Use Application/Browser and drag it into the Main sequence.
In the Application/Browser field, click Indicate Application on Screen, then navigate to the browser where the web form is located and indicate the web form window or tab.
Once the browser is selected, it will embed the browser as part of the automation.

# Navigate to Web Form:
After setting up the Use Application/Browser activity, use the Navigate To activity to navigate to the web form’s URL.
Inside the Use Application/Browser container, search for Navigate To and add it to the workflow.
In the URL property of Navigate To, enter the URL of the web form.

# Fill in Web Form Fields:
To input data into the form, use Type Into activities for each field on the form.

# Steps:
Search for the Type Into activity in the Activities panel and drag it into the sequence under the Navigate To activity.
Click the Indicate on Screen button in the Type Into activity and select the form field where you want to enter the data (e.g., the Name field).
Enter the text (e.g., "John Doe") in the Text property of the Type Into activity.
Repeat this step for each form field, such as Name, Email, Phone, etc.

# Select Dropdowns or Checkboxes (if applicable):
For dropdown fields, use the Select Item activity.
For checkboxes or radio buttons, use the Check activity.

# Steps:
Search for Select Item for dropdowns. Indicate the dropdown field and specify the value in the Item property.
Use Check to select checkboxes or radio buttons, and indicate the field on the web form.

# Submit the Form:
To submit the form, use the Click activity.
Drag the Click activity below the fields that you filled out.
Click Indicate on Screen in the Click activity and select the Submit button on the web form.

# Save and Run the Workflow:
Press CTRL+S to save the workflow.
Click the Run button to execute the automation.
The robot will open the web form in the browser, fill in the details as provided in the Type Into activities, and submit the form.

# UiPath WorkFlow:
![Screenshot 2024-09-26 214141](https://github.com/user-attachments/assets/13909089-cba0-4360-a7e1-232bff9dc64d)
![Screenshot 2024-09-26 214337](https://github.com/user-attachments/assets/7dbaf9be-5477-4665-a4a1-5426c51ae265)
![Screenshot 2024-09-26 214406](https://github.com/user-attachments/assets/d213ba10-6601-4a18-854f-e52ec8f2f854)
![Screenshot 2024-09-26 220051](https://github.com/user-attachments/assets/f09ff222-7813-44c6-9480-25f189165a95)
![Screenshot 2024-09-26 220132](https://github.com/user-attachments/assets/afd33b2f-d4a5-413d-ba5e-2a87348359fa)
![Screenshot 2024-09-26 220358](https://github.com/user-attachments/assets/ad3e90e9-9017-4100-b9d8-22f51b15c1fa)
![Screenshot 2024-09-26 220412](https://github.com/user-attachments/assets/f28405d5-079e-45d9-809c-73e7d162fb39)
![Screenshot 2024-09-26 220522](https://github.com/user-attachments/assets/5d7e7c9f-41b9-409d-9835-e31b0751e9d2)
![Screenshot 2024-09-26 220616](https://github.com/user-attachments/assets/da5eb7ce-79a2-4eaf-89f7-d2be9e27c312)

# Result:
The web form is successfully filled and submitted using UiPath Studio with the Application/Browser activity, demonstrating the automation of a web-based form without explicitly opening a browser each time.








