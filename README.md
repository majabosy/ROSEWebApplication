# ROSE Web Application

## Overview
The **ROSE Web Application** is a platform designed for the management of cervical cancer screening events. It provides a user-friendly interface that enables users to browse and book upcoming screening events, ensuring accessibility to essential healthcare services. The application allows for participant registration, profile editing, volunteer sign-up, and event management by administrators. Additionally, it includes a chatbot feature for enhanced user support, allowing participants to cancel or reschedule their bookings and join waiting lists for fully booked events.

## GitHub Repository
Access the project repository [here](https://github.com/JimzSnowby/KV6002TeamProject).

## Hosted Website
The ROSE Web Application is hosted online and can be accessed [here](https://w20021570.nuwebspace.co.uk/assessment/app/).

## Installation Instructions

### Prerequisites
Ensure that you have the following installed on your machine:
- **Node.js** (version 14 or higher)
- **npm** (Node Package Manager)

### Clone the Repository
Clone the ROSE Web Application repository to your local machine:
```bash
git clone https://github.com/JimzSnowby/KV6002TeamProject.git
```

### Dependencies Installation
Install the required dependencies for the project:
```bash
npm install
npm install html2canvas jspdf
npm install react-calendar
npm install react-icons --save
npm install react-chatbot-kit
npm install react-hot-toast
npm install bcryptjs
```

In the same directory, install any additional hidden or missing dependencies or libraries:
```bash
npm i –d
```

### Tailwind CSS
Since **Tailwind CSS** is already integrated into the project, it will be automatically configured during the build process. If you wish to install it locally, use:
```bash
npm install -D tailwindcss postcss autoprefixer
```

### Start the Application
To start the development server and run the application locally, execute:
```bash
npm run dev
```
The application will open in your default web browser at the URL specified in the terminal.

## System Credentials
This section provides login credentials for different user roles within the ROSE Web Application. Use the following credentials to access the respective functionalities.

### Admin Credentials
- **Head of Admin:**  
  - **Email:** bobby@gmail.com  
  - **Password:** bobby  

- **Regular Admin:**  
  - **Email:** katy@gmail.com  
  - **Password:** katy  

### Participant Credentials
New participants can register through the **“Become a Participant”** menu. Here are some existing participant accounts:
| Email               | Password   |
|---------------------|------------|
| farah@gmail.com     | password1  |
| aisha@gmail.com     | password2  |
| sandra@gmail.com    | password3  |
| foo@gmail.com       | password4  |
| rebecca@gmail.com   | password5  |
| alice@gmail.com     | password6  |

### Volunteer Credentials
Volunteers can sign up via the **“Become a Volunteer”** tab on the website. Here is an existing volunteer account:
- **Email:** rahman.lee@gmail.com  
- **Password:** volunteer123  

## Features
- **Event Management:** Users can browse and book upcoming cervical cancer screening events.
- **Registration:** New participants can provide essential information for event attendance.
- **Profile Editing:** Registered users can edit their profiles to ensure accurate information.
- **Volunteer Sign-Up:** Volunteers can register to support screening events, facilitating recruitment and coordination.
- **Admin Access:** Administrators have specialized features for managing events, users, and other platform aspects.
- **Newsletter Subscription:** Sponsors and supporters can sign up to receive newsletters.
- **Chatbot Support:** A chatbot feature is available to assist users with common queries.
- **Booking Management:** Participants can cancel or reschedule their bookings and join waiting lists for fully booked events.

