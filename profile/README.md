# ML-for-B-E

![](head_picture.png)

## Timetable Info

## Timetable ML and planning
https://docs.google.com/spreadsheets/d/1AOx12J9GmASa02Xztr7iaI-rxc2h3ToLkP-sPInRov4/edit?usp=sharing

# Badges

## Objectives

All organization's repositories should contain a version of the following badges. The goal is to improve the readability and understand the use and the level of readiness of the repository (main branch).

## Badges explained

![use](https://img.shields.io/badge/use-Summer%20Camp-green) 
folder to be downloaded by Summer camp's participants for specific course.

![use](https://img.shields.io/badge/use-Project-green) 
Project developped by or for students on a specific issue

![readiness](https://img.shields.io/badge/readiness-initialization-red) 
A repository with the badge ![use](https://img.shields.io/badge/use-Summer%20Camp-green) will have this badge if the main branch contains at least the following folders/files:

```
xxx-course/
├── global_planning/        (optional)
├── notebooks/              --> this folder contains all the notebooks used for the course and the TD
│   └── **.ipynb/  
├── figures/
│   └── **.png/ (.jpeg)
├── slides/
│   └── **.ppt/ (.pdf)
├── src/
├── tests/
│   ├── notebooks/        --> do the notebook run?
│   └── src/              --> unit testing
├── requirements/
│   └── **.txt
├── .gitignore
├── README.md
└── setup.py

```

![readiness](https://img.shields.io/badge/readiness-downloadable-red) the notebooks contain all the information necessary for the intended course

![readiness](https://img.shields.io/badge/readiness-fully%20implemented-red) the repository is downloadable and all the tests (functions and notebooks) are implemented And the (will-be) CI passes
