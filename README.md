<div align="center">
  
![Banner](prince-banner.svg)

### `Backend Engineer` · `ML Systems` · `Distributed Systems`

*Building production backends and ML systems that ship.*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00D9FF&center=true&vCenter=true&width=520&lines=Spring+Boot+microservices+with+AWS;ML+pipelines+from+training+to+serving;Redis+%C2%B7+RabbitMQ+%C2%B7+PostgreSQL;Student+%40+RIT+Bengaluru)](https://git.io/typing-svg)

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/princekhatri1013)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:princekhatri1013@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Prince-Khatri)
![Location](https://img.shields.io/badge/📍_Bengaluru,_India-grey?style=flat-square)

</div>

---

> Information Science Engineering student at **Ramaiah Institute of Technology, Bengaluru** — focused on scalable backend systems and applied machine learning.

I work on systems where correctness and structure matter: service boundaries, data flow, and models that are trained, tracked, and served — not just notebook demos.

- **Currently:** Designing Spring Boot microservices and end-to-end ML pipelines
- **Focus:** Distributed backends, event-driven design, and ML model serving

---

## Featured Projects

### [`SeatNova`](https://github.com/Prince-Khatri/SeatNova) — Movie Ticket Booking Platform
> Microservices booking system with distributed seat locking, async payments, and a secured API gateway.

- Seven Spring Boot services for movies, theatres, bookings, and payments — routed through Eureka and a centralized config server
- Seat holds enforced in Redis with Lua scripts to prevent double-booking under concurrency
- Booking and payment state kept in sync over RabbitMQ; Razorpay webhooks confirm payments asynchronously
- API Gateway validates JWTs from Keycloak (OAuth 2.0 + PKCE) before forwarding traffic
- Each domain service owns its own PostgreSQL schema

`Java` `Spring Boot` `Spring Cloud` `Eureka` `Redis` `RabbitMQ` `PostgreSQL` `Razorpay` `Keycloak`

---

### [`CafeOps`](https://github.com/mrsahiljaiswal/CafeOPS) — POS with Demand Forecasting
> Full-stack point-of-sale platform that predicts meal demand and keeps inventory aligned with real orders.

- Spring Boot REST API for orders, meals, inventory, and forecast endpoints; React + Vite frontend for POS and analytics
- Orders deduct ingredients from center inventory using recipe mappings and unit conversion
- Python ML service (LightGBM) forecasts demand; backend calls it over HTTP and surfaces model vs. actual metrics
- Training and prediction pipelines with preprocessing artifacts; experiment tracking via MLflow
- Docker Compose brings up PostgreSQL, backend, ML service, and frontend as one stack

`Java` `Spring Boot` `PostgreSQL` `React` `LightGBM` `Flask` `MLflow` `Docker`

---

### [`Cartora`](https://github.com/Prince-Khatri/Cartora-E-Commerce-Platform) — E-Commerce Product Backend
> Spring Boot product API with cloud object storage for catalog images.

- REST endpoints for product create, update, delete, and listing with JPA persistence
- Product images uploaded and removed through AWS S3 (AWS SDK v2)
- Multipart image handling wired into the product lifecycle so catalog media stays consistent with DB state

`Java` `Spring Boot` `Spring Data JPA` `AWS S3` `REST APIs`

---

### [`Next Word Predictor`](https://github.com/Prince-Khatri/Next-Word-Predictor) — LSTM Language Model
> End-to-end next-word prediction: train an LSTM, track runs in MLflow, serve suggestions over a Flask API.

- Modular pipeline for ingestion, tokenization, training, and inference — config-driven via YAML
- LSTM with embedding and dropout, trained with early stopping; experiments logged in MLflow
- Flask service returns next-token predictions for a notepad-style UI (Space for hint, Tab to accept)
- Top-k sampling at inference for controlled, non-greedy completions

`Python` `TensorFlow` `Keras` `LSTM` `MLflow` `Flask` `NumPy`

---

## Tech Stack
<div align="center">

| Domain | Technologies |
|--------|-------------|
| **Languages** | Java · Python · SQL · C++ |
| **Backend** | Spring Boot · Spring Cloud · REST APIs · Flask |
| **Data & Messaging** | PostgreSQL · Redis · RabbitMQ · H2 |
| **ML / AI** | TensorFlow · Keras · LightGBM · NumPy · Pandas · Scikit-Learn · MLflow |
| **Cloud & Infra** | AWS S3 · Docker · Eureka · Keycloak |
| **Frontend** | React · Vite |
| **Tools** | Git · Linux · Maven · Jupyter |

</div>


---
## 📊 GitHub Stats

<table align="center">
  <tr>
    <td align="center">
      <img
        src="./profile/top-langs.svg"
        width="400"
        alt="Top Languages"
      />
    </td>
    <td align="center">
      <img
        src="./profile/streak.svg"
        width="400"
        alt="GitHub Streak"
      />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img
        src="https://raw.githubusercontent.com/Prince-Khatri/Prince-Khatri/output/github-contribution-grid-snake-dark.svg"
        width="800"
        alt="GitHub Contribution Snake"
      />
    </td>
  </tr>
</table>

---


## What I'm Working Toward

```
[x] End-to-end ML pipeline (data → training → serving)
[ ] Harden distributed booking flows under real load
[ ] Deeper work on systems design and ML at scale
```

---

<div align="center">

*"The best way to understand an algorithm is to implement it yourself."*

**Open to internships, collaborations, and interesting problems.**

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/princekhatri1013)
[![Email](https://img.shields.io/badge/Drop_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:princekhatri1013@gmail.com)

</div>
