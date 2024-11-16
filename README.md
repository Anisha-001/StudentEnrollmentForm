# <h1 > StudentEnrollmentForm </h1>

<p>This form will work as intended based on your requirements for a student enrollment system. The logic handles adding and updating student records in the STUDENT-TABLE relation of the SCHOOL-DB database.</p>

<h4> After coding using html and javascript Student Enrollment Form will look like below given screenshot. </h4>

![image](https://github.com/user-attachments/assets/e0f6bdd6-4fc5-481b-a91d-5ea43a6ca3c5)

<h4> In The Database. </h4>

![image](https://github.com/user-attachments/assets/21ec8bca-fb22-45c9-a820-bc42e529d06f)

<h2> Key Features:</h2>
<h6> 1.Primary Key: The form uses Roll No as the primary key. It checks if the Roll No exists in the database before enabling the appropriate buttons.<br>
2. Button Logic:
If Roll No exists, the Update button is enabled, allowing the user to update student data.
If Roll No does not exist, the Save button is enabled, allowing the user to add new student data.<br>
3. Field Validation: Ensures all fields are filled before saving or updating data.<br>
4. Form Reset: The Reset button clears the form and reverts it to its initial state.<br>
5. Database Interaction: The code interacts with the database through a mock API endpoint. You'll need to replace the database check and interaction with a real database API.</h6>


<h2>procedure </h2>
<p> 
  <h2> Steps to Create a Student Enrollment Form</h3>
  <h4>1. Requirements Gathering </h4>
  <p> Before you start developing the form, clarify the following requirements:

Input Fields:<br>

Roll No (Primary Key)<br>
Full Name<br>
Class<br>
Birth Date<br>
Address<br>
Enrollment Date<br>
Primary Key: Roll No (must be unique). <br>

Validation: Ensure that all fields are filled before saving the form.<br>

Buttons:<br>

Save: Save new records.<br>
Update: Update existing records.<br>
Reset: Clear the form.<br>
Back-end: The data should be saved to a database (e.g., MySQL, PostgreSQL) with a table for student enrollment.</p>


<h4> 2. Designing the Form</h4>
<p> <h5>Structure:</h5>

Use HTML to create the basic structure of the form.<br>
Use CSS (or a framework like Bootstrap) to style the form for a user-friendly experience.<br>
Use JavaScript (or jQuery) for form validation and controlling button states.</p>
</p>
