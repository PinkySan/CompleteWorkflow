# Complete Workflow
Within this repository i want to create my own personal workflow/toolchain. 
This consists on the following parts
* Git-Server (e.g Gitlab or Github)
* Package-Server (e.g Atlassian C/C++ Package Manager)
* Build-Server (e.g Jenkins, Github Actions, Gitlab Pipeline)
* Software Quality server (e.g Codacy, Sonarcloud, Sonarcube)
* Password Manager (e.g OpenLDAP)

Further information might be in the wiki

## Constraints
Every part should be editable, on premise and free.
Furthermore the complete toolchain might be downloadable by docker.

## Goal
The complete workflow should be runable within 
* a single docker container or
* docker compose
* kubernetes cluster
At this point i am not sure which solution might be the best
