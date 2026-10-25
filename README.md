# CS-360-Inventory-App

An Android inventory management application developed using Java, SQLite, and Android Studio. The app helps users track inventory, manage stock quantities, and choose whether to receive SMS notifications.

## CS-360 Module Eight Journal

### Inventory App Portfolio Reflection

#### What I Built

For my CS-360 project, I developed an Inventory App to help users organize products, track stock levels, and manage inventory more efficiently. I designed the application with warehouse employees, inventory managers, and small business owners in mind. These users need quick access to accurate inventory information so they can update quantities, monitor available products, and identify items that may need to be restocked.

The application includes a login system, inventory management tools, and optional SMS notifications. My goal was to create a practical application that supports everyday inventory tasks without making them unnecessarily complicated. I wanted users to spend less time navigating the app and more time completing their work.

#### My Design Choices

When planning the user interface, I focused on the tasks people would perform most often. For example, someone updating inventory during a busy workday should be able to locate a product and change its quantity without navigating through several screens. This helped me prioritize simplicity, accessibility, and clear organization.

I designed a login screen and an inventory screen that displays product names, quantities, and stock information. I also included options to add, edit, and delete inventory records. I organized these features around common inventory tasks so users could find the information they needed and make updates efficiently.

Throughout the design process, I learned that a successful interface involves more than appearance. It should also make the application easy to understand and use. I believe my design was effective because it focused on the user's responsibilities, presented important information clearly, and avoided unnecessary navigation.

#### How I Built It

I developed the application using Java and Android Studio, with SQLite providing local data storage. I approached the coding process by dividing the project into smaller, manageable tasks rather than attempting to complete every feature at once. This strategy helped me stay organized, review individual components, and understand how each feature contributed to the application.

One of the most important parts of development was connecting the inventory interface to the SQLite database. The application needed to accept user input, manage inventory records, and retrieve stored information. Working with these components strengthened my understanding of how the interface, application logic, and database interact.

I also incorporated testing throughout development instead of waiting until the end. This helped me evaluate individual features and consider how changes might affect other parts of the application. In future projects, I plan to continue using incremental development, regular testing, and organized problem-solving to manage complex programming tasks more effectively.

#### Testing the App

I tested the application's main inventory features by adding products, updating quantities, deleting records, and reviewing saved information. These tests helped me evaluate how the application handled inventory changes and how the interface interacted with the database. They also reinforced the importance of checking data storage and retrieval rather than focusing only on what appears on the screen.

I also tested the application with SMS permissions granted and denied. This was particularly important because text notifications are optional, and users may choose not to enable them. Comparing both permission settings helped me evaluate whether the notification feature could affect essential inventory operations.

Through testing, I recognized that application functionality depends on more than completing the expected sequence of actions. Developers also need to consider different user decisions, including declining optional permissions. This experience strengthened my understanding of why testing is essential for identifying potential problems, evaluating functionality, and improving the reliability of an application.

#### Challenges and Problem-Solving

One of the challenges I faced was accounting for optional SMS notifications without making them a requirement for inventory management. Since users can deny messaging permissions, I needed to consider how the application should respond while still supporting its primary purpose.

To address this challenge, I focused on keeping inventory management separate from the notification feature. I evaluated the application's core operations with SMS permissions both enabled and disabled, allowing me to examine how these features interacted under different conditions. This approach helped me recognize the importance of designing optional functionality around the user's choices rather than assuming every permission will be granted.

The experience also changed how I approach problem-solving. Instead of considering each feature independently, I learned to examine how one component might affect another. In future projects, I plan to identify these relationships earlier, consider alternative user actions during development, and test features under different conditions before finalizing the application.

#### What I Am Most Proud Of

The component I am most proud of is the inventory management system and its integration with SQLite. Developing this functionality allowed me to apply my knowledge of Java programming, database operations, and Android application development to a project with a practical purpose.

I am particularly proud of how this component brought together several important concepts from the course. The inventory interface provides a way for users to interact with their records, while the database supports storing and retrieving that information. Working on this connection helped me understand how different parts of a mobile application work together to support the user.

This project also showed me how much I have grown as a programmer. Earlier in my coursework, I focused mainly on writing code that met the assignment requirements. Throughout this project, I began considering the broader development process, including user needs, interface design, data management, testing, and problem-solving.

Completing the Inventory App strengthened my technical skills and gave me more confidence in approaching future mobile development projects. Adding it to my GitHub portfolio allows me to demonstrate what I learned in CS-360 while documenting my progress as I continue developing my programming abilities.
