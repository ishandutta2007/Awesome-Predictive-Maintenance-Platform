# Awesome-Predictive-Maintenance-Platform

## Top Predictive Maintenance Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Machine Health, Anomaly Detection, Failure Prediction, Sensor Analytics & Asset Reliability*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Predictive Maintenance (PdM)**. These systems use sensor data, machine learning, and domain knowledge to detect anomalies, predict failures, and optimize maintenance for industrial assets and fleets.



**Examples** include Augury, Nanoprecise, Senseye, Uptake, C3 AI Reliability, IBM Maximo Monitor, Fiix Foresight, SparkCognition, AssetWatch, and Infinite Uptime (the category leaders).



**Open-source emphasis**: Full commercial predictive maintenance platforms with proprietary sensors, domain models, and scale are dominant. Open options exist primarily as ML frameworks, anomaly detection libraries, edge IoT stacks, and experimental platforms. This section lists the strongest available open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Starting Tier Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Augury](https://www.augury.com/)** | AI-powered machine health & predictive maintenance platform combining continuous vibration/acoustic sensor data with expert analysis for process industries. | ~$50–$150/monitored machine/month (Hardware/installation quoted separately) | No free tier or trial (Demo & ROI calculator only) |
| **[Nanoprecise](https://www.nanoprecise.io/)** | Predictive maintenance solution focused on vibration, acoustic, and thermal sensor analytics for industrial assets. | Custom quote-based (Subscription per monitoring point/asset) | No free tier or trial (30-min expert demo available) |
| **[Senseye (Siemens)](https://www.siemens.com/)** | Siemens’ enterprise predictive maintenance platform using AI & industrial data to anticipate equipment failures. | Custom quote-based (Per-asset monthly subscription via Siemens sales) | No free tier or trial (Consultation & demo available) |
| **[Uptake](https://www.uptake.com/)** | Industrial AI and predictive analytics platform oriented toward heavy equipment & fleet health (rail, mining, construction). | ~$100,000/year platform licensing (Enterprise quote-based) | No free tier or trial (Guided demo available) |
| **[C3 AI Reliability](https://c3.ai/)** | Enterprise AI application for predictive maintenance and reliability within the C3 AI platform. | $0.55/vCPU-hour ($250k for 3-month pilot engagement) | No full platform free tier; 14-day trial for select cloud marketplace modules |
| **[IBM Maximo Monitor](https://www.ibm.com/products/maximo)** | Asset monitoring and anomaly detection application within the IBM Maximo Application Suite. | ~$40,000/year (IBM AppPoints subscription model) | No permanent free tier; time-limited demo/trial via IBM or AWS Marketplace |
| **[Fiix Foresight](https://fiixsoftware.com/)** | Predictive maintenance and AI insights within the Fiix CMMS/EAM platform (Rockwell Automation). | Free tier ($0) / Paid starting at $45/user/month (Basic plan) | Permanent Free plan limited to 3 users, 25 active PM tasks, and ~20 assets |
| **[SparkCognition](https://www.sparkcognition.com/)** | Enterprise AI platform offering predictive maintenance, asset analytics, and visual AI solutions. | Custom quote-based (Scales by deployment scope and fleet size) | No free tier or trial (Guided demo available) |
| **[AssetWatch](https://www.assetwatch.com/)** | End-to-end machine health monitoring platform with wireless sensors and expert advice. | $199 upfront trial fee; full service quote-based subscription | 30-day paid trial plan for $199 (Includes sensors & cloud access) |
| **[Infinite Uptime](https://www.infinite-uptime.com/)** | Industrial IoT & prescriptive maintenance solution for high-frequency vibration and acoustic monitoring. | Custom quote-based (Hardware sensors per unit + PlantOS subscription) | No free tier or trial (On-site demo & proof of concept available) |



## Open-Source GitHub Projects

- **[Experimental open predictive maintenance platforms](https://github.com/)**  

  Community and initiative projects aiming to provide sensor ingestion, anomaly detection, health scoring, and maintenance integration in an open stack.



- **[Anomaly detection and time-series open libraries](https://github.com/)**  

  Widely used open-source libraries (Isolation Forest, autoencoders, LSTM-based models, Prophet, etc.) applied to industrial sensor data for PdM.



- **[Industrial IoT and edge open platforms](https://github.com/)**  

  Open edge and IIoT frameworks that support sensor data collection, local inference, and integration with higher-level analytics.



- **[Machine learning for predictive maintenance notebooks and repos](https://github.com/)**  

  Research and educational projects demonstrating anomaly detection, remaining useful life (RUL) estimation, and failure prediction on public datasets.



- **[CMMS/EAM open systems with extension potential](https://github.com/)**  

  Open maintenance management tools (e.g., components of Odoo or other CMMS) that can be extended with predictive models.



- **[OPC-UA, MQTT, and industrial protocol open stacks](https://github.com/)**  

  Open connectivity components for ingesting data from PLCs, historians, and sensors into analytics pipelines.



- **[Health scoring and dashboard open prototypes](https://github.com/)**  

  Simple open tools for visualizing asset health, trends, and alerts.



- **[TinyML and edge inference open projects](https://github.com/)**  

  Frameworks for running lightweight anomaly detection models directly on edge devices.



- **[Public industrial datasets and benchmarks](https://github.com/)**  

  Open datasets and evaluation frameworks used to develop and compare predictive maintenance models.



- **[Integration and work-order open helpers](https://github.com/)**  

  Scripts and connectors that push predictive alerts into existing CMMS or notification systems.



### Additional Strong Open-Source Options

- Building custom PdM pipelines with open anomaly detection and time-series libraries on top of existing sensor/historian data.

- Using open IIoT and edge platforms for data collection and local inference.

- Extending open CMMS tools with ML models for smaller or less complex environments.

- Accepting that proprietary sensor hardware, large domain-specific model libraries, multi-site scale, and proven ROI in heavy industry still favor commercial platforms (Augury, Senseye, Uptake, C3 AI, etc.).

- Combining open analytics with commercial PdM or CMMS for hybrid deployments.



**Frameworks for building custom systems**: Ingest sensor data via open IIoT protocols → store time-series data → train or apply open anomaly detection / RUL models → generate health scores and alerts → integrate with CMMS for work orders. Suitable for organizations with data science capacity and existing instrumentation. Commercial platforms remain the practical choice for most industrial users who need rapid deployment, domain expertise, and managed sensor-to-insight solutions.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Predictive maintenance systems influence maintenance decisions that affect safety, uptime, and costs. Incorrect predictions or missed failures can have serious operational and safety consequences. Open-source or self-built solutions require rigorous validation, domain expertise, and ongoing model monitoring. This list is not engineering, safety, or operational advice.



---

**Made for reliability engineers, maintenance leaders, and industrial AI teams who want better asset health insights.**

Let's keep predictive maintenance data-driven, actionable, and as open as practical.
