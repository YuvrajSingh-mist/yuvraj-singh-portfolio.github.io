---
title: "PlogPayouts | AI-driven Plogging System"
collection: talks
type: "Google's Solution Challenge '24"
excerpt: "Transform your daily jog into a mission for a cleaner world with PlogPayouts. Our innovative website + app rewards you for collecting litter, promoting fitness and environmental cleanliness. Utilizing AI for trash categorization and optimized routes, and fostering community through shared stories, PlogPayouts turns every step into a step towards a greener, more inclusive society. Join us and make a difference today! "
permalink: 
venue: "IIIT"
date: December '23 - March '24
location: "Bhubaneswar"
---

 Team Lead + Backend (AI/ML)

* **Vision/Goal**: We aim to provide not only an idea but also a solution to bring about a small and effective change in the garbage collection process  and  also tacking the social stigma regarding the position and work of garbage collectors as perceived by the society, so as to harbour a more cleaner and greener environment while working together without any social differences.

* **Solution**: Our product (website + app) provides a solution to ever-growing concern about a healthy environement and cleanliness altogether, especially in places where there is scarcity of any garbage collectors.  Our solution integrates an every days activity which keeps one fit jogging while contributing little bit to a healthy environement by collecting litter from manageable trash sites, leading to our solution - PlogPayouts.

* **Features** 

**Categorization of Trash w/ Deep Learning** | Used Transfer Learning on VGG19 model alongwith a custom dataset combined with an open-sourced and hand labelled ones.

**Reward System** | Earn points for each category and count (using YOLOv8) of litter collected during plogging and once the garbage collected has been verified by the Garbage Collector on-site (so the garbage collected does reach to a factory through the worker), points are sent. | Redeem points in the 'Store' for gift cards. | The categorization of garbage is intended for smoothing out the process of post garbage collected by already organizing the garbage as much as possible.

**Map Location** | Genetic Algorithm automatically finds the best route for the locations of trash sites marked as 'Favourite' so as to cater to their jogging times (upto 3 max).

**Blog System** | Share plogging experiences, environmental tips, and success stories through the integrated blog system, brining in the community together and breaking the social stigma how 'garbage collector' are perceived.

* **Tools**: 

**Client:** | Flutter, HTML, CSS JavaScript, Bootstrap

**Backend:** | Flask, Python ,Django , Keras, OpenCV, YOLOv8

**Storage:** | Firebase Firestore, Realtime Database, Storage

**Other Tools:** | GCP APIs, Mapbox, Render, Docker


[**Project Link**](https://github.com/YuvrajSingh-mist/PlogPayouts)