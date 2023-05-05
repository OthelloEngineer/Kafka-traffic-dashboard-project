# Kafka-traffic-dashboard-project
A project created in order to improve my personal skills on Event-Driven-Architecture, Kafka and logs/observability of traffic along with visualization

# Objectives
- To get practical experience with Kafka-streams and Kafka-Connector
- To improve my understanding of EDA (Event Driven Architecture)
- To leverage my knowledge gained from reading ["Effective Kafka by Emil Kartov"](https://www.amazon.com/Effective-Kafka-Hands-Event-Driven-Applications/dp/B0863R7MKG)
- To increase my experience with logging and metrics tools along with state of the art visualisation with Grafana
- To improve my workflow with continuous documentating and research. 
- To increase my knowledge of benchmarking and testing tools with synthetic traffic data platforms. 

# Functionality

As this is a project that is planned, as of writing this, to only run locally via kubernetes the testing and usage of this will excusively consist of manual entries of the user and synthetic traffic from custom developed scripts. 

The functionality consists of three major parts.
1. A web interface that will make use of REST-endpoints to the cluster
2. A backend designed with EDA with Kafka as the Event Store. 
3. A dashboard with visualisations of the current and previous states of the application.

