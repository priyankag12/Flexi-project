# Flexi-project

## Document:
System Requirement Specification Document

## Title:
System Requirement Specification for Online Examination Management System

## Problem Statement:
Processes for traditional paper-based exams are becoming less effective and have geographical limitations. Inadequate data analysis for performance improvement and manual grading mistakes are a few of the issues that arise when there is no online examination administration system. A complete online examination management system that provides safe, scalable, automated test administration, grading, and data-driven insights is needed to address these difficulties in order to satisfy the needs of contemporary education.

## Objective(Purpose):
An online exam management system's primary objective is to adequately handle and supervise examinations online while offering convenience, security, effortless grading, instantaneous outcomes, and data insights for both educators and learners.

## Scope:
An online test management system's scope includes digitizing the whole exam procedure.It entails managing question banks, securely administering tests, automatically grading exams, and analyzing test results. The technology streamlines the scheduling and administration of exams while meeting the demands of various educational institutions and online learning.

## Document conventions:
Examples of document conventions for an online examination management system are standardized formatting, distinct file and folder name standards, version control procedures, and the uniform use of headers, typefaces, and styles. These principles make it simple to navigate, collaborate on, and maintain technical documentation, user manuals, and system design documents.

## Intended Audience and Reading Suggestions:
The online examination management system documentation is aimed at educators, managers, technical support staff, and students who will be utilizing and maintaining the system.
Reading Suggestions:
For system configuration, test development, and result analysis, educators and administrators should consult the user manuals. The technical documentation will be useful for troubleshooting and integration by technical support teams. Students get access to instructions for taking tests and comprehending comments on their performance.

## Product Perspective:
The online examination administration system is a stand-alone programme that offers instructors and students a complete platform to administer tests online. If needed, it smoothly interacts with Learning Management Systems (LMS) and communicates with user devices via web browsers. In a safe and user-friendly setting, the system includes test development, distribution, grading, and result analysis. Administrators have the option to control user, course, and test settings. The system can be easily customised, updated, and scaled to fit institutions of all sizes because to its modular architecture.

## Product Features:
1. Creating and Customising Exams: Exams with various question formats, time constraints, and difficulty levels may be easily created and customised.
2. Secure Exam Environment: Make sure the testing environment is secure with anti-cheating safeguards, prohibiting unauthorised activity.
3. Instantaneously evaluate multiple-choice questions and offer manual grading choices for arbitrary answers.
4. Access real-time information on student performance, the efficacy of questions, and overall test trends.
5. **User-Friendly Interface:** Give students, teachers, and administrators an easy-to-use interface to improve the test experience overall.

## Operating Environment:
The web-based environment in which the online examination administration system runs makes it available through current web browsers like Chrome, Firefox, Safari, and Edge. It works with many different operating systems, including Windows, macOS, and Linux. The system needs a strong internet connection to give exams, grade them, and analyse the results. Users from various geographic areas can utilise it, giving flexibility for remote learning and evaluation.

## Design and Implementation Constraints:
1. Scalability During peak periods, the system must manage potentially many concurrent users, necessitating a strong server architecture and load balancing algorithms.
2. security To stop unauthorised access, data breaches, and exam cheating, strict security measures are necessary.
3. **Compatibility:** To provide a consistent user experience, the system must work flawlessly on a variety of devices, browsers, and operating systems.
4. Accessibility: To guarantee that the platform is useable by people with impairments, accessibility standards must be followed.
5. **Data Privacy:** Adherence to data protection laws is required to preserve user data and uphold privacy throughout system operations.

## User Classes and Characteristics:
1. Students Users taking tests with varied levels of technical expertise and topic knowledge, either on campus or remotely.
2. Educators Users who design, administer, and grade tests and are looking for a user-friendly interface.
3. **Administrators:** Users in charge of monitoring the system, controlling user accounts, programmes, and system settings; they need extensive control and reporting tools.
4. Users offering help, troubleshooting, and maintaining smooth system performance; this requires a high level of technical knowledge.
5. **System Developers:** Users who are in charge of system upkeep, updates, and modification and who need high-level technical know-how to make system improvements.

## Functional Requirements:
### Exam Creation and Management :-
The capacity for teachers to design and arrange tests using a variety of question kinds. There is an option to specify the probable dates, exam length, and timer. Question alternatives and order are randomly generated to avoid cheating.
### Question Bank Management :-
A place where teachers may save and arrange questions for later use. The ability to group questions by kind, complexity, and subject.
### Assessment and Grading:
Auto-Grading: Support auto-grading of multiple-choice and objective questions.
Manual Grading: Allow teachers to manually grade subjective questions.
Result Calculation: Calculate and display exam scores and results to students.
Feedback: Provide feedback and explanations for correct/incorrect answers.
### Security Features:-
Session Management: Implement secure session management to prevent unauthorized access.
Data Encryption: Encrypt sensitive user data and exam content.
Authentication and Authorization: Ensure proper authentication and authorization mechanisms.
Anti-Cheating Measures: Implement anti-cheating measures, such as lockdown browsers, to deter cheating during exams.

These functional requirements form the basis for designing and developing the Online Examination Management System.

## NonFunctional Requirements:
### Reliability and Availability:-
Uptime: Specify the desired level of system uptime (e.g., 99.9% availability) and any planned maintenance windows.
Fault Tolerance: Describe how the system should handle and recover from hardware or software failures to minimize disruptions.
### Load and Stress Testing:-
Describe the procedures and criteria for conducting load and stress testing to ensure the system can handle peak usage without degrading performance.
### Scalability and Capacity Planning:-
Detail plans for scaling the system as user and examination loads increase over time.
### Usability and User Experience:-
User Interface: Define user interface guidelines for consistency and ease of use.
Accessibility: Ensure the system complies with accessibility standards, making it usable by individuals with disabilities.
### Data Management:-
Data Backup and Recovery: Specify data backup procedures and recovery strategies in case of data loss or corruption.
Data Retention: Define how long user and exam data will be retained and when it will be purged.

These non-functional requirements will help ensure that the Online Examination Management System meets not only its functional goals but also the quality, performance, security, and usability expectations of stakeholders.
