# StudyNotion - Ed-Tech Platform

![StudyNotion Logo](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMgAAAAoCAYAAAC7HLUcAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAsYSURBVHgB7VyLURtJEG3hf5WrTo7gRAQWEdwSweEIwBGAI0BEYByBRQSGCCQisBwBexFYrnKVf9hcv3WPrtWa2ZkVayHO86oWtKv5T/f0d9WhJfHp06ei0+k85avg2z5fXbmAKT8vr66uyh8/frzj+/GjR4/GlJFxy9BpUpgJvnt5ebnPRH9A/zFDKkpmmvH379+PmFlKysi4BUhiEDDGt2/fDvn/AbUAZpRhZpSM24Aog3z9+nWfGWNAzSVGDJAog/v3759QRsaaopZBmDletiU1ggPodI6ZSV5QRsYawssgolK94f8FrWIQnc7k3r172/x/ShkZawQvg7DkeMvM0adVDoQNeJYk25SRsUbYsA9ErUpljil7tI742uZr88GDBx1cTOhPWAJt8bPnXOY0pSFIK/RNGRlrhDkJwrGNvY2NjdcJ9RDnOEg1sLndHrcL4t+JlWVGefHw4cNjugagIn7+/LlyKnBb09uiuiG25D7fuXNnyus7od8MQitv+GMf3k5eg+d0g5gxiAxsxB97kToI/m0v46LlPgbcx2GkGAhjcxmiBoMzYe16bCcwyWmdaxnzd59viqm+fPly5T7zHMY8jmurnCyVR9xWzz7H/Hidt8g/jgs1jmMexytqCbF15r7BHLODVGhtTDcErWIN6BcyB8D1BhRXuaqYCzUAJAYIAdIv4Fjo8nNIxxGX86qP+I6vC1yySf8LCHMsXFCjtcQy0OWeUIuIrTP39w+tEe7ij0iP3VhhxC18zCEqDQivkHLv+dmZryxEJhMpygXjKnAt83WUeopz38c8/kI9Qj3EWaaKQABsOLxzW9ljVqlx2PMxrREgsUBPPLY/+TA+u+kUJSdBBgllpz6bA8wFr5ecDIe4ENvACeGTBEKYY4qAiT45/mKYG1Jui50FW/CK8f9NXnCtIvT45Nqj3xC8LufwFrp7XpcdECOtEXCo8rWHvbuuLdoGKgnCBPZXrCAvpNdgZE5/7dNxAd6QATPQuT0F2BY453q1BjuPaZ8SGFfrtAAIwEouZpIBMzGYyBFDwVe1+CJ9/tCEwm30uXzlrHBGoqTazPryGY+uDoAkTbvBLpcNaiDaksNiErGNCjnpXRtnPJ8FNZWZfofb+7tufNzOBff/jv8X8qgrh0VjQsS4ZI+gOfTwDPGs0HxS19nOw9eWWUeXKDuV/pHGdO6rw3v4UrV7ArqUTJEDmUPVBn/33NXvyERHFEHIoyAGXa+m6ilEpXlWpKh0KQaaqIcXapzeeApsD554tTn8f/r48eNJyvjhtpb6I23fuOcadUa2bNAo4ELHxmzzd29tfbGvMMZu3fy4b9Tt2771/LCHHJB9EWtPzwN




## Project Description

StudyNotion is a fully functional ed-tech platform built on the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS). The platform facilitates the creation, consumption, and rating of educational content, aiming to provide:

- A seamless and interactive learning experience for students, making education accessible and engaging.
- A platform for instructors to showcase expertise and connect with learners globally.

## Table of Contents

1. [System Architecture](#system-architecture)
2. [Front-end](#front-end)
3. [Back-end](#back-end)
4. [API Design](#api-design)
5. [Deployment](#deployment)
6. [Testing](#testing)
7. [Future Enhancements](#future-enhancements)
8. [Conclusion](#conclusion)

---

## System Architecture

The StudyNotion platform comprises three main components: front end, back end, and a MongoDB database. It follows a client-server architecture, with ReactJS for the front end, NodeJS/ExpressJS for the back end, and MongoDB for the database.

**[Architecture Diagram](#link_to_your_diagram)**

## Front-end

The StudyNotion front end is designed using ReactJS and Figma for a clean, minimalistic interface. Key pages include:

### For Students:
- Homepage
- Course List
- Wishlist
- Cart Checkout
- Course Content
- User Details
- User Edit Details

### For Instructors:
- Dashboard
- Insights
- Course Management Pages
- View and Edit Profile Details

### For Admin (future scope):
- Dashboard
- Insights
- Instructor Management
- Other Relevant Pages

Frameworks and tools used: ReactJS, CSS, Tailwind, Redux, VSCode.

**[Figma Design](https://www.figma.com/file/Mikd0FjHKAofUlWQSi70nf/StudyNotion_shared)**

## Back-end

### Back-end Architecture:

StudyNotion uses a monolithic architecture with Node.js, Express.js, and MongoDB. Features include:

- User authentication and authorization
- Course management
- Payment Integration (Razorpay)
- Cloud-based media management (Cloudinary)
- Markdown formatting

Frameworks, libraries, and tools used: Node.js, MongoDB, Express.js, JWT, Bcrypt, Mongoose.

### Data Models and Database Schema:

- Student schema
- Instructor schema
- Course schema

## API Design

The StudyNotion API follows REST principles and is implemented using Node.js/Express.js. Sample endpoints:

- /api/auth/signup (POST)
- /api/auth/login (POST)
- /api/auth/verify-otp (POST)
- /api/auth/forgot-password (POST)
- /api/courses (GET, POST, PUT, DELETE)
- /api/courses/:id/rate (POST)

**[Sample Requests and Responses](#link_to_api_docs)**

## Deployment

The deployment involves hosting on various cloud services:

- Front end: Vercel
- Back end: Render or Railway
- Media files: Cloudinary
- Database: MongoDB Atlas

**[Hosting Environment and Infrastructure](#link_to_deployment_docs)**

## Testing

Details of the testing process, types of testing, and frameworks/tools used.

## Future Enhancements

1. **Gamification features**: Badges, points, and leaderboards for increased user engagement (Medium Priority).
2. **Personalized learning paths**: Tailoring learning paths based on individual interests (High Priority).
3. **Social learning features**: Group discussions, peer-to-peer feedback, and collaborative projects (Medium Priority).
4. **Mobile app**: Enhanced accessibility for users (High Priority).
5. **Machine learning-powered recommendations**: Personalized course recommendations (Medium to High Priority).
6. **VR/AR Integration**: Immersive learning experiences (Low to Medium Priority).

## Conclusion

StudyNotion is designed to deliver a versatile and intuitive ed-tech experience. This document provides an overview of the platform's architecture, features, deployment, and future enhancements. The platform's development journey will involve overcoming challenges while achieving project milestones.
