# Entry 3
### 2/19/2021

Today, I've tried coding with Javascript and [Firebase](https://firebase.google.com/) as I'm getting ready to create my To-Do List. I'm currently using Repl as the platform for coding my project and tinkering with my tool, Firebase. As I am still learning how to master Firebase, I watched videos on how [Javascript and Firebase](https://www.youtube.com/results?search_query=javascript+firebase) can be incorporated together in making a project such as a To-Do List.

I would say that I'm currently on step 5 of the Engineering Design Process, which **create a prototype**. Since the problem of my project is to help individuals who struggle in remembering their tasks. To solve this problem, I've research how Firebase can create a more stable platform in helping individuals save their data. [What Can Firebase Do?](https://firebasetutorials.com/what-can-firebase-do/) provided me with a lot of knowledge in understanding the different parts of Firebase and allowed me to clearly understand the part I would be using for my To-Do List. Out of the four categories (Develop, Quality, Analytics, and Grow), I believe that I would focus mainly on Develop since it contains key components of Authentication, Database, and Storage. Authentication is something like the login page of an app/website where users can create a username and password to access their account. Database is known as the platform where all the data is stored in the background. In Firebase, there is two types of database, Cloud Firestore and Realtime Database. Both databases help to sync and storage data. Storage allows the user to store information they have inputted. This component is important for my project since it allows the user to store their task(s). Without storage, my to-do list would be a one-time use where the information that the user put is not saved, making it unbeneficial. As I want to create a To-Do List that is beneficial and efficient for everyone, I'm thinking of making a system that works first then adding other add-on features later on. 
____
***REALTIME DATABASE:***
Realtime Database is a database that allows data to be stored immediately onto the Firebase Realtime Database when data is added through the app/website that has Firebase incorporated into it. Realtime Database is often used and seen for text messaging apps/websites. 

***CLOUD FIRESTORE:***
Cloud Firestore is a database that stores information onto a "cloud". This type of database also allows users to sync their accounts across all their devices while having the ability to share information with others.
____
As I proceed to dive deeper into understanding Realtime Database and Cloud Firestore, I figured that Cloud Firestore is the right database for my project. Since it allows the users to store information while keeping all their information in one place where they can refresh the page, etc. From my understanding of Cloud Firestore, Cloud Firestore stores data as collections of documents which allows users to navigate among their inputs keeping everything organized into different categories rather than having everything stored in one large JSON tree in Realtime Database. As I decided to start my project with INDEX.HTML, SCRIPT.JS, and Firebase Cloud Firestore, I've gotten a lot of help from this [youtube tutorial](https://www.youtube.com/watch?v=pSVHDk4hK8Y). This video talks about how a to-do list can be created by using HTML, JAVASCRIPT, and FIREBASE which is very informative since I've just started learning about Firebase and how it works with HTML and JAVASCRIPT.

Shown below are the codes I've coded with my partner, Cindy:
<br>
PLEASE NOTE THAT THESE CODES ARE JUST OUR TESTING CODES!
```HTML
  HTML:
1    <body>
2      <!-- Input To-Do Task Part-->
3      <p class="header">Task</p>
4      <div class="container">
5        <div class="the_task_container">
6          <div class = "the_task_data">
7            <p id="the_task_title"></p>
8            <div id="the_task_tools">
9              <button id="task_done_button" onclick="task_done();"><i class="fa fa-check"></i></button>
10             <button id="task_edit_button" onclick="task_edit();"><i class="fa fa-pencil"></i></button>
11             <button id="task_delete_button" onclick="task_delete();"><i class="fa fa-trash"></i></button>
12           </div>
13         </div>
14       </div>
15     </div>
16     <!-- Task Finish -->
17     <p class="header" >Finish Task</p>
18     <div class="container">
19       <div class="task_container">
20         <div class = "task_data">
21          <p id="task_title">Task Title 1</p>
22         </div>
23       </div>
24     </div>
25   </body>
```
Lines 4-5 would show a button for the task. From Lines 8-12, it allows users to edit, delete, and check tasks (marking them as done). As we want to create a to-do list that is easy to use, we included icons that will represent each action making it easier for users to use. From Lines 17-24, it allows users to organize their tasks that are complete/finish to be placed under "Finished Task". 
____
```JS
  SCRIPT JS:
1    function data() {
2      var text = document getElementById("usertext").value;
3      console.log(text);
4    }
5    function add_task(){
6      console.log("add_task");
7    }
8    function task_done(){
9      console.log("task_done");
10   }
11   function task_edit(){
12     console.log("task_edit");
13   }
14   function task_delete(){
15     console.log("task_delete");
16   }
```
When the user inputs a task and presses "Enter", the code above specifically ```function data()``` would take the input and store it in console.log. The other functions would allow the user to edit the tasks, delete the tasks, add tasks, and mark the tasks as done. These functions are presented as buttons in the HTML file. 
____
The skills I've used would be **Debugging** and having a **Growth mindset**. The skill of having a **Growth mindset** allowed me to be patient in learning the different components of Firebase which also pushed me in tinkering and coding for my project. Oftentimes, if I don't do enough researching and practicing what I've learned, it's really hard for me to have a positive mindset in what I'm going to create. As I get more in contact with projects like this, I've learned more about how I should learn which encourages me to work harder. **Debugging** is another skill that I've used. Since I'm constantly learning more about my tool and the outcome of this project, debugging has become an important factor in helping me identify what I've done incorrectly. Despite that debugging is displeasing, it truly allowed me to make my codes more clear and easier to understand for the future. Overall, I think **Debugging** and **Growth mindset** are skills that helped me understand my code and tool (Firebase) while helping me grow as an individual.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
