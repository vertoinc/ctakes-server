# Veritas NLP
NLP Engine powered by Apache CTakes and UMLS Terminology Services.

## Docker Installation
1. Clone this repository
```
https://github.com/vertoinc/veritas-nlp.git
```
2. Create an `.env` file with the following information
```
HOST=0.0.0.0
PORT=9999
UMLSUSER=<YOUR UMLS USERNAME>
UMLSPW=<YOUR UMLS PASSWORD>
```
3. Run docker compose on daemon mode
```
$ docker-compose up -d
```
4. Send POST messages to this endpoint
```
http://localhost:5000/ctakes
```
