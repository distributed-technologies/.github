# Distributed Technologies
Distributed Technologies is a team working for Energinet, the sole Danish TSO. As a team under the Innovation and Digitalization department, we innovate and experiment with new technologies, as well as develop tools and platforms that will help transition Denmark to sustainable energy. We are called Distributed Technologies because we develop distributed systems that are robust, highly available and have the workload distributed across multiple systems or nodes. This is important to the Danish energy sector, because uptime is a very important metric in developing these systems, and the distribution of both workloads as well as data, makes the system more robust. 

This Github organization was created to have a common place for our repositories that are developed open source and we welcome anyone to contribute or give feedback to our code. Since we are a team that works with many different technologies and works in different problem domains, we have created a [wiki](https://github.com/distributed-technologies/wiki) where you can get a full overview of the project we are working on, as well as find information about our development methods. 

## License
We publish all our code under the Apache 2.0 license. We use many different open source projects in this organization and we do not overrule their respective licenses. 

## Projects

#### Secure compute and communications platform (SCCP)
One of the projects we are developing is called SCCP, which is a highly available, fast, secure, robust platform which will run future applications for the energy grid in Denmark. We are developing this platform to enable other teams at Energinet to create algorithms that can run on the platform and in the future make decisions for the danish power grid. One instance of the platform that is being built at the moment is called the real-time platform (RTP). This platform runs Kafka and will be able to provide data from certain systems to algorithms if they request it and then generate an output. 

If you are visiting this page to try out this platform and develop applications for it, please visit the [Yggdrasil repository](https://github.com/distributed-technologies/yggdrasil) for instructions on how to deploy our platform to Azure in a simple and fast way. 

#### Filemover
The filemover is a project that is currently being developed because the current filemover at Energinet will reach its EOL soon. Currently, a PoC is being developed, which you can find at [here](https://github.com/distributed-technologies/filemover-poc).
