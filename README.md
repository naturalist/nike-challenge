# Trimet Vehicles Near You

This is a serverless single-page application for Web and Mobile. Its purpose is to show all Trimet vehicles within a radius of 3 miles of your location.

## Live Example

You can see a live example here: [https://naturalist.github.io/nike/](https://naturalist.github.io/nike/). The application will scale its size if viewed from a mobile device. 

Please make sure that your browser or phone allows geolocation services, and that you do not have any tracker blockers, such as Ghostery or uBlock. They can sometimes block Google Maps.

## Background

This project was created on a Wednesday evening as part of this [https://github.com/uber/coding-challenge-tools](coding challenge) for Nike.

The challenge objective has been slightly modified to adapt it better to Portland's Trimet API.

## Problem

Create a service that gives real-time location for public transportation in the immediate vicinity of the user. The app should geolocalize the user, and it should display all vehicles on a map, where the user could see them move in (almost) real time.

## Solution

Given that only publicly available API endpoints have been used, such as [https://developer.trimet.org/ws_docs/vehicle_locations_ws.shtml](Trimet Vehicle Location Service) and [https://maps.google.com](Google Maps), it has been deemed that this application does not need a back end. The latter would have been required **if** either of the services used required authentication.

Therefore, a serverless single-page application with responsive design has been created using the following tools:

* The [http://vanilla-js.com](VanillaJS JavaScript framework) - a fast, lightweight, cross-platform framework
for building incredible, powerful JavaScript applications.
* The [https://minicss.org/index](MiniCSS CSS framework) - providing responsive grids and pleasant typefaces. 
* The [https://developer.trimet.org/ws_docs/vehicle_locations_ws.shtml](Trimet Vehicle Location Service)
* [https://maps.google.com](Google Maps)


