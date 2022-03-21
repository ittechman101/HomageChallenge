# Homage Challenge - @Kyle Wilson 2022/03/19
Homage Code Challenge for Vaccination Center App in Singapore

## Challenge Description
COVID-19 is a global pandemic and to allow country wide activities to resume, vaccinations are introduced to decrease the death rate from the infection.
You are tasked to build a reservation system for COVID-19 vaccinations in Singapore. This means a user should at least be able to schedule their 1st vaccination dose. Each vaccination centre has a different number of nurses that work on different days; the amount of patients each centre can handle will differ.
The system should support following features:
- Support multiple vaccination centres in Singapore 
- Keep into account the daily supply of the nurses for each centre and their duty schedule
- Model the daily capacity of a centre and accordingly allocate the vaccination slots to the residents 
- Support CRUD operations for the slot reservation 
- Avoid double reservation (What happens if the same user books again?) 
- The solution should handle the resource contention (What happens if 2 different users book the same time slot?)
## How to Install backend and frontend?
_Open two console windows and Go to backend and frontend folders, and then execute following commands._
```sh
cd backend or frontend
npm install
npm start
```

> I built both backend and frontend projects and enhanced the front-end UI for more features of this challenge..

## Project architecture for Vaccination Reservation Management System.
- The backend project was built by Node.js [Express](https://nodejs.org/).
About the project dependencies, please reference the backend/package.json file.
Backend provides CRUD API for front-end of the vaccination reservation system.

- The frontend project was built by [React.js](https://reactjs.org/).
About the project dependencies, please reference the frontend/package.json file.

- Database (SQLite)
./backend/data/database.sqlite

## How do you do Unit Testing in backend
> cd backend
> npm run test

## How to Use the App
> Note: We have static vaccination centeres in database.
And every nurse can supply up to 24 people per a day in each center.
This means that people can select among 24 time slots per a day if the center has more thann one nurse scheduled on the date.

![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/1.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/2.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/3.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/4.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/5.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/6.PNG)
![alt text](https://github.com/ittechman101/HomageChallenge/blob/4e9afd3dad8893d2b1dc2dde32bccbc1367d6657/screenshots/7.PNG)



