# API's

### RESTful API Design

RESTful API we mean an API that follows Representational State Transfer (REST) architectural style.

REST is a very popular approach to building APIs because it emphasizes simplicity, extensibility, reliability, and performance.

* **Simplicity**: The way to interact with API resources is well-defined and strict: you have a clear and simple path to follow concerning what you can and cannot do. Interaction is stateless: requests have all data needed to move resources to the next state.
* **Extensibility**: Support for representing the same resources with different formats or even versions, ability to add new resources without changing others, etc.
* **Reliability**: Clear separation of actions with and without side-effects, the possibility of retrying requests with idempotent actions, etc.
* **Performance**: Caching made possible via well-defined semantics, scalability made possible because server resources can be isolated in each request due to stateless interaction, etc.

REST:

* _Resources_ – You can think of those as the “nouns” of your system. For example, in a food-delivery service API, the nouns would be restaurant, menu, menu item, restaurant owner, etc. Those nouns are what hold the _State_, the “S” in REST.
* _Representations_ – Representations are the way API clients see the resources. A RESTful API never hands resources directly to a user. Interactions happen only via representations of the real resource. For example, you can store all the menu items for a restaurant in a database table, but the representations of these items in your API might be a list of names and prices, perhaps filtered to reflect restrictions specified by the user. To do this, we use media types such as JSON and XML. That’s why REST is “RE”presentational.
* _Actions_ – Because API clients do not have direct access to _resources_, they need _actions_ to alter the state of a _resource_. Those _actions_ are the _verbs_ of our system. They are what “transfer” the state, the “T” of REST.

**It’s important to understand that REST is not a protocol, but an architectural style. It’s a set of rules and guidelines that define how a system should function.**



{% embed url="https://www.oreilly.com/content/how-to-design-a-restful-api-architecture-from-a-human-language-spec/" %}

{% embed url="https://slack.engineering/how-we-design-our-apis-at-slack/" %}



{% embed url="https://cloud.google.com/apis/design" %}



{% embed url="https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design" %}

{% embed url="https://github.com/WhiteHouse/api-standards" %}



{% embed url="https://github.com/microsoft/api-guidelines/blob/vNext/Guidelines.md" %}

{% embed url="https://ics.uci.edu/~fielding/pubs/dissertation/top.htm" %}

{% embed url="https://ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation.pdf" %}



{% embed url="https://www.youtube.com/watch?v=-mN3VyJuCjM" %}



{% embed url="https://blog.treblle.com/the-10-rest-commandments/" %}



{% embed url="https://opensource.zalando.com/restful-api-guidelines/#introduction" %}



