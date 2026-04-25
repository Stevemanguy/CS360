Overview

This artifact is a completed mobile app project developed in CS 360. The application is an inventory app designed to help users keep track of item quantities on a mobile device. The app was built to support simple inventory management in work settings where stock levels 
may change often and need to be updated quickly. It gives users a way to create an account, log in, add inventory items, adjust quantities, delete items, and receive an SMS alert when an item reaches zero.

This project was designed to address a practical user need. A user in a warehouse, retail setting, or small business may need a simple way to monitor inventory without using a large or expensive system. The app was meant to focus on that need by keeping the features 
direct and easy to use.

Screens and Features

The app includes a login screen and an inventory screen. The login screen allows a new user to create an account and allows an existing user to sign in. This supports the need for basic account access and persistent user data. The inventory screen allows a user to add 
items, change quantities, and remove items from the database. It also displays inventory records in a clear list so the user can review current stock.

The UI was designed with the user in mind by keeping the layout simple and focusing on the main tasks the user needed to complete. The login screen only includes the fields and buttons needed to create an account or log in. The inventory screen places the item entry 
fields near the top and the list of current items below that. This supports a straightforward workflow where the user can enter information, review it, and make changes without moving through unnecessary screens. I think the design was successful because it stayed 
focused on the app’s main purpose and avoided extra features that would have made the interface more confusing.

Coding Approach

My approach to coding this app was to build it in smaller pieces instead of trying to complete everything at once. I first created the layouts, then worked on the database helper, then added the login and account creation logic, and finally connected the inventory 
features and SMS alert behavior. Breaking the project into smaller steps made it easier to test each part and find problems before moving on.

One technique I used was to focus on one main feature at a time and test it before adding the next one. I also relied on clear naming for classes, variables, and methods so the code was easier to follow. This approach can be applied in future projects because it makes 
development feel more manageable and helps reduce confusion when something is not working.

Testing Process

I tested the app throughout development by using the Android Emulator. I checked whether account creation worked, whether login credentials were saved correctly, whether inventory items could be added and removed, and whether quantities updated properly. I also tested 
the SMS permission behavior to make sure the app still worked if permission was denied and that it could send a text alert when permission was granted.

This process was important because it revealed problems that were not obvious just by looking at the code. For example, some layout issues affected whether text boxes were visible, and some logic issues affected whether input fields were being read correctly. Testing 
helped identify those problems and made it easier to fix them before moving forward.

Innovation and Problem Solving

One challenge during the full design and development process was getting all the parts of the app to work together in a consistent way. It was not enough to make the screens look correct. The user interface, database, and app logic all had to connect properly. I had to 
make adjustments when parts of the layout did not appear correctly and when the inventory screen was not reading user input the way I expected.

Another challenge was the SMS feature. Even after permission was granted, testing it required checking whether the alert was actually being sent in the emulator. I had to troubleshoot that process and confirm that the app was sending SMS messages through the emulator’s 
messaging system. That required some trial and error, but it helped me better understand how app behavior and testing tools work together.

Strongest Area of the Project

The part of the project where I think I was most successful was connecting the app’s user interface to the database and making the app perform the main inventory tasks. The app allows a user to create an account, log in, add items, update quantities, delete records, and 
trigger an SMS alert when stock reaches zero. That part of the app showed my understanding of how the front end and back end of a mobile app work together. It also showed that I could take a planned design and turn it into a functioning application.

Files Included

This repository includes the completed Android Studio project ZIP file for the app. That file contains both the finalized UI design and the completed code used to make the app functional. The project reflects the full development process from planning and design to 
coding and testing.
