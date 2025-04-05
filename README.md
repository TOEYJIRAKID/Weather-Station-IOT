###### [(ระบบนี้ Transfer มาจาก Github Account เก่า --> https://github.com/TOEYJIRAKIT/64102080_IOT07)](https://github.com/TOEYJIRAKIT/64102080_IOT07)

## 🚀 **Project Name** :

Weather Station - Weather Monitoring System Using IoT

## 📌 **Project Overview** :

Weather Station is an IoT-based system designed to monitor environmental conditions such as temperature and humidity in real-time. By integrating sensors with a microcontroller and a web dashboard, this project allows users to remotely observe weather data from anywhere. The system is ideal for use in agriculture, smart homes, and educational purposes where environmental awareness is crucial.

## 🎯 **Objective** :

- Develop a sensor-based system to collect temperature and humidity data.
- Transmit data from the sensors to a central server using a microcontroller.
- Display the environmental data on a web interface in real-time.
- Allow data to be stored and accessed for analysis using JSON Server.

## ✨ **Key Features** :

- **Real-time Temperature Monitoring** – Captures current ambient temperature from the environment.
- **Humidity Detection** – Tracks atmospheric moisture using digital sensors.
- **Web Dashboard** – Displays weather data on a user-friendly interface.
- **Data Logging** – Stores records for future review and trend analysis.

## 🛠 **Tech Stack** :

- **Frontend:** CSS3, HTML5, JavaScript, Bootstrap, Python
- **Other:** JSON Server

## 📂 **GitHub Repository (Source Code)** :

- [https://github.com/TOEYJIRAKID/Weather-Station-IOT](https://github.com/TOEYJIRAKID/Weather-Station-IOT)

## ⚙️ **Installation & Setup** :

1. **Clone the repository**  
   ```bash
   git clone https://github.com/TOEYJIRAKID/Weather-Station-IOT.git
   ```  
2. **Install json-server**  
   ```bash
   npm install json-server
   ```  
3. **Run the JSON Server**  
   ```bash
   npx json-server data.json --watch --port 3000
   ```  
4. **Open http://localhost:3000/sensors to view the json data.**

## 📃 Example JSON Data :

```json
{
  "sensors": [
    {
      "message": "{\"humidity\":55.000000, \"temperature\":23.700001}",
      "id": 1
    },
    {
      "message": "{\"humidity\":95.000000, \"temperature\":27.200001}",
      "id": 2
    }
  ]
}
```

## 📽️ **Project Preview** :

![Weather Station](https://github.com/TOEYJIRAKID/personal_gif_public/blob/main/Weather-Station.gif)
