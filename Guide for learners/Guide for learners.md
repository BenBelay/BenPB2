# Guide for learners

## Motivation

---

There are two main parts to my project: making a Progressive Web App (PWA) and controlling a Raspberry Pi.

**_Progressive Web Apps_**

Understanding and creating a PWA is a very good skill to have. Progressive Web Apps are like native phone apps but work from your web browser, and are available to be downloaded on your phone and computer. You are able to install them straight from your browser without having to go through an App Store and additionally can be installed on any type of device whether it be an iPhone, or Samsung phone. As well as being able to use them without internet, they are extremely fast (with the use of cache) and offer a very integrated, seamless user experience. They don't require you having to learn a proprietary programming language like Swift (that make Apple phone apps) and overall a great tool to use to make an application; a good skill to learn.

**_Raspberry Pi_**

Raspberry Pi's are basic computers that have a vast range of capabilities, as well as being cheap and fairly easy to use. For beginners, it is a great tool to start learning how to interact code with physical devices such as controlling LED's. For more advanced users, the potential is immeasurable, such as making a video doorbell or a Raspberry Pi drone. Some further advanced example can be seen here: [https://www.itpro.co.uk/mobile/21862/raspberry-pi-top-projects-to-try-yourself](https://www.itpro.co.uk/mobile/21862/raspberry-pi-top-projects-to-try-yourself).

Connecting these two parts can allow for phone/web applications to control physical, hardware devices. Existing examples where this union is used are Smart Home heating systems, Smart Home assistants like the Google Home and Phillips Hue lights. These are fairly new-to-the-market creations and similar creations can be done by anyone with some programming experience; programmers can then create their own phone-controlled devices that could eventually be worth a lot of money. This project is a very useful and practical skill to learn especially for people with an interest in the merging of hardware and software, and provides a great leap into the field of technology.

## Background

---

**_Progressive Web Apps_**

Prior to starting the project, it would be ideal for the user to have a basic understanding of making a website using HTML, CSS and JavaScript. This is because Progressive Web Apps are built upon the back-end of websites. Full-stack knowledge (front-end/client-side and back-end/server-side) is needed to make the website, and this can be learnt for free by taking certain courses. A very good example is this course offered by Coursera: [https://www.coursera.org/learn/html-css-javascript-for-web-developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers).

Although there is no/minimal cost to learning full-stack web development, it does take a lot of time and practice to create a good website. Learning from different sources could be beneficial, and creating small projects to test your understanding would be useful. The following are additional courses that could also be completed:

- [https://www.youtube.com/watch?v=Q33KBiDriJY](https://www.youtube.com/watch?v=Q33KBiDriJY)
- [https://www.youtube.com/watch?v=XlvsJLer_No&list=PLZlA0Gpn_vH8jbFkBjOuFjhxANC63OmXM](https://www.youtube.com/watch?v=XlvsJLer_No&list=PLZlA0Gpn_vH8jbFkBjOuFjhxANC63OmXM).

**_Raspberry Pi_**

For this particular project, you will need a Pi2Go Lite robot vehicle that can be purchased from here: [https://bit.ly/3vJ4luT](https://bit.ly/3vJ4luT), but check with your school or university if they have similar Raspberry Pi robots. This project can accommodate different variations of robots, but ideally use the one recommended. Alternatively, other Raspberry Pi kits can be purchased without the robot extension but will ultimately produce a different result.

Assembling this robot would also require soldering. An SD card will also be needed to download the appropriate software as well as a USB WiFi stick for connection. A tool kit that includes a soldering iron, SD card and WiFi stick to purchase are shown in the websites below :

- [https://amzn.to/2Rn4vsG](https://amzn.to/2Rn4vsG)
- [https://amzn.to/3aZUSHH](https://amzn.to/3aZUSHH)
- [https://amzn.to/3umb1Pa](https://amzn.to/3umb1Pa)

Raspberry Pi's can be coded in many different programming languages, but for this particular project we will code it in Python. Python is a popular and comparatively easy language to learn to code in, and can be learn from these free courses:

- [https://www.youtube.com/watch?v=rfscVS0vtbw](https://www.youtube.com/watch?v=rfscVS0vtbw)
- [https://www.youtube.com/watch?v=QLTdOEn79Rc&list=PLqnslRFeH2UqLwzS0AwKDKLrpYBKzLBy2](https://www.youtube.com/watch?v=QLTdOEn79Rc&list=PLqnslRFeH2UqLwzS0AwKDKLrpYBKzLBy2)

The target audience for this project is primarily for sixth-form/university students who may already have some experience in coding and possibly electronics/engineering experience.

## Learning Materials

---

**_Progressive Web Apps_**

Progressive Web Apps (PWAs) differ from normal responsive web pages with two main specific files: the Service Worker and the Web App Manifest file. The Service Worker is responsible for allowing the web page to work offline through the process of caching data, and the Manifest file includes information about the downloadable app.

A brief video explaining Progressive Web Apps is shown below

- [https://www.youtube.com/watch?v=sFsRylCQblw](https://www.youtube.com/watch?v=sFsRylCQblw)

More detailed videos of how to create a PWA are show below

- [https://www.youtube.com/watch?v=WbbAPfDVqfY](https://www.youtube.com/watch?v=WbbAPfDVqfY)
- [https://www.youtube.com/watch?v=ksXwaWHCW6k&t=1s](https://www.youtube.com/watch?v=ksXwaWHCW6k&t=1s)

A checklist of what you need to include in your webpage to qualify it to be a PWA is shown here:

- [https://web.dev/pwa-checklist/](https://web.dev/pwa-checklist/)

These resources will allow you to successfully turn a webpage into a Progressive Web App.

The aim of creating the PWA for this project is to act as a remote controller for the Raspberry Pi robot. Therefore you will need to make a website that would have controls to control a robot, such as a D-Pad.

If the JavaScript element is difficult to understand in the videos above, the following video provides help in improving your JavaScript knowledge:

- [https://www.youtube.com/watch?v=W6NZfCO5SIk](https://www.youtube.com/watch?v=W6NZfCO5SIk).

**_Raspberry Pi_**

The first stage of the Raspberry Pi robot is assembling it. Instructions for this are evidenced below as well as a soldering tutorial:

- [https://4tronix.co.uk/blog/?p=944](https://4tronix.co.uk/blog/?p=944)
- [https://www.youtube.com/watch?v=AqvHogekDI4](https://www.youtube.com/watch?v=AqvHogekDI4)

The next stage of the Raspberry Pi robot involves the setup: downloading the Raspbian Operating system on the SD card, connecting the Raspberry Pi to the internet and downloading the correct software. This can be done by going through the following video:

- [https://www.youtube.com/watch?v=rESbe0dGbls&list=PLit2e-Vwcp2oHi_Y6ogfzgaQUHbUU6tCj&index=2](https://www.youtube.com/watch?v=rESbe0dGbls&list=PLit2e-Vwcp2oHi_Y6ogfzgaQUHbUU6tCj&index=2)

You are then able to begin controlling the robot. The following website links show the documentation code needed to control the robot and a video explaining how to link the code to the robot:

- [https://4tronix.co.uk/blog/?p=475](https://4tronix.co.uk/blog/?p=475)
- [https://bit.ly/3tb44PH](https://bit.ly/3tb44PH)

Additional links are included in the case that specific errors are occur:

- SSH unable to connect to Raspberry Pi: [https://bit.ly/2RjF9Ms](https://bit.ly/2RjF9Ms)
- PuTTy not connecting to Raspberry Pi: [https://bit.ly/3nI1643](https://bit.ly/3nI1643)

Once this is completed, you need to connect the PWA with the Raspberry Pi robot. You will need to first set up a secure connection between the PWA and the robot. A useful website is shown here, using node.js:

- [https://www.w3schools.com/nodejs/nodejs_raspberrypi.asp](https://www.w3schools.com/nodejs/nodejs_raspberrypi.asp)

The following video explains how to control an LED with a remote server:

- [https://www.youtube.com/watch?v=c6FOpPXbLjs](https://www.youtube.com/watch?v=c6FOpPXbLjs)

Understanding this will help connect a server to a executable file - you will then be able to access the webpage remotely to run the code to control the robot.

## Evaluation

---

Overall, this project is very useful.

The Progressive Web App part challenges the user's ability to work with server-side code, and improves the user's understanding of JavaScript. Progressive Web Apps are becoming a lot more common in today's use however are not taught heavily at even a university level. Creating a PWA is not a demanding task, but is a useful skill to learn.

Building, setting up and programming a Raspberry Pi is more of a niche skill to learn. However, it does teach the user about electronics, and allows them to see how to make software connect with hardware - often more difficult than the two skills individually. This skill may come with difficulties but can be achieved.

Connecting the PWA with the Robot is a more demanding task. It requires a strong understanding of server-sided code and node.js as well as advanced knowledge in using Raspbian (Raspberry Pi's operating system) command line. This skill is difficult and will take more time but necessary to complete the project. I believe it is worth learning this as the outcome outweighs the time taken master this skill; the advanced level attained by achieving this will help the user gain practical skills that can be applied in many similar tasks and projects.
