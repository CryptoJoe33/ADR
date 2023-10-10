# Title
Permissions

## Status
Accepted

## Context
There are many different changes or improvements which include:

### User Review and Ratings
Allowing users to leave a review on an establishment that they dined at allows users to make decisions prior to dining at that certain establishment. 

### Location Tracking
The app needs to have accurate tracking data of the progress of the food as well as relevant locations that are around the user. This can also tie into the review and rating as they will be able to locate nearby restaurants and view their reviews from other users.

### Notification System
This allows users to get realtime updates on the progress of their order. With notifications, they can get text or email updates based on how far the food is from their current location.

What is the change that we're proposing and/or doing?

## Decision

### User Review and Ratings
Earlier we mentioned adding a review portion of the application which will allow users to leave reviews on establishments. To allow the app to do this we will need to implement a user interface that lets users input their review but also allow users to view reviews made on an establishment of interest. For the front-end to work, we will also need a back-end that can enable the reviews to be stored and then called upon when they need to be displayed.

### Location Tracking
Inside the application we will have to implement many capabilities. Some of these capabilities could include GPS tracking, again, for accurate measurement of where the food is located in your vicinity as well location of food that is on it's way.

### Notification System
Similar to the User Review and Ratings decision that we made, the notification system will need a front-end for users to write their messages and view messages sent to them as well as the back-end to do so. This function also has to be designed correctly for push notifications to work properly. It may also need added security if someone that you do not know is messaging you about your food.


## Consequences

### User Review and Ratings
Pros: It allows users to engage in the community as well as be more invested in the app as they have a say that matters to some people. Also forces establishments to change depending on what the users say.
Cons: More data has to be stored regarding the users as what they say has to be stored as well as the data then has to be displayed.

### Location Tracking
Pros: Allows for users to be given valid recommendations for eating and food establishments regarding their location.
Cons: GPS and location tracking can be a scary thing considering it is not something that you want everyone to know. Having proper data storage is important when acquiring sensitive information like location.

### Notification System
Pros: Keeps users in the loop of promotions or just the progress of their orders. It can help with advertising and marketing as well to keep users informed on what is new with the app and locations around them
Cons: Hard to manage notifications for users in a timely fashion as things can get outdated.

