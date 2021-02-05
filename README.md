# Pudding (ELK)

Global Project Funding Service

## ✋Team Members

- [![title](https://img.shields.io/badge/DEVLOPER-최윤선-123456)](https://github.com/OMEGA-Y)
- [![title](https://img.shields.io/badge/DEVLOPER-이연정-123456)](https://github.com/YeonJeongLee00)
- [![title](https://img.shields.io/badge/DEVLOPER-유창헌-123456)](https://github.com/dbckdgjs369)
- [![title](https://img.shields.io/badge/DEVLOPER-노기진-123456)](https://github.com/nohgijin)

---

## 🧞Quick Start 

### 1. Clone & Install Packages

```bash

git clone https://github.com/siliconValleyTeamA/ELK.git
cd ELK

```

### 2. Add settings folder then add .env.db / .env.logstash in to settings

1) add .env.db in settings folder

```bash
.env.db
{
    MYSQL_ROOT_PASSWORD: Your MYSQL_ROOT_PASSWORD,
    MYSQL_DATABASE: Your MYSQL_DATABASE Name
}
```
2) add .env.logstash in settings folder

```bash
.env.logstash
{
    DB_HOST= Your DB_HOST
    DB_PORT= Your DB_PORT
    DB_DATABASE= Your DB_DATABASE
    DB_PASSWORD= YOUR PASSWORD
    DB_USERNAME= YOUR DB_USERNAME
}
```

### 3. Run ELK

1) docker-compose build
![ELK-build](https://user-images.githubusercontent.com/67114268/106853443-0e715700-66fd-11eb-8c19-85511050f3bc.gif)

2) docker-compose up
![ELK-up](https://user-images.githubusercontent.com/67114268/106853345-e681f380-66fc-11eb-9c33-dccc2457b849.gif)

---
## Kibana Example
![Kibana](https://user-images.githubusercontent.com/67114268/106853290-d10cc980-66fc-11eb-8222-82decc5099e5.gif)

