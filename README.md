# Pet Hotel

## Description

_Duration: 2  Days_

Pet Hotel is a Pet Boarding Management App for a hypothetical pet hotel. The user can add pets to the database of pets, including the option to upload a pet photo. Once a pet is added, the user can check-in and check-out pets, as well as manage clients (pet mom & dads),
adding new clients and deleting old ones. 


## Prerequisites

The following software is required to install Pet Hotel:

- [Node.js](https://nodejs.org/en/)
- [PostgreSQL](https://www.postgresql.org/download/)


## Installation

1. Create a database named `pet_hotel`
2. The queries in the `database.sql` file are set up to create all the necessary tables and populate the needed data to allow the application to run correctly. The project is built on [Postgres](https://www.postgresql.org/download/), so you will need to make sure to have that installed. I recommend using Postico to run those queries as that was used to create the queries.
3. Open up your editor of choice and run an `npm install`
4. If Postgres is not already running, start it by entering `brew services start postgresql` into the terminal
5. Run `npm run server` in your terminal
6. Run `npm run client` in your terminal
7. The `npm run client` command will open up a new browser tab for you!


## Usage

1. Anais is the owner of Bubbles & Beds Pet Hotel. B&B offers an overnight boarding service for pets.
2. Anais used to keep track of her clients and their pets in an Xcel spreadsheet, but now she uses Pet Hotel.
3. Anais has a new client Jane who would like to board her puppy Milo, so first Anais registers Jane as a Pet Owner.
4. Next, Anais registers Milo as a Pet, including Milo's breed and description, and then uploads a photo of Milo for easy identification.
5. On the day Jane drops Milo off for the first time for boarding, Milo is already in the system and so Jane clicks the Check-In button next to Milo's name so she knows that Milo is currently being cared for at the B&B Pet Hotel. When Milo's stay is over, Anais clicks Check-Out.
6. Six months later, when Jane informs Anais that she is moving to a different town and will no longer be a client of Anais', she deletes Jane as an Pet Owner so as not to clog up her database.


## Built With

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Firebase](https://firebase.google.com/)
- [Reactstrap](https://reactstrap.github.io/)
  

## Acknowledgements

Thanks to [Prime Digital Academy](www.primeacademy.io) who equipped and helped me to make this application a reality and my cohort who built this web application alongside me.


## Support

If you have suggestions or issues, please contact me through [LinkedIn](https://www.linkedin.com/in/kristenstoeckeler/).