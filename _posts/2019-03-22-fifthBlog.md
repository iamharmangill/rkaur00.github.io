# [ My Fifth Blog for Second Project ]({% post_url 2019-03-22-fifthBlog %})

- This week I worked on connecting my front-end part to firebase database. Since Firebase offers two cloud-based database solutions, I am making use of **Cloud Firetsore**. To know more about this you can check it at: [https://firebase.google.com/docs/database/rtdb-vs-firestore](https://firebase.google.com/docs/database/rtdb-vs-firestore)

- I made the project in firestore with name **todoList**
- I made two collections in firestore out of which one collection is to store the todo data and the other collection is to store the done List data.

![Image](/Images/image13.png)

- To connect my angular framework with firebase, I use CLI command: **npm i \-\-s firebase @angular/fire** and add the environment variables in my front-end part in **environments/environment.ts** file.
- Anything I write in the input field will show in Todo part and also get stored in **mytodoList** collection in firestore.

![Image](/Images/image14.png)

![Image](/Images/image15.png)

- Once I drag that list to the done list, It will get automatically deleted from **mytodoList** collection in firestore and get added to **doneList** collection in firestore.

![Image](/Images/image17.png)

![Image](/Images/image16.png)
