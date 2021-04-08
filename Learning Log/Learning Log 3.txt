# Log 1 - 17/02/21

### What has been done:

---

I have chosen 2 people on my course to collaborate with on a group project. After discussion, the current task is to create an iOS mobile app that wirelessly connects to an Arduino with an integrated WiFi module and controls a separate device - a robot. We have decided to learn how to code in Swift, as well as learn how to use an Arduino and connect one to an iOS application.

### What have I learned:

---

I have not learned anything yet, but I have collated useful information such as YouTube tutorials and an online course, preparing myself to learn the basics of Swift. Using a Windows operating system would mean I must install macOS on a virtual machine.

### Any changes to my goal:

---

No changes have been made to this goal yet.

### Next steps to achieve my goals:

---

I must now prepare by using the resources gathered to get a better understanding on the skill I am learning. I will also need to create a plan, laying out my goals; I will be using the tool Notion to collect all of my information. I will need to purchase an Arduino and learn how to create a simple servo-powered robot with it.

# Log 2 - 15/03/21

### Any changes to my goal:

---

Myself and my group have now discussed our idea with our professor and he has helped us aim our project in a better direction. The overall task has stayed the same, but changes as to how we will create the project have changed. We are now learning how to create a Progressive Web Application (PWA) rather than use Swift to create the remote controller app. This change was due to the inconvenience of learning Swift as each member has a Windows computer, and because learning a new programming language to create a simple remote control would be excessive. Learning how to create a PWA would build on, and extend, the knowledge each member already has from building a website - however would still be a great challenge to implement and do well.

Another change made was to use a Raspberry Pi robot as opposed to using an Arduino as well as then making a robot separately. This combined robot would mean less time would be consumed on making sure the robot functions as it should, and more time focused on creating the PWA and syncing it with the robot. As Raspberry Pi's have an in-built operating system would also mean that we could code the robot's instructions in Python, not needing to learn C++ for example. Hosting a server on a Raspberry Pi is also much easier than on an Arduino. 

Below is an image of the Raspberry Pi:

![Image of the Raspberry Pi robot](C:\Users\benja\Desktop\PB2\Resources\Images\Raspberry Pi robot)

### What has been done:

---

I have created a project journal, using a tool called Notion, that myself and my group can collaboratively add to - mainly for organisation purposes. Here we can share resources easily as well as plan and schedule meetings: [https://www.notion.so/Copy-of-Programming-Black-PB2-2nd-Summative-d76b258ef7ee4204a26f84296398adb3](C:\Users\benja\Desktop\PB2\Resources\Images\Current webpage) (Date: 17/02/21 - 15/03/21). 

We have also started creating the front-end, client-side of the Progressive Web App. We have also implemented the service worker that allows for user requests to be cached. This means the remote controller application can work offline.

 Shown below is the current iteration of the user-end remote controller that would eventually control the movement of the robot. 

![Screenshot of current webpage layout - frontend](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f9f0d540-eac7-4563-b4a0-445d11fc47c8/Untitled.png)

### What have I learned:

---

I have learned about Progressive Web Applications, and have already made the basics of one. I now know how Service Worker's function and I am able to implement it into a web page. I have a better understanding of how to create a good web page.

### Next steps to achieve my goals:

---

We must now begin working on the backend of the Progressive Web App; completing all of the POST and GET requests necessary. More work will need to be done to understand how we would connect the Raspberry Pi Robot to the PWA. We must also see if we can get the Robot to function on its own with a simple Python script.

# Log 3 - 08/04/21

### What has been done:

---

I have managed to get the Raspberry Pi robot set up and functioning on its own. I connected the robot to the internet, and I wrote scripts in Python on my computer that communicates with the robot wirelessly. I am able to control the robot within an SSH Client, supported by PuTTY, and this works successfully. I have also written code for the necessary preset commands that my robot will perform; with a click of a button, the robot will move drawing a square with its path, draw out a circle and many more.

My group have also completed all aspects of the Progressive Web App (PWA). Together, we completed the functionality of the Service Worker and have made sure that it is Lighthouse-compliant (a tool made by Google that checks the functionality of web pages). Content is able to be loaded offline and I am able to get push notifications working. Despite completing the basic POST and GET requests, I have not yet connected the PWA to the Raspberry Pi robot.

### What have I learned:

---

I have learned how to use the Raspberry Pi operating system and command terminal; this allowed me to find the IP address of the robot and for the purpose of connecting it to WIFI. I also understand how to use an SSH Client to connect the Raspberry Pi to a computer, and to then run Python code to control the robot. I needed to research the specification of my particular Raspberry Pi to understand the specific functions used to control the robot.

I have also learned a lot more about Service Workers. I understand how to use the commands necessary such as "Fetch", "Push", and "Sync" and how to cache pages. 

### Any changes to my goal:

---

No major changes have been made, but I did find it difficult connecting the Raspberry Pi robot to my computer, and needed several different approaches before I got it working. I used several forums as well as many discussions with my group members to solve this problem. We assumed that this would be an easy task, but it proved to be difficult and we were forced to push back further work. This change of scheduling was accounted for in our Notion page and we managed to organise our work around it: [https://www.notion.so/Programming-Black-PB2-2nd-Summative-db1a9927c0014ca5badac17883b910fa](https://www.notion.so/Programming-Black-PB2-2nd-Summative-db1a9927c0014ca5badac17883b910fa)

### Next steps to achieve my goals:

---

The final sizeable task is to connect the Progressive Web App to the Raspberry Pi robot. This would be done using with backend JavaScript that would to the Python scripts already made. This should allow any person that has access to the web page to control the robot (given that the robot is on and running). This may be a difficult task as we are using an SSH Client.