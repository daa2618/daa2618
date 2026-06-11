# Hi, I'm Dev A
## Data Scientist | Machine Learning and Computer Vision | Sports Technology

Research Analyst and Developer specialised in transforming complex datasets into actionable intelligence. My work sits at the intersection of **Machine Learning**, **Computer Vision**, and **Data Engineering**, with a focus on building end-to-end pipelines from research prototypes to scalable systems.

---

### Featured Project: [BrandSpotter](https://github.com/daa2618/brandspotter)

A three-stage logo detection and identification pipeline that knows when it does not know. New brands appear constantly in real-world footage, so instead of forcing every crop into the closest known class, BrandSpotter rejects logos it has never seen.

**Detection** (YOLO11m) locates logo regions, **classification** (ResNet50) identifies the brand, and an **open-set rejection** stage (entropy/energy scoring) flags unknown brands rather than mislabelling them. All models trained from scratch on [LogoDet-3K](https://github.com/Wangjing1551/LogoDet-3K-Dataset) (3,000 logo classes, 158,652 images).

```text
Image -> YOLO11 detection -> ResNet50 classification -> open-set rejection -> known brand | "unknown"
```

| Stage | Model | Headline metric |
|-------|-------|-----------------|
| Detection | YOLO11m | mAP@0.5 = 0.894, mAP@0.5:0.95 = 0.639 |
| Classification | ResNet50 | Top-1 = 0.889, Top-5 = 0.966, Macro F1 = 0.895 (35 brands) |
| Open-set rejection | Entropy scoring | AUROC = 0.897 vs 15 brands never seen in training |

Reproducible local-prep plus Colab (T4) training workflow, leakage-safe train/val/test splits, published weights on [HuggingFace](https://huggingface.co/vectorized-dev/brandspotter), full evaluation notebooks, and a documented account of the v1 open-set operating-point trade-offs rather than cherry-picked numbers.

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
* **Technical Leadership:** Authored 20+ internal guides and tutorials on LLMs, Deep Learning, Cluster Analysis, and ML workflows to support team capability building.

---

### Open Source Projects

* **[BrandSpotter](https://github.com/daa2618/brandspotter):** Three-stage YOLO11 + ResNet50 + open-set rejection pipeline for logo detection with built-in unknown-brand rejection, trained from scratch on LogoDet-3K.
* **[UK House Price Index](https://github.com/daa2618/uk_house_price_index.git):** Self-serving Python dashboard to visualise UK house price index by geography and time period.
* **[Datapopy](https://github.com/daa2618/datapopy):** Python API wrapper for streamlined data extraction from data.police.uk.
* **[London Data Store](https://github.com/daa2618/london_data_store):** Module to search, filter, and extract data from the London Data Store.
* **[sodakit](https://github.com/daa2618/sodakit/):** Enhanced Python client for the Socrata Open Data API.

---

### Connect

- [LinkedIn](https://www.linkedin.com/in/dev-anand-anbarasu)
- [Portfolio Website](https://daa2618.github.io)

*Currently focused on productionising ML pipelines for sports technology and expanding open-source contributions in computer vision.*
