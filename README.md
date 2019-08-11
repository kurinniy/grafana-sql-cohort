# Grafana MySQL cohort analysis demo

This is demo docker image allows you to play around with cohort analysis in Grafana.

It shows user retention of imaginary website split by months. 

[RETENTION GRAPH]

And amount of money spent split by month users register.

[TURNOVER GRAPH]

## Installation

To run this image you need Docker installed.

```bash
git clone https://github.com/kurinniy/grafana-sql-cohort.git
cd grafana-sql-cohort
docker-compose up --build
```

After installation complete, open Grafana in browser:

http://0.0.0.0:3000

**Login:** admin  
**Password:** secret

Enjoy!