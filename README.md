# Event-Ticketing API

## Project Description

A Mule 4 project simulating an event ticketing web API, demonstrating communication between 3 back-end APIs. Includes event logging.

## Getting Started

> Extract EricSchmidtP1TicketingAPI, EricSchmidtP1EventAPI, and EricSchmidtP1VenueAPI to a local directory, preserving the data structure.

> Edit database connection configuration (if necessary) in the config.yaml properties file in each project folder.

> Start all 3 services in Mule.

## Usage

> Using a REST-ready web client, send requests to the "ht<span>tp://localhost:(specified port)/(requested function path)" directory using the specified HTTP method. Supported function paths and their HTTP methods are below.

## Features

List of features ready:
* /event/getAll (GET) - Returns a list of all events
* /event/add/{ID} (PUT) - Adds an event to the event database with the specified ID
* /event/{ID} (GET) - Returns a list of events matching the specified ID
* /event/delete/{ID} (POST) - Removes all events matching the specified ID in the event database

* /venue/getAll (GET) - Returns a list of all venues
* /venue/add/{ID} (POST) - Adds a venue to the venue database with the specified ID
* /venue/{ID} (GET) - Returns a list of venues matching the specified ID
* /venue/delete/{ID} (POST) - Removes all venues matching the specified ID in the venue database

* /ticketing/getEvents (GET) - Returns a list of all events
* /ticketing/addEvent/{ID} (PUT) - Adds an event to the event database with the specified ID
* /ticketing/findEventByID{ID} (GET) - Returns a list of events matching the specified ID
* /ticketing/deleteEvent/{ID} (POST) - Removes all events matching the specified ID in the event database
* /ticketing/getVenues (GET) - Returns a list of all venues
* /ticketing/addVenue/{ID} (POST) - Adds a venue to the venue database with the specified ID
* /ticketing/findVenueByID{ID} (GET) - Returns a list of venues matching the specified ID
* /ticketing/deleteVenue/{ID} (POST) - Removes all venues matching the specified ID in the venue database