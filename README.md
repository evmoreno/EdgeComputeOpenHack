# Edge - Art of the possible

Deploy Azure GPU enabled VM
Create NC12v2 VM in Azure on Ubuntu 18.04 
-	Install drivers - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install nvidia docker and ensure nvidai-smi is working inside docker for you - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install iot edge on your VM - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-linux
OR use the Azure deploy button ere this does all above from UX -  https://github.com/MSKeith/iotedge-vm-deploy

Tutorials creating and deploying solutions to Edge:
-	Deploy FactoryAI Vision - https://github.com/Azure-Samples/azure-intelligent-edge-patterns/tree/master/factory-ai-vision
-   Azure Stack Edge docs - https://docs.microsoft.com/en-us/azure/databox-online/azure-stack-edge-j-series-configure-gpu-modules
-	Intelligent Edge Git Hub repo samples - https://github.com/Azure-Samples/azure-intelligent-edge-patterns
-	Live Video Analytics  -https://docs.microsoft.com/en-gb/azure/media-services/live-video-analytics-edge/use-intel-openvino-tutorial
-	Live Video Analytics GitHub repo has samples and some utils includes RTSP simulator  - https://github.com/Azure/live-video-analytics
-	You can also train a CustomAI vision model, export to container and deploy to IOT Edge here is an example- https://azure.github.io/Vision-AI-DevKit-Pages/docs/Tutorial-HOL_Using_the_VisionSample/


Setup CICD for IoT Edge to deploy your container solution and even setup monitoring IoT Edge modules:
-	IoT Hub and IoT Edge Module Monitoring - Expose and ingest IoT Edge Metrics into Azure Monitor Log Analytics workspace - https://github.com/veyalla/ehm  
-	IoT Edge Container Debug logs to Azure Monitor - Ingest IoT Edge container logs into Azure Monitor Analytics workspace - https://github.com/veyalla/logspout-loganalytics 
-	Use Grafana to send IoT Edge Container Debug to Azure Monitor - https://github.com/veyalla/edge-telegraf-monitor


# IoT Edge Concepts
- IoT Hub - https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub
- IoT Edge Runtime - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime
- IoT Edge Modules - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-modules
- IoT Edge Module communication - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime#module-communication
- IoT Edge on Kubernetes - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-kubernetes# & Tutorial - https://microsoft.github.io/iotedge-k8s-doc/
- Container Host interactions - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options
    Storage - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-access-host-storage-from-module
    Network - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options#map-host-port-to-module-port

# IoT Workshops
- Internet of Things learning path - https://github.com/microsoft/Internet-of-Things-Event-Learning-Path
- Internet of Things - https://github.com/Microsoft/MCW-Internet-of-Things
- IoT Smart City - https://github.com/Microsoft/MCW-IoT-and-the-Smart-City
- MlOps - https://github.com/microsoft/MCW-ML-Ops
- Predictive Maintenance for Field Devices - https://github.com/microsoft/MCW-Predictive-Maintenance-for-remote-field-devices
- Securing IoT End to End - https://github.com/microsoft/MCW-Securing-the-IoT-end-to-end

# Microsoft Learn Edge Content
- AI Edge Engineer - https://docs.microsoft.com/en-us/learn/paths/ai-edge-engineer/
- Introduction to IoT - https://docs.microsoft.com/en-gb/learn/paths/introduction-to-azure-iot/
- Securely connect IoT Devices- https://docs.microsoft.com/en-gb/learn/paths/securely-connect-iot-devices/
- Build intelligent edge with IoT Edge - https://docs.microsoft.com/en-gb/learn/paths/build-intelligent-edge-with-azure-iot-edge/
- Develop IoT Solutions with IoT Central - https://docs.microsoft.com/en-gb/learn/paths/develop-iot-solutions-with-azure-iot-central/
- Synapse Analytics -https://docs.microsoft.com/en-us/learn/paths/realize-integrated-analytical-solutions-with-azure-synapse-analytics/?_lrsc=1212a841-a9d8-45f4-9e7c-3db61ef82a85
- Azure Digital Twins - https://docs.microsoft.com/en-us/learn/paths/develop-azure-digital-twins/

# Analytics & AI Workshops
- Machine Learning - https://github.com/microsoft/MCW-Machine-Learning
- Synapse & AI - https://github.com/microsoft/MCW-Azure-Synapse-Analytics-and-AI
- Big Data & Visualisation - https://github.com/Microsoft/MCW-Big-Data-and-Visualization
- Cognitive Services & Deep Learning - https://github.com/Microsoft/MCW-Cognitive-Services-and-Deep-Learning
- CosmosDB Real-time analytics - https://github.com/Microsoft/MCW-Cosmos-DB-Real-Time-Advanced-Analytics
- Innovate with Data & AI - https://github.com/microsoft/MCW-Innovate-and-modernize-apps-with-Data-and-AI
- Intelligent Analytics - https://github.com/Microsoft/MCW-Intelligent-Analytics
- Analytics and SQL 2019 - https://github.com/microsoft/MCW-Modernizing-Data-Analytics-with-SQL-Server-2019

# Data Workshops
- Migrate to Azure SQL - https://github.com/microsoft/MCW-Migrating-SQL-databases-to-Azure
- Migrating Oracle to Azure SQL -  https://github.com/Microsoft/MCW-Migrating-Oracle-to-Azure-SQL-and-PostgreSQL
- SQL Engineering Team workshops - https://microsoft.github.io/sqlworkshops/
- Migrating Oracle to PostgreSQL - https://github.com/Hrashid789/ora2pgWorkshop

# DataOps
- Modern Data warehouse DataOps -https://github.com/Azure-Samples/modern-data-warehouse-dataops

# Demos
- IoT Solution Demos -https://github.com/Azure-Samples/IoTDemos
# Devices
- nVidia Jetson Nano DevKit -  https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit
- Deploying an AI/IoT Model https://github.com/NVIDIA-AI-IOT/trt_pose

# Use Pre-trained Models for Edge AI
Intel OpenVino - https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit/pretrained-models.html
nVidia -https://developer.nvidia.com/blog/training-custom-pretrained-models-using-tlt/

# Technical Whitepapers
- Oracle to PostgreSQL migration guide - https://github.com/microsoft/OrcasNinjaTeam/blob/master/Oracle%20to%20PostgreSQL%20Migration%20Guide/Oracle%20to%20Azure%20Database%20for%20PostgreSQL%20Migration%20Guide.pdf

# Register for OpenHacks
- Developer focused team based events - https://openhack.microsoft.com/

# Check out these projects
- Project15 - https://github.com/microsoft/project15
- HealthyCountryAi - https://github.com/microsoft/HealthyCountryAI
- Microsoft researh -  https://www.microsoft.com/en-us/research/
- IoT Central - https://github.com/Azure/iot-central







