# Entry 2
### 11/30/2020

Today, I have been tinkering with the tool, [Firebase](https://firebase.google.com), to determine whether or not I would be using it. I've recently been on [YouTube](https://www.youtube.com/results?search_query=javascript+firebase), [Repl.it](https://repl.it/) and Firebase to understand how Firebase can be incorporated into Repl.it.

Throughout the Engineering Design Process, I have researched the problem of how my project would be different and unique from other existing applications. I have also brainstormed possible solutions for individuals that are unorganized or need help in time management. I wanted to create an application that includes a to-do list with an additional component such as a timer. I have been interested in **Firebase** and have decided to use this tool for my Freedom Project. Specifically, I have been tinkering with the **Realtime Database** feature in **Firebase**. This feature allows information to be **stored on a database** and **retrieves data** when needed. To add on, with the Realtime Database, I would be able to make a to-do list that stores the inputs of the user while allowing them to see what they have already done. My idea is to mainly focus on the to-do list, itself, where individuals would be able to add tasks, mark tasks as completed, refresh the page. However, including a timer to this to-do list would make it more beneficial to students, adults, and even teens. With a timer, people would be able to time themselves on how much time they should spend on doing their tasks. Despite that there are many to-do list apps out there, my to-do list would be easy to use while being simple yet efficient for everyone to use. 
____
***Shown below are the Firebase codes that I tinkered with:***
<br>
*The first script indicates that the Firebase App Tools are allowed into the HTML file. The second script indicates that the Realtime Database feature is incorporated into the file and makes sure it is working. And the final script indicates that the Firebase service is added to the HTML file.*
```ruby
  <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-app.js"></script>
```
```ruby
  <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-analytics.js"></script>
```
```ruby
  <script>
    var firebaseConfig = {
      apiKey: "AIzaSyCCIdGo1CZ8uUnUrmeo-vwfQgkr3PLs4R0",
      authDomain: "tinkering-52eea.firebaseapp.com",
      databaseURL: "https://tinkering-52eea.firebaseio.com",
      projectId: "tinkering-52eea",
      storageBucket: "tinkering-52eea.appspot.com",
      messagingSenderId: "102162150983",
      appId: "1:102162150983:web:340d7b6fceb0b17134e362",
      measurementId: "G-XCRFENWZWE"
    };
    // Initialize Firebase
    firebase.initializeApp(firebaseConfig);
    firebase.analytics();
  </script>
```
___
The skills I used would be **How to Google** and **Problem Decomposition**. The skill Problem Decomposition allowed me to view the tool, itself as different parts, making it easier for me to understand. By breaking things down into smaller parts, visually help me see where I am going in understanding the tool. How to Google is the other skill I used because Firebase wasn't taught to me like learning geometry. I was clueless about how Firebase function when it is incorporated into an IDE. I had to google what the basic idea of Firebase was. I searched *Getting started in Firebase Realtime Database* and found a [YouTube video](https://www.youtube.com/watch?v=noB98K6A0TY) that was helpful. This video introduces what Firebase Realtime Database is used for and gave an example of how Realtime Database would be incorporated with Javascript. I also found this [tutorial](https://riptutorial.com/firebase/example/29622/getting-started-in-firebase-with-a-simple-hello-world-web-app-in-javascript) that introduces how to set up Firebase into HTML files. Overall, I think **Problem Decomposition** and **How to Google** are skills that helped me understand my tool, Firebase while determining whether or not this tool would be useful for building my application.



[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
