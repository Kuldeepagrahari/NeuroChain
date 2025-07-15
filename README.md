<h2>#Team- Infinity</h1>

# 🧠 NeuroChain – AI-Powered Cognitive Supply Chain Management System

> An intelligent, real-time, and self-adaptive platform to revolutionize retail supply chains — from **demand forecasting** and **inventory equalization** to **last-mile delivery optimization**, **vendor auto-integration**, and **voice-assisted warehouse control**.

---

## 🚀 Problem Statement

In today's rapidly evolving retail landscape, businesses suffer from:
- **Unbalanced inventory** leading to stockouts and overstocking.
- **Static demand planning**, unable to adjust for festivals, weather, or real-time events.
- **Inefficient last-mile delivery**, especially in Tier-2/3 cities or traffic-heavy zones.
- **Manual warehouse operations**, which are slow and error-prone.
- **Disconnected vendors**, requiring human intervention for restocking and PO creation.

These challenges not only reduce profit margins but also degrade the **customer experience** and cause **supply chain fragility**.

---

## 💡 Our Vision – What is NeuroChain?

**NeuroChain** is inspired by the **human brain** – constantly sensing, learning, and adapting to its environment.

It is an end-to-end, AI-driven **cognitive supply chain management system** that:
- Forecasts store-level demand dynamically
- Automatically shifts stock between locations
- Optimizes last-mile delivery routes in real time
- Integrates directly with vendors for seamless restocking
- Enables voice-controlled operations inside warehouses

All in one **smart, unified platform**.

---

## 🧩 Core Modules & Features

### 1. 🧠 Demand Sensing Engine
- Predicts **localized product demand** using time series models (LSTM + Prophet).
- Factors in **seasonality**, **local events**, and **weather changes**.
- Helps prevent stockouts or overstocking **before they happen**.

### 2. 🔄 Inventory Equalizer
- Uses **clustering + optimization algorithms** to suggest **real-time stock transfers**.
- Balances inventory across stores based on predicted shortfall or excess.
- Powered by **Google OR-Tools** for constraint-based decisions.

### 3. 🚚 Smart Last-Mile Routing
- Uses **reinforcement learning** to dynamically assign the **fastest delivery paths**.
- Considers real-time **traffic data**, **historical delivery times**, and **route risks**.
- Reduces fuel cost, delivery delay, and operational stress.

### 4. 🔗 Vendor Integration APIs
- RESTful APIs for vendors to **auto-sync stock levels**, **trigger replenishment**, and **track PO status**.
- Supports multiple vendors with flexible thresholds.
- Minimizes the need for human monitoring or emails.

### 5. 🎙️ Voice Assistant for Warehouse Managers
- Voice interface (using Google Speech/Web Speech API) for **hands-free operations**.
- Can **check stock**, **initiate stock movement**, or **respond to alerts** verbally.
- Increases warehouse agility and accessibility.

---

## 📊 Real-Time Dashboard

An interactive React-based dashboard visualizes:
- 📈 Predicted demand per product/store
- 📦 Live inventory across warehouse/store network
- 🚛 Current delivery routes & ETAs
- 🛠 Vendor stock-in-transit and order sync
- 🗣 Voice assistant transcript + status logs

Built with a responsive design, suited for both desktop and warehouse tablets.

---

## 🛠️ Tech Stack

| Layer        | Tools/Libraries |
|--------------|-----------------|
| **Frontend** | React.js, Tailwind CSS, Chart.js, Leaflet.js |
| **Backend**  | Python, FastAPI |
| **Database** | PostgreSQL, Redis |
| **ML Models**| LSTM (Keras), Prophet, scikit-learn |
| **Optimization** | Google OR-Tools |
| **Voice Interface** | Web Speech API, Google Speech-to-Text |
| **APIs**     | Google Maps API, Weather API, Custom Vendor APIs |

---

## 🧪 Dataset Simulation

We simulate real-world scenarios using:
- `sales.csv` – product sales history per store
- `store_locations.json` – latitude, longitude, and capacity
- `traffic_mock.json` – estimated travel times per delivery window
- `vendors.json` – connected suppliers and their lead times

All data is open-source or generated.

---

## 📹 Demo Video

Watch our complete walkthrough here:  
👉 <a href="https://youtu.be/R4VWDtKYdx4?si=_n1j4MASamwntxj7"> Demo Video Link



