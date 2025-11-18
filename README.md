## EX 08: WebFormAutomation

### Aim
To automate the process of filling and submitting a basic web form using UiPath Studio, specifically targeting the ACME System 1 login page.

### Procedure (Steps)

1.  **Project Creation:** Create a new UiPath Process named `WebFormAutomation`.
2.  **Navigate to URL:** Use the **Open Browser** activity, setting the URL to `https://acme-test.uipath.com/login`.
3.  **Fill Email:** Use a **Type Into** activity to enter the email into the Email field.
4.  **Fill Password:** Use a second **Type Secure Text** activity to enter the password into the Password field.
5.  **Submit Form:** Use a **Click** activity to press the "Login" button.
6.  **Execute:** Run the workflow (`Main.xaml`).

### Output 

<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/248340c4-ff95-45ff-b33e-66916084d4ee" />

### Result
The automation successfully opens the ACME login page, enters the provided credentials into the respective input fields, and clicks the "Login" button, demonstrating basic web UI automation capability.
