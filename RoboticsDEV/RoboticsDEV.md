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

# How do we develop Modern Software?

<!--v-->

# Pick a programming Language

| ![Python Logo](assets/markdown-img-paste-20190119173231961.png) | ![JavaScript Logo](assets/markdown-img-paste-20190119173534494.png) | ![C++ Logo](assets/markdown-img-paste-20190119173609722.png) |
| --------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
|                                                                 |                                                                     |                                                              |
