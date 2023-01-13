# Riddy - Sustainable Carpooling on the Blockchain

Welcome to Riddy, the decentralized, blockchain-based carpooling platform that connects drivers and passengers with similar schedules and routes while promoting sustainability and reducing the environmental impact of transportation. Our platform is built on smart contract technology, ensuring secure, transparent and tamper-proof transactions.

We use the Tremble Maps API to match drivers and passengers based on their pre-planned commuting schedule, including earliest depart time, latest allowed arrival time, start location, destination, and vehicle capacity. Our system also uses Google Maps API traffic prediction to help predict expected trip time.

Users can post their schedules ahead of time to be matched by our system, and our mobile application, built with React Native, also allows for real-time matching during the driver's trip. To ensure data security, we use decentralized technology to save user data. Our platform tracks and shows the carbon emissions saved by using carpooling in real-time, and offers incentives for drivers using green energy vehicles.

Riddy is committed to reducing the environmental impact of transportation and promoting sustainability. Download the Riddy mobile application soon and experience efficient and eco-friendly commuting with secure and transparent transactions ensured by smart contract technology.



## Features

1. Carpool matching based on pre-planned commuting schedules: Riddy uses Tremble Maps APIs to match drivers and passengers based on their commuting schedule, including earliest depart time, latest allowed arrival time, start location and destination, and vehicle capacity.
2. Real-time traffic prediction: Riddy uses Google API traffic prediction to predict expected trip time for users, helping them to plan their journey more efficiently.
3. Decentralized data storage: To ensure user data safety, Riddy utilizes decentralized technology to save user data.
4. Multi-platform Mobile App: Riddy is a mobile app that will be developed using React Native which makes it easy to access on all the mobile devices with Android or iOS as their operating system .
5. Real-time matching: Users can post their schedules ahead of time to be matched by the system, as well as real-time matching during the driver's trip.Community support: The app welcomes contributions and feedback from the community to help improve the functionality and user experience of Riddy.
6. Capability to handle million of concurrent requests: The database and the server will be strong enough to manage all the requests send from both the drivers and the passengers.

## Technical Specification

### Platform

- Our platform is built on blockchain technology using smart contract
- Backend: Python, Flask, SQL
- Frontend: React Native, TailWind
- Server: AWS (Amazon Web Service)
- Database: Google Spanner

### APIs / Third party services

- Tremble Maps API for geolocation and route optimization

- Google Maps API for traffic prediction and expected trip time calculation
- AI and Machine Learning models to optimize matching algorithm
  - Mixing types of AI searching algo including but not limited to DFS, BFS, IDS, to solve the traveling salesman problem
  - Inferential action: bayesian neural network. 
- Google Spanner

### Database

We use decentralized databases to ensure secure storage of user data. A decentralized database/ledger stores information across a network of distributed computers as opposed to on a single centralized server. We will be utilizing Google Spanner as the third party service provider. Riddy will benefit from its high availability with zero scheduled downtime and online schema changes, the strong capability to handle the million of concurrent requests, and its high-performance ACID (consistency, atomicity, isolation, and durability) transactions with strong consistency over regions and continents. 

### Service Hosting

- AWS Elastic Container Service (ECS) will be used to manage the deployment, scaling, and operations of Docker containers.
- AWS Lambda will be used for serverless computing and handle events such as user registration and carpool matching in real-time.
- Amazon S3 will be used to store user data, such as schedules and ride information, in a highly available and scalable object storage service.
- Amazon CloudFront will be used to distribute the app globally and ensuring fast and secure delivery of content to users.

AWS provides a range of services that can be used to automatically scale the app based on traffic demand, ensuring that the app can handle large numbers of users without interruption. 

### Security

- We use decentralized technology and smart contract to ensure secure, transparent and tamper-proof transactions on the platform.

### Environmentally friendly

- Our platform tracks and shows the carbon emissions saved by using carpooling in real-time.
- Encourages the use of green energy vehicles and offer incentives for drivers using such vehicles through our platform

### Mobile Application

- The mobile application will be built with React Native and will be available for download on App Store and Google Play Store.
- Our mobile application allows for real-time matching and posting of schedule ahead of time

### Future Plans

- We plan to continue to improve our matching algorithm and incorporate more advanced features such as carpooling for specific events and flexible scheduling for part-time or shift workers.
- To explore more partnership with environmental/sustainability organization and expand our service in more cities and regions.


## Requirements

In order to run the Riddy carpooling matching system, you will need the following:

- Tremble Maps API
- Google Maps API keys
- A blockchain platform such as Ethereum for smart contract deployment


## Technical Flow Chart
![riddy-flow](https://user-images.githubusercontent.com/36619969/212412311-a90d69e1-baed-4589-8bd1-87734d9c60f3.jpeg)


## Acknowledgements

We would like to extend our gratitude to the following individuals and organizations for their support and contributions to the development of Riddy:

- Tremble Maps API and Google Maps API for providing the geolocation and traffic prediction services.
- Our beta testers for providing valuable feedback and helping to improve the platform.
- Our advisors for their guidance and expertise.
- Our partners for their support in promoting sustainability and reducing the environmental impact of transportation.
- We would also like to thank the open-source community for the technologies that we have used to build Riddy.

Thank you for your interest in Riddy. We look forward to continuing to improve and expand the platform.
