🛒 Full-Stack E-Commerce Web Application
A robust, scalable, and fully-functional E-Commerce Web Application built using Python (Flask) for the backend and hosted on AWS Cloud Infrastructure (EC2 & RDS). This project simulates a complete online shopping experience with user authentication, OTP email verification, cart management, and order processing.

🚀 Deployment Architecture
Frontend: HTML + CSS (Jinja2 templating)

Backend: Flask (Python)

Database: MySQL, hosted on AWS RDS

Hosting: Deployed on AWS EC2 (Ubuntu instance)

Email Service: SMTP (via smtplib and email.mime)

✅ Key Features
User Registration with OTP Verification

Secure user signup with real-time email OTP using SMTP.

Login & Password Reset

Email-based OTP password recovery system.

Cart Management

Add/update/delete products from cart.

Quantity-based dynamic pricing.

Order History

Persistent storage of user orders.

Email Notifications

Automated emails for verification and password reset.

Session Flow

Personalized user dashboard and seamless navigation.

🧱 Tech Stack
Layer	Technology
Frontend	HTML, CSS, Jinja2
Backend	Python, Flask
Database	MySQL (AWS RDS)
Deployment	AWS EC2 (Ubuntu Server)
Email	Python smtplib, email.mime
DB Connector	PyMySQL

🔐 Security & Validation
Form input validation on registration and password reset.

Secure password management.

OTP is regenerated upon failed verification for enhanced safety.

No sensitive credentials hardcoded in production (use .env for deployment).







