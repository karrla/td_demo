# Appointment Scheduler TD
![Image](https://cosmicjs.com/uploads/b5467280-9745-11e7-9fec-572a0ce3e796-app-scheduler.png)
### [View Demo](https://cosmicjs.com/apps/appointment-scheduler/demo)

This Appointment Scheduler lets users select a day and a one-hour time slot between 9AM and 5PM to meet with us. It integrates with Twilio to send a confirmation text that their appointment has been scheduled.
This also comes with a [Cosmic JS Extension](https://cosmicjs.com/extensions) so we can manage the appointments right from within the Cosmic JS dashboard.

### Getting Started
#### Local Installation
1. [Go to Cosmic JS](https://cosmicjs.com) and create a Bucket to store your appointments.
2. Download the repo
```
git clone https://github.com/cosmicjs/appointment-scheduler
```
3. Install packages and start the app
```
npm i
COSMIC_BUCKET=your-bucket-slug npm start
```
Go to http://localhost:3000 to see your app.  To connect to Twilio, you will need to first create a Twilio account and add your access keys.

#### Cosmic JS Installation
You can also install the app directly to your Cosmic JS Bucket located in `Your Bucket Dashboard > Apps`.  To connect your Twilio keys, just add them to the environment variables section of your Bucket `Your Bucket Dashboard > Deploy Web App > Set Environment Variables` 
