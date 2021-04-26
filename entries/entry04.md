# Entry 4
### 4/25/2021

As of right now, Cindy and I have continued in exploring the different components in [Firebase](https://firebase.google.com/) and decided to use [Cloud Firestore](https://firebase.google.com/products/firestore). Since we are still figuring out parts of the Firestore feature, we got to understand how Firestore works through [Firebase Firestore Tutorials](https://www.youtube.com/watch?v=4d-gIPGzmK4&list=PL4cUxeGkcC9itfjle0ji1xOZ2cjRGY_WB). We will incorprate our learnings of Firebase Firestore from the tutorials into our To-Do List making it functional to use. 
<hr>
In this Engineering Design Process, I am continuing on "createing a prototype." Troughout our findings, we noticied that Cloud Firestore works with our project better that RealTime Database. As both databases help store data and uses the information that is inputed, Firestore allows user to store their data in the cloud. This is benefital to my freedom project, "TO-DO LIST", because allows the user's task to automatically in sync with the system. We began planning the base of our To-Do List on the index.HTML and script.JS and we will be working on the code throughout the nest few weeks.
<hr>
Since, I've decided to use Firebase as my final tool for my freedom project, I have added some Firebase and Firestore codes to our certain platform, Repl.it.
```HTML
1   <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-app.js"></script>
2   <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-firestore.js"></script>
3   <script>
4     var firebaseConfig = {
5       apiKey: "AIzaSyBqpFbx2BD0gokHFkjG7_dgjTp_4F28RTU",
6       authDomain: "firestore-testing-9095c.firebaseapp.com",
7       databaseURL: "https://firestore-testing-9095c.firebaseio.com",
8       projectId: "firestore-testing-9095c",
9       storageBucket: "firestore-testing-9095c.appspot.com",
10      messagingSenderId: "257330495741",
11      appId: "1:257330495741:web:3f252dfece211887f5be94",
12      measurementId: "G-S63PKJ1VQZ"
13    };
14    // Initialize Firebase
15    firebase.initializeApp(firebaseConfig);
16    firebase.firestore();
17  </script>
```
Line 1 allows the Firebase app to be installed into our program which then we would be able to have access to the Firebase App Tool in our index.HTML. Line 2 allows us to have access to the Cloud Firestore feature in which our program would be running on. Lines 3 - 17 allows Firebase to work in our platform, Repl.it.



[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
