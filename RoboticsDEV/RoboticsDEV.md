---
layout: "Reveal Presentation"
title: "Robotics for Developers"
date: "2019-01-19 13:21"
separator: \n---\n
verticalSeparator: <!--v-->

---

<style type="text/css">
table td{
border:none;
}
</style>


# Robotics For Developers

---

An Introduction to Robotics and ROS - for software people!

---

# Presentation Goals

- Review Robotics Development
- Introduce the Robotics Operating System (ROS)
- Get Developers excited to write Robot Code!

---

# Who am I?

<!--v-->

# Gabriel Isko
- Robotics Engineer
- Applications at RoboteQ
- Obsessed with Robots

---

# What is a Robot?

<!--v-->

![Simple Robot Flowchart](assets/markdown-img-paste-20190119155641756.png)

<!--v-->


![Simple Robot and Environment Flowchart](assets/markdown-img-paste-20190119155525233.png)


<!--v-->


![Simple Robot Flowchart](assets/markdown-img-paste-20190119155641756.png)

<!--v-->


![Robot Flowchart and Process](assets/markdown-img-paste-20190119155449668.png)


<!--v-->

![Complicated Robot Flowchart](assets/markdown-img-paste-2019011915534223.png)

<!--v-->

<img alt="Super Complicated Robot Flowcart" src="assets/markdown-img-paste-20190119161226787.png" width="75%">

<!--v-->

## It's Getting Complicated!

---

# How do we write software for these Robots?

---

## Hobbyist Method: Write some code!

<!--v-->

Works well enough for simple Robots

![Simple Robot Flowchart](assets/markdown-img-paste-20190119155641756.png)

Remember this guy?

<!--v-->

![Aruino, Button, and Motor Setup](assets/markdown-img-paste-2019011916204573.png)

<!--v-->

![Arduino IDE](assets/markdown-img-paste-20190119162707812.png)

<!--v-->

## Pros:

- Easy to set up
- Simple to use
- Great for Hobbyiests and Educators

<!--v-->

## Cons:
- One source code file
- Not maintainable, extensible or scalable
- Breaks whenever we try to do something complicated

---

## Industrial Method: Kludge Automation Technology!

<!--v-->

Programmable Logic Controllers:


![Parker Automation Controller](assets/markdown-img-paste-20190119171724699.png)

<!--v-->

![Ladder Logic Application](assets/markdown-img-paste-20190119163640170.png)


<!--v-->

Communication Methods:

|                                                      |                                                      |
| ---------------------------------------------------- | ---------------------------------------------------- |
| ![Profinet Logo](assets/markdown-img-paste-20190119164451142.png) | ![EtherNet/IP Logo](assets/markdown-img-paste-2019011916452108.png)  |
| ![Device Net Logo](assets/markdown-img-paste-2019011916454236.png)  | ![CANOpen Logo](assets/markdown-img-paste-20190119170209430.png) |

<!--v-->

## Pros:

- Used for other Applications
- Actively support by Companies
- Provides the Backbone of automation

<!--v-->

## Cons:

- Full of proprietary systems that don't work well together
- Controller by Corporations that have conflicting business interests
- Ultimately, not suitable for Robotics

---

# IS THERE NO GOOD WAY?

---

(let's back up)

---

# How do we Develop Modern Software?

<!--v-->

## Pick a programming Language

| ![Python Logo](assets/markdown-img-paste-20190119173231961.png) | ![JavaScript Logo](assets/markdown-img-paste-20190119173534494.png) | ![C++ Logo](assets/markdown-img-paste-20190119173609722.png) |
| --------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |

<!--v-->

## What this accomplishes

- Different programming languages are suitable for different applications
- We can choose the lanuage most appropriate for our project
-

<!--v-->

## Not Enough for Modern Software Development
- Doesn't help us re-use software libraries that aren't Standard
- Doesn't help us build, test, or distribute the software we develop
- Doesn't (always) Help us port code to multitple platforms
- Maybe we want to use more than one language...
<!--v-->

## Pick a Software Ecosystem
- Package manager
- Package Repositories, Standard Universes
- Standardized Development Tools and libraries

<!--v-->

# Examples

<!--v-->

# How do I Build a Website?

<!--v-->

## I could use Node JS, and the NPM package Manger

![Node.js Logo](assets/markdown-img-paste-20190119180927123.png)

![NPM Logo](assets/markdown-img-paste-20190119180941123.png)

<!--v-->

# I want to make a Data Science Application

<!--v-->

# I can use the Anaconda Distributtion of Python

![Anaconda Logo](assets/markdown-img-paste-20190119181547977.png)

![Pandas logo](assets/markdown-img-paste-20190119181641903.png)

![Tensorflow + Scikit Learn Logo](assets/markdown-img-paste-20190119181805186.png)

<!--v-->

# Let's go Broader

<!--v-->

# I want to Develop Software and administarte a Computer

<!--v-->

# I can Use A GNU/Linux Distribution, and Associated Tools

![](assets/markdown-img-paste-20190119182214275.png)
![](assets/markdown-img-paste-20190119182250989.png)
![](assets/markdown-img-paste-20190119182341837.png)
