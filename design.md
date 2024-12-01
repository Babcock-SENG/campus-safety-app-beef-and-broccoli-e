# Use Case Diagram

## Actors:

- _Student_: The primary user who interacts with the app for various safety-related features.
- _Campus Security_: The staff responsible for monitoring safety events, providing updates, and responding to emergencies.
- _App System_: The mobile application platform that interacts with both the students and campus security, providing necessary services.

## Use Cases:

- _View Emergency Contacts_:  
  Students can view important emergency contacts, such as campus security, local police, hospital, etc.

- _Receive Campus Security Updates_:  
  Students receive push notifications or alerts about security incidents or campus safety updates (e.g., lockdowns, warnings).

- _View Real-Time Safety Map_:  
  Students can see a map of the campus with live safety information, such as areas with recent security incidents, active patrol routes, or evacuation zones.

- _Report Safety Concerns_:  
  Students can report suspicious activity or other safety-related issues directly to campus security via the app.

- _Administer Security Alerts_:  
  Campus security can send updates or alerts to students through the app.

- _Monitor Reports_:  
  Campus security can view reported safety concerns, track incident reports, and respond as necessary.

## Relationships:

- _Student_ can interact with the app to:

  - View emergency contacts.
  - Receive updates about campus security.
  - View the real-time safety map.
  - Report safety concerns.

- _Campus Security_ interacts with the app to:
  - Administer security alerts.
  - Monitor reported safety concerns.

---

# Process Model

## What Process Model are we using and why?

We’re using the _Agile process model_. This is because it is flexible, iterative, and is the most suitable for our time constraint. It also allows for simultaneous working on deliverables.

---

# Scenario Analysis

## Scenario 1: Emergency Contact Access

### Situation:

A student witnesses a suspicious incident on campus late at night and needs to report it immediately.

### User Actions:

1. The student opens the app and selects the "Emergency Contacts" feature from the home screen.
2. The app displays a list of emergency numbers, including campus security, local police, and a 24/7 helpline.
3. The student taps the "Call Campus Security" button to report the incident.

### Challenges:

- Ensuring the app loads quickly in stressful situations.
- Providing localized emergency contact details based on the user’s location.

### Opportunities:

- Add an "SOS" button for immediate action without navigating menus.
- Integrate quick call shortcuts for faster response.

---

## Scenario 2: Campus Security Update Notification

### Situation:

A power outage affects a part of the campus, raising safety concerns for students in nearby areas.

### User Actions:

1. A push notification alerts users: "Power outage in Building B. Avoid the area. Updates to follow."
2. The student opens the app to read detailed instructions and safety tips, such as avoiding dark areas and using alternative routes.
3. The app provides a map highlighting affected zones and safe pathways.

### Challenges:

- Ensuring timely and reliable delivery of notifications.
- Balancing the volume of notifications to avoid overwhelming users.

### Opportunities:

- Allow users to customize alert preferences (e.g., types of updates they receive).
- Incorporate location-based notifications for proximity-specific alerts.
