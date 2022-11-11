## Data Engineering Test - Raízen Analytics

# Installation 

Table of Contents
-----------------
  * [Requirements](#requirements)
  * [Installation](#installation)


Requirements
------------

Tools requires the following to run:

  * Docker
  * [docker-compose](docker-compose)

Installation
------------

Clone this repository and go to directory.

git clone https://github.com/rwurdig/Data-Engineering-Test-Raizen-Analytics.git

Initialize the Database.

* Airflow deploy

docker-compose up airflow-init
docker-compose up -d

After returning this message:

airflow-init_1       | Upgrades done
airflow-init_1       | Admin user airflow created
airflow-init_1       | 2.3.4
start_airflow-init_1 exited with code 0

Your envoirment was successed building.

The account created has the login airflow and the password airflow.

Accessing the web interface
The webserver is available at: http://localhost:8080. The default account has the login airflow and the password airflow.

## Running already builded
docker-compose up

