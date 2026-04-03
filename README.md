# Smart-e-Hospital-Management-System-with-AI-Based-Disease-Prediction
Developed a hospital management system using Python (Tkinter) and MySQL with role-based access, integrating Machine Learning for symptom-based disease prediction and Deep Learning (ResNet50) for pneumonia detection from chest X-rays.



**Description:**

The Smart Hospital Management System is an advanced GUI-based application developed using Python (Tkinter), MySQL, Machine Learning, and Deep Learning to automate and enhance hospital operations. The system incorporates a role-based architecture supporting Admin, Doctor, and Patient functionalities, ensuring secure and structured access to hospital data.

Patients can register through an interactive graphical interface by providing personal details, and securely log in using encrypted passwords (bcrypt). The system allows patients to view doctors, book appointments, and access billing information generated automatically via database triggers.

A key highlight of the system is the integration of Artificial Intelligence for disease prediction. The application includes a Machine Learning model trained on symptom-based data, enabling patients to select symptoms through a user-friendly checkbox interface and receive predicted diseases along with confidence scores. This enhances preliminary diagnosis and assists in early medical guidance.

Additionally, a Deep Learning model (ResNet50) is implemented for medical image analysis. Patients can upload chest X-ray images, and the system predicts whether the patient is likely to have pneumonia, along with prediction confidence. This feature demonstrates the application of computer vision in healthcare.

Doctors can view their appointments, update treatment status, and record diagnoses and prescriptions, while administrators can manage doctors, monitor system activity through audit logs, and oversee patient records.

The system ensures data integrity through relational database constraints, stored procedures, and triggers (e.g., automatic bill generation after appointment booking). Overall, the project demonstrates the integration of frontend GUI development, backend database management, and AI-driven healthcare analytics to create a comprehensive and intelligent hospital management solution.

