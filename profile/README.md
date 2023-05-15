## Inspiration
Our project aims to tackle a modern day problem in a data-driven economy. The data centers that exist all over the world are power hungry energy farms, and our project is 
an attempt to address this issue by promoting sustainable practices. By utilizing old laptops and idle systems, we are able to repurpose resources that would otherwise go to waste, and create a distributed database system that is both eco-friendly and cost-effective. In fact, our project would be just 873 WattHours/GB as compared to 5000WattHours/GB consumed by an average Data Center.

## What it does and How we built it.
Introducing a revolutionary new solution to the problem of energy consumption in data centers: our system utilizes the unused computing power of existing consumer laptops to create a sustainable and energy-efficient distributed data storage network. By distributing data to these already-existing devices, we eliminate the need for expensive and energy-intensive data centers, reducing the carbon footprint of data storage and promoting sustainability.

Our system operates through a server that maintains a network of active hosts, which are consumer laptops that have opted in to participate in the network. The server maintains two tables: a table of active hosts and a two-layered data pointer table that maps client IDs to data filenames and the corresponding host IDs. This ensures efficient data storage and retrieval.

Clients connect to the network through a web socket and can store and retrieve data in a secure and reliable manner. All data is encrypted and compressed on the client side and error handling is built in to ensure a smooth and reliable user experience.

By utilizing existing consumer laptops that would otherwise sit idle, our system promotes sustainability by repurposing otherwise wasted energy. Additionally, our system eliminates the need for costly and energy-intensive data centers, further reducing the carbon footprint of data storage. Join us in revolutionizing the way we store and access data while promoting a sustainable future.

## What's next for DeeBee
Making DeeBee was super exciting and we plan to continue its development. Some things we will build on:
* Improved security and compression
* Using machine learning to implement a better load balancing
* Solving availability issues and edge cases of drop of client or servers
* Scaling up the server with Kubernetes clusters and reliability of the server
