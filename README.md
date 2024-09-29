## What is L(earn)-app?

# Driving School Management Application with Business Model Inspired by Booksy

## Author: Filip Cyboran  
## Supervisor: Dr. Piotr Lasek  
## Field of Study: Computer Science  
## Type of Work: Engineering Thesis

## Project Overview:
This project involves creating a mobile application to facilitate the management of the driving school learning process. The application draws inspiration from the business model of the popular service platform Booksy. The app will allow users to sign up for driving courses, manage schedules for theoretical and practical lessons, and book exams. Additionally, it will offer various features to support both students and instructors, including:

- User registration and login through Apple, Google, Facebook, or via a traditional form.
- Automatic detection of the user's location and displaying nearby driving schools.
- Profile management, including adding or changing profile photos.
- A schedule of theoretical and practical lessons, along with information about the instructors.
- A list of instructors with the ability to view their availability and book lessons.
- Communication options with the driving school's office or instructors via phone, email, or chat.
- The ability to purchase a premium version, offering AI-driven educational tests and additional features.

## Innovation and Practical Value:
The innovation of this project lies in adapting the Booksy business model to the driving education sector and enhancing it with AI-based personalization features. The application integrates advanced communication between students and instructors, as well as driving school management, which is currently missing in the market. The project bridges the gap between traditional and modern approaches to course enrollment and lesson management in driving schools.

## Technology Stack:
The project will use modern backend technologies, such as Java with the Spring Boot framework and a MySQL database, and cutting-edge frontend technologies like React Native for mobile app development. Additionally, the project will leverage several AWS services for cloud infrastructure, including:

- **Amazon RDS** for managing the MySQL database.
- **Amazon EC2** for hosting the backend server.
- **Amazon S3** for storing user-uploaded files such as profile photos.

OAuth will be implemented for secure authentication through popular platforms like Apple, Google, and Facebook.

### Project Management & Design:
- **Scrum methodology** will be followed using **Jira** for task management and sprint planning.
- **Figma** will be used for UI/UX design and prototyping.
- The project will include **UML diagrams** to model the system architecture and design.


## How to use this repository?

### clone the Repository of the Fucking coolest app in Da World 

```bash
git clone --recurse-submodules https://github.com/cyboranf/-L-earn-mobile-application/
```

### update the Submodules of the Fucking Best app in Da World 

```bash
git submodule update --remote --merge
```

```bash
git add .
git commit -m "submodules - updated, cause we're not about that stale code life"
git push

