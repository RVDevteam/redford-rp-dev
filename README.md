# Redford RP Server

This repository contains the configuration and resources for **Redford RP**, a RedM roleplay server based on the **VORP Core** framework.  
Developed and maintained by **RVDevteam**.

---

## Features
- Based on [VORP Core](https://github.com/VORPCORE)
- Configurable via `server.cfg`
- Easy setup with an example configuration
- Database integration (MySQL)
- Preconfigured essential resources (VORP Core, VORP Menu, VORP Inputs, VORP Character, WeatherSync, etc.)

---

## Getting Started

### 1. Open `server.cfg` and fill in all required fields:
- `sv_licenseKey`
- `steam_webApiKey`
- `mysql_connection_string` (database credentials)
- Admin identifiers under `add_principal`

> **Note:** Do **not** commit your real `server.cfg` to the repository — it should stay private.

---

### 2. Database Setup
- Make sure you have a MySQL database ready.  
- The required tables and schema are not included in this repo.  
  - If you need the structure, **contact the RVDevteam** for the latest SQL files.  
- Ensure your `mysql_connection_string` in `server.cfg` matches your DB configuration.

---

### 3. Run the Server
- Launch FXServer:
- 
  ```bash
  redford-rp-dev/server/FXServer.exe
