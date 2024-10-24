# LecturerClaimsApp
### **LecturerClaimsApp: Overview**

The **LecturerClaimsApp** is a web-based application designed to manage claims submitted by lecturers for hours worked. The application simplifies the process of submitting, approving, and managing these claims in a structured and efficient manner. It leverages the **ASP.NET MVC** framework, making it accessible from a web browser, and provides functionality for both lecturers and administrators.

---

### **What the Program Does**

1. **Lecturer Claims Submission**
   - Lecturers can submit claims for the hours they have worked.
   - The claim form collects relevant details such as:
     - **Lecturer Name**: The name of the lecturer submitting the claim.
     - **Hours Worked**: The total hours worked by the lecturer.
     - **Hourly Rate**: The rate at which the lecturer is compensated.
     - **Additional Notes**: Any additional information or context related to the work.
     - **Document Upload**: Optional feature for lecturers to upload supporting documents like time logs or invoices.

2. **Claims Management (Admin)**
   - Administrators can manage the claims submitted by lecturers.
   - Claims can have the following statuses:
     - **Pending**: Claims that are awaiting approval or rejection.
     - **Approved**: Claims that have been approved and will be processed for payment.
     - **Rejected**: Claims that were rejected with or without a reason.
   - Admins have the ability to:
     - **Approve** claims by clicking an "Approve" button.
     - **Reject** claims by clicking a "Reject" button.

3. **Claim Review**
   - Both lecturers andadministrators can view submitted claims.
   - Claims are listed in a table format, displaying:
     - The lecturer’s name.
     - Hours worked.
     - Hourly rate.
     - Additional notes provided.
     - Document (if uploaded) as a downloadable link.
     - Claim status.
   - Claims can be reviewed, and documents can be viewed or downloaded as needed.

4. Responsive User Interface
    The application is designed using Bootstrap, ensuring it is mobile-friendly and responsive across different devices.
     The user interface is intuitive and clean, allowing users to quickly navigate through the application’s features.


Key Features
Submit Claims: Lecturers can log in and submit claims for their worked hours.
- Manage Claims: Admins can approve or reject submitted claims.
  Document Upload: Allows lecturers to upload supporting documents with their claims.
Responsive Design: The application is accessible on both desktop and mobile devices.
User Authentication: Supports login functionality (if implemented) to ensure only authorized users can submit or manage claims.




This application provides an efficient way for institutions to manage lecturer payments, ensuring that claims are handled systematically and that lecturers can easily submit their work hours for approval.
