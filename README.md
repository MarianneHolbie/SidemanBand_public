# SidemanBand Web App


Welcome to the SidemanBand web app public repository! 

The world is populated by both professional and nonprofessional music groups. The individuals comprising these groups often participate in multiple bands or pursue music as a secondary occupation. Just like anyone else, they may encounter unforeseen circumstances such as illness, injury, or work-related travel that necessitates their absence.
When a music group plans a concert, the designated person in charge typically begins by inquiring about everyone's availability. If necessary, they then proceed to search for potential replacements. The primary objective is to find substitute musicians as quickly as possible to allow for rehearsals with the new members, if applicable. Nevertheless, there are instances where replacements need to be secured at the eleventh hour.
Finding suitable replacements can be a complex process that often relies on musician networks. These networks facilitate the exchange of potential names and contact information through phone calls. However, sharing someone's contact details without their consent poses difficulties, and acting as the intermediary can result in a waste of time.
This project aims to streamline the process of finding replacements for music groups, eliminating the need for extensive phone calls that consume hours of valuable time.

SidemanBand is the perfect platform to help Band to found sidemen and for Sideman to found band to replace for gig.

For learning more see the [LANDING PAGE](https://sidemanband-lp.vercel.app/) 
and blogpost in [Medium](https://medium.com/@marianne.arrue/with-sidemanband-say-goodbye-to-wasting-time-and-spending-hours-on-the-phone-to-find-replacement-97719543d8d0)

## Features

- **Create and Manage Profiles:** Users can create and manage their profiles: update informations, add or delete instrument and level of pratics, add or delete band.

- **Search List** Users band can search a list of sidemen with specific requierement and contact them directly in app

- **Replacement request** Users band can emit a message for all sidemen corresponding to searched requierement for a specific gig and manage answer.

- **Notification:** Sideman can view all replacement request in the notification tab and respond


## Technologies Used

- **Docker-compose** Docker compose is used with 2 images : one for the API and the other one for the MySQL database.

- **FastAPI:** FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.

- **JWT** JSON Web Tokens are an open, industry standard RFC 7519 method for representing claims securely between two parties.

- **MySQL** MySQL is the world's most popular open source database is that it provides comprehensive support for every application development need.

- **SvelteKit:** SvelteKit is the framework used to build the frontend of the web app. It offers a delightful development experience and efficient rendering for optimal performance.

- **Tailwind CSS:** Tailwind CSS is utilized for styling the web app, providing a flexible and utility-first CSS framework.

## Installation

--- Only for authorize user ---

- fork repository
- build docker
``` 
docker compose build 
```
- run with docker desktop your created container
- in the folder where you download the fork, launch the api with 
``` 
uvicorn app.main:app --reload --port 3000 
```
- on the other terminal, go to the front part directory and build front with
``` 
npm run dev
```

Now you can connect to your local in port 3000 to view the connexion to the back part, in :3000/docs to view the swagger doc, and http://localhost:5173/ to view the front part.

## Usage

on the local deployement you can create user, create instrument or groupe, delete instrument or group, send message of specific sideman in a view list or send a notification for all sideman coresponding search with intereact in the dashboard after authentication.

## Related projects
None

## Contributing - Licensing

All right reserved - [Marianne Arrué](https://www.linkedin.com/in/mariannearrue/)
