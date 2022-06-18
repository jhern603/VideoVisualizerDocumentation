# Video Analytics and Heatmap
## Description
As part of my 2021 Summer internship at Oracle, I was tasked with creating an analytics tool and visualizer for our dynamic media delivery tool.
## Implementation
This project was implemented using FaaS cloud methodologies on [OCI](https://cloud.oracle.com/) using Java, PostgresDB for data storage, and other open source tools.
The first step in creating the project was creating useful data that our end-client can consume using raw video events (namely play and pause events) which was later transformed to generate views for the entire video and sections of the video. Once we enriched the data, it was necessary to breakdown the data into different levels relationally (each video can have multiple sessions, each session can have multiple events. There exists one session for each video.)
Once the data was relationally separated, and stored on different schemas in our DBMS, it was later visualized using Grafana.
## Lessons Learned
This project was my first time ever working in the cloud. This presented many challenges such as just understanding what the cloud truly is, how to set up an environment for the cloud, optimization for the cloud, and many other things.
This project allowed me to learn how to effectively communicate with not only my team, but with other teams about issues that I was faced while developing the project.
## Screenshots
[PENDING]
