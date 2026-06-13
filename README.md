# Hi, I'm Dev A
## Data Scientist | Machine Learning and Computer Vision | Sports Technology

Research Analyst and Developer specialised in transforming complex datasets into actionable intelligence. My work sits at the intersection of **Machine Learning**, **Computer Vision**, and **Data Engineering**, with a focus on building end-to-end pipelines from research prototypes to scalable systems.

---

### Featured Project: [BirdSpotter — Open-Set Bird Species Recognition](https://birdspotter-demo-207832056402.europe-west2.run.app)

A bird-species classifier that knows when it does not know. Most classifiers force every image into their nearest known class, so show them a species they were never trained on and they confidently mislabel it. BirdSpotter adds an entropy-based open-set rejection stage that abstains, returning "unknown" instead of guessing wrong.

Trained from scratch on CUB-200-2011 (160 known species, with 40 held out entirely as unknown). A ResNet50 backbone with two-phase fine-tuning and calibration discipline, served via FastAPI + Gradio in Docker and deployed live on Google Cloud Run.

| Stage | Approach | Headline metric |
|-------|----------|-----------------|
| Classification | ResNet50 | Top-1 = 0.781, Top-5 = 0.954 (160 known species) |
| Open-set rejection | Entropy scoring | AUROC = 0.756 vs 40 held-out unknown species |

Built to release standard: leakage-safe train/val/test splits, its own test suite, and a published (not hidden) limitation, namely that fine-grained look-alike species are genuinely hard to reject. **[Try the live demo](https://birdspotter-demo-207832056402.europe-west2.run.app)** with a non-bird photo and watch it return "unknown".

---

### Technical Expertise

* **Machine Learning and Computer Vision:** YOLO11 / YOLOv8 Object Detection, PyTorch, ResNet50 Classification, Open-Set Recognition (entropy/energy rejection), Multi-stage Clustering (HDBSCAN), Cloud Vision API Benchmarking (AWS Rekognition, Azure, Google Vision).
* **Data Engineering:** Modular ETL Pipelines, REST API Aggregation (SERP, Alpha Vantage, Polygon.io), Async/Concurrent Processing, NAS Integration, Automated Data Updates.
* **Financial Data and Analysis:** Batch Backtesting Frameworks, Indicator Analysis (Tom DeMark), Market Cap Screeners, Portfolio Transaction Logs.
* **Tools:** Python, SQL, PowerBI, Google Colab, DGX (GPU Training), Jira, Confluence.

---

### Featured 2025 Professional Milestones

* **Global Brand Discovery Architecture:** Designed a multi-stage clustering and human-in-the-loop validation system for global brand identification across sports broadcasting.
* **Computer Vision Pipeline:** Built and benchmarked object detection pipelines using YOLOv8/v11 on DGX infrastructure, including SAM-assisted annotation workflows that reduced annotation time significantly.
* **Cloud Vision API Benchmarking:** Conducted systematic benchmarking between AWS Rekognition, Azure, Google Vision, and open-source solutions for production-ready brand detection.
* **Open-Set Computer Vision:** Built object detection and classification systems that recognise when an input falls outside the known label set, rejecting unseen classes rather than forcing an incorrect prediction.
* **Technical Leadership:** Authored 20+ internal guides and tutorials on LLMs, Deep Learning, Cluster Analysis, and ML workflows to support team capability building.

---

### Open Source Projects

* **[UK House Price Index](https://github.com/daa2618/uk_house_price_index.git):** Self-serving Python dashboard to visualise UK house price index by geography and time period.
* **[Datapopy](https://github.com/daa2618/datapopy):** Python API wrapper for streamlined data extraction from data.police.uk.
* **[London Data Store](https://github.com/daa2618/london_data_store):** Module to search, filter, and extract data from the London Data Store.
* **[sodakit](https://github.com/daa2618/sodakit/):** Enhanced Python client for the Socrata Open Data API.

---

### Connect

- [LinkedIn](https://www.linkedin.com/in/dev-anand-anbarasu)
- [Portfolio Website](https://daa2618.github.io)

*Currently focused on productionising ML pipelines for sports technology and expanding open-source contributions in computer vision.*
