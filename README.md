# Video Analytics and Heatmap
## Description
As part of my 2021 Summer internship at Oracle, I was tasked with creating an analytics tool and visualizer for our dynamic media delivery tool.
## Implementation
This project was implemented using the [FaaS](https://www.cloudflare.com/learning/serverless/glossary/function-as-a-service-faas/#:~:text=Function%2Das%2Da%2DService%20(FaaS)%20is%20a,element%20in%20a%20web%20application.) cloud methodology on [OCI](https://cloud.oracle.com/) using [Java](https://www.java.com/en/), [PostgresDB](https://www.postgresql.org/) for data storage, and other open source tools.
The first step in creating the project was creating useful data that our end-client can consume using raw video events (namely play and pause events) which was later transformed to generate views for the entire video and sections of the video. Once we enriched the data, it was necessary to breakdown the data into different levels relationally (each video can have multiple sessions, each session can have multiple events. There exists one session for each video.)
Once the data was relationally separated, and stored on different schemas in our DBMS, it was later visualized using [Grafana](https://grafana.com/).
## Lessons Learned
This project was my first time ever working in the cloud. This presented many challenges such as just understanding what the cloud truly is, how to set up an environment for the cloud, [optimization for the cloud](https://www.cloudzero.com/blog/cloud-optimization#:~:text=Cloud%20optimization%20is%20the%20process,resources%20among%20different%20use%20cases.), among many other challenges.
This project allowed me to learn how to effectively communicate with not only my team, but with other teams about issues that I was faced while developing the project.
## Screenshots
[PENDING]
