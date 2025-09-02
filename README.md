# TaskFlow - Professional Task Management App

A comprehensive task management and team collaboration Progressive Web App (PWA) built with Firebase.

## 🚀 Features

- **📱 Mobile App**: Installable PWA with offline support
- **👥 Team Collaboration**: Multi-user task assignment and management
- **📊 Analytics Dashboard**: Task completion tracking and insights
- **📅 Calendar View**: Visual task scheduling and deadline management
- **🔔 Real-time Notifications**: Instant updates across all devices
- **📋 Kanban Board**: Drag-and-drop task management
- **📈 Project Management**: Organize tasks by projects with progress tracking
- **🔐 Secure Authentication**: Google OAuth integration
- **📱 Cross-platform**: Works on desktop, mobile, and tablet

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Firebase (Firestore, Authentication, Hosting)
- **PWA**: Service Worker, Web App Manifest
- **Charts**: Chart.js for analytics
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)

## 🌐 Live Demo

**App URL**: https://taskflow-chd8c.web.app

## 📱 Installation

### Mobile (Android/iOS):
1. Visit the app URL in your mobile browser
2. Tap "Add to Home Screen" when prompted
3. The app will install like a native mobile app

### Desktop:
1. Visit the app URL in Chrome/Edge
2. Click the install icon in the address bar
3. Click "Install" to add to your desktop

## 🏗️ Local Development

1. Clone the repository
2. Configure Firebase:
   - Copy `js/config-template.js` to `js/config.js`
   - Add your Firebase configuration
3. Install Firebase CLI: `npm install -g firebase-tools`
4. Login to Firebase: `firebase login`
5. Deploy: `firebase deploy`

## 📋 Project Structure

```
TaskFlow/
├── index.html          # Main application file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── js/
│   ├── config.js      # Firebase configuration
│   └── config-template.js
├── firebase.json      # Firebase hosting config
├── firestore.rules    # Database security rules
└── firestore.indexes.json
```

## 🔧 Configuration

1. Create a Firebase project at https://console.firebase.google.com
2. Enable Authentication (Google provider)
3. Enable Firestore Database
4. Enable Hosting
5. Update `js/config.js` with your Firebase config

## 👥 User Roles

- **Admin**: Full access to user management and all features
- **Manager**: Task and project management capabilities
- **Member**: Basic task management and collaboration

## 📊 Features Overview

### Dashboard
- Task statistics and completion rates
- Recent tasks overview
- Deadline alerts and overdue notifications
- Performance charts and analytics

### Task Management
- Create, edit, and delete tasks
- Assign tasks to team members
- Set priorities and due dates
- Add comments and updates
- Bulk import from CSV

### Project Organization
- Create and manage projects
- Color-coded project identification
- Project progress tracking
- Task grouping by projects

### Calendar Integration
- Monthly and yearly calendar views
- Task scheduling and deadline visualization
- Overdue task identification

### Analytics
- Completion rate tracking
- Performance insights
- Productivity scoring
- Timeline analysis

## 🔔 Notifications

- Real-time task assignments
- Status change notifications
- Comment notifications
- Deadline reminders
- Cross-device synchronization

## 🛡️ Security

- Firebase Authentication
- Firestore security rules
- User role-based access control
- Data validation and sanitization

## 📱 PWA Features

- Offline functionality
- App-like experience
- Push notifications
- Home screen installation
- Fast loading with caching

## 🚀 Version History

- **v1.0.0**: Initial stable release with full mobile app functionality

## 📄 License

This project is proprietary software developed for internal use.

## 👨‍💻 Developer

Developed by Musaddiq Hasan for JS Bank Limited - IT Network & Security Team.