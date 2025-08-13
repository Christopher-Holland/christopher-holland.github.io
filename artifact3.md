# Databases Narrative

For milestone four, I again selected my **Animal Rescue Inventory System**. This project was originally a console-based application that allowed for the intake, tracking, and reservation of animals. The initial version lacked a graphical interface, database integration, and secure authentication. I chose this artifact because it provided an excellent opportunity to expand its functionality by adding a database and secure user authentication.

The primary enhancement for this project was migrating the application to a **full-stack web solution** using **Node.js**, **Express**, and **MongoDB**. I designed and implemented a MongoDB schema to store user accounts, animal records, and password reset tokens. This change provided persistent storage and improved scalability compared to the in-memory data handling in the original version. 

To ensure security, I incorporated **bcrypt hashing** for password storage, session-based authentication, and a password reset workflow using secure, randomly generated tokens with expiration times. Additionally, I implemented server-side input validation using the **express-validator** library to prevent invalid or malicious data from entering the database. These rules enforced constraints such as minimum password length, valid email format, and matching password confirmation fields — safeguards that protect both data integrity and application security.

From a database perspective, this enhancement demonstrates my ability to **design, implement, and integrate** a MongoDB database in a secure and functional manner. From a software engineering standpoint, it showcases my capability to **modernize outdated systems** into maintainable, scalable, and secure full-stack solutions.

This work aligns with all of the **course outcomes** by demonstrating my ability to:
- Design and evaluate computing solutions that address real-world needs.
- Apply professional database practices.
- Implement secure coding strategies.

Overall, the enhancements made to this artifact have transformed it into a **fully functioning, database-driven web application** with the capability to deliver real value to users in real-world scenarios.
