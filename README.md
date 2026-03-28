# Herlangga Yusuf Syailendra
**Software Engineer | Backend, Data & Infrastructure Specialist**

Focused on scalable backend systems, secure domain management, and cost-efficient cloud architectures.

---

### Technical Stack

* **Backend Engineering:**
  * Python (FastAPI, Django), Node.js (Express), Rust (Actix), Go.
  * Designed RESTful and gateway APIs (OpenAI/Ollama-compatible → AWS Bedrock).
  * Implemented high-performance services with focus on concurrency and low-latency responses.
  * Applied context optimization (compression, offloading) for LLM-based systems.
  * Built middleware for validation, feature gating, and request standardization.

* **Data Engineering (SatuData UMS):**
  * Developed data pipelines for institutional analytics and reporting.
  * Orchestrated workflows using Airflow and n8n (scheduled & event-driven).
  * Managed OLAP systems (ClickHouse, BigQuery, AWS Athena) for large-scale queries.
  * Synced OLAP → OLTP data for dashboarding and operational use (e.g., Grafana).

* **Databases:**
  * OLTP: PostgreSQL, MySQL  
  * OLAP: ClickHouse, BigQuery

* **Cloud & DevOps (SatuData UMS):**
  * Managed infrastructure on AWS & GCP with cost optimization strategies.
  * Designed API gateways and lightweight service layers for unified access.
  * Implemented logging, monitoring, and query optimization for high-load systems.

* **Infrastructure:**
  * NGINX (reverse proxy, load balancer, API gateway)
  * Linux (Ubuntu, Amazon Linux), Docker

* **Monitoring & Observability:**
  * Implemented Grafana dashboards connected to BigQuery for website analytics and monitoring.
  * Monitored services deployed on Google Cloud Run using query-based metrics.
  * Aggregated logs and usage data into BigQuery with cost-efficient query design.

* **Distributed Systems (Mailing Pipeline):**
  * Built event-driven email tracking system using **ListMonk → AWS SES → AWS SNS → Custom Service → ClickHouse**.
  * Processed delivery, bounce, complaint, and engagement events in near real-time.
  * Designed ingestion service for high-throughput event handling and normalization.
  * Stored and queried large-scale email analytics in ClickHouse for reporting and monitoring.
  * Ensured reliability with retry handling, idempotent processing, and queue-based architecture.

* **Distributed Rendering:**
  * Designed and managed Blender-based rendering farm for parallel job processing.
  * Implemented job distribution, queueing, and node coordination across multiple machines.
  * Optimized resource utilization (CPU/GPU scheduling) for batch rendering workloads.
  * Automated rendering pipelines and output aggregation.

* **Frontend (Basic):**
  * SvelteKit, TailwindCSS (internal tools & dashboards)

---

### System Management & Security

* **Domain Governance (Cloudflare):** DNS lifecycle, zone management, and environment-based routing.
* **Edge Security:** WAF, bot protection, rate limiting, Zero Trust enforcement.
* **Access Control:** Identity-based access (Cloudflare Access) for internal systems.
* **Traffic Management:** Load balancing, failover, and edge routing strategies.
* **SSL/TLS:** Automated certificate management and HTTPS enforcement.

---

### NGINX & Linux Administration

* **API Gateway & Reverse Proxy:** Centralized routing and upstream management for services.
* **Performance Optimization:** Worker tuning, connection scaling, and caching strategies.
* **Security Hardening:** HSTS, CSP, rate limiting, IP filtering.
* **Linux Operations:** systemd services, firewall (iptables/ufw), SSH hardening.
* **Observability & Automation:** Logging, monitoring, cron jobs, and bash scripting.

---

### Open Source & Projects

* **Teknum Blog** – Technical writing platform.  
* **Spectator** – Monitoring and tooling system.  
* **Mr-Packages** – Package discovery platform.  

---

### Contact

* **Email:** herlangga72@pakar-it.com  
* **LinkedIn:** linkedin.com/in/herlangga72  
