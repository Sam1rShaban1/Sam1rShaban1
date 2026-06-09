<!-- Hero Section -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=00bf8f,001510&height=280&section=header&text=Samir%20Shabani" width="100%"/>
</div>

<div align="center">
  
  <!-- Typing Animation -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=24&duration=3500&pause=1000&color=20C20E&center=true&vCenter=true&width=435&lines=Researcher+%26+Full+Stack+Engineer;Building+Intelligent+Edge+Systems;GPU-Accelerated+Digital+Twins;Training+Vision+Transformers" alt="Typing animation"/>
  </a>

  <!-- Social Badges -->
  <p>
    <a href="https://linkedin.com/in/samir-shabani">
      <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
    <a href="https://www.kaggle.com/samirshabani">
      <img src="https://img.shields.io/badge/View_Kaggle_Profile-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/>
    </a>
    <a href="https://huggingface.co/SamirShabani">
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white"/>
    </a>
    <a href="mailto:shabani.samir12@gmail.com">
      <img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
    </a>
  </p>
</div>

---

### The Developer Journey

Hi, I'm **Samir**. Based in **North Macedonia**, I am a Computer Science graduate from **SEEU** and a **Researcher & Full Stack Engineer** at the Max van Der Stoel Institute.

My journey started in **hardware design** (working as a CAD Designer & CNC Programmer), giving me a unique perspective on the physical world. Today, I combine that engineering mindset with **Deep Learning, Edge AI, and Cloud-Native Systems** to build intelligent solutions that run on constrained devices.

I don't just train models; I deploy them to the **Edge**. My work focuses on creating **Hybrid AI Systems** that run on GPUs, Raspberry Pis, and ESP32s to monitor air quality, optimize RF networks, and enable real-time inference at scale.

**🏆 Recent Achievements:**
- **ICAMES 2026** - Most Applicable Project Award (Boğaziçi University)
- **Williams & May Global Innovation Challenge** - Selected Finalist
- **GPU-Accelerated Digital Twin** - 50x+ speedup in RF planning simulations
- **Cloud-Native IoT Pipeline** - Full observability stack with K3s, ArgoCD, EMQX

---

### Technical Proficiency

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="30%">
        <b>Artificial Intelligence</b><br><br>
        <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn,opencv&perline=4" />
        <br><br>
        <i>Focus: Deep Learning, Federated Learning, Time-Series Forecasting, Vision Transformers.</i>
      </td>
      <td align="center" width="30%">
        <b>IoT & Hardware</b><br><br>
        <img src="https://skillicons.dev/icons?i=raspberrypi,arduino,cpp,linux&perline=4" />
        <br><br>
        <i>Focus: LoRaWAN, ESP32, Raspberry Pi, GPU Computing (CUDA/CuPy).</i>
      </td>
      <td align="center" width="30%">
        <b>Cloud & Tools</b><br><br>
        <img src="https://skillicons.dev/icons?i=gcp,docker,git,bash&perline=4" />
        <br><br>
        <i>Focus: Kubernetes (K3s), ArgoCD, NATS, VictoriaMetrics, GitOps.</i>
      </td>
    </tr>
  </table>
</div>

---

### Featured Research & Implementations

<details>
<summary><b>1. GPU-Accelerated Digital Twin & RF Planning (Click to Expand)</b></summary>
<br>
<blockquote>
  High-fidelity digital twin for 5G network optimization with GPU-accelerated simulations.
</blockquote>

*   **The Challenge:** RF planning simulations require millions of path loss calculations; traditional CPU approaches are too slow.
*   **The Solution:** I constructed a **Digital Twin of Tetovo** using satellite data (DSM/DTM) and building footprints.
    *   **GPU Acceleration:** Offloaded 10⁸ path loss calculations to NVIDIA P100 using **CuPy**.
    *   **Optimization:** Implemented parallel Monte Carlo simulations with **NSGA-II genetic algorithm**.
    *   **Result:** 50x+ speedup vs. CPU baseline.
*   **Tech Stack:** `Python` `CuPy` `NVIDIA CUDA` `NSGA-II` `Monte Carlo` `Pycraf`
</details>

