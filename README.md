# Logging System - Django with ELK Stack

## Overview

The **Logging System** project integrates Django with the **ELK Stack** (Elasticsearch, Logstash, and Kibana) for real-time logging and monitoring. This setup is designed to capture logs from a Django application, forward them to Logstash, store them in Elasticsearch, and visualize them using Kibana.

### Technologies
- **Django** for web framework
- **ELK Stack**:
  - **Elasticsearch** for storing and indexing logs
  - **Logstash** for processing and forwarding logs
  - **Kibana** for visualizing logs
- **Docker** for containerized deployment

## Quick Start

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-repo/logging-system.git
cd logging-system
