# CS360 - Event Tracker App

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of my app was to create an event tracking application that allows users to log in, create accounts, and keep track of upcoming events with simple CRUD functionality. The app was designed to meet the need for an easy way to organize and remember important dates, especially for students, parents, or working adults with busy schedules. The app provides reminders and notifications through SMS, helping users stay on top of their events.

---------------------------------------------------------------------------------------------------
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app includes screens like a login and register screen so users can create accounts and sign in, an event list screen that shows all upcoming events in a grid with headers, and buttons to add or delete events. I also built an add event screen where users can put in the event name, description, date, and time, and an event details screen for viewing information about a specific event or editing details. Lastly, I included an SMS permission screen, since the app needs access to send text reminders. While designing these, I really focused on keeping the layout clean and consistent so users wouldn’t feel overwhelmed.

---------------------------------------------------------------------------------------------------
How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

When I moved into coding, I took a step-by-step approach. Normally I like to code one feature at a time, and having the design already finished gave me a clear plan to follow. This made the development process smoother because I didn’t have to constantly go back and change code when I wanted to adjust the layout. It also helped me stay organized since I could just connect the XML designs with the Java code feature by feature.

---------------------------------------------------------------------------------------------------
How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

To make sure everything worked, I tested the app frequently in the emulator as I added new parts. I checked edge cases, like what happens if a user leaves a field empty or denies SMS permission. Testing like this was important because it showed me where things could break and gave me a chance to fix issues early.

---------------------------------------------------------------------------------------------------
Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the bigger challenges I faced during this project was working with SMS permissions, since it was something completely new to me and required following Android’s rules for runtime permissions. At first, I struggled with getting the app to respond correctly when the user either accepted or denied the request, and it took a lot of trial and error to figure out how to properly check and handle permissions. I had to spend time reviewing documentation and experimenting until I could make the feature both functional and user-friendly. In the end, I was proud to see the SMS notifications working as intended because it showed not only that I could learn and apply something new, but also that I could design it in a way that respected user choice and still kept the app flowing smoothly.

---------------------------------------------------------------------------------------------------
In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think I was especially successful in showing my skills through the logical flow of the app and its functionality. From the login screen to adding, viewing, and deleting events, each step follows naturally and makes sense for the user. I paid attention to keeping the screens consistent and easy to navigate, so it feels like a complete app rather than just separate pieces. I was also proud of how the functionality tied together smoothly. The database connections, event management features, and SMS permission screen all worked as intended, and I made sure they supported the overall goal of the app.
