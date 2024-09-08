# PROGRAMMING-2B-PART-1-

The Contract Monthly Claim System (CMCS) is a prototype for a Windows-based application developed using .NET Core with WPF (Windows Presentation Foundation). The system is designed to manage monthly claims submitted by lecturers and verified by program coordinators and academic managers.

This prototype provides a front-end user interface (UI) to demonstrate the system's basic functionality, including submitting claims, approving/rejecting claims, uploading supporting documents, and tracking the claim status. Note: This is a non-functional prototype at this stage, designed for visual representation.

Features
User Interface (UI):
Submit Claim: Lecturers can submit their claims.
Approve/Reject Claim: Program Coordinators and Academic Managers can verify and approve/reject the claims.
Upload Supporting Documents: Lecturers can upload any supporting documentation required for their claim.
Track Claim Status: Allows users to track the current status of their submitted claim.
Key Technologies Used:
C# (Advanced)
.NET Core
Windows Presentation Foundation (WPF)
Unified Modeling Language (UML) Class Diagram for Database Design (coming in future versions)
Project Structure
shell
Copy code
📂 CMCS
 ┣ 📂 Assets              # Folder for images and other resources used in the UI
 ┣ 📂 Views               # Contains WPF XAML pages for each part of the UI
 ┣ 📂 ViewModels          # Contains ViewModel classes (if using MVVM pattern)
 ┣ 📂 Models              # Contains models representing data (optional for future stages)
 ┣ 📜 MainWindow.xaml     # Home screen UI
 ┣ 📜 MainWindow.xaml.cs  # Code-behind for MainWindow.xaml
 ┣ 📜 TrackStatusPage.xaml # UI for tracking claim status
 ┣ 📜 TrackStatusPage.xaml.cs # Code-behind for TrackStatusPage.xaml
 ┣ 📜 SubmitClaimPage.xaml # UI for submitting claims (to be implemented)
 ┣ 📜 ApproveClaimPage.xaml # UI for approving/rejecting claims (to be implemented)
 ┣ 📜 UploadDocumentPage.xaml # UI for uploading documents (to be implemented)
 ┗ 📜 README.md           # This README file
Installation and Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/Contract-Monthly-Claim-System.git
Open the project in Visual Studio:

Ensure you have Visual Studio 2019 or newer installed.
Open the solution file (.sln) in Visual Studio.
Build the project:

In Visual Studio, click on Build > Build Solution.
Run the project:

Once the project builds successfully, run the application by pressing F5 or clicking Debug > Start Debugging.
Usage
Submit Claim: On the home screen, click on the "Submit Claim" button to navigate to the Submit Claim page.
Approve/Reject Claims: Click on the "Approve/Reject Claims" button to navigate to the page for verifying and approving/rejecting claims.
Upload Supporting Documents: Upload necessary documentation for claims by clicking on the "Upload Supporting Documents" button.
Track Claim Status: Click on the "Track Claim Status" button to enter your claim number and track the current status of your claim.
Version Control
Version control is managed through GitHub. Please ensure that all changes are committed and pushed to the repository regularly.
Commits: All commits must be descriptive and relevant to the changes made (e.g., Added TrackStatusPage.xaml UI, Updated MainWindow navigation).
Repository: Contract Monthly Claim System GitHub Repository
To Do (Future Development)
Backend Integration: Implement the logic to make the UI functional.
Database Design and Implementation: Implement the database and integrate it with the system to store claim details, statuses, etc.
Claim Submission Logic: Develop the code for submitting claims, storing documents, and tracking claim status.
Admin Functionality: Provide functionality for program coordinators and academic managers to approve or reject claims.
Contributing
Fork the repository.
Create your feature branch: git checkout -b feature/my-feature.
Commit your changes: git commit -am 'Add new feature'.
Push to the branch: git push origin feature/my-feature.
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

