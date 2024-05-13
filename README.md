## ConnectED: Bridging the Digital Divide with 5G, MEC, and VR Education

![logo](https://github.com/OliviaGrundman94/ConnectED-App/assets/100932591/25ae7e1d-a1dc-4c2f-b64b-981f6f2b257e)


ConnectED is an innovative educational platform designed to deliver immersive virtual reality (VR) learning experiences to students in Least Developed Countries (LDCs). By leveraging 5G technology and Mobile Edge Computing (MEC), ConnectED overcomes connectivity barriers and provides equitable access to high-quality educational content.

### Key Features

* **Offline VR:**  Stores and delivers VR content locally on a MEC server, eliminating the need for internet connectivity.
* **5G Connectivity:** Leverages 5G's high bandwidth and low latency for smooth, real-time VR interactions.
* **Curriculum-Aligned Lesson Plans:** Provides comprehensive lesson plans tailored to LDC educational standards.
* **User-Friendly Interface:** Designed for easy navigation and use by both teachers and students.
* **Open5GS Integration:** Utilizes Open5GS for core network functionality and network simulation.
* **Cost-Effective:** Minimizes hardware requirements, requiring only mobile devices at the school level.

### Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/[your-username]/ConnectED.git
   ```

2. **Install Dependencies:**
   ```bash
   cd ConnectED
   pip install -r requirements.txt
   ```

3. **Run the Server:**
   ```bash
   python server.py
   ```

4. **Access ConnectED:**
   - Open a web browser on a connected mobile device.
   - Navigate to `https://[your-server-ip-address]:5000`

### Project Structure

* `/content`: VR lesson plans and 3D models
* `/aframe`: A-Frame library and custom components
* `/server.py`: Python script for running the local server
* `/cert.pem`: SSL certificate for HTTPS (local development only)

### Technologies Used

* A-Frame
* Python
* Open5GS
* UERANSIM

### Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

