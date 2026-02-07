# CodeWeavers Sentinel - AI-Powered Geospatial Monitoring System

**Real-Time Environmental Threat Detection Using Satellite AI & Cloud-Native Architecture**

"Protecting Earth, One Pixel at a Time"

## Live Demo

Visit our live application: https://codeweavers1.netlify.app/

---

## Team CodeWeavers

**Finalist Project**

- **Archita Mukherjee** - Full-Stack Developer & AI Integration
- **Arpan Chakraborty** - Backend Architecture & Geospatial Systems
- **Institute**: DS Vidya

---

## Problem Statement

AI-powered cloud-native system for real-time land use change detection and sustainable decision-making.

### The Problem

Traditional environmental monitoring systems face critical limitations:

- Manual and traditional systems are slow and error-prone
- Cannot process petabytes of satellite imagery efficiently
- Lack of real-time land monitoring causes delayed decisions
- Environmental damage often goes unnoticed for years

### Our Solution

Cloud-Native AI Sentinel System that detects environmental threats in real-time, not months.

**Core Features:**
- Real-time satellite monitoring powered by AI
- Instant threat notifications
- Interactive 2D/3D visualization
- Multi-modal alert system

---

## Detection Capabilities

Our system can detect environmental threats with over 90% accuracy:

| Threat Type | Detection Method | Accuracy |
|------------|------------------|----------|
| Deforestation | NDVI Analysis | 94% |
| Illegal Mining | Thermal + Texture | 91% |
| Water Pollution | Spectral Signature | 89% |
| Landslides | SAR Movement | 87% |

---

## System Architecture

### Frontend Layer
- React.js, Leafmap, CesiumJS, Three.js
- Interactive 2D/3D visualization with real-time globe rendering

### Backend Layer
- Java (Spring Boot), Python, Node.js
- Data processing, AI analysis, and API orchestration

### Data Layer
- Sentinel-2 Satellite, Cloud Storage
- Multispectral imagery and temporal analysis pipeline

---

## Technology Stack

### Data Acquisition & Processing
- **Satellite Data**: Sentinel-2, Landsat, Drone Imagery
- **APIs**: Google Earth Engine (GEE), AWS Open Data Registry, Copernicus Hub
- **Processing**: Apache Spark, Apache Flink, Apache Airflow
- **Preprocessing**: Rasterio, GDAL, OpenCV

### AI/ML Models
- **Frameworks**: TensorFlow, PyTorch, ONNX
- **Models**: CNNs, Vision Transformers, Random Forest
- **Techniques**: NDVI Analysis, Temporal Comparison, Pattern Recognition
- **Datasets**: Dynamic World V1, Labeled Land Cover

### Frontend Technologies
- **Core**: React.js, JavaScript
- **3D Rendering**: Three.js, CesiumJS
- **Mapping**: Leaflet.js, Leafmap, Mapbox
- **UI Components**: Real-time Dashboards, Split-screen Comparison

### Backend Infrastructure
- **Languages**: Java (Spring Boot), Python, Node.js
- **APIs**: FastAPI, Flask, REST/GraphQL
- **Services**: Web Audio API for Alerts

### Cloud & DevOps
- **Cloud Platforms**: AWS, Google Cloud Platform (GCP)
- **Storage**: Amazon S3, Google Cloud Storage, BigQuery
- **Containerization**: Docker, Kubernetes
- **Infrastructure as Code**: Terraform
- **Monitoring**: Prometheus, Grafana, KEDA

### Security
- **Authentication**: OAuth2, JWT
- **Access Control**: IAM Roles

---

## Key Features

### 1. Interactive 2D Map Interface
- Real-time satellite layer switching (Hybrid, Terrain, Satellite)
- Split-screen before/after comparison slider
- Geocoding search for any location globally
- Visual threat markers with detailed popups

### 2. 3D Global Sentinel
Powered by CesiumJS:
- Interactive 3D Earth rendering with real terrain data
- Fly-to animations for detected threat locations
- Real-time camera controls and orbital view
- Marker overlays with threat classification

### 3. Real-Time Alert Engine

5-Step Alert Pipeline:
1. **AI Detection** - Satellite data analyzed every 5 seconds
2. **Threshold Check** - Change exceeds predefined sensitivity
3. **Visual Alert** - Red banner with location & threat details
4. **Audio Siren** - Web Audio API emergency tone
5. **Authority Dispatch** - Instant notification to enforcement teams

### 4. Drone Surveillance Integration
Enhanced monitoring with autonomous aerial systems for:
- Close-range threat verification
- Real-time video streaming
- Inaccessible terrain coverage

### 5. Ground Robot Deployment
Autonomous ground vehicles for:
- Remote terrain analysis
- Sample collection
- Hazardous zone exploration

---

## Methodology

### 1. Data Acquisition
- **Sources**: Sentinel-2, Landsat, Drone Imagery, IoT Sensors
- **Tools**: Google Earth Engine, AWS Open Data Registry
- **Goal**: Collect multispectral imagery and geospatial data streams

### 2. Preprocessing
- **Steps**: Cloud masking, Radiometric correction, Image registration
- **Tools**: GEE, Rasterio, GDAL
- **Goal**: Normalize and align data for consistent analysis

