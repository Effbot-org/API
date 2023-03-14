# API
<a href="https://effbot.org/application-programming-interface-api-in-simple-terms/">Application Programming Interface</a>
What is an Application Programming Interface or API?
Application Programming Interface (API) can be considered as a bridge between two different software systems, allowing them to communicate with each other using some set of protocols.  The API defines the rules for this communication, including what data can be exchanged and how the request for information should be made.

Understand by day to day examples
You might have seen login systems on various sites. When you try to create a new account, there are various options you can do. First is to do it manually by filling in all the details like Name, email, and Password. The second way is to use Google, Facebook, or Twitter accounts to signup. Similarly for signin also.

This function that enables people to log in to websites by using their Google, Facebook, or Twitter profile login details is a type of Application Programming Interface (API).

Since Google, Facebook, etc already have users’ data in their database, any other website can use their data to verify users without taking every credential from fresh. This convenient feature allows any website to leverage an API from one of the more popular services to quickly authenticate the user, saving them the time and hassle of setting up a new profile for every website service or new membership.

Have you ever wondered how different travel websites show you live flight ticket availability status? This is only possible because these third-party booking websites use API provided by flight operating companies in lieu of paying their charges.

Another Example: Google Maps use US train tracking API to watch a specific train’s real-time movements to determine public transport travel times. The train you want to take is late, perhaps the bus gets you there faster. How do they know the bus times? By using the bus service APIs. How do they know which bus is going to arrive fastest? By accessing the highway department traffic flow monitoring API.

The route the most direct bus is going to take will be delayed by an accident on the freeway, another bus with a longer path will arrive first. All those APIs from all those separate services combine together to answer a question for Google Maps.

These APIs allow third-party applications to get access to data up to a limited layer called the API layer keeping the main internal system safe.

From all the above discussion, now you can somewhat conclude that API involves two parties. One who has lots of data regarding something and another who wants data for some purpose. Since hacking someone’s database to get data is not a joke and also not legal, hence big companies that have a tremendous amount of data create their APIs and provide those who need it to get access to those data. These APIs can be free of cost or paid.

Also, one point to be noted, API is not only meant for interacting one site with another. There is a concept of internal API where one functionality of a site interacts with another functionality through its own API.

For example, you create a Machine Learning model and create an API for the model. Through this API you can take the user’s data send it to the model for the prediction and respond back to the user query with the predicted results.

Advantages of building an API
Simplifies Application Production: A large modern complex application is built into several small components and they are joined further for a complete application.  APIs allow applications and system components to communicate with each other on internal networks as well as over the Internet.
Automation:  Using APIs, computers rather than people can manage the work. Through APIs, agencies can update workflows to make them quicker and more productive.
Availability of Rare data: The data that is generated and stored in databases at the government level or big business levels (like National ID data) can be accessed if these organization or firm provide their API.
Making money through API: There are a tremendous number of companies these days whose main revenue source is selling their APIs, called API Economy. In this model, the enterprise exposes digital business capabilities and products to a developer audience using APIs. The developer audience integrates relevant APIs within their products, digital services, or applications thereby exposing the enterprise to a larger external audience and greater revenue.
How an Application Programming Interface works
API is actually an intermediary layer between an application and the web server that processes data transfer between systems.


Basically, a client application initiates an API request to retrieve information which is processed from an application to the web server via the API’s Uniform Resource Identifier (URI). After receiving a valid request, the API makes a call to the external program or web server that sends a response to the API with the requested information. Finally, API transfers the data to the initial requesting application.

Even though data can be directly accessed from another site database, then what’s the need for API? This is so because the API provides a secure layer that gives access to only the data which the provider is happy to share keeping their main core system unaccessed and protected. Also, through API, a provider can cap the number of accessing requests.

The majority of the API requires a valid key to be used.  To use an API that requires an API key, you first need to obtain a key from the API provider. Some providers offer a free key that has limited usage limits, while others require payment to access their API. Once you have obtained an API key, you include it in the API requests you make, typically in the form of an HTTP header or as a query parameter in the URL.

Some common examples of APIs
Universal logins: A popular API example is the function that enables people to log in to websites by using their GMAIL profile login details.

Travel booking comparisons: Travel booking sites aggregate thousands of flights, showcasing the cheapest options for every date and destination. This service is made possible through APIs that provide application users with access to the latest information about availability from hotels and airlines.

Third-party payment processing: For example, the now-ubiquitous “Pay with PayPal” function you see on e-commerce websites works through an API. This allows people to pay for products online without exposing any sensitive data or granting access to unauthorized individuals.

Different Types of API
Open APIs: Also known as external or public APIs, Open APIs are available to developers and other users with minimal restrictions. They may require registration, an app ID, or an API key to function.

Internal APIs:  Also known as private APIs, these internal APIs are hidden from external users and only exposed to internal systems. They are intended to improve productivity and communication across different internal development teams.

Composite APIs:  These composite APIs bundle multiple endpoints or services into a single API request/response. These services allow developers to access several endpoints in a single call. Composite APIs are useful in microservices architecture where performing a single task may require information from several sources.
