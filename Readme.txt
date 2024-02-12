>>> Elderly Care Hub

Elderly Care Hub is a web-based application designed to assist in monitoring and providing emergency assistance for the elderly. It includes an Exercise Tracker to log daily exercises and  an Emergency Assistance feature for sending alerts through mail but here it is just monitored on screen .

>>> Features

1. Exercise Tracker
- Log various exercise types such as walking, stretching, cycling, and yoga.
- Record the duration of each exercise session.
- View today's exercise log in a user-friendly interface.

2. Emergency Assistance
- Press the emergency button to send an alert in case of an emergency.
- Provides a status update on the emergency alert.

3. Nodemailer 
-Send emails using Nodemailer with Gmail as the service provider.


>>> Technologies Used
- HTML
- CSS
- JavaScript
- Node js

>>> How to Use
1. Open the `index.html` file in a web browser.
2. Use the Exercise Tracker to log daily exercises.
3. In case of an emergency, press the Emergency Alert button.
4. View the status of the emergency alert.
5. Install dependencies by running `npm install` in the project directory.
6. Open the `index.js` file and update the following fields:

   - `user`: Your Gmail email address.
   - `pass`: Your Gmail app password. (Note: You might need to [generate an app password](https://support.google.com/accounts/answer/185833?hl=en) for security reasons.)

7. Run the project using the command `node index.js`.
8. Check the console for a success message indicating that the email has been sent.


>>> Notes
- The project uses a simulated backend logic to showcase the Emergency Assistance feature.
- Combine the simulated backend logic nodemailer project with frontend project for email notifications of emergency alert and exercise tracking.