<details>
<summary><b>2. Bio-Inspired Spatiotemporal Forecasting (Click to Expand)</b></summary>
<br>
<blockquote>
  Hybrid WOA-CNN-BiLSTM-AM model for hyper-local PM2.5 air quality forecasting.
</blockquote>

*   **The Challenge:** Predicting localized air pollution with general models fails due to spatial/temporal complexity.
*   **The Solution:** Designed a **hybrid WOA-CNN-BiLSTM-AM model**.
    *   **WOA:** Whale Optimization Algorithm for automated hyperparameter tuning.
    *   **CNN:** Extracts spatial features from sensor grids.
    *   **BiLSTM:** Captures temporal dependencies in time-series data.
    *   **Attention Mechanism:** Focuses on important features for better predictions.
    *   **Performance:** Superior convergence & accuracy vs. standard GRU/LSTM architectures.
*   **Tech Stack:** `TensorFlow` `Python` `Federated Learning` `Matplotlib`
</details>

<details>
<summary><b>3. Cloud-Native IoT Edge Cluster (Click to Expand)</b></summary>
<br>
<blockquote>
  Production-grade edge computing infrastructure with full observability and GitOps workflows.
</blockquote>

*   **Architecture:** Bare-metal **Kubernetes (K3s)** cluster managed via pure **GitOps** with ArgoCD.
*   **Streaming Pipeline:** 
    *   **EMQX** for MQTT message brokering.
    *   **NATS JetStream** for event streaming and persistence.
    *   **VictoriaMetrics** for time-series metrics collection.
*   **Observability:** Full stack with **Prometheus**, **Loki**, **Tempo** for distributed tracing.
*   **Features:** Auto-scaling, zero-downtime deployments, comprehensive monitoring.
*   **Tech Stack:** `K3s` `Ansible` `ArgoCD` `NATS` `EMQX` `VictoriaMetrics` `Prometheus` `Loki` `Tempo`
</details>

<details>
<summary><b>4. Long-Range IoT Edge Network (Click to Expand)</b></summary>
<br>
<blockquote>
  Distributed LoRaWAN network for collecting environmental data off-grid and validating air quality models.
</blockquote>

*   **Hardware:** Arduino Nano 33 BLE (Sensing) + LilyGO T-Beam (Transmission).
*   **Logic:** The Nano collects Temperature/Humidity/Pressure and sends it via BLE to the T-Beam, which transmits data kilometers away using **LoRa** technology.
*   **Applications:** Air quality monitoring, environmental sensing, real-time data collection.
*   **Optimization:** Implemented deep sleep cycles to run on battery power for extended periods.
*   **Tech Stack:** `C++` `Arduino IDE` `LoRa` `Meshtastic` `Python`
</details>

---

### GitHub Analytics

<div align="center">
  <br>
  <!-- Dynamic Contribution Graph (Snake) -->
  <br><br>
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</div>

---

### 🎓 Education & Certifications

**Bachelor of Science in Computer Science**  
South East European University (SEEU) | Tetovo, North Macedonia  
GPA: 8.9/10.0 | Oct 2022 – Present (Graduating 2026)

**Certifications:**
- Oracle Cloud Infrastructure GenAI Professional
- Unity Certified Programmer
- IBM Linux Shell Scripting

---

### 💼 Current Role

**Researcher & Full Stack Engineer (Part-time)**  
Max van Der Stoel Institute, SEEU | Feb 2026 – Present

- Architecting scalable multi-tenant platform supporting 90,000+ users
- Engineered core backend using Django 5.x & DRF with SAML2 authentication
- Designed async architecture with Celery + Redis for background processing
- Established security framework with Pytest, rate-limiting, and RBAC

---

### 🚀 Let's Connect

I'm always interested in collaborating on innovative projects, discussing new technologies, and contributing to open-source. Feel free to reach out!

- 💼 Open to research collaborations and full-time opportunities
- 🔬 Interested in: AI/ML, IoT, GPU Computing, Distributed Systems, Edge AI
- 📧 Contact me through LinkedIn or email