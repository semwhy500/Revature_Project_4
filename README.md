# Event-Ticketing API

## Project Description

A Mule 4 project simulating an event ticketing web API, demonstrating communication between 3 back-end APIs. Includes unit testing with Mockito/JUnit and event logging with Log4j. 

## Getting Started

> Extract EricSchmidtP1TicketingAPI, EricSchmidtP1EventAPI, and EricSchmidtP1VenueAPI to a local directory, preserving the data structure.

> Edit database connection configuration (if necessary) in the config.yaml properties file in each project folder.

> Start all 3 services in Mule.

## Usage

> Using a REST-ready web client, send requests to the "ht<span>tp://localhost:(specified port)/(requested function path)" directory using the specified HTTP method. Supported function paths and their HTTP methods are below.

## Features

List of features ready:
* /event/findAll (GET) - Returns a list of all events
* /event/save (PUT) - Adds an event to the event database
* /venues/getvenues (GET) - Returns a list of all venues
* /venues/addvenue (POST) - Adds a venue to the venue database
* /event/{ID} (GET) - Returns a list of events matching the specified ID
* /event/delete/{ID} (POST) - Removes all events matching the specified ID in the event database
* /venues/{ID} (GET) - Returns a list of venues matching the specified ID
* /venues/delete/{ID} (POST) - Removes all venues matching the specified ID in the venue database
