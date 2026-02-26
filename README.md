# TruStock_Android_App
A native Android application engineered for warehouse inventory management using a local SQLite database and automated SMS alerts.


1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

        TruStock helps businesses maintain accurate inventory records as items move through a warehouse. Managing a retail           warehouse sales floor taught me that workers are not interested in using apps that are slow and hard to understand.          Therefore, I made sure that user friendliness and a clean display was a main focus in the design.

2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

        I built a single uncluttered screen with dynamic Update and Delete buttons right next to the item quantities.                Eliminating extra clicks in the design reduced visual clutter so the users could stay focused on their tasks.
   
3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

       My approach was that I mapped out the data first and tested frequently in small chunks. I started with the design            layout, then implimented SQLite backend, then wrote the Java code. I will definitely use this incremental strategy on        future projects because it makes catching bugs more efficient.
   
4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

        I made sure to test frequently in the Android emulator throughout the project. This was important because it allowed         me to fix a crash early caused by the wrong layout parameters. That allowed me to fix the simple error and make sure         the app was working as intended before moving on to the next phase.
 
5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

        In order to create a scalable UI, I had to think outside the box with my backend code instead of just hardcoding             buttons in the XML. I utilized a loop that generated custom Update and Delete buttons for every single item pulled           from the database.
   
7. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

         The compnent that I was successful in implimenting was linking the SQLite backend to the devices hardware features.          Getting the database to update and automatically trigger a low stock SMS alert proved my ability to build a fully            functional application.
