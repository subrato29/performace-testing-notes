- Connection Time: Time to connect to Server from client

- Response time: is a measure of how responsive an application or subsystem is to a client request.

- Throughput – indicates the number of transactions per second an application can handle, the amount of transactions produced over time during a test. requests per second, calls per day, hits per second, reports per year, etc.

- Scenarios: In the context of performance testing, a scenario is a sequence of steps in your application. A scenario can represent a use case or a business function such as searching a product catalog, adding an item to a shopping cart, or placing an order.

- Bottleneck - Used to describe a single part of a system that prevents further processing or significantly degrades the performance of the system as a whole

- Capacity - The degree to which a system can perform data processing until performance degrades. For example, the number of new customers being added to a database

- Concurrency - Normally this means the number of simultaneous virtual users driving transactions across the User Journeys in a given performance test scenario, but can also mean the number of transactions synchronised to happen at exactly the same point.

- Key Performance Indicators (KPI) - The set of targets which set the expected performance targets within the Production system. These may include page response times, user concurrency, batch processing times, data throughput volumes, transaction failure rates, and underlying infrastructure behaviour (e.g. Maximum Average CPU used, Minimum Free Memory Available, thresholds for remaining physical storage / disk usage, logging space etc)

- Load Testing - A type of Performance Testing used to evaluate the behaviour of a system or component when the load on the system (via users and transaction) progressively increases up to and including peak levels

- Non-functional requirements (NFRs) - Requirements that do not relate to the functioning of the system, but to other aspects of the system such as reliability, usability and performance

- Performance Engineering - Activities designed to ensure a system will be designed and implemented to meet specific non functional requirements. Often takes place following completion of testing activities that highlight weaknesses in the design and implementation.

- Performance Test Plan - Typically a written document that details the objectives, scope, approach, deliverables, schedule, risks, data and test environment needs for testing on a specific project.

- Performance Testing - Testing designed to determine the performance levels of a system

- Reliability - Related to stability, reliability is the degree to which a system provides the same result for the same action over time under load.

- Scalability - The degree to which a system’s performance and capacity can be increased typically by increasing available hardware resources within a set of servers (vertical scaling) or increasing the number of servers available to service requests (horizontal scaling).

- Soak Testing - A type of Performance Testing used to evaluate the behaviour of a system or component when the system is subjected to expected load over a sustained period of time

- Spike Testing - A type of Performance Testing used to evaluate the behaviour of a system or component when subjected to large short-term changes in demand. Normally this is to test how the system responds to large increases in demand, e.g. User Logins, Black Friday-like sales events etc.

- Stability - The degree to which a system exhibits failures and errors when under normal usage. For example, erroneous errors when registering new users under load.

- Stress Testing - A type of Performance Testing used to evaluate the behaviour of a system or component when subjected to load beyond the anticipated workload or by reducing the resources the system can use, such as CPU or memory.

- Transaction Volume Model (TVM) - A document detailing the user journeys to be simulated, the click-path steps that make up the user journeys and associated load / transaction volume models to be tested. This should include information regarding the geographical locale from where users will be expected to interact with the system and the method of interaction e.g. mobile vs desktop.

- User Journey - The path through the system under test that a group of Virtual Users will use to simulate real users. It should be noted that key performance / volume impacting journeys should be used as it is impractical to performance test all possible User Journeys, a good rule-of-thumb is to use the 20% of User Journeys that generate 80% of the volume.
Virtual User - A simulated user that performs actions as a real user would during the execution of a test.
