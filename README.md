# Client-CRM-Lite
Client CRM Lite
📊 Concept
Client CRM Lite is a lightweight, browser-based CRM (Customer Relationship Management) application designed to help individuals or small businesses track their contacts, manage conversations, monitor deal values, and set follow-up reminders. It's built for simplicity and ease of use, providing essential CRM functionalities without unnecessary complexity.

💡 Features
Contact Management:

Add new contacts with details such as Name, Email, Phone, Last Conversation Date, Deal Value, Notes, and Tags.

Edit existing contact information.

Delete contacts.

Contact Cards with Tags:

Each contact is displayed as a card, showing key information at a glance.

Tags allow for easy categorization and filtering of contacts (e.g., "Lead," "VIP," "Hot").

Sorting Options:

Sort contacts by Name (alphabetical), Last Conversation Date (most recent first), or Deal Value (highest first).

Search Functionality:

Quickly find contacts by searching their name, tags, or notes.

Reminder System for Follow-ups:

Set a "Next Follow-up" date for each contact.

A modal automatically appears on load if there are any follow-ups due today or in the past.

Mark individual reminders as "Done" or clear all pending reminders.

Local Storage Persistence:

All contact data is saved directly in your browser's Local Storage, meaning your data persists even if you close the browser tab or window.

Custom Message Boxes:

Uses custom-designed alert and confirmation dialogs for a consistent user experience, replacing native browser prompts.

Responsive Design:

The interface is designed to be usable across various screen sizes, from mobile devices to desktops, thanks to Tailwind CSS.

🔧 Technologies Used
HTML5: For the structure and content of the web page.

Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

JavaScript (ES6+): For all interactive functionalities, data management, and DOM manipulation.

Font Awesome: For various icons used throughout the application.

🚀 How to Use
Open the Application: Simply open the index.html file in your web browser.

Add a New Contact:

Fill in the "Add New Contact" form at the top.

Fields marked with * are required.

Separate tags with commas (e.g., Lead, Hot, Follow-up).

Click "Add Contact" to save.

Manage Contacts:

Each contact appears as a card below the form.

Edit: Click the "Edit" button on a contact card to pre-fill the form with its details, then click "Update Contact" to save changes.

Set Follow-up: Click "Set Follow-up" to choose a date for your next interaction.

Delete: Click "Delete" to remove a contact. A confirmation prompt will appear.

Filter and Sort:

Use the "Sort by" dropdown to arrange contacts by name, last conversation, or deal value.

Type into the "Search" bar to filter contacts by name, tags, or notes.

Handle Reminders:

If you have any follow-ups due, a "Upcoming Follow-ups" modal will appear automatically when you load the page.

Click "Done" next to an individual reminder to clear it.

Click "Mark All Done" to dismiss all pending reminders.

You can close the reminder modal at any time using the "X" button.

💾 Data Persistence
This application uses your browser's localStorage to save your contact data. This means your contacts will remain in the application even if you close and reopen your browser.

Note: localStorage is specific to your browser and device. Your data will not be synchronized across different browsers or devices.
