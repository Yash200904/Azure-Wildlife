# Wildland Fire Azure AI Project

## Project Overview
This project investigates the recovery of the **2000 Jasper Fire**, one of the most devastating wildfires in the Black Hills of South Dakota. Using Landsat satellite imagery, machine learning models, and Azure Machine Learning Studio, our goal is to analyze the ecological recovery and explore actionable insights for forest management, wildfire resilience planning, and recovery efforts that can be applied worldwide.

### Objectives
- Utilize Landsat imagery accessed via Earth Explorer and processed through ESPA to assess post-fire recovery in the Jasper Fire region.
- Analyze key ecological metrics such as burn severity, vegetation recovery, and fuel load modeling.
- Develop machine learning workflows to process geospatial data and automate analysis.
- Highlight the ongoing efforts of the U.S. Forest Service to restore the Black Hills forest ecosystem.

### Background
The **Jasper Fire** ignited on August 24, 2000, when a woman intentionally flicked a lit cigarette off the side of the road, setting off a wildfire that burned over **83,000 acres** of the Black Hills National Forest. This fire became a tragic reminder of the destructive consequences of human negligence.

As we approach the **25-year memorial** of this catastrophic event, the impact of the fire is still visible in the Black Hills. Unlike many forests that naturally regenerate after a wildfire, much of the burned area has required human intervention. Each spring, the U.S. Forest Service has a narrow two-week window to **hand-plant approximately 400 acres of native Ponderosa Pines**, which are grown locally in greenhouses. The slow recovery process underscores the challenges of reforesting this unique ecosystem.

---

## Team Members
- **Manuel Malla** (Lead): Information Technology engineering student at Universidad Técnica de Machala, Ecuador. Specializes in geospatial research and mangrove ecosystem monitoring.
- **Yash Padhara** (Co-Lead): B.Tech Computer Engineering student at CVM University, India. Focused on academic projects and emerging technologies.
- **Sneha Pandey**: Pre-final year Artificial Intelligence and Machine Learning student from Delhi, India. Contributor to JuliaHealth and researcher in deep learning applications.
- **Philippa Burgess**: Graduate student specializing in geospatial intelligence and machine learning, leveraging Azure AI for disaster resilience and recovery.

---

## Project Workflow

### Data Collection
We used the following workflow to acquire and preprocess data:
1. **Earth Explorer**: Landsat satellite imagery of the Jasper Fire region was accessed through the USGS Earth Explorer platform.
2. **ESPA**: The imagery was downloaded in **GeoTIFF format** in two batches:
   - **jasper-landsat-130**
   - **jasper-landsat-054**
3. **Azure Storage Blob**: The TIFF files were uploaded to Azure Storage Blob for collaborative access by the team.

### Data Analysis
- **Burn Severity Mapping**: Using indices like **dNBR (Differenced Normalized Burn Ratio)** to measure the severity of the fire’s impact on vegetation.
- **Vegetation Recovery**: Using **NDVI (Normalized Difference Vegetation Index)** to track regrowth over the past 25 years.
- **Fuel Load Modeling**: Leveraging 3D geospatial data, including LiDAR, to model fuel loads and better understand forest recovery dynamics.

### Tools and Platforms
- **Azure Machine Learning Studio**: For geospatial data analysis and machine learning model development.
- **Azure Storage Blob**: To securely store and share large geospatial datasets.
- **GitHub Repository**: For collaboration and project management.

### Key Milestones
1. **Data Preprocessing**:
   - Download and clean satellite imagery data.
   - Organize datasets into Azure Storage Blob for shared team access.
2. **Exploratory Data Analysis**:
   - Analyze burn severity and vegetation recovery trends using spectral indices.
   - Explore ecological factors like slope, aspect, and elevation.
3. **Model Development**:
   - Train machine learning models to classify burn severity and predict vegetation recovery.
   - Develop workflows for time-series analysis of satellite imagery.
4. **Application and Insights**:
   - Provide recommendations for wildfire management and forest resilience planning.
   - Generalize methodologies for global wildfire recovery efforts.

---

## Literature Review

### Burn Severity and Recovery
- The **Jasper Fire** demonstrated the long-lasting effects of high-severity burns in forests that lack natural regeneration mechanisms. Indices such as **dNBR** and **dNDVI** were validated in studies to classify burn severity and track vegetation changes.
- The slow recovery of Ponderosa Pines in the Black Hills has required strategic interventions, including human-assisted reforestation efforts.

### Fuel Load and Risk
- **LiDAR** and **Terrestrial Laser Scanning (TLS)** are critical for modeling fuel loads. These technologies provide detailed data on vegetation structure, informing fire risk assessments and recovery plans.

### Public Data Sources
- **Landsat**: Multi-temporal satellite imagery to assess pre- and post-fire conditions.
- **NOAA**: Climate and weather data for understanding wildfire risk and resilience.
- **USGS National Map**: Topographic data for analyzing terrain-related burn severity.

---

## GitHub Repository
[**Wildland Fire Azure AI Repository**](https://github.com/YOUR_REPO_LINK)  
This repository includes:
- Preprocessing and analysis scripts
- Azure ML Studio notebooks
- Documentation for each stage of the project

---

## Acknowledgments
This project is supported by mentors from the **USGS EROS Center - Wildland Fire Support Team**. We deeply appreciate their guidance and the resources provided.

---

## Contribution Guidelines
1. Access Azure Blob Storage for data.
2. Collaborate on GitHub by cloning the repository, committing code, and pushing updates.
3. Participate in task assignments and discussions via GitHub Issues and Milestones.

---

## Contact
For any inquiries, please reach out to the team:
- Manuel Malla: mmalla1@outlook.com
- Yash Padhara: yashpadhara@example.com
- Sneha Pandey: gd6601692@gmail.com
- Philippa Burgess: philippa.burgess@studentambassadors.com 
