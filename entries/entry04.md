# Entry 4
### 4/25/2021

As of right now, Cindy and I have continued exploring the different components in [Firebase](https://firebase.google.com/) and decided to use [Cloud Firestore](https://firebase.google.com/products/firestore). Since we are still figuring out parts of the Firestore feature, we got to understand how Firestore works through [Firebase Firestore Tutorials](https://www.youtube.com/watch?v=4d-gIPGzmK4&list=PL4cUxeGkcC9itfjle0ji1xOZ2cjRGY_WB). We will incorporate our learnings of Firebase Firestore from the tutorials into our To-Do List making it functional to use. 

<hr>

In this Engineering Design Process, I am continuing to "create a prototype." Throughout our findings, we noticed that Cloud Firestore works with our project better than RealTime Database. As both databases help store data and use the information that is inputted, Firestore allows user to store their data in the cloud. This is beneficial to my freedom project, "TO-DO LIST" because allows the user's task to automatically in sync with the system. We began planning the base of our To-Do List on the index.HTML and script.JS and we will be working on the code throughout the next few weeks.

<hr>

Since I've decided to use Firebase as my final tool for my freedom project, I have added some Firebase and Firestore codes to our certain platform, Repl.it.

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

**Description to Code Above:**
<br>
Line 1 allows the Firebase app to be installed into our program which then we would be able to have access to the Firebase App Tool in our index.HTML. Line 2 allows us to have access to the Cloud Firestore feature on which our program would be running on. Lines 3 - 17 allow Firebase to work in our platform, Repl.it.

```JS
1     var db = firebase.firestore();
2       db.collection("lists")get().then((doc) => {
3     })
```

**Description to Code Above:**
<br>
From lines 1 - 3, we wanted to indicate the collection that we wanted to grab. Despite that the code is incomplete, we are still tinkering on how we indicate the collection in Firestore on Repl.it. From our understanding, .get() and doc are IMPORTANT parts in allowing Firestore to work. This is because it gets the document information from Firestore applies it to the index.HTML.

```HTML
1    <!-- input to-do task part -->
2    <p class="header"> Task </p>
3    <div class="container">
4       <div class="the_task_container">
5         <!-- Task -->
6         <p id="usertext" type="text" placeholder="Start A Task"/></p> <!-- 4 place that the task will show up -->
7         <div class = "the_task_data">
8           <p id="the_task_title"> </p>
9           <div id="the_task_tools">
10            <button id="task_done_button" onclick="task_done();"> <i class="fa fa-check"> </i>  </button>
11            <button id="task_edit_button" onclick="task_edit();"> <i class="fa fa-pencil"> </i>  </button>
12            <button id="task_delete_button" onclick="task_delete();"> <i class="fa fa-trash"> </i>  </button>
13          </div>
14        </div>
15      </div>
16    </div>
17    <!-- task finish -->
18    <p class="header" > Finish Task </p>
19    <div class="container">
20      <div class="task_container">
21        <div class = "task_data">
22          <p id="task_title">Task Title 1 </p>
23        </div>
24      </div>
25     </div>
```

**Description to Code Above:**
<br>
The lines above show the buttons for marking, editing, and deleting the tasks. Since we plan to make a To-Do List that is easy to use, we are trying our best to make this as efficient as possible, in which we would include a "Finished" section for the tasks that are completed. 

<hr>

**MVP - Skills:**
<br>
When planning my MVP with Cindy, we were still getting the hang of understanding Firebase and Firestore. Although Firebase and Firestore is a complex tool to use, I am will spend time with Cindy to understand the significance of self-learning/self-teaching in advancing our project. As we are working on the HTML and JS of our project, we are testing our project, to ensure that there is no huge error in which it would take a long time to debug. Our next plan is to make the bottoms work for what it is programmed for. 

<hr>

The skills I've used are **Debugging** and **Time Management**. As I debugged my code, it allowed me to understand that Cloud Firestore would work better with my To-Do List rather than RealTime Database. Since Firestore is a complex feature in Firebase, it took many tries to work with my code. Thus, I learned more about the Firestore feature from my errors that I've made through the process of debugging. Also, with the help of the *Firebase Firestore Tutorials*, I can understand the main role of Firestore. Since the school year is coming to an end, I can keep track of time in making progress in my project. Time Management is a skill that I struggle with since it is hard for me to make time in which I can spend on learning about Cloud Firestore and how it should be incorporated into my project. Furthermore, this allowed me to understand the importance of time management and how it is beneficial to me.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
