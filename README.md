
# ✦ ━━━━ ⟡ CLOUD MONITORING & DOCKERIZED FLASK APPLICATION ⟡ ━━━━ ✦

═══════════════════════════════════════════════════════════════════════




## ◈ PROJECT OVERVIEW ◈

This project demonstrates the deployment, monitoring, and management of a Dockerized Python Flask web application on Ubuntu Linux using modern cloud and DevOps technologies.

The entire infrastructure was manually configured inside a VirtualBox Ubuntu environment to simulate a real-world cloud support and infrastructure deployment workflow.

The project includes:

✧ Linux Administration  
✧ Docker Containerization  
✧ Nginx Reverse Proxy Configuration  
✧ Prometheus Monitoring  
✧ Grafana Dashboard Visualization  
✧ Docker Networking  
✧ Infrastructure Troubleshooting  
✧ Monitoring Architecture  
✧ Service Deployment & Validation  

This project was built with the goal of understanding how modern cloud infrastructure components communicate with each other in production-style environments.

═══════════════════════════════════════════════════════════════════════

# ❖ TABLE OF CONTENTS ❖

### ➊ Project Objectives
### ➋ Technologies Used
### ➌ Project Architecture
### ➍ Screenshots
### ➍ Infrastructure Workflow
### ➎ Docker Deployment
### ➏ Monitoring Stack
### ➐ Troubleshooting & Debugging
### ➑ Skills Gained
### ➒ Real-World Concepts Learned
### ➓ Future Improvements
### ⓫ Resume Description
### ⓬ Conclusion

═══════════════════════════════════════════════════════════════════════

# ✦ ➊ PROJECT OBJECTIVES ✦

The primary objective of this project was to gain practical hands-on experience with cloud support and DevOps technologies by building a complete deployment and monitoring environment from scratch.

## ◎ Main Objectives

✔ Deploy a Python Flask application on Ubuntu Linux

✔ Learn Linux administration and terminal operations

✔ Containerize applications using Docker

✔ Configure Nginx reverse proxy

✔ Build monitoring infrastructure

✔ Configure Prometheus for metrics collection

✔ Visualize infrastructure metrics using Grafana

✔ Understand Docker networking concepts

✔ Learn troubleshooting methodologies

✔ Simulate production-style infrastructure deployment

✔ Gain practical cloud support engineering experience

═══════════════════════════════════════════════════════════════════════

# ✦ ➋ TECHNOLOGIES USED ✦

| Technology | Purpose |
|━━━━━━━━━━━━|━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━|
| Ubuntu Linux | Operating system environment |
| Python | Backend programming language |
| Flask | Lightweight web framework |
| Docker | Application containerization |
| Nginx | Reverse proxy server |
| Prometheus | Infrastructure monitoring |
| Grafana | Metrics visualization |
| VirtualBox | Virtualized lab environment |
| Linux Terminal | Server administration |

═══════════════════════════════════════════════════════════════════════

# ✦ ➌ PROJECT ARCHITECTURE ✦

```text
Browser
   ↓
Nginx Reverse Proxy
   ↓
Docker Container
   ↓
Python Flask Application
   ↓
Prometheus Monitoring
   ↓
Grafana Dashboard Visualization
```

═══════════════════════════════════════════════════════════════════════



# # ❖ ❖ P R O J E C T   S C R E E N S H O T S ❖ ❖

The following screenshots demonstrate the successful implementation, deployment, monitoring, troubleshooting, and containerization workflow of the complete cloud monitoring infrastructure project.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 1 — ALL DOCKER CONTAINERS RUNNING

This screenshot displays all active Docker containers running successfully inside the Ubuntu Linux environment, including the Flask application, Prometheus, and Grafana monitoring services.

## ◎ Key Highlights

➤ Docker container orchestration

➤ Multi-container deployment

➤ Infrastructure service management

➤ Linux container environment

➤ Monitoring stack deployment

