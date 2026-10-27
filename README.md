# Abeer Miglani

**I build backend services.**

ECE undergrad at Shiv Nadar University. I build backend services: most recently Ripple, an async simulation API with FastAPI, Celery, PostgreSQL and Redis. I'm learning Go, and I wrote a Redis-style TCP server in C++ to understand what sits under the API.

Open to SWE internships · [portfolio.abbykayo.com](https://portfolio.abbykayo.com) · [Résumé](https://portfolio.abbykayo.com/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/abeermiglani/) · [am319@snu.edu.in](mailto:am319@snu.edu.in)

```console
$ curl https://portfolio.abbykayo.com/api/profile.json
{
  "name": "Abeer Miglani",
  "role": "Backend engineer",
  "status": "Open to SWE internships",
  "learning": ["Go"],
  …
}
```

## Projects

**[ripple](https://github.com/AbeerMiglani/ripple)**: Manipal Hackathon 2026, sole developer. `Python` `FastAPI` `Celery` `PostgreSQL` `Redis`<br>
A FastAPI service that simulates how one infrastructure failure cascades through a city's networks. Simulations run as Celery jobs with retries, results stream over WebSockets through Redis pub/sub, and the API has role-based keys, a Redis rate limiter and Redis caching. A Rust (PyO3) extension cut worst-case latency from 1.5 s to 190 ms.

**[redis-cpp](https://github.com/AbeerMiglani/redis-cpp)**: a Redis-style TCP server in C++, built from first principles. `C++` `POSIX sockets`<br>
Raw POSIX sockets, a length-prefixed binary protocol, and an event loop over non-blocking sockets so one thread serves many clients. Benchmarked at 25K requests per second over loopback.

## Stack

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go_(learning)-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

<sub>`curl https://portfolio.abbykayo.com` prints my résumé in your terminal; `/api` serves it as JSON.</sub>
