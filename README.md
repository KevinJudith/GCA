# GCA

Design a cloud architecture

## Potential options
- Compute Engine
- App Engine
- Cloud Run
- GKE

## More on GKE
- Container based
- Streamline development
- Scalable

## More on cloud run
- Managed service
- Does not support stateful application

## Google Cloud Architecture
Helps safe time and get started quickly
https://cloud.google.com/architecture


### Lexicon
Stateful application: In stateful applications, the server keeps track of the state of each user session, and maintains information about the user's interactions and past requests

Preemptible VM/machines/instances: Preemptible instances are VM instances that can be created at a much lower price than a regular instance. The only difference is that the compute engine can terminate these instances if those resources need to be reclaimed for other tasks. Preemptible instances also have a 24-hour limit after which they are terminated.

## Notes
Custom instances are a good way to optimize cost because you don't have to pay for the resources you don't use.

Bigtable is ideal for IoT, gives consistently sub-10ms latency, and can be used at a petabyte scale.

Dataflow is a fully managed service that can be used to process both streams and batches of data. Nearline is a good fit because the data could be accessed every month.

KPI needs to be bound in time.

BigQuery is Google Cloud's serverless data warehousing tool, which is
not used for processing real-time data.

Compute Engine provides virtual machines similar to your on-premises environment, making the transition smoother.

GKE is ideal for containerized applications and provides autoscaling.

URL map is a set of rules for routing incoming HTTP(S) requests to specific backend services

## Keywords
`VPC`, `Container`, `VM`, `Instance`, `Zone`, `Region`, `Subnet`, `Scalability`, `Shield VM`, `Parallel Deployment`, `IAC`, `IAM`, `Cloud Deployment Manager`, `Compute Engine`, `Cloud Run`, `GKE`, `Cluster`, `Load Balancer`, `URL Map`, `Pod`, `Node`, `kubectl autoscale`