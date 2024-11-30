# my-portfolio
A collection of my software development projects.
# My Project Portfolio  

Welcome to my portfolio repository! Here, you'll find a collection of my software development projects. Each project showcases a different aspect of my skills and interests. Click on the links below to explore them in more detail.  

## Projects  

### 1. [Antonie Motors Mobile Application](https://github.com/username/project-repo](https://github.com/PerlaJbara/XBCAD7319-MobileAppPOE.git)  
The Antonie Motors Mobile Application simplifies business management for automotive service providers with tailored tools for Admins and Employees, secured via Role-Based Access Control (RBAC). Built using Kotlin in Android Studio (Iguana) and Firebase, it ensures efficient data storage and authentication.

Key Features
Common Features
User Registration/Login: Role-specific registration with admin approval and biometric login support.
Persistent Data Storage: Firebase-powered secure storage.
Settings Management: Update passwords, delete accounts, and log out.
Admin Features
Quote & Receipt Generator: Create and edit PDFs with biometric authentication.
Customer & Vehicle Management: Manage customer profiles, vehicle details, and images.
Inventory Tracking: Stock and parts management with low-stock alerts.
Employee Management: Approve registrations, manage leave requests, and assign tasks.
Analytics Dashboards: Insights into customers, vehicles, and employee performance.
Employee Features
Leave Requests: Submit and track leave approvals.
Task Management: Update tasks, set reminders, and view task history.
Leaderboard: Monthly task completion ranking.
Profile Management: Update personal details and profile pictures.


System Requirements

Software:

IDE: Android Studio (Iguana)
Database: Firebase (Realtime Database, Storage, Authentication)
Target SDK: 35 | Minimum SDK: 27

Hardware:

Processor: Quad-Core 1.8 GHz+
RAM: 4GB (8GB recommended)
Storage: 500MB+ free space
OS: Windows 10/11 or macOS Mojave+
Android Device: API Level 27+
Setup Instructions

Clone the Repository:

https://github.com/PerlaJbara/XBCAD7319-MobileAppPOE.git 

Configure Firebase: Add google-services.json and enable Realtime Database, Authentication, and Storage.
Set SDK Versions: Ensure Target SDK = 35 and Minimum SDK = 27.
Build and Run: Use an emulator or device with API Level 27+ to explore features.



### 2. [Antonie Motors Web Application](https://github.com/username/project-repo](https://github.com/Daniel-Antonie/AntonieMotors-XBCAD7319.git)  
The Antonie Motors Web Application streamlines business operations and enhances customer experiences with Role-Based Access Control (RBAC). Built using ASP.NET Core MVC and Firebase, it offers specialized features for Admins and Customers.

Key Features
Role-Based Access Control (RBAC)
Admins: Access business metrics, manage employees, vehicles, customers, and service records.
Customers: Access profiles, track vehicle services, and view payment receipts.
Admin Features
Admin Dashboard: Manage client profiles, service records, employees, and schedules.
Analytics Dashboard: Metrics on services completed, pending, and durations.
Service History & Documents: Generate and view service history, quotes, and receipts.
Customer Features
Vehicle Tracking: Real-time updates on service progress (e.g., “In Progress,” “Awaiting Parts,” “Completed”).
Profile Access: View personal details and payment history.
Shared Features
Business Information Hub: A landing page with service details, contact information, and locations.
Secure Login/Registration: Admin and customer-specific login and registration.
System Requirements
Software:

IDE: Visual Studio 2022+
Framework: .NET 8
Database: Firebase (Realtime Database, Storage, Authentication)

Hardware:

Processor: Dual-Core 2.0 GHz+
RAM: 4GB (8GB recommended)
Storage: 500MB+ free space
OS: Windows 10+

Setup Instructions

Clone the Repository:
https://github.com/Daniel-Antonie/AntonieMotors-XBCAD7319.git  
Restore Dependencies:
Open the solution in Visual Studio.
Use NuGet Package Manager to install missing dependencies.
Configure Firebase:
Add Firebase credentials to appsettings.json:
json
Copy code
{
  "Firebase": {
    "ApiKey": "<YourApiKey>",
    "AuthDomain": "<YourAuthDomain>",
    "DatabaseURL": "<YourDatabaseURL>",
    "ProjectId": "<YourProjectId>",
    "StorageBucket": "<YourStorageBucket>"
  }
}
Run the Application:
Set the project as the startup project.
Press Ctrl+F5 and navigate to http://localhost/ in your browser.

### 3. [Gourmet Guru] (https://github.com/username/project-repo](https://github.com/PerlaJbara/OPSC7312-POE-GourmetGuru.git)  
Gourmet Guru is an innovative Android application designed to help users save, manage, and explore recipes. It utilizes a custom-built API that provides access to a diverse database of over 160 recipes spanning 8 cultural cuisines.

Key Features
Core Features
User Authentication:

Google Login (SSO): Seamless login using Google accounts.
Email Registration/Login: Secure registration and login via email and password.
Recipe Management:

Add and view custom recipes on the "My Recipes" page.
Explore a database of 8 cultural cuisines with over 20 recipes per cuisine.
Custom Collections: Create and manage personalized recipe collections by combining custom recipes and database recipes.

User-Defined Features
Meal Planning: Assign recipes to specific meals for each day of the week.
Shopping List: Generate ingredient-based shopping lists from the weekly meal plan, displayed by day or alphabetically.
Search Recipes: Search recipes across both custom collections and the database.
Filter Recipes: Filter recipes by cuisine type.
Timer with Notifications: A built-in timer with push notifications when the timer ends, even if the app is closed.
Settings and Account Management
Change Password, Logout, or Delete Account: Manage account settings from the profile page.
Account Deletion: Requires password re-entry and user confirmation.
System Requirements
For Android Emulator (Android Studio):

OS: 64-bit Windows 8/10/11
CPU: x86_64 architecture, 2nd-gen Intel Core/AMD with Hypervisor
RAM: 8GB
Disk Space: 8GB
For Android Devices:

OS: Android 8.1 (API level 27)
RAM: 1GB
Storage: 100MB
Setup Instructions
Clone the Repository:
https://github.com/PerlaJbara/OPSC7312-POE-GourmetGuru.git
Run on Android Studio Emulator:

Ensure system requirements are met.
Build and run the app from Android Studio.
Run on Android Device:

Deploy the app on an Android device running API level 27 or higher.
