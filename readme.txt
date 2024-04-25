--Readme document for Farahnaz Hoque & Hannah Huynh, fhoque@uci.edu & hannahnh@uci.edu, 53208125 & 94187472--

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/20
- 3/3 The ability to log overnight sleep
- 3/3 The ability to log sleepiness during the day
- 3/3 The ability to view these two categories of logged data
- 3/3 Either using a native device resource or backing up logged data
- 3/3 Following good principles of mobile design
- 3/3 Creating a compelling app
- 2/2 A readme and demo video which explains how these features were implemented and their design rationale

2. How long, in hours, did it take you to complete this assignment?
16 Hours

3. What online resources did you consult when completing this assignment? (list specific URLs)
Ionic documentation

4. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
Hannah and Farahnaz

5. Is there anything special we need to know in order to run your code?
For webpage view run: ionic serve in sleeptracker folder

--Aim for no more than two sentences for each of the following questions.--

6. Did you design your app with a particular type of user in mind? If so, whom?
No, we did not have any particular users in mind while designing the app. Instead we focused on making the app simple so everyone would be able to utilize it. 

7. Did you design your app specifically for iOS or Android, or both?
The design aspect of our app was mostly designed for iOS. 

8. How can a person log overnight sleep in your app? Why did you choose to support logging overnight sleep in this way?
A person can log their overnight sleep by choosing the day/time they slept and the day/time they woke up. This would allow users to log previous day overnight sleep if they may have forgotten while enforcing an ‘uh-oh’ pop up for accidental future overnight sleep logs. 

9. How can a person log sleepiness during the day in your app? Why did you choose to support logging sleepiness in this way?
A person can log sleepiness by dragging the 

10. How can a person view the data they logged in your app? Why did you choose to support viewing logged data in this way?
A person can navigate to the view data tab at the bottom of the screen where they have the option to switch in between overnight sleep data and sleepiness data. We chose this way so users can differentiate between their type of data logged and keep track of them separately. 

11. Which feature did you choose--using a native device resource, backing up logged data, or both?
We selected to back up logged data using ionic storage. As a result of that, the data is stored locally as opposed to globally (that would have been achieve if Firebase was used). 

12. If you used a native device resource, what feature did you add? How does this feature change the app's experience for a user?
N/A

13. If you backed up logged data, where does it back up to?
The backed up logged data is stored using Capacitor Storage which utilizes Ionic’s built in library to support it. 

14. How does your app implement or follow principles of good mobile design?
Our app implemented a useful initial view where it welcomes the user to the app and briefly explains what each tab does. Our app also implemented error prevention by handling checks for overnight sleep input such as disallowing future times to be recorded. 