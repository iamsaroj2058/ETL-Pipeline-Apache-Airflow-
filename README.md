# ETL-Pipeline-Apache-Airflow-
This is where i am learning  how ETL pipeline actually works ,What is  Astro?.,What is Airflow?.ETL Pipeline Implementation and Deploy ETL pipeline using Astro and Airflow



### APache Airflow
--> Airflow is a platform to programmatically author ,schedule and monitor workflows.

### Why use airflow?
- TO orchestrate(to design or organize something) the data pipeline/ETL Workflow
- Easily schedule,monitor,troubleshoot data pipelines
- Visually see the data pipelines
- Automate the ETL task

### Key features of Airflow
- Pure python based programming
- Useful Ui
- Easy to use 
- Open Source
- Robust Integrators,i.e. many built in plug and play operators that are ready to execute your tasks on GOogle cloud platform,Amazon web Services,Microsoft Azure,Databases and many other thirdparty services.



### CHallenges Handeled by Airflow

- Failures
- Monitoring
- Dependencies
- Scalability
- Deployment
- Process historic data


## Airflow Installation for Linux server

<!-- Airflow need a home,~/airflow is the default -->
1. export AIRFLOW_HOME = ~/AIRFLOW

<!-- iNSTALL USING PIP3 -->
2. pip3 install apache-airflow

<!-- start the web server ,default port is 8080 -->
3. airflow webserver -p 8080

<!-- start the scheduler -->
4. airflow scheduler


<!-- launch the airflow GUI admin screen in browser -http://localhost:8080 -->

## Airflow Install for Windows PC

- Prerequisites
* WSL Install  --> Microsoft Windows feature letting developers run a native GNU/Linux environment (like Ubuntu, Debian) directly on Windows, accessing Linux command-line tools (Bash, grep, sed) and applications without needing a separate VM or dual-boot setup, ideal for using Linux tools alongside Windows apps seamlessly.

- to install WSL . go to terminal and simply type *** wsl --install ***  then it automatically install the wsl

* Docker Desktop
