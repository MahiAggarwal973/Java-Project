# Online Learning Management System
TABLE OF CONTENTS
<br>
1.Overwiew
2.Features
3.Technolofy Stack
4.Prerequisites
5.Usage
6.JDBC Implementation Notes
<hr>
1.<i>OVERWIEW</i>
<br>
An Online Learning Management System (LMS) is a software application designed to facilitate the administration,documentation,tracking,reporting,automation,and delivery of educational courses,training programs,or learning and development programs.Think of it as a digital classsroom that brings together learners,instructors,and course content in a centralized platform.It is web-based platform designed to facilitate the delivery,management,and tracking of educational content and activities.It provides a centralized space where educators,administrators,and learners interact for teaching and learning purposes.
<br>
Developed using Java for backend operations,JDBC for database interaction,and HTML/CSS/JavaScript for the frontened.
<hr>
2.<i>FEATURES</i>
<br>
<b>Admin</b>
 * User Management
   * Input: User details (name, email, role)
   * Output: Confirmation message for successful user creation/update/deletion
   * Functionality: Create, edit, or delete user accounts and manage user roles.
 * Course Management
   * Input: Course details (title, description, syllabus)
   * Output: Confirmation message for successful course creation/update/deletion
   * Functionality: Manage courses, including creation, editing, and deletion.
 * Performance Analytics
   * Input: Course and user performance data
   * Output: Reports and visualizations
   * Functionality: Analyze performance metrics and generate reports.
 * System Settings
   * Input: Configuration settings
   * Output: Confirmation message for successful settings update
   * Functionality: Manage system-wide settings.
<b>Instructor</b>
 * Course Creation
   * Input: Course content, quizzes, assignments
   * Output: Confirmation message for successful course creation
   * Functionality: Create and manage course content.
 * Assignment Grading
   * Input: Student submissions
   * Output: Grades and feedback
   * Functionality: Grade assignments and provide feedback.
 * Student Management
   * Input: Student list
   * Output: Student performance reports
   * Functionality: Monitor student progress and performance.
<b>Student</b>
 * Course Enrollment
   * Input: Course selection
   * Output: Confirmation message for successful enrollment
   * Functionality: Enroll in courses.
 * Access Materials
   * Input: Course materials
   * Output: Access to materials
   * Functionality: View and download course content.
 * Submit Assignments
   * Input: Assignment submissions
   * Output: Confirmation message for successful submission
   * Functionality: Submit assignments.
 * Progress Tracking
   * Input: Course progress
   * Output: Progress reports
   * Functionality: Track and view course progress.
<hr>
3.<i>Technology Stack</i>
<br>
Layer            Technology
Backend           Java , Spring Boot
Frontened         HTML , CSS ,JavaScript
Database          MySQL
Database Access   JDBC
<hr>
4.<i>Prerequisites</i>
<br>
Before setting up the project locally , ensure the following software is installed:
1. Java Development Kit (JDK):Version 11 or later is required for the development and execution of the LMS application.
2. Apache Maven:Used for dependency management and building the project.Simplifies the inclusion of required libraries and frameworks.
3. MySQL:Version 8 or later is recommended for database management.It will store user data, courses, enrollments, assignments, and other entities.
4. Git:A version control system used for cloning repositories and managing code changes.
5. Integrated Development Environment (IDE):Options: IntelliJ IDEA, Eclipse, or any preferred Java IDE.Facilitates coding, debugging, and project management.
---
<hr>
5.<i>Usage</i>
<br>
<B>Admin</B>
1. User Management:Displays a table listing all user accounts (students, instructors, admins).Options include creating, editing, and deleting users.
2. Course Management:Displays all available courses in a table format.Admins can create new courses and edit or delete existing ones.
3. Performance Analytics:Provides graphs and tables showcasing key performance metrics for courses and users.Helps track course completion rates, student engagement, and overall system usage.
4. System Settings:A dedicated panel to manage system-wide configurations such as email notifications, user permissions, and themes.
5. System Activity Monitoring:Real-time updates on system activities like new user registrations, course enrollments, and assignment submissions.
---
<b>Instructor</b>
1. Course Management:Displays a list of courses created by the instructor.Options to edit, update, or delete course content.
2. Assignment Grading:Provides an interface for reviewing and grading student submissions.Instructors can leave comments or feedback directly on submissions.
3. Student Performance:A table displaying student performance metrics and progress in courses taught by the instructor.
4. Course Enrollment Stats:Visual graphs and reports showing enrollment statistics and engagement levels for each course.
5. Feedback Summary:A section to view feedback received from students and provide additional responses or clarifications.
---
<b>Student</b>
1. Course Enrollment:Lists all courses the student is enrolled in with options to view course details and syllabus.
2. Material Access:Provides an interface for viewing and downloading course materials such as videos, PDFs, and notes.
3. Assignment Submission:A section to upload and track assignment submissions.Displays deadlines and submission status.
4. Progress Tracking:Offers graphs and tables showing progress in enrolled courses and completed assignments.
5. Feedback and Grades:Displays grades and feedback received for assignments, quizzes, and exams.
---
<hr>
6.<i>JDBC Implementation Notes</i>
<br>
1. Database Connection:
 * The application uses Spring's JdbcTemplate for interaction with MySQL.
2. SQL Queries:
 * Native SQL is used for CRUD operations, optimized for MySQL.



