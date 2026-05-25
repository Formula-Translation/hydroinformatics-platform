# Hydroinformatics Platform

A portfolio case study of a web-based hydroinformatics platform for geospatial visualization, simulation scenario management, and environmental time-series analysis.

> Note: This repository is a public case study. The full production source code, client data, model files, and credentials are not included.

## Overview

This platform was designed to support water management workflows by combining GIS visualization, hydrological simulation data, and interactive dashboards.

The system helps users explore simulation scenarios, inspect time-series results, and understand spatial water-related data through a web interface.

## Key Features

- Interactive GIS map for water infrastructure and station visualization
- Simulation scenario management
- Gantt-style timeline for scenario start and end dates
- Time-series charts for water level, discharge, rainfall, and related variables
- DFS0 time-series file generation workflow
- Backend API integration for model data and simulation metadata
- Dashboard interface for monitoring and decision support

## Tech Stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- Mapbox / MapLibre
- Recharts

### Backend
- FastAPI
- Python
- PostgreSQL
- SQLite
- REST API

### Data & Simulation
- MIKE by DHI file workflows
- DFS0 / RES1D time-series data
- Hydrological simulation metadata
- Geospatial datasets

### Infrastructure
- Cloudflare Tunnel
- Nginx
- Docker-ready backend structure

## Architecture

```text
User Interface
   ↓
Next.js Frontend
   ↓
REST API
   ↓
FastAPI Backend
   ↓
PostgreSQL / SQLite / Model Files
   ↓
Hydrological Simulation Data
