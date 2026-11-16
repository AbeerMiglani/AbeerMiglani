# Abeer Miglani

**I write systems software in C++.**

ECE undergrad at Shiv Nadar University. Right now I'm building a Redis-style server from scratch in C++; before that, Ripple, a simulator for how failures cascade through a city's infrastructure.

Open to SWE internships · [portfolio.abeermiglani.com](https://portfolio.abeermiglani.com) · [Résumé](https://portfolio.abeermiglani.com/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/abeermiglani/) · [am319@snu.edu.in](mailto:am319@snu.edu.in)

```console
$ now
building  Redis-style server in C++ (5/10 milestones)
learning  Rust
```

## Projects

**[redis-cpp](https://github.com/AbeerMiglani/redis-cpp)**: a Redis-style server in C++, built from first principles. `C++` `POSIX sockets`<br>
TCP server and client on raw POSIX sockets, a length-prefixed binary protocol to frame messages over the byte stream, `read_full`/`write_all` loops so partial reads never corrupt a request, and an event loop over non-blocking sockets so one thread serves many clients. Benchmarked at 25K requests per second (38 µs median, 82 µs p99 over 100K loopback round trips). Next up: the key-value store.

**[ripple](https://github.com/AbeerMiglani/ripple)**: Manipal Hackathon 2026, sole developer. `Rust` `Python` `WebSockets`<br>
Simulates how one infrastructure failure cascades through a city's power, water, transit and telecom networks. A Rust (PyO3) extension handles the all-pairs shortest-path hotspot, and the cascade streams to the map wave by wave over WebSockets.

## Stack

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/Rust_(learning)-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)<br>
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<sub>`curl https://portfolio.abbykayo.com` prints my résumé in your terminal.</sub>
