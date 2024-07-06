# Sleep Tracker App for Informatics 133

## Project Overview
This project is a mobile application built using the Ionic framework to help users track their sleep patterns and daytime sleepiness. The primary functionalities include logging overnight sleep, logging sleepiness levels during the day, and viewing these logs. Additional enhancements such as native device feature utilization and persistent data storage are also included.

### Students
- Hannah Huynh
- Farahnaz Hoque

## Development Setup
- **Node.js Version:** Ensure Node.js 20.11.0 LTS or newer is installed.
- **Ionic CLI:** Install Ionic CLI globally via `npm install -g @ionic/cli`.
- **Primary Framework:** Angular

## Functional Specifications

### User Interface Development
- User-friendly interface for logging and viewing sleep data.
- Intuitive components such as buttons, input fields, and lists.

### Sleep Logging Features
- Log when users went to bed and when they woke up.
- Convenient input method for use right after waking up or before going to sleep.

### Daytime Sleepiness Logging
- Implement the Stanford Sleepiness Scale (1-7) for logging sleepiness throughout the day.
- Reminders/notifications to prompt users to log their sleepiness at various times.

### Data Viewing Capabilities
- Views to show both sleep and sleepiness logs, either together or separately.
- Clear data presentation providing insights into user’s sleep habits.

### Native Device Resource Utilization (Option 1)
- Enhance user experience by leveraging native device resources like the accelerometer or notification system.
- Practical applications such as assessing sleep quality via accelerometer data or using reminders for sleepiness logging.

### Persistent Data Storage (Option 2)
- Data storage solutions using either Firebase or local storage to retain data after app restarts.
- Functionalities for managing (viewing, editing, deleting) the stored data.

## Technical Requirements
- **Integration of Starter Code:** Incorporate the provided starter code into the new Ionic project.
- **Dependencies Management:** Install and manage all necessary dependencies, including the nanoid package for UUID generation.
- **Testing and Deployment Preparation:** Use `ionic serve` for local testing and prepare the app for potential deployment on both Android and iOS.

## Documentation

### Project Progress
- Regular updates on progress, design decisions, resources used, and obstacles encountered.
- Detailed setup and operation instructions included.

### Design Choices
- Justifications for design choices aligning with good principles of mobile design.
- Any additional features or significant deviations from the starter code should be documented.

## Project Setup Instructions

1. **Clone Repository:**
   ```bash
   git clone <repository_url>
   cd a4-sleeptracker
2. **Install Ionic CLI:**
   ```bash
   npm install -g @ionic/cli
3. **Install Dependencies:**
   ```bash
   npm install
4. **Start the Ionic App:**
   ```bash
   ionic serve

## Development Notes
### Dependencies
1. **Node.js:** v20.11.0 LTS or newer
2. **Ionic CLI:** Latest version
3. **Nanoid:** For UUID generation
