# PRESCRIPTO 👨‍⚕🏥🤒

*Prescripto* is a full-stack web application designed to make healthcare more accessible by simplifying the process of booking doctor appointments. It offers three levels of login: *Patient, **Doctor, and **Admin, each with distinct features tailored to their roles. The app integrates **online payment gateways (Stripe and Razorpay)* to facilitate seamless and secure payments. Built using the *MERN stack* (MongoDB, Express.js, React.js, and Node.js), Prescripto provides an efficient, user-friendly experience for both patients and healthcare providers.


#Demo
<br>
*UI* 👉 [LINK](https://prescripto-frontend-lovat.vercel.app)
<br>
*Admin Dashboard* 👉 [LINK](https://prescripto-admin-beta.vercel.app)

## 🛠 Tech Stack

- *Frontend*: React.js
- *Backend*: Node.js, Express.js
- *Database*: MongoDB
- *Payment Gateways*: Stripe, Razorpay
- *Authentication*: JSON Web Token (JWT)

## 🔑 Key Features

### 1. Three-Level Authentication

- *Patient Login*: 
  - Patients can sign up, log in, and book appointments with doctors.
  - Manage appointments (view, cancel, or reschedule).
  - Secure online payment options available (cash, Stripe, Razorpay).
  - User profile with editable information (name, email, address, gender, birthday, profile picture).
  

![UI](https://github.com/user-attachments/assets/f953ae81-7cc8-4b6b-8101-c3aa47d0aada)


- *Doctor Login*:
  - Doctors can log in and manage appointments.
  - Dashboard displays earnings, number of patients, number of appointments, and latest bookings.
  - Update profile details (description, fees, address, availability status).
  - View appointment details (patient info, payment mode, appointment status).

![doctor-panel](https://github.com/user-attachments/assets/ed488e0a-a61a-4cb1-b95a-f19b9135f9b2)




- *Admin Login*:
  - Admins can create and manage doctor profiles.
  - Dashboard with analytics: total doctors, total appointments, total patients, and recent bookings.
  - Add new doctors (image, specialty, degree, experience, address, fees, etc.).
  - View and manage all appointments (cancel or mark as completed).

![admin-panel](https://github.com/user-attachments/assets/5479b3c0-0663-41ec-9fe2-17434249155c)


## 📄 About Page

- Provides information about *Prescripto’s vision* and mission.
- *Why Choose Us* section highlights:
  - *Efficiency*: Streamlined appointment process.
  - *Convenience*: Online booking and payment.
  - *Personalization*: Tailored experience based on user preferences.
- Footer section with additional links.

## 📅 Doctor Appointment Page

- Displays detailed information about the selected doctor:
  - *Profile picture, qualification, experience*, and a brief description.
  - *Appointment booking form*: Choose date, time, and payment method.
  - Online payment options: *Cash, Stripe, or Razorpay*.
  - *Related doctors* section at the bottom.
- Users need to *create an account or log in* before booking an appointment.

## 👤 User Profile

- Accessible after login.
- Users can view and edit their profile:
  - *Upload profile picture*.
  - Update *name, email, address, gender, and birthday*.
- View list of upcoming and past appointments.
- *Logout* option available.
