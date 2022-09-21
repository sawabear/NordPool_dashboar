# NordPool_dashboar
Dashboard of electricity prices in Europe and volumes of electricity exchange between Russia and Europe.

In first quarter of 2022 years website Nord Pool closed historical data about their energy system for non-Europe users. So u can see my code and only screenshots of dashboard.

# How does it work
1. Upd_script - how u can see it's a script for updating data. It's better to use another way to run the code, but this is how i did.
2. Day_price_parer - sending request to NordPool website and download historical data. Then formating this data and save on local disk. Also this code get future electricity price from nasdaq. Warning! THIS CODE DOESN'T WORK BECAUSE NordPool CLOSED DATA.
3. Price_dashboard - create dash on data. U should change path to your local path with NordPool data (u can download this file from this repository) and run this code. Please, check IP before starting server.
