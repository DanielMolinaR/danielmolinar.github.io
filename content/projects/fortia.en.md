+++
title = 'CRM for physiotherapy clinic'
date = 2021-05-15T17:20:16+01:00
draft = false
+++

The project I undertook involved the development of a comprehensive [CRM](https://en.wikipedia.org/wiki/Customer_relationship_management) (Customer Relationship Management) system tailored specifically for a physiotherapy clinic. The primary objective was to create an integrated toolset capable of streamlining the management processes associated with users, appointments, and prescribed exercises, ultimately enhancing the clinic's operational efficiency and service quality.

This CRM system caters to three distinct user categories: **patients, employees, and administrators**. Each category has been endowed with **specific privileges and access levels within the system**. Administrators enjoy comprehensive control over user management, appointment scheduling, and exercise administration. Employees, on the other hand, are tasked with managing appointments and patient-related activities assigned to them, whereas patients have the autonomy to oversee their individual appointment bookings, exercise regimens, and personal account details.

Security is of paramount importance, and as such, an array of measures has been implemented to safeguard sensitive data. These include **token-based authentication mechanisms** as defined in the protocol [OAuth2.0](https://oauth.net/2/), data encryption protocols, and email verification procedures for new user registrations, ensuring the integrity and confidentiality of information stored within the system.

The development of the application involved a bifurcated approach encompassing both [frontend](https://github.com/DanielMolinaR/front-fisioterapia) and [backend](https://github.com/DanielMolinaR/API-REST) components. Vuetify, a Vue.js-based material design framework, was employed for crafting the frontend interface. Leveraging Vuetify facilitated the creation of an intuitive, visually appealing **reponsive** user interface that seamlessly adapts to various devices, be it **desktops or mobile devices**. Meanwhile, the backend logic was constructed using **Go**, a programming language renowned for its performance and concurrency capabilities. Communication between the frontend and the backend is done through a **RESTful API**, which is responsible for handling requests and responses between both parties.

The database used to store the application information is **PostgreSQL**, which offers robustness and security in data management. In addition, **KeyCloak** was integrated for user account management and the generation of access tokens and refresh tokens, following the OAuth 2.0 protocol to guarantee security in user authentication and authorization.

Furthermore, the application was engineered as a **Progressive Web Application (PWA)**, endowing it with native-like capabilities and enabling users to install it directly onto their mobile devices via a web browser. This implementation grants users the convenience of offline access and push notifications, enhancing overall user experience and accessibility.

In summation, the project represents a successful endeavor in the realm of physiotherapy clinic management, characterized by a meticulous focus on security, usability, and cross-device compatibility. By harnessing advanced technologies and adhering to best practices in software development, the CRM system offers a robust solution tailored to the specific needs of the healthcare sector.