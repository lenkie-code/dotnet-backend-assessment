# dotnet-backend-assessment
.NET Software Engineer Assesment

Martha owns a local library, her customers often complain about coming to the book store and not finding the books they
came to borrow. To prevent this, customers currently call the library and ask if the books they are looking for are available. Typically, over the call:

1. The customer specifies the name of the book
2. Martha checks her library for the book
3. If it's available, the customer has the option to reserve it for the next 24 hours until they've come to the library to collect it.
4. If the book is reserved, another customer cannot reserve or borrow it.
5. If the book has been borrowed by another customer, Martha lets the enquiring customer know when the book would be returned to the library

Martha's library has recently gained massive popularity after a visit from a popular fiction novel writer. Her customer base has increased and continues to grow. She would like to focus on rennovating her library to accomodate more people. Managing and renting out books over the telephone is taking too much of her time and resources, she is looking for a way for customers to search her library, reserve and borrow books online. She wants her customers to be able to access her library with whatever device they choose (cellphone, laptop, desktop, etc.)

Her grandson has a lot of experience with building web applications and has volunteered to build a progressive web application that customers can use to access Martha's library from any device they choose. He has tasked you to build an API that can provide all the functionality for managing customers, books and reservations.

In your implementation, take into account the following key details:

- **Authentication & Authorization**: Since the application will most likely store customer data, some security constraints must be enforced on who has access to the data.
- **API Documentation**: The application should run on any device, documenting the API would be important as it would allow any frontend engineer to make the app available to customers using different devices.


### Bonus:

For books that are reserved / currently borrowed out, customers should be able to request to be notified once the book is now available in the library. In this initial iteration, the notification could be persisted in some notifications table / storage at the time the book becomes available.

### What Tools Can You Use?

- Use this opportunity to showcase your understanding of software architecture and  .NET Core.
- You may use whatever persistent storage you think is best. 
- Demonstrate your understanding of OAuth and how it can be used to secure APIs. You can use your own Identity Server or leverage an existing one.