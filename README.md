# Automating Employee Onboarding with Microsoft Forms, Power Automate, and Entra
![Microsoft Azure Banner](https://github.com/KLavallais/KLavallais/blob/assets/Microsoft-Azure-Banner_0002.jpg?raw=true)

In this tutorial, we delve into a comprehensive process for new employee onboarding utilizing Microsoft Forms, Power Automate, and the integration with Microsoft Entra for creating user accounts. The tutorial focuses on crafting a user-friendly form for gathering essential information from new hires and employing Power Automate to automate the data integration into our systems. A critical part of this automation includes creating an Entra user for each new employee, specifically assigning them to the appropriate department—highlighted here with the creation of the Help Desk department.

---

## Tools/Programs Used:
- **Microsoft Forms**: Used to create an intuitive onboarding form that collects all necessary new hire information.
- **Power Automate**: Automates the process of transferring form data to Microsoft Entra and creating user accounts.
- **Microsoft Entra**: Manages the automated creation of new users in the directory and assigns them the correct department and access permissions.
- **Azure Active Directory**: Integrates with Entra for managing user authentication and department-based access controls.
- **Office 365 Integration**: Helps manage user credentials and assignments within a familiar ecosystem.

---

## Skills Demonstrated:
- **Identity and Access Management (IAM)**: Automated the creation of user accounts and their assignment to appropriate departments.
- **Role-Based Access Control (RBAC)**: Assigned users to the Help Desk department based on form responses, ensuring correct access permissions from the start.
- **Power Automate Workflows**: Created a dynamic cloud-based workflow to automatically create Entra users based on form input, reducing manual overhead.
- **Department Creation and Assignment**: Dynamically created departments in real time as part of the onboarding process, ensuring new hires were placed into the correct organizational units.
- **Form Automation for User Provisioning**: Gathered information from onboarding forms and used it to provision users in the system, streamlining the IAM process.

---

## Key Features of This Tutorial:

- **Microsoft Forms Creation**: I walk you through building a user-friendly onboarding form for new employees that captures essential data.
  
- **Power Automate Flow**: You’ll learn how I configure Power Automate to handle the backend automation, linking form responses directly to user creation in Entra.

- **Entra User Creation**: I demonstrate the process of dynamically creating Entra users based on form input and assigning them to the proper department, in this case, the Help Desk.

- **Department-Based Role Assignment**: The system I’ve built automatically assigns users to the correct department, ensuring proper access and privileges without manual intervention.

- **End-to-End Automation**: This is a fully automated process, from form submission to user provisioning in the directory, which drastically reduces the time needed to onboard new employees.

---

## Video Demonstration

[![Watch the video](https://github.com/KLavallais/KLavallais/blob/assets/Permissions%20and%20Security%20Groups%20Azure%20Thumbnail.jpg)](https://youtu.be/4OCqiQdUeMQ)


---

## Detailed Walkthrough:

### Step 1: Creating the New Employee Onboarding Form

I begin by creating a **Microsoft Form** that collects vital employee information, such as name, department, and device requirements. For this demonstration, I focus on the department field, ensuring the user will be assigned to the correct group in Entra. 

![Microsoft Forms Demonstration](https://github.com/KLavallais/KLavallais/blob/assets/Microsoft%20Forms%20Demonstration.gif)

---

### Step 2: Setting Up Power Automate Cloud Flow

Next, I walk through the process of creating a **Power Automate** flow. This flow triggers when a new form is submitted, capturing the responses and using them to create a new user account in **Microsoft Entra**.

The flow automatically assigns the new employee to the **Help Desk** department based on their form responses, ensuring they have the right permissions and access to begin their work immediately.

---

### Step 3: Creating the Help Desk Department

Before I finalize the flow, I create the **Help Desk** department within Entra, as it will be necessary to assign our new hires to it.

**Department Creation**: The Help Desk group is dynamically created within the system, ensuring that as new employees onboard, they are immediately placed in the correct department.

---

### Step 4: Testing the Automated Flow

To ensure everything is working as intended, I fill out the form as an imaginary user, **John Doe**, and submit it. The flow runs automatically, and within moments, John Doe is added to Entra, complete with the correct department and access permissions.

I verify the success of this process by refreshing the user list and confirming that all the details are correct for **John Doe**.

---

### Step 5: Finalizing Permissions

After the user is created, I can perform any additional tasks needed, such as assigning more granular permissions or adding the user to additional groups. However, most of the work is already done thanks to the automation I’ve set up.

---

## Conclusion

By leveraging Microsoft Forms, Power Automate, and Entra, I’ve created an automated process that significantly reduces the time and effort involved in onboarding new employees. This system not only ensures accuracy but also integrates new users seamlessly into the organization, allowing IT professionals to focus on higher-priority tasks.

For IAM and PAM professionals, this demonstration showcases how automation can optimize user provisioning and access management, making onboarding a much smoother and faster process. 

Thank you for watching and have a great day!


