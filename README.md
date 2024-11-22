<h2>Real-time News Subscription Service</h2>

<h4>Background</h4>:You're tasked with designing a real-time news subscription service for a media company. The system needs to notify subscribers about breaking news as soon as it's published by the news agency.

<h4>Scenario Description</h4>:The system comprises two main components: NewsAgency and Subscriber.

<h4>NewsAgency</h4>:Represents the central hub for publishing news. It maintains a list of subscribers and notifies them whenever new news is available.

<h4>Subscriber</h4>:Represents users or entities subscribed to the news service. Subscribers receive immediate notifications about any breaking news published by the agency.

<h2>Requirements:</h2>

<h4>Subscription Management:</h4>Users should be able to subscribe to the news service.
Subscribers should be notified promptly when new news is published.

<h4>Dynamic Subscription Updates:</h4>The system should allow for dynamic subscription updates. Subscribers can subscribe, unsubscribe, or modify their preferences without disrupting other subscribers.

<h4>Decoupled Communication:</h4>Ensure that the communication between the news agency and subscribers is decoupled. Subscribers shouldn't directly request news updates but should be notified by the news agency when new information is available.

<h4>Expected Behavior:</h4>When the news agency publishes breaking news, all subscribed users should receive immediate updates.
Subscribers can join or leave the service without affecting the delivery of news to other subscribers.
The system should provide flexibility for future enhancements, such as personalized subscriptions or categorization of news updates.

<h2>Constraints:</h2>
The system should be scalable to handle a growing number of subscribers without compromising performance.
Ensure that the implementation follows object-oriented design principles and promotes loose coupling between the news agency and subscribers.
