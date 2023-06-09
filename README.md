# Return-tracker-app

### Use-case
I am a person who enjoy shopping online at a wide variety of retailers (Amazon, Nike, Adidas, Nordstrom, etc.). As I do a lot of my shopping online, I end up having to return a lot of products. Many of these returns can only be dropped off at certain shipping providers (e.g. FedEx, UPS, USPS). I easily lose track of which returns need to be dropped off where and by when, and also forget key information such as if I need to print out my own shipping label, if it is attached to the return confirmation email, or if it is unnecessary (e.g. QR Code return label). I would like a simple app that fetches data from my email to gather an easy to understand list of my ongoing and completed Returns. This list should, at the very least, show clear and concise information on: (1) the retailer, (2) the return deadline, and (3) key return information such as the shipping provider. 

### Project breakdown
Here's a possible breakdown of the app's functionality:

1. User authentication: Build a login system that allows users to securely sign in to the app using their email and password.
2. Email integration: Integrate the app with the user's email account (e.g. Gmail, Outlook) using an API like Google's Gmail API or Microsoft's Outlook REST API. Use JavaScript to retrieve the necessary information from the user's emails, such as the retailer name, return deadline, and shipping provider.
3. Data processing: Parse the retrieved email data and extract the relevant information, such as the retailer name, return deadline, and shipping provider. Use JavaScript to process the data and generate a list of ongoing and completed returns.
4. User interface: Build a user interface that displays the list of returns in a clear and concise manner. Use JavaScript and a front-end framework like React or Next.js to display the list and allow users to interact with it, such as filtering the returns by retailer or sorting them by deadline.
5. Notifications: Implement a notification system that reminds the user of upcoming return deadlines and any required actions, such as printing a shipping label. Use JavaScript and a notification library like Toast or Noty to display the notifications.

Building this app will require you to use JavaScript to manipulate data, handle user input, and display information on the screen. It will also involve integrating with external APIs and libraries, which can help you gain experience working with third-party services.

### Rough Lesson Plan
Here's a rough lesson plan we can follow to build out the app:

##### Lesson 1
Setting up the development environment: We'll start by setting up the development environment, which includes installing any necessary software and tools, such as Node.js, NPM, and your text editor of choice. We'll also create a new project directory and initialize a new Node.js project.

##### Lesson 2
Building the user authentication system: We'll create a user authentication system that allows users to securely sign in to the app using their email and password. We can use a library like Passport.js to handle user authentication and store user data in a database.

##### Lesson 3
Integrating with the user's email account: We'll integrate the app with the user's email account using an API like Google's Gmail API or Microsoft's Outlook REST API. We'll use JavaScript to retrieve the necessary information from the user's emails, such as the retailer name, return deadline, and shipping provider.

##### Lesson 4
Parsing email data and displaying a list of returns: We'll parse the retrieved email data and extract the relevant information, such as the retailer name, return deadline, and shipping provider. We'll use JavaScript to process the data and generate a list of ongoing and completed returns. We'll also build a user interface that displays the list of returns in a clear and concise manner.

##### Lesson 5
Adding notifications and reminders: We'll implement a notification system that reminds the user of upcoming return deadlines and any required actions, such as printing a shipping label. We'll use JavaScript and a notification library like Toast or Noty to display the notifications.

##### Lesson 6
Deploying the app: Finally, we'll deploy the app to a web host like Heroku or Vercel to make it accessible to users.

We can work on each of these steps together in our regular sessions, providing explanations, examples, and exercises to reinforce your learning and help you apply what you've learned to the project. We can also break down each step into smaller tasks and track them using GitHub's Issues feature, which will help us stay organized and on track.
