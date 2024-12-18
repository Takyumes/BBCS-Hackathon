# Warmth & Care Hub - An Interactive Support Platform for the Homeless

Welcome to **Warmth & Care Hub**, a web application designed to connect volunteers, organizers, and support centers to help the homeless community effectively. The platform includes event dashboards, interactive maps, and tools to facilitate volunteering and donations.

---

## **Project Idea**

**Warmth & Care Hub** aims to:
1. Allow organizers to create and manage events for volunteers (e.g., food drives, fundraising, shelter work, food aid-delivery).
2. Enable volunteers to discover and sign up for events.
3. Display local food banks, donation centers, and events on a **map** using OpenStreetMap.
4. Provide a centralized platform to **connect organizers, volunteers, and those in need**.

---

## **Core Features**
- **Account Creation** Organizers and Volunteers Alike can register and log in based on their role(org or volunteering), Account Widget on top right corner of dashboard allow user to view account details
- **Event Creation:** Organizers can create events with titles, descriptions, categories, dates, and locations.
- **Event Dashboard:** A dashboard for organizers and volunteers to manage and discover events.
- **Interactive Map:** Displays event locations, food banks, and donation centers.
- **Filters:** Volunteers can filter events by **category** and **date**.
- **Event Details Page:** Provides detailed event information with an option for organizers to edit or cancel events.

---

## **Accessing the Files**

Follow the steps below to access and run the project:

### **1. Clone the Repository**
Use the following Git command to clone the repository:
```bash
git clone https://github.com/your-username/Warmth-and-Care-Hub.git

### **2. Set Up Firebase**
To run this project locally or deploy it, follow these steps:

1.  Create a Firebase Project:
- Go to Firebase Console.
- Create a new project.

2.  Set Up Firestore:
- Go to Firestore Database → Create a new database (start in test mode).

3.  Get Your Firebase Configuration:

- Add a Web App in Firebase Console to get the configuration keys.

4. Replace Firebase Configuration: Replace the Firebase configuration in all .html and script files:

`const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_ID",
    appId: "YOUR_APP_ID"
};`

5. Run the Project: 
Use a local server to test the project (e.g., VS Code Live Server or npx http-server).


