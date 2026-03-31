# Herlangga Yusuf Syailendra
Backend / Data / Infrastructure Engineer

Builds scalable backend systems, data pipelines, and cloud infrastructure with focus on performance, reliability, and cost efficiency.

---

## Experience Highlights

- Reduced system latency from ~4s to **<100ms** through backend and infrastructure optimization  
- Lowered cloud cost by **~40%** via architecture and query improvements  
- Built monitoring system (Grafana + BigQuery) with **5x faster anomaly detection**  

---

## Systems

### Email Pipeline
AWS SES → SNS → Service → ClickHouse  
- Processed **500K+ events** (delivery, bounce, engagement)  
- Handled **50K+ emails** with strong deliverability (SPF, DKIM, DMARC)  
- Idempotent, retry-safe ingestion design
  <div align="center">
    <img width="1878" height="936" alt="image" src="https://github.com/user-attachments/assets/05357ec0-1ec6-4adc-b01d-e8acb1d457fc" />
    <p> Monitoring Email from SES Dumped to Clickhouse, We Can See Who Open And Click at Low Cost, and making it an good method to create and estabilish leads</p>
  </div>


### Data Platform
- Migrated Athena → BigQuery for better performance and cost control  
- Built OLAP pipelines for analytics  
- OLAP → OLTP sync for dashboards and services


### Observability
Cloud Run + BigQuery + Grafana  
- Centralized logging and monitoring
  <div align="center">
    <img width="1881" height="941" alt="image" src="https://github.com/user-attachments/assets/a760c7c5-894c-47b0-bd7f-46942343d435" />
    <p>Website Latency and Load Monitoring Dumped fron Cloudrun -> Log Router -> BigQuery -> Grafana -> Alert -> Discord </p>
  </div>
  <div align="center">
    <img width="1884" height="944" alt="image" src="https://github.com/user-attachments/assets/2d022086-0dcf-4d1d-a044-7f338d8e7c43" />
    <p>Website Uptime Monitoring using Uptime Kuma -> Discord </p>
  </div>
- Query-driven metrics for services

  Documentation Of Basic Infrastructure

  Dashboard Example:
  <div align="center">
    <img width="1868" alt="image" src="https://github.com/user-attachments/assets/7a2464dd-0b41-469e-bdd0-2b77f071566d" />
    <p>Analyzing Token Usage From <b>"AWS Bedrock Wrapper to OpenAI Compatible"</b> Project and Monitor it's Cost</p>
  </div>
  
### Other Systems
- API gateway for AI services (OpenAI / Ollama → Bedrock)
  
  Result : [AWS Bedrock Wrapper to OpenAI Compatible](https://github.com/herlangga72/AWS-Bedrock-Wrapper-to-OpenAI-Compatible)
  
  Technology Used:
   - Rust
   - Clickhouse
   - SQlite 
- Distributed Blender rendering (multi-node)
- n8n Automation for Email Processing
  <div align="center">
    <img width="1878" height="930" alt="image" src="https://github.com/user-attachments/assets/a74e5020-2157-4d2e-9368-dd5feb9a1eb1" />
    <p>n8n That triggered from email -> Listmonk -> Discord -> Review -> Send   </p>
  </div>

---

## Tech Stack

**Backend:** Python, Node.js, Rust, Go  
**Data:** ClickHouse, BigQuery, Athena  
**Infra:** NGINX, Linux, Docker  
**Cloud:** AWS, GCP  
**Monitoring:** Grafana  

---

## Links

- GitHub: https://github.com/herlangga72  
- LinkedIn: https://linkedin.com/in/herlangga72  
- Email: herlangga72@gmail.com  
