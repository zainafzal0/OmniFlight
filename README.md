<p align="center">
<img src="https://github.com/alish2001/OmniFlight/blob/master/frontend/public/omniflight_logo_black_background.png?raw=true">
</p>

Direct flights from more than 1000 airlines on an interactive flight map. Search, find, compare, and save any flight path or airline route with our flight maps!

# Data Loading

The database will initialize tables and load data from the [data directory](/database/data) upon the creation of the docker volume aka first start.
If you want to run this auto-creation again, delete your docker volume and restart the docker-compose.

# Instructions to run the app

1. Clone the repo
2. Run the following command `docker-compose up --build`
3. Navigate to the OmniFlight site to register and login

The app should now be available on `localhost:3000`

## Demo

### Homepage

<img src="https://github.com/zainafzal0/OmniFlight/blob/master/images/omniHome.png" alt="home_page" width="500"/>

### Search for flights

<img src="https://github.com/zainafzal0/OmniFlight/blob/master/images/omniSearch.png" alt="search" width="500"/>

### See flight statistics

<img src="https://github.com/zainafzal0/OmniFlight/blob/master/images/omniStats.png" alt="stats" width="500"/>
