# CLIMR-microservices

Microservices used for adminstration of the [Construal Level International Multilab Replication Project (CLIMR)](https://climr.org/)

CLIMR uses a self-hosted instance of [Baserow](https://baserow.io). This project provides a number of microservices that
that integrates with baserow via webhooks.  


## Development

### System requirements
CLIMR-microservices uses [FastAPI](https://fastapi.tiangolo.com) and the code runs under python 3.10 or above

### Install and run the application

Clone this repository: 

<pre>git clone https://github.com/Segerberg/climr-microservices.git</pre>

Install requirements with pip:

<pre>pip install -r requirements/base.txt</pre>

Navigate to app folder

<pre>cd app</pre>

Start server:
<pre>uvicorn main:app --reload</pre>

## Run with Docker

TBD

