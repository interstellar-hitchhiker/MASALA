MASALA
IBDP Exam Scheduler and Display with Changing Cell Colors

GitHub Repository

Welcome to the IBDP Exam Scheduler and Display tool. This application helps you efficiently schedule and manage your IBDP exams. It enables you to create a detailed exam schedule, including exam durations, reading times, start times, and accommodations. The schedule can be displayed in a finalized web view or exported to an Excel file for easy sharing, printing, and record-keeping.

Features
Dynamic Exam Schedule Generation: Enter the number of exams, and the tool generates a customizable schedule table.
Time Calculations: Automatically calculates reading periods, 30-minute warnings, 5-minute warnings, and end times based on input durations and start times.
Accommodation Adjustments: Includes functionality to add extra time for students with special needs. The accommodation percentage is applied directly to the end time, updating the 30-minute and 5-minute warnings accordingly.
Export to Excel: Download the finalized exam schedule as an Excel file.
Live Time Updates: Displays a live clock and highlights schedule cells based on the current time.
Save and Load Schedule: Save the current schedule to a JSON file and load a saved schedule from a JSON file.
Responsive Design: Ensures usability across different devices and screen sizes.
How to Use
Set Exam Date: Select the date for the exams.
Enter Number of Exams: Specify how many exams are being scheduled for the selected date.
Generate Schedule: Click on "Create Schedule Table" to generate the schedule table.
Fill in Exam Details:
Enter the subject for each exam.
Specify the duration (hours and minutes) for each exam.
Allocate reading time if applicable.
Set the start time for each exam.
When using accommodations, the percentage is added to a row at the bottom of the column. This shows the original exam duration and start time, along with the 30-minute and 5-minute warnings for the original exam time. This design assumes that special and non-special needs students share the same room, with individual 30-minute and 5-minute warnings provided one-on-one. If multiple students in each subject exam have different accommodation percentages, it is advised to run the accommodations in a separate room and provide a column for each student (e.g., Science HL Paper 3 (Jane Smith)) so students can see their individual exam and name. Future versions of the app will relocate the accommodations row above the start time, update the end time, and correctly place the 30-minute and 5-minute warnings before the accommodated end time.
View and Export Schedule:
Click on "Export to Excel" to export the schedule to an Excel file.
Click on "Finalized Schedule Display" to see a finalized view of the schedule with live updates.
Click on "Save Schedule" to keep an offline .json version of the completed table with subject names and time details to load and display at a later date.
Click on "Load Schedule" to upload a saved .json file and display the exam(s) with subject names and time details already to go.
GitHub Pages Site
You can view and interact with the IBDP Exam Scheduler and Display directly here: GitHub Pages Site

Installation
To set up the IBDP Exam Scheduler and Display locally:

Clone the repository:

bash
Copy code
git clone https://github.com/<your-username>/<your-repository>.git
Navigate to the project directory:

bash
Copy code
cd <your-repository>
Open index.html in your web browser to start using the scheduler.

Technologies Used
HTML: Structure of the scheduler.
CSS: Styling for a user-friendly interface.
JavaScript: Functionality and interactivity.
Bootstrap: Responsive design framework.
Moment.js: Time manipulation and formatting.
Flatpickr: Date and time picker.
SheetJS (xlsx): Exporting the schedule to Excel.
FileSaver.js: Saving schedules as JSON files.
License
This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License. This includes all past, current, and future versions. See the LICENSE file for more details.

Contributing
We welcome contributions to improve the IBDP Exam Scheduler and Display. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Commit your changes (git commit -am 'Add a new feature').
Push to the branch (git push origin feature/your-feature-name).
Open a pull request.
Acknowledgements
Special thanks to all contributors and users who provide valuable feedback to help improve this tool.
