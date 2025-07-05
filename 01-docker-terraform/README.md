# 01 - Docker and Terraform (My Learning Notes)

This is a summary of what I learned in the first week of the **Data Engineering Zoomcamp**. The focus was on setting up a local data environment using **Docker** and **PostgreSQL**, and working with the **NYC Yellow Taxi dataset**.

---

## ?? What I Set Out to Learn

- How to run a PostgreSQL database locally using Docker
- How to use `pgcli` to interact with the database in the terminal
- How to explore and understand the NYC Yellow Taxi dataset
- How to ingest raw CSV data into a PostgreSQL table

---

## ?? Tools I Installed

Before I could get started, I made sure the following were installed on my machine:

- **Docker**: for running PostgreSQL in a container  
  [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

- **pgcli**: a terminal-based database client with autocomplete  
  Installed using:
  ```bash
  pip install pgcli
