# LAB - Class 11

## Project: Code Academy Parcel Service (CAPS)

### Authors: Branden Ge

### Problem Domain

This lab demonstrates how to implement an event-driven application using Node Events. A series of event listeners and event emitters pass messages to each other.

- [GitHub Repo](https://github.com/brandenge/code-academy-parcel-service)

### Setup

- N/A

#### Running the app

1) Run `node server/hub.js` to start the server hub event listeners.
2) Run `node drivers/driverEvents.js` to start the drivers event listeners and emitters.
3) Run `node vendors/vendorEvents.js` to start the vendor event listeners and emitters.

#### Features / Routes

Events

1) New Order - emitted from vendorEvents to itself to trigger the entire event chain.
2) Pickup - emitted from vendorEvents
3) In-Transit - emitted from driverEvents
4) Delivered - emitted from driverEvents

#### UML Diagram

![UML Diagram](uml11.png)

Diagram created with [Figma](https://www.figma.com/)

#### Credits: [Demo code from Ryan Gallaway at Code Fellows](https://github.com/codefellows/seattle-code-javascript-401d48/tree/main/class-11/inclass-demo)
