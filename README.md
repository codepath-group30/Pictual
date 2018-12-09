##Contributors
* Festus Ojo
* Jenelle Maximo
* Sameen Yassar Khan

## Pictual

### App Description
As the saying goes, "A picture is worth a thousand words." Pictual is a visual reminder app that reminds users of events or through pictures rather than words!

### App Idea Evaluation
- Mobile: Users are able to use pictures from their camera or gallery and attach a location if they want to. Real-time notifications allow the user to be puctual to the event.
- Story: Many people would find our app useful in their daily lives.
- Market: According to an article by the Social Science Research Network in 2004, 65% of the population are visual learners. Anyone and everyone can use this app. People forget things and Pictual is here to help.
- Habit: Everyone has places to be and we can lose track of time. Pictual can be used daily to remind users of their schedules.
- Scope: This app might be technically challenging since a lot of the features are going to include user inputs of pictures and locations.

---

### User Stories

# Product Spec Design: Visual Reminder
Your [design product spec](https://hackmd.io/SR5ovxoOTQ6cCrvQ33qnGw?edit) (described in that link) will look like the following in your README:

## 1. User Stories (Required and Optional)

**Required Must-have Stories**

 * User can create a new account and login.
 * User can upload a picture taken from their camera.
 * User can upload a picture taken from their gallery.
 * User can click on a picture and see/edit the information for that picture.
 * User can set a date and time to be reminded.(through notifications)
 * User can scroll to see their visual reminders im chronological order.
 * User can delete a visual reminder.


**Optional Nice-to-have Stories**

 * User can add a description to each visual reminder.
 * User can connect their visual reminders to their phone calendars.
 * User can input location connected to visual reminder.
 * User can input gifs.
 

## 2. Screen Archetypes

 * Login
   * User will first generate an account
       * Integrate third-party connection SDKs (i.e Facebook or Google SDK)
   * After generating an account, they'll be prompted to log in to the account upon launching the app
       * Will also be allowed to log back in through these third-party connection SDKs
 * Stream
   * Lists out the reminders needed for the day in the form of images that are easy to remember 
   * Uses list view to show them in chronological order
 * Detail
   * Each image on the user's stream can be clicked on to show more textual details about the event
 * Creation
   * Allows user to add more information about an already existing image reminder
   * Allows user to add additional image reminders
 * Profile
   * Basic layout of a profile that will allow users to see the number of goals they've completed in a particular    day/week/month/this year
 * Settings
   * Allows user to control the notifications they receive to their phone through push notifications/integration    to calendar


## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * Press to add a picture as a reminder (either by taking pictures or using existing ones from the gallery)
 * Add reminder to Calendar
 * Set date and time
 * View Profile
 * Recents
 * Settings

**Flow Navigation** (Screen to Screen)

 * Login
   * Google (or any other third-party connection SDKs)
   * Home
 * Register
   * Home
 * Stream
   * Details
 * Settings
   * Stream
   * Calendar
   * Photos (Gallery)
   * Home
 * Detail
   * 
 * Creation
   * Photos (Gallery)
   * Camera
   * Home
 * Profile
   * Home
   * Google (or other third-party apps)

---

### Wireframes
<img src="https://github.com/codepath-group30/Pictual/blob/master/wireframe.gif" width=200><br>

---

### App Pitch Presentation
https://docs.google.com/presentation/d/17Fz6dCfxI4gY4FzWWJvT1sUJjL43OgP8U5ytbBb2cso/edit#slide=id.p

### App Video for Demo Day
<img src="https://youtu.be/Q1fn-bT-W6E><br>
