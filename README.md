[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://dss123.streamlit.app/)

# MKDC DSS 1,2,3
This repository contains code for Decision Support System 1, 2, 3 within the Mekong Delta Centre.

# Water Management Decision Support System for the Mekong Delta

- DSS 1, 2, 3 is designed to calculate water quality, water supply, and water shortage risk for the Mekong Delta Centre. 

## Features

- DSS 1: calculate Water Quality Index (WQI)
- DSS 2: calculate Water Supply Capacity Index (WSCI)
- DSS 3: calculate Water Shortage Risk Index (WSRI)
	

## Prerequisites

- Docker installed on your machine.

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/thangqd/dss123.git
	```
	
2. **Build the Docker Image:**
	```bash
	cd dss123
	docker-compose build 
	```
	
3. **Run the Docker Container:**
    ```bash
    docker-compose up
	```

4. **Access the DSS:**

Open your web browser and go to http://localhost:8501 to interact with the Decision Support System.

## Support
For any inquiries or issues, please https://github.com/thangqd/dss123/issues

<img src="./images/dss2.png"/>
