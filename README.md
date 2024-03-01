# Real-time-Chat-Messenger
This project is a Chat Server Playground built with Django, incorporating various features for user management, friend system, public and private chatrooms, real-time notifications, and deployment to production.

## Features

### User Management
- **Registration:** Users can register for an account.
- **Login:** Registered users can log in to their accounts.
- **Logout:** Users can log out of their accounts.
- **Forgot Password:** Option to reset forgotten passwords.
- **Change Password:** Users can change their passwords.
- **View Accounts:** Users can view their account details.
- **Update Account Properties:** Users can update their account information.
- **Search for Other Users:** Search functionality to find other users.

### Friend System
- **Send Friend Requests:** Users can send friend requests to other users.
- **Accept Friend Requests:** Ability to accept incoming friend requests.
- **Decline Friend Requests:** Users can decline friend requests.
- **Cancel Friend Requests:** Option to cancel outgoing friend requests.
- **Remove Friends:** Users can remove friends from their list.

### Public Chatroom
- **Public Chatroom:** A chatroom accessible to all authenticated users.
- **Real-time Chat:** Utilizes Django Channels and WebSockets for real-time messaging.

### Private Chatroom
- **1-on-1 Conversations:** Private chat feature for users to have one-on-one conversations.
- **Real-time Chat:** Implements Django Channels and WebSockets for instant messaging.

### Notifications
- **Real-time Notifications:** Users receive real-time notifications for events such as friend requests and private chat messages.
- **Actionable Notifications:** Ability to accept or decline friend requests directly from notifications.

### Push to Production
- **Purchase a Domain:** Acquire a domain for hosting the website.
- **Host on Digital Ocean:** Deploy the website on Digital Ocean.
- **Redis Configuration:** Configuration for Redis as a cache and message broker.
- **Daphne for Sockets:** Utilizes Daphne for handling WebSocket connections.

