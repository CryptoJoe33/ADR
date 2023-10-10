# Title
Data Storage

## Status
Accepted

## Context
Some specific motivations can include:

### User Convenience
Users want the most convenient way to view their orders currently or in the past. Maybe even being able to reorder past things that they may have enjoyed. This can enhance the user experience as the user can now have important functionality in the app.

### Competitive Advantage
If it has not been done already, order history can provide the application competitive advantage in the bustling food delivery business. As stated before, it increases the user experience in the application which can forward more users to your specific application.

### Retention and Loyalty
It is easier to come back to an app that is easy to understand and easy to use. Adding an order history functionality can increase user's loyalty by allowing them to reorder similar if not the same items as a previous order.

## Decision
The change that we are imposing is an order history feature. This feature lets users view old orders easily within the app.

### Data Storage Solution
Due to this added order history feature, we will need to implement a database, whether that be an SQL or NoSQL database to effectively store user information about their previous orders. This can then be returned to the user easily whenever it is called upon so that the user can view their past transactions/orders.

### Data Retrieval Mechanism
Similar to Data Storage Solution, Data Retrieval Mechanism will be implemented in the app to allow for the users to have their data retrieved and displayed.


## Consequences
Many different implications can be applied to the order history feature, some of which can be difficult to apply and implement and some the opposite. Here are some examples of easy to implement:

### User Retention
Offering the order history feature can allow users to return to an app that they already know very well and allows users to return to the order history screen without thinking about it too much.

### Marketing and Personalization
Going hand-in-hand with Notification System, Marketing and Personalization can be useful for users to get real-time updates about the app and establishments around then, as well as reactions to reviews that might be interacted with.

Here are some more difficult implications to add

### Data Privacy and Security
This can be difficult to implement as it is so important to an app such as this which includes GPS tracking of your current location, as well as important and sensitive data regarding the user. It also has to comply with the user privacy policy which can get tedious.

### Data Backup and Recovery
With all this data being used and transferred, there may be an issue that arises from this. This is why it is imperative to have an efficient Data Backup and Recovery plan as it would be very dangerous for user information to be lost in the process. It must be planned well for it to go well.