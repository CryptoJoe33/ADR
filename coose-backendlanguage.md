# Title

Selection of Backend Language for Project

## Status

Accepted

## Context

The issue that were seeing is that there are numerous requirements that are are wanted by the clients that asks for the user to be able to easily access data that needs be stored in a database. 

1. Order History: User needs to be able to re order past orders from any restaurant
2. Order tracking: User needs to be able to track a order ono a real time basis 
3. API Integration: The app needs to be up to date with restaurant menu items.
4. Notification System: The app needs to send notifications on order confirmation, order updates , order delivery and promotions.
5. Payment Gateway: The app needs to able to handle transactions, and be secure.

## Decision

The change that were doing is that we are going to be implementing Node.js as our backend language in our development phase of the project.

## Consequences

What becomes easier:

1.  Gps Tracking: With using Node.js we are now able to implement gps tracking by using Socket.io. Socket.io enables bi-directional communication between web server and clients.

2. Push-Notifications: Node.js offers to allow to integrate Push Notifications which is requested by the client

3. Payment Gateway: Node.js allows to integrate with Stripe which is a popular payment gateway, Stripe is a level 1 service provider, which means that the payments will be secure.



