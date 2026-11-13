<h1 align="center">Pedro Fernandes</h1>

<p align="center">
  <img src="https://img.shields.io/badge/DATA_ENGINEERING-0D1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PLATFORM_ENGINEERING-0D1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DATAOPS-0D1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DEVOPS-0D1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MLOPS-0D1117?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/APACHE_AIRFLOW-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/GEOSPATIAL_DATA-007C92?style=for-the-badge" />
</p>

<p align="center">
  I build and run the platforms that keep data, ML and geospatial workloads reliable in production, on-prem and in the cloud.
</p>

<p align="center">
  <a href="https://linkedin.com/in/pedrofernandespt">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About

I'm a **Data Engineer at [CEiiA](https://www.ceiia.com/)** (Portugal). I work across the whole path from raw data to product: **data engineering, architecture, DataOps, MLOps and DevOps**. I'm best at **turning prototypes into production systems**: pipelines that run unattended for years, services other teams build on, and engineering standards that let a data team scale without chaos.

**Platform engineering:** beyond pipelines, I'm the person who makes **Apache Airflow run successfully**, on-premises or in the cloud with **Astronomer**: deployed, configured, scalable and dependable enough that data and ML teams can simply build on top of it.

Before CEiiA, I built BI dashboards and data pipelines for retail and automotive clients (**Power BI, SQL Server, MongoDB**), gathering requirements directly from them, and worked on computer vision with **TensorFlow**.

I also contribute to the **STAC API ecosystem** and I'm an active member of the **Apache Airflow** community.

> 🔎 **Open to new opportunities** in data engineering and platform engineering (Airflow, DataOps, MLOps, geospatial platforms). Reach me on [LinkedIn](https://linkedin.com/in/pedrofernandespt).

## ⭐ Highlights

### 🛠️ Airflow platform (on-prem & cloud)
**Problem:** data and ML teams need a scalable, reliable orchestration platform they can build on without worrying about the infrastructure underneath.<br>
**What I built and run:** the on-premises Airflow platform, including service deployment and configuration on on-prem machines, containerised production packaging with **Docker**, automated **CI/CD** pipelines, and strategies for running high-volume ML workloads at scale. I can also run Airflow in the cloud with **Astronomer**.<br>
**Result:** the platform behind the team's daily production pipelines.

### 🚢 Real-time maritime data platform
**Problem:** vessel (AIS) data arrives continuously, with duplicates and a constant need for both "latest position" and full history.<br>
**What I built:** a Python ingestor running every 2 minutes that maintains separate *Current* and *Historical* tables and adds only new records (no duplicate positions or timestamps), exposed through a **FastAPI** REST service on PostgreSQL/PostGIS and MongoDB.<br>
**Result:** running at **>99% uptime since August 2021**.

### 🗺️ Vessel imaging dataset pipeline
**Problem:** building ML-ready vessel imagery requires fusing two very different sources at scale.<br>
**What I built:** a daily **Airflow** pipeline combining AIS data with **Sentinel-2** raster imagery to generate vessel imaging datasets, using Spark and multiprocessing for performance.<br>
**Result:** running daily in production for years. The work grew into an integrated solution combining vessel tracking with raster imagery for **ESA's PhiSat-2 mission**.

### 🏗️ Geospatial platform architecture
Architected on-premises and cloud geospatial platforms from integrated components (**STAC, GeoServer, THREDDS, object storage, PostGIS**), working across GeoTIFF, NetCDF, COG and GPKG, and turning prototypes into production-ready, containerised systems.

### ⚙️ DataOps, DevOps & MLOps
Abstracted ML jobs into reusable, configuration-driven tasks instead of one-off scripts, and defined how high-workload ML processes run in a scalable environment. Automated deployment with CI/CD pipelines and containerised packaging, so data and ML code moves to production in a repeatable way. Monitored pipelines and data for duplicates, errors and failures.

### 👥 Engineering leadership & standards
Set engineering standards and best practices for the data team, including Python package development guidelines, release flow and gitflow. Mentored colleagues in software engineering and CI/CD, and provided technical guidance on data engineering direction.

## 🌍 Open source

| Project | Contribution |
|---|---|
| [**stac-fastapi-elasticsearch-opensearch**](https://github.com/stac-utils/stac-fastapi-elasticsearch-opensearch) | Contributor. A production-ready STAC API implementation on FastAPI with Elasticsearch and OpenSearch backends, published on PyPI and as Docker images. |
| [**stac-fastapi-mongo**](https://github.com/Healy-Hyperspatial/stac-fastapi-mongo) | Contributor. A STAC API implementation on FastAPI with a MongoDB backend. |
| [**Apache Airflow**](https://github.com/apache/airflow) | Community contributor: bug reports and feature feedback from running Airflow in production ([my issues](https://github.com/apache/airflow/issues?q=is%3Aissue+author%3Apedro-cf)). |

## 💻 Tech stack

**Platform & DevOps**<br>
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Astronomer](https://img.shields.io/badge/Astronomer-0B0B0B?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git%20%2F%20GitFlow-F05032?style=flat-square&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-555555?style=flat-square)

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Data & ML**<br>
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-555555?style=flat-square)

**Backend & databases**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)

**Storage & cloud**<br>
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Geospatial & remote sensing**<br>
![STAC](https://img.shields.io/badge/STAC-007C92?style=flat-square)
![GeoServer](https://img.shields.io/badge/GeoServer-3B8CBA?style=flat-square)
![THREDDS](https://img.shields.io/badge/THREDDS-4B8BBE?style=flat-square)
![COG](https://img.shields.io/badge/COG%20%2F%20GeoTIFF%20%2F%20NetCDF-2E7D32?style=flat-square)
![Sentinel-2](https://img.shields.io/badge/Sentinel--2-0B3D91?style=flat-square)

**BI & analytics**<br>
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
