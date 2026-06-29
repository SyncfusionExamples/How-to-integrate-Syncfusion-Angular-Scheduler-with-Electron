# Angular-Electron Integration with Syncfusion Scheduler

This project is a desktop application built with Electron and Angular, integrating [Angular Scheduler](https://www.syncfusion.com/angular-components/angular-scheduler) for advanced event management capabilities. It delivers a full desktop experience with multi-view scheduling and built-in CRUD operations. This implementation demonstrates how to seamlessly combine Angular with Electron to create a robust, cross-platform desktop solution using the Angular Scheduler with enterprise-grade scheduling features.

## Features
- **Multi-View Scheduling:** Support for various calendar views including day, week, month, and agenda views
- **CRUD Operations:** Complete create, read, update, and delete functionality for events
- **Cross-Platform Desktop App:** Built with Electron for Windows, macOS, and Linux compatibility
- **Angular Integration:** Leverages Angular's powerful component architecture and data binding
- **Event Management:** Full-featured event management with support for recurring events and resource scheduling
- **Responsive Design:** Adaptive UI that works seamlessly across different screen sizes

## Prerequisites
Ensure the following tools are installed:
- Node.js 16+
- npm 8+
- Angular CLI
- Electron

## Installation
1. **Clone the project**
2. **Install dependencies**
    ```bash
    npm install
    ```

## Running the Application
### Build the Angular application
```bash
npm run electron-build
```
### Start the Electron desktop app
```bash
npm run electron
```

## Configuration
The application can be configured through Angular environment files and Electron main process settings. Customize event sources, scheduler views, and desktop window properties to suit your requirements.

## Documentation
For detailed information about the Syncfusion Scheduler component and Angular integration, refer to the following resources:

- **Angular Introduction:** https://ej2.syncfusion.com/angular/documentation/introduction
- **Angular Schedule Component:** https://ej2.syncfusion.com/angular/documentation/schedule/getting-started
- **Syncfusion Components:** https://help.syncfusion.com/