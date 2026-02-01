Academic Record Management System (MySQL)

This project is a MySQL-based relational database system designed to manage academic records for a higher education institution. The system addresses challenges such as invalid registrations, poor performance tracking, and unauthorized data changes by enforcing strong database design principles and business rules.

The database consists of six core tables: students, modules, exams, module statistics, exam audit, and top performers, all connected through primary and foreign keys to maintain referential integrity. Constraints and validations are implemented to ensure data accuracy, including checks for valid student data and minimum grade thresholds for top performers.

The system uses stored procedures and functions to automate key operations such as validating student enrollment before capturing exam results, calculating distinctions, passes, and failures, and generating performance statistics per module and across the institution.

Triggers are implemented to automatically update top performers and maintain an audit trail of exam result changes, capturing both previous and updated values along with timestamps. Views are used to simplify reporting, including overall student performance status and average marks by city.

Sample data was inserted to test all constraints, procedures, triggers, and views, ensuring reliability, accuracy, and proper error handling throughout the system
