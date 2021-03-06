# [ My Second Blog for Second Project ]({% post_url 2019-02-28-secondBlog %})
This week I learned about creating new components and routing.
- In angular, the only default component we get is "app-component". In any project we need different pages, for instance, we need Homepage, aboutus and contactpage and to make them, we need to create new components.
- To create new components, open the terminal of your visual studio code and type **ng generate component componentname**
- This will generate the component with the name you defined and import that component automatically in your **app-module.ts file**
- Upto now I have generated four components: home, about, contact and nav.
- Home, About and Contact page just hold the static data and nav component has link to all these pages. To set all things, the code I am using in **nav.component.html** file is:

```
<header>
  <div class="container">
  <nav><ul><li><a routerLink="/">Home</a></li>
    <li><a routerLink="/about">About</a></li>
    <li><a routerLink="/contact">Contact us</a></li></ul></nav></div>
</header>
```
- Now to do the routing, you must have "app-routing.module.ts" file, which is included in your project if while installing you type "yes" for routing. In routes, we need to provide the path and name of component. For instance:

**{path:'about',component:AboutComponent}**

- When you run it using **ng serve** and open brower and type **http://localhost:4200/**, you would get the following page:
![Image](/Images/home.png)
- When you click on About, you would get:
![Image](/Images/aboutus.png)
- When you click on Contact page, the following page would appear:
![Image](/Images/contact.png)

**References**
- [https://angular.io/docs](https://angular.io/docs)
- [https://www.youtube.com/watch?v=5wtnKulcquA](https://www.youtube.com/watch?v=5wtnKulcquA)



