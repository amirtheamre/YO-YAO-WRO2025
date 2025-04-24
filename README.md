Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Введение

 Робот был собран из деталей комплекта LEGO EV3, на одном блоке из данного издания. Были использованы следующие моторы и датчики: large motor, middle motor, ultrasonic color sensor. Провода были подключены последовательно, отдавая приоритет каждой детали соответсвено. Программа для робота была написана используя блок-код, программы LEGO EV3 Classroom. Поворотная система была реализована при помощи датчика цвета, который при необходимом цвете совершал поворот влево или вправо соответсвенно.
 
