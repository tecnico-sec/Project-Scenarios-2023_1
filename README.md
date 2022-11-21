Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Project Scenarios

Congratulations! You have been hired by one of the following companies.
Each company has its business context and, more important, a set of security challenges (that will appear later).
More ahead in the project, your team will have to write a proposal to address a specific security challenge.

<!--
Additional challenges can be proposed, as long as there is a clear security core, which will require the use of cryptographic primitives.
-->

_Important note: the security aspects, both functional and assurance ones, are the essential points where you should focus your work and will be the main metrics to be considered in the grading. In the designed and proposed solutions, user interface concerns are secondary._

----

## 1. Retail: MusicMarkt

_Business Context_

MusicMarkt is an online store that sells all things music related. It offers a large variety of items such as musical instruments, sound systems, CDs, vinyls and other merchandise.

MusicMarkt allows reservations to be made for some new products before they are made available.
These products are usually CDs, vinyls, limited edition items, etc.

In order to reward loyal costumers and loyal fans, MusicMarkt has a scoreboard for each band and artist that ranks customers by the money they have spent on items from that band or artist.
When reservations open for a new item, during the first 24 hours only the top ranked customers in the respective scoreboard(s) can make a reservation.

## 2. Transportation & Distribution: Lemon

_Business Context_

Lemon is an international shared electric vehicle company that operates in Portugal since 2018, both with electric scooters and electric bicycles.

Customers can look for and unlock these vehicles through a mobile app or a website, where they also perform the payment for the used services.

Lemon's employees also have an internal app to pick up wrongly parked vehicles, which has access to their location through GPS and suggests the best course with Google Maps integration.

## 3. Restaurants & Tourism: TheCork

_Business Context_

TheCork is a service that allows its users to taste the best food and wines in town by enabling easy restaurant reservations via a very user-friendly mobile application that integrates seamlessly with the restaurants' calendars.

TheCork offers a mobile app to its customers to display the list of restaurants available at the user’s location. It also allows them to book a table for a specific number of people if the restaurant still has free tables.
There is also a website that provides the same functionality.
TheCork also provides back-office for the restaurants which is used to manage the schedule and to approve or deny the customers reservations.

The system also has an external integration with a discount card service provider, that allows customers to use their card points in order to have discounts in their bookings.

## 4. Insurance & Banking: NCMB

_Business context_

Nova Caixa Milenar Bancária NCMB is a bank that operates in Portugal since 1900.
It has a large portfolio of clients, from individuals to small businesses, and large multi-national organizations.
NCMB has a large catalog of products: credit cards, mortgages, and small loans, and acts as a financial broker (allowing customers to trade shares and other assets).

The front-office of the NCMB offers a public website that displays the products and services; a private website in which clients can access their bank account information and subscribe to their products.
The information presented on the websites and corresponding features can also be accessed through a mobile app.

A back-office is used by the bank employees to contact the clients, propose new products, and manage the portfolio of the customers (buy and sell financial assets).

The system has integration with external institutions, namely, the Bank of Portugal (to communicate the financial details of the customers) and insurance companies (to promote insurance services that are associated with the loans).

## 5. Healthcare: SAH

_Business context_

_Saint Acutis_ hospital operates in Portugal since 2020.
It provides Urgent Care, open 24/7 (24 hours, 7 days a week).
It also provides Speciality Consultations, including: Orthopedy, Cardiology, and Dermatology.

The front-office of the hospital offers both a public web site, for displaying general information, and a customer web site, where patients can check their appointments and make new ones.
There is also a mobile application that provides the same functionality.

The back-office is used to manage the schedule, the room reservations, and the medical records.

The system has integrations with external institutions, namely, the Ministry for Health, and several exam facilities and laboratories.

## 6. Legal: ALA

_Business Context_

The ALA (Ávila & Lisieux Attorneys) is a Law Firm providing legal services in both Fiscal and Criminal Law.
The legal office has a front-end server that runs a web site displaying the usual overview of the firm organization, areas of activity and contact information, as well as providing some services to both ALA lawyers and clients.
This website and services can be accessed both by desktop browsers and by a mobile application.

The ALA website services are connected to a back-office that is used to manage all persistent data.

Furthermore some of these services involve third party entities within the Portuguese legal system with which legal documents must be exchanged.

Since ALA handles court cases around sensitive topics that may involve people willing the compromise the data and systems of ALA, its managers are worried that some of its services might be attacked.
The weakest link seems to be the communication between the ALA system and both the ALA clients (desktop and mobile) and other external entities.

## 7. Industry: StarDrive

_Business context_

StarDrive automotive is a company focused on self-driving and remote control vehicles.
The production plant deploys several sensors and actuators, to achieve a mostly automatic assembly line.
The entire production plant is controlled by a complex system that allows the engineers to oversee the production process and detect anomalies.

The front-office of the StarDrive management system allows the employees to monitor the production process.
A “public” version of the front-office can be accessed from the Intranet of StarDrive allowing any employee to see, in real-time, the production statistics and the distribution of the working shifts.
A private area of the front-office allows the factory employees to consult private information about their job status (for example: salary, absent working days, parental leaves, etc).

A back-office is used by the engineers to buy production parts, manage information about the factory employees (for example team salaries), query stock information, access information from the sensors, and access the actuators to control the production process.

The system has integration with external institutions, namely, providers, audit companies, accounting firms to process salaries and taxes, and car dealerships.

## 8. Utilities: EcoGes

_Business Context_

EcoGes is the new system for the Electricity provider, which allows clients to have a minute-by-minute update on their energy consumption and production (if that is the case).
With this new system, the user will be able to monitor the energy cost of every household appliance or how much energy the solar panels are producing by logging into the EcoGes website.
This system is also used to manage the contract of every user and to calculate the monthly invoices regarding the consumed energy, the energy plan (flat rate or bi-hourly rate), and taxes.

This system is composed of a public website (front-office), for the clients to have access to energy consumption information and update their personal data; an internal private back-office (via a website or through a management console) where the employees of EcoGes can manage the system according to their role in the company (marketing, account manager, technical assistance, or system manager).

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