![All Containers Running](dockerstatus.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 2 — PROMETHEUS CONNECTED TO GRAFANA

This screenshot verifies the successful integration between Grafana and Prometheus through the monitoring API connection.

## ◎ Key Highlights

➤ Prometheus API integration

➤ Monitoring infrastructure connectivity

➤ Grafana data source configuration

➤ Real-time metrics communication

➤ Monitoring stack validation

![Prometheus Connected](c_apiconnectedprometheus.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 3 — FLASK APPLICATION DEPLOYMENT

This screenshot demonstrates the successful deployment and execution of the Flask web application.

## ◎ Key Highlights

➤ Flask application hosting

➤ Web application deployment

➤ Browser accessibility

➤ Python backend execution

➤ Service verification

![Flask Application](c_application.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 4 — DOCKER INSTALLATION & CONFIGURATION

This screenshot verifies Docker setup and container engine configuration inside the Linux environment.

## ◎ Key Highlights

➤ Docker Engine setup

➤ Container management

➤ Linux administration

➤ Docker command execution

➤ Infrastructure preparation

![Docker Installation](c_docker.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 5 — DOCKER CONTAINER STATUS

This screenshot displays active Docker container information and running services.

## ◎ Key Highlights

➤ Docker container monitoring

➤ Container lifecycle management

➤ Service deployment tracking

➤ Infrastructure management

➤ Running service verification

![Docker PS](c_docker_ps.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 6 — DOCKERIZED APPLICATION EXECUTION

This screenshot demonstrates the Flask application running successfully inside Docker containers.

## ◎ Key Highlights

➤ Application containerization

➤ Dockerized deployment

➤ Python container execution

➤ Production-style architecture

➤ Container-based hosting

![Docker Running](c_docker_running.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 7 — FINAL PROJECT DEPLOYMENT PROOF

This screenshot represents the successful completion of the complete cloud monitoring infrastructure project.

## ◎ Key Highlights

➤ Full infrastructure deployment

➤ Monitoring stack implementation

➤ Docker deployment success

➤ Linux server configuration

➤ Production workflow implementation

![Final Project](c_final.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 8 — GRAFANA MONITORING DASHBOARD

This screenshot displays the final Grafana monitoring dashboard visualizing CPU, Memory, Disk, and system metrics in real time.

## ◎ Key Highlights

➤ Real-time monitoring dashboard

➤ CPU analytics

➤ Memory utilization tracking

➤ Disk usage visualization

➤ Infrastructure observability

➤ Performance analytics

![Grafana Dashboard](c_finalmonitoringdashboard.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 9 — GRAFANA PLATFORM INTERFACE

This screenshot demonstrates the Grafana monitoring and visualization platform running successfully.

## ◎ Key Highlights

➤ Grafana monitoring platform

➤ Dashboard visualization

➤ Infrastructure analytics

➤ Monitoring environment

➤ Observability implementation

![Grafana Platform](c_grafana.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 10 — GRAFANA LOGIN INTERFACE

This screenshot shows the Grafana authentication and dashboard access interface.

## ◎ Key Highlights

➤ Monitoring platform authentication

➤ Grafana access management

➤ Dashboard login system

➤ Monitoring portal access

➤ Infrastructure analytics entry point

![Grafana Login](c_grafana_login.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 11 — GRAFANA HOME DASHBOARD

This screenshot demonstrates the Grafana dashboard homepage after successful login and configuration.

## ◎ Key Highlights

➤ Dashboard management

➤ Monitoring workspace

➤ Infrastructure visualization

➤ Analytics dashboard

➤ Monitoring platform configuration

![Grafana Homepage](c_grafanahomepage.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 12 — NGINX CONFIGURATION

This screenshot demonstrates the Nginx reverse proxy configuration used to route requests to the Flask application.

## ◎ Key Highlights

➤ Reverse proxy implementation

➤ Nginx web server setup

➤ HTTP request forwarding

➤ Service routing

➤ Infrastructure networking

![Nginx Setup](c_ngin.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 13 — NGINX REVERSE PROXY WORKFLOW

This screenshot verifies successful communication between Nginx and the Flask application backend.

## ◎ Key Highlights

➤ Reverse proxy workflow

➤ Web traffic management

➤ Backend communication

➤ Service accessibility

➤ Production-style architecture

![Nginx Running](c_nginx_running.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 14 — PROMETHEUS MONITORING PLATFORM

This screenshot displays the Prometheus monitoring interface used for infrastructure metrics collection.

## ◎ Key Highlights

➤ Infrastructure monitoring

➤ Metrics collection

➤ Monitoring endpoints

➤ Real-time monitoring

➤ Prometheus server execution

![Prometheus Dashboard](c_prometheus.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 15 — FLASK SERVER EXECUTION

This screenshot shows the Flask application server actively running inside the Linux terminal environment.

## ◎ Key Highlights

➤ Flask backend execution

➤ Python server runtime

➤ Network port exposure

➤ Linux terminal operations

➤ Application hosting

![Flask Running](flaskrunning.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# ◉ 16 — SERVER NETWORK CONFIGURATION

This screenshot demonstrates the network and IP configuration used during deployment and monitoring setup.

## ◎ Key Highlights

➤ Server networking

➤ Infrastructure connectivity

➤ IP configuration

➤ Network routing

➤ Linux network administration

![Server Network Configuration](server_network_config.PNG)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


═══════════════════════════════════════════════════════════════════════

# ✦ ➍ INFRASTRUCTURE WORKFLOW ✦

## ◉ STEP 1 — UBUNTU LINUX SETUP

A dedicated Ubuntu Linux virtual machine was created using VirtualBox to simulate a real Linux server environment.

### ◎ Tasks Performed

➤ Installed Ubuntu Linux  
➤ Configured networking  
➤ Verified internet connectivity  
➤ Updated Linux packages  
➤ Configured terminal environment  
➤ Installed required dependencies  

### ◎ Learning Outcomes

✦ Linux installation process  
✦ Linux package management  
✦ Terminal navigation  
✦ Linux networking basics  

═══════════════════════════════════════════════════════════════════════

## ◉ STEP 2 — DOCKER INSTALLATION & CONFIGURATION

Docker was installed and configured to containerize and manage the Flask application.

### ◎ Tasks Performed

➤ Installed Docker Engine  
➤ Started Docker services  
➤ Enabled Docker services  
➤ Verified Docker functionality  
➤ Learned Docker commands  
➤ Managed Docker containers  

### ◎ Important Commands Used

```bash
sudo apt update

sudo apt install docker.io -y

sudo systemctl start docker

sudo systemctl enable docker

docker ps
```

### ◎ Learning Outcomes

✦ Docker installation  
✦ Container lifecycle management  
✦ Docker command usage  
✦ Docker troubleshooting  

═══════════════════════════════════════════════════════════════════════

## ◉ STEP 3 — FLASK APPLICATION DEVELOPMENT

A lightweight Flask web application was created to simulate a deployable cloud-hosted service.

### ◎ Flask Application Features

➤ Browser accessible  
➤ Lightweight web framework  
➤ Docker compatible  
➤ Linux hosted application  
➤ Port-exposed deployment  

### ◎ Flask Application Code

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Cloud Project Running Successfully!"

app.run(host='0.0.0.0', port=5000)
```

### ◎ Learning Outcomes

✦ Flask framework basics  
✦ Python web development  
✦ Application routing  
✦ Service deployment concepts  

═══════════════════════════════════════════════════════════════════════

# ✦ ➎ DOCKER CONTAINERIZATION & DEPLOYMENT ✦

The Flask application was containerized using Docker to simulate modern cloud-native deployment architecture.

## ◉ Dockerfile Configuration

```dockerfile
FROM python:3.10

WORKDIR /app

COPY . .

RUN pip install flask

CMD ["python", "app.py"]
```

## ◉ Docker Build Command

```bash
docker build -t cloud-project .
```

## ◉ Docker Run Command

```bash
docker run -d --network host --name flask-container cloud-project
```

## ◉ Docker Verification

```bash
docker ps
```

### ◎ Learning Outcomes

✦ Docker image creation  
✦ Docker container deployment  
✦ Docker networking  
✦ Container lifecycle management  

═══════════════════════════════════════════════════════════════════════

# ✦ ➏ NGINX REVERSE PROXY CONFIGURATION ✦

Nginx was configured as a reverse proxy to forward incoming browser requests to the Flask application running inside the Docker container.

## ◉ Why Reverse Proxy Was Used

✔ Simulates production infrastructure

✔ Separates frontend traffic from backend services

✔ Improves request management

✔ Common real-world deployment architecture

## ◉ Nginx Configuration

```nginx
server {
    listen 80 default_server;

    location / {
        proxy_pass http://127.0.0.1:5000;
    }
}
```

### ◎ Learning Outcomes

✦ Reverse proxy architecture  
✦ Nginx configuration  
✦ Browser-to-server communication  
✦ Service routing concepts  

═══════════════════════════════════════════════════════════════════════

# ✦ ➐ MONITORING INFRASTRUCTURE ✦

A complete monitoring stack was implemented using Prometheus and Grafana to simulate enterprise-level infrastructure monitoring.

═══════════════════════════════════════════════════════════════════════

## ◉ PROMETHEUS MONITORING

Prometheus was deployed to collect infrastructure metrics and monitor services.

### ◎ Responsibilities of Prometheus

➤ Metrics collection  
➤ Infrastructure monitoring  
➤ Service monitoring  
➤ Metrics scraping  
➤ Monitoring endpoint management  

### ◎ Deployment Command

```bash
docker run -d --name prometheus --network monitoring -p 9090:9090 prom/prometheus
```

═══════════════════════════════════════════════════════════════════════

## ◉ GRAFANA DASHBOARD VISUALIZATION

Grafana was integrated with Prometheus to create professional monitoring dashboards.

### ◎ Dashboard Features

➤ CPU monitoring  
➤ RAM monitoring  
➤ Disk utilization graphs  
➤ Real-time metrics visualization  
➤ Infrastructure analytics  

### ◎ Deployment Command

```bash
docker run -d --name grafana --network monitoring -p 3000:3000 grafana/grafana
```

═══════════════════════════════════════════════════════════════════════

## ◉ NODE EXPORTER INTEGRATION

Node Exporter was used to expose Linux server metrics to Prometheus.

### ◎ Metrics Collected

✔ CPU Usage

✔ Memory Usage

✔ Disk Utilization

✔ Network Traffic

✔ System Uptime

### ◎ Deployment Command

```bash
docker run -d --name node-exporter --network monitoring -p 9100:9100 prom/node-exporter
```

═══════════════════════════════════════════════════════════════════════

# ✦ ➑ PROJECT FEATURES ✦

◆ Dockerized Flask application deployment

◆ Ubuntu Linux server management

◆ Nginx reverse proxy configuration

◆ Real-time infrastructure monitoring

◆ Prometheus metrics collection

◆ Grafana dashboard visualization

◆ Docker networking implementation

◆ Linux service management

◆ Infrastructure troubleshooting

◆ Monitoring architecture setup

◆ Production-style deployment simulation

═══════════════════════════════════════════════════════════════════════

# ✦ ➒ TROUBLESHOOTING & DEBUGGING ✦

One of the most important aspects of this project was solving real-world deployment and networking issues.

═══════════════════════════════════════════════════════════════════════

## ◉ ISSUE 1 — Docker Container Exiting Automatically

### ◎ Problem

Docker container stopped immediately after startup.

### ◎ Solution

➤ Checked Docker logs  
➤ Fixed Flask configuration  
➤ Rebuilt Docker image  
➤ Restarted containers  

### ◎ Learning

✦ Container debugging  
✦ Docker troubleshooting  
✦ Service verification  

═══════════════════════════════════════════════════════════════════════

## ◉ ISSUE 2 — Flask Application Not Reachable

### ◎ Problem

Browser could not access the Flask application.

### ◎ Solution

Configured Flask application using:

```python
host='0.0.0.0'
```

### ◎ Learning

✦ Application networking  
✦ Port exposure  
✦ Browser accessibility  

═══════════════════════════════════════════════════════════════════════

## ◉ ISSUE 3 — Nginx 502 Bad Gateway Error

### ◎ Problem

Nginx reverse proxy could not communicate with Flask container.

### ◎ Solution

➤ Reconfigured Docker networking  
➤ Verified container status  
➤ Restarted Nginx services  
➤ Corrected reverse proxy settings  

### ◎ Learning

✦ Reverse proxy troubleshooting  
✦ Service communication  
✦ Linux networking concepts  

═══════════════════════════════════════════════════════════════════════

# ✦ ➓ KEY ACHIEVEMENTS ✦

🏮 Successfully deployed Dockerized Flask application

🏮 Configured Nginx reverse proxy

🏮 Implemented Prometheus monitoring

🏮 Built Grafana monitoring dashboards

🏮 Managed Docker networking

🏮 Performed infrastructure troubleshooting

🏮 Simulated production-style deployment

🏮 Gained practical cloud support experience

═══════════════════════════════════════════════════════════════════════

# ✦ ⓫ SKILLS GAINED ✦

## ◉ Linux Skills

➤ Linux terminal navigation  
➤ Package management  
➤ Service management  
➤ Networking basics  
➤ Troubleshooting  

## ◉ Docker Skills

➤ Docker image creation  
➤ Container deployment  
➤ Docker networking  
➤ Container troubleshooting  

## ◉ Monitoring Skills

➤ Infrastructure monitoring  
➤ Metrics collection  
➤ Dashboard visualization  
➤ Monitoring integrations  

## ◉ Cloud Support Skills

➤ Deployment workflows  
➤ Infrastructure troubleshooting  
➤ Linux administration  
➤ Service monitoring  

═══════════════════════════════════════════════════════════════════════

# ✦ ⓬ FUTURE IMPROVEMENTS ✦

This project can be enhanced further by implementing:

➤ AWS EC2 deployment

➤ HTTPS SSL configuration

➤ Docker Compose integration

➤ Kubernetes deployment

➤ CI/CD pipeline setup

➤ Advanced monitoring alerts

➤ Log aggregation

➤ Auto-scaling concepts

➤ Multi-container architecture



═══════════════════════════════════════════════════════════════════════

# ✦ CONCLUSION ✦

This project provided practical hands-on experience with Linux administration, Docker containerization, reverse proxy configuration, monitoring infrastructure, and deployment troubleshooting.

The implementation simulated a real-world cloud support and DevOps workflow using modern infrastructure technologies and monitoring systems.

The project significantly improved practical understanding of:

✦ Linux-based deployment environments  
✦ Infrastructure monitoring systems  
✦ Docker containerization workflows  
✦ Reverse proxy architecture  
✦ Troubleshooting methodologies  
✦ Service deployment pipelines  
✦ Monitoring dashboard visualization  

Overall, this project strengthened practical cloud support engineering knowledge and provided real exposure to deployment architecture, infrastructure management, monitoring systems, and Linux administration concepts commonly used in modern cloud environments.
````
