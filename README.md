<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Rahul%20Podugu&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Architecting%20Scale%20%7C%20Distributed%20Systems%20%7C%20Generative%20AI&descAlignY=55&descAlign=50&descSize=20&descColor=ffffff" alt="Rahul Podugu Banner" width="100%"/>
</div>

<div align="center">
  
  [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rahulpodugu/)
  [![Gmail Badge](https://img.shields.io/badge/-Email-c14438?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:rahulpodugu2@gmail.com)
  [![GitHub Badge](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/Rahul2251999)

  <br />

  <img src="https://img.shields.io/badge/Focus-Event_Driven_Architecture-0A0A0A?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-RAG_&_Vector_Search-0A0A0A?style=flat-square"/>
  <img src="https://img.shields.io/badge/Location-USA-0A66C2?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Open_to_Roles-2ea44f?style=flat-square"/>

</div> 

---

### ⚡ Engineering Snapshot
> *Performance-obsessed Backend Engineer specializing in high-throughput Java systems and AI integration.*

| **Metric** | **Impact** |
| :--- | :--- |
| **Scale** | Handled **100K+ daily transactions** with **99.9% uptime** via Spring Boot & AWS. |
| **Latency** | Cut service latency by **~40%** introducing **Kafka + Saga** choreography. |
| **AI Ops** | Automated **30%** of payment queries using **LangChain RAG** pipelines. |
| **Performance** | Achieved **p99 ≤150ms** for 50K+ users via Redis caching & SQL tuning. |

---

### 🛠️ The Arsenal

<table align="center">
  <tr>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" />
      <br>Java
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=spring" width="48" height="48" alt="Spring" />
      <br>Spring
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=kafka" width="48" height="48" alt="Kafka" />
      <br>Kafka
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" />
      <br>Redis
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="Postgres" />
      <br>PostgreSQL
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=aws" width="48" height="48" alt="AWS" />
      <br>AWS
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=kubernetes" width="48" height="48" alt="Kubernetes" />
      <br>K8s
    </td>
     <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
      <br>Python/AI
    </td>
  </tr>
</table>

<div align="center">
  <b>Libraries & Tools:</b> <br/>
  <code>LangChain</code> <code>FAISS</code> <code>Docker</code> <code>Grafana</code> <code>Jenkins</code> <code>Hibernate</code>
</div>

---

### 🧠 System Architecture & Philosophy

I don't just write code; I design resilient systems. Here is a high-level view of the **RAG & Event-Driven patterns** I implement:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ffcc00', 'edgeLabelBackground':'#ffffff', 'tertiaryColor': '#fff'}}}%%
graph LR
    subgraph "Event Driven Core"
    A[User Action] -->|API| B(Producer Svc)
    B -->|Async Event| C{Kafka Topic}
    C -->|Consumer Group| D[Inventory Svc]
    C -->|Consumer Group| E[Audit Svc]
    end

    subgraph "AI Layer"
    F[Query] -->|LangChain| G[Vector Search]
    G -->|Context| H[LLM Response]
    end
    
    style C fill:#f96,stroke:#333,stroke-width:2px
    style G fill:#61dafb,stroke:#333,stroke-width:2px