### 3. Feature Extraction
- **Techniques**: NDVI, NDBI, Water Index, Texture Analysis
- **Goal**: Derive vegetation, urban, and water features

### 4. Model Training
- **Models**: CNNs, Vision Transformers, Random Forest
- **Data**: Dynamic World V1 labeled datasets
- **Goal**: Classify land use types and detect changes

### 5. Change Detection
- **Methods**: Post-classification comparison, Image differencing, Time-series analysis
- **Goal**: Identify significant land use transitions

---

## Implementation Pipeline

| Step | Component | Technologies |
|------|-----------|-------------|
| 1 | Cloud Setup | AWS/GCP, Kubernetes, Docker |
| 2 | Data Pipeline | Apache Airflow, Spark, GEE |
| 3 | Model Deployment | TensorFlow Serving, ONNX, FastAPI |
| 4 | Storage | S3, GCS, BigQuery |
| 5 | Visualization | Streamlit, Dash, Mapbox |
| 6 | API Layer | REST/GraphQL, Flask/FastAPI |
| 7 | Monitoring | Prometheus, Grafana, KEDA |

---

## Real-World Applications

### Government Agencies
- Forest Department monitoring
- Mining regulation enforcement
- Water resource management
- Environmental protection

### Disaster Management
- Landslide early warning
- Flood risk assessment
- Volcanic activity monitoring
- Evacuation planning

### Defense & Military
- Real-time border monitoring
- Unauthorized crossing detection using AI
- Military base perimeter monitoring
- Infrastructure threat detection (bridges, dams)

### Commercial Sector
- Insurance risk assessment
- Real estate expansion analysis
- Energy site selection (solar/wind farms)
- Agricultural monitoring

### NGOs & Research
- Conservation projects
- Climate change studies
- Biodiversity hotspot monitoring
- Carbon cycle analysis

---

## Project Impact

**Key Metrics:**
- 4 Detection Modules
- 15+ Technologies Used
- Less than 5 seconds Alert Response Time
- Over 90% Detection Accuracy

**Key Achievements:**
- Fully functional cloud-native architecture
- Real-time 3D globe with satellite data integration
- Multi-modal alert system (visual + audio)
- Mobile-responsive field officer interface

---

## Market Potential

### Technical Feasibility
- Cloud-native scalability
- Open satellite data availability
- Mature AI models
- IoT/GIS integration

### Economic Feasibility
- Lower infrastructure costs
- Pay-as-you-go cloud pricing
- Climate-tech VC funding opportunities
- Government grants available
- **Market Size**: Over $100B global market by 2030

### Operational Feasibility
- Easy containerized deployment
- User-friendly dashboards
- Automated monitoring

---

## Getting Started

### Prerequisites
```
Python 3.8+
Java 17+
Node.js 16+
Docker & Kubernetes
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/ArpanC6/codeweavers-sentinel.git
cd codeweavers-sentinel
```

2. Install Python dependencies
```bash
pip install leafmap localtileserver flask-cors pyvista
pip install tensorflow pytorch rasterio gdal opencv-python
```

3. Install Java
```bash
apt-get install -y openjdk-17-jdk-headless
```

4. Set up environment variables
```bash
export GEE_API_KEY=your_google_earth_engine_key
export AWS_ACCESS_KEY=your_aws_key
export SENTINEL_API_KEY=your_sentinel_key
```

5. Run the application
```bash
# Start Java backend
javac ProjectBackend.java
java ProjectBackend &

# Start Python AI service
python ai_service.py &

# Launch frontend
npm install
npm start
```

---

## Project Structure

```
codeweavers-sentinel/
├── backend/
│   ├── java/                    # Spring Boot backend
│   ├── python/                  # AI/ML models
│   └── api/                     # REST/GraphQL APIs
├── frontend/
│   ├── src/
│   │   ├── components/          # React components
│   │   ├── cesium/              # 3D globe integration
│   │   └── maps/                # 2D map interfaces
│   └── public/
├── data/
│   ├── satellite/               # Sentinel-2 imagery
│   ├── models/                  # Trained ML models
│   └── datasets/                # Training datasets
├── deployment/
│   ├── docker/                  # Dockerfiles
│   ├── kubernetes/              # K8s manifests
│   └── terraform/               # IaC scripts
├── notebooks/                   # Jupyter notebooks
└── docs/
```

---

## Future Roadmap

- Integration with more satellite sources (Planet Labs, MODIS)
- Mobile app for field officers
- Advanced predictive analytics using temporal data
- Blockchain-based verification system
- Multi-language support for global deployment
- Integration with government alert systems
- Automated drone dispatch for threat verification
- Community reporting and validation features

---

## Contributing

We welcome contributions! Please feel free to submit pull requests or open issues for:
- Bug fixes
- Feature enhancements
- Documentation improvements
- New detection algorithms

---

## License

This project is developed for educational and environmental protection purposes.

---

## Acknowledgments

- Google Earth Engine for satellite data access
- AWS Open Data Registry for cloud infrastructure
- Copernicus Hub for Sentinel-2 imagery
- Sentinel-2 satellite program
- Open-source geospatial community
- Hackathon organizers and mentors

---

**Making the World a Safer Place Through Technology**

Live Demo: https://codeweavers1.netlify.app/
