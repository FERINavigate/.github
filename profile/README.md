# FERINavigate: Internal Navigation Solution for FERI Faculty
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)

FERINavigate is a web and mobile application aimed at enhancing the daily navigation experience for students and staff at the FERI Faculty. The app features classroom scheduling, a detailed interactive map of the faculty, and a navigation module that utilizes your phone's location to guide you to the right room. It is a Practicum I project developed for the FERI Faculty by students.

![FERINavigate Map Showcase](https://github.com/user-attachments/assets/2b0e33e1-27e6-43bb-bb1a-77c531ac67cd)

## Table of Contents
- [Introduction](#introduction)
- [Project Goals](#project-goals)
- [Technical Overview](#technical-overview)
    - [Components](#components)
        * [Scheduling Module](#scheduling-module)
        * [Map Module](#map-module)
        * [Navigation Module](#navigation-module)

## Introduction
FERINavigate is designed to improve the navigation experience for anyone on the FERI Faculty campus. The app provides up-to-date class schedules, an interactive map with all rooms and offices, and a navigation feature that uses your phone's GPS to guide you to the correct classroom. Whether you're a first-time visitor or a long-time student, FERINavigate is there to make sure you never get lost.

## Project Goals
- **Simplified Navigation**: Provide real-time navigation to rooms and offices within the FERI campus using the phone's location data.
- **Class Scheduling**: Display personalized schedules for students, helping them keep track of classes and locations.
- **Campus Map**: An interactive map that shows building layouts, important locations, and classrooms.
- **Accessibility**: Ensure that the app is user-friendly and accessible to all students and staff.

## Technical Overview
FERINavigate consists of three key modules that work together to offer a seamless navigation experience.

### Components
#### Scheduling Module
- **Description**: Allows users to view their class schedule and be notified about upcoming classes.
- **Technology**: The module fetches real-time schedule data from the FERI Faculty's servers.

#### Map Module
- **Description**: An interactive map of the FERI Faculty, with layers for classrooms, offices, and important facilities.
- **Technology**: Built using React, this module lets users explore the faculty building and find any room or office with ease.

#### Navigation Module
- **Description**: The heart of the app, this feature detects the user's location via GPS and provides real-time directions to the correct classroom or location within FERI.
- **Technology**: Integrates with the phone’s native GPS functionality and provides turn-by-turn guidance on the campus.

