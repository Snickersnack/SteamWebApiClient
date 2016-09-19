# SteamWebApiClient
Simple Java/postgres backend for polling and persisting Dota 2 data

Multithreaded Dota 2 polling service built with Hibernate and Tomcat. Pulls all current and historical match info from the Dota, then pulls corresponding steam info for each player from the Steam API. Stores all data in a postgres database.


