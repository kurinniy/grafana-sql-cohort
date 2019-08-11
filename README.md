# Grafana MySQL cohort analysis demo

This docker image allows you to play around with cohort analysis in Grafana using MySQL.

It shows user retention of imaginary website split by months. 

<img align="center" alt="Users retention graph" width="680" height="239" src="https://github.com/kurinniy/grafana-sql-cohort/blob/master/img/users-retention.png" />

And amount of money spent split by month users register.

[[https://github.com/kurinniy/grafana-sql-cohort/blob/master/img/users-turnover.png|Users turnover]]

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