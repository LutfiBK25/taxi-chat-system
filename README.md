# IN-APP Chat System for Company Like Uber
### Goal: Build an in-app chat service that enables communication between riders and drivers without revealing personal phone numbers.

## Requirments:
- Riders & Drivers must sign in, secure password reset (optional Two-factor authentication)
- User profiles: Name, Profile Pic, User type. (Data can be updated)
- Riders or Drivers can initiate chat with the other party (Other party should recive a notification)
- Real-time Messaging (optionally support other media types like pictures and videos), indicators (sent, delivered, seen)
- Users can look at thier past history (Make sure it is securly stored)
- Notifications even chat app is not open.
- encrypted messaging and phone numbers masked.
- number of messages sent should be limit in a short time for spam
- chat remains active for duration of ride and additional 5 minutes after drop off then it becomes read-only for both parties.
- chat can only be initiated once the app matches the rider with a driver.


## Notes:
### App should track Ride Status
- Search for a driver
- Driver found but not yet picked up
- Rider picked up and ride in progress
- Rider dropped off
- chat is read-only 


## Phases:
- Phase 1: Design & Setup

Design database schema.
Setup project structure with Spring Boot and necessary dependencies.
Initial setup of frontend project structure (if applicable).
- Phase 2: Core Features

User authentication.
Profile management.
Real-time chat implementation.
- Phase 3: Advanced Features

Message status indicators.
Chat history & retrieval.
Notifications.
- Phase 4: Security & Optimization

Implement rate limiting.
Enhance security features.
Performance optimization.
- Phase 5: Deployment & Testing

Deploy the application on the cloud.
Rigorous testing for bugs, vulnerabilities, and performance.
- Phase 6: Feedback & Iteration

Collect user feedback.
Implement necessary changes based on feedback.


# Lets Start

