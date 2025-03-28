# California-Reservoirs-Data-Car-Sounds-Dashboard-
CMPE 273 Hackathon

### Project Overview:
We have been assigned two projects focusing on scalable enterprise distributed architectures:

1. **State Reservoir Water Department**:
    - Transition from a legacy architecture to a modern distributed architecture.
    - Build a simple, user-friendly interface that integrates existing water data sources into the new distributed system.

2. **Automobile Company**:
    - Develop a scalable distributed architecture to capture and monitor safety equipment and conditions within vehicles.
    - Specifically utilize motor sound detection to meet safety and regulatory standards required by the state for vehicle approval.

---

### Data and Model Details:

- **Dataset Used**: DCASE 2021 Task 2 (unsupervised anomalous sound detection dataset).
- **Purpose**: Detect normal and anomalous motor sounds from machinery, especially "Car" sounds, under realistic and varying environmental conditions.
- **Available Data**:
    - Sound clips (~10 sec each) categorized by normal/anomalous states.
    - Different machine types (fan, gearbox, pump, slide rail, Car, Train, valve).
    - Source domain (normal conditions) and target domain (shifted/realistic conditions).

---

### Tasks to be Done Clearly:

#### Step 1: **Water Department Project**
- Design and implement a modern, distributed backend architecture using microservices.
- Develop interfaces (e.g., REST APIs) for consuming and integrating legacy data sources.
- Provide a user-friendly dashboard or web interface for end-users to visualize and interact with water resource data.

#### Step 2: **Automobile Company Project**
- Leverage the existing pre-trained motor sound detection model from the DCASE 2021 dataset.
- Implement an anomaly detection pipeline specifically tailored for "Car" audio clips.
- Create a scalable backend service to process audio data in real-time or batch processing scenarios, identifying anomalies.
- Develop a monitoring dashboard/interface for visualizing the state of safety equipment and anomaly detection status.

---

### Deliverables:
- **Distributed Architecture Designs**: Documentation clearly showing system design (microservices, databases, message queues, cloud services used).
- **Integration of Data Sources**: Demonstration that legacy data can be seamlessly integrated into the new architecture.
- **Interactive Dashboards**:
    - **Water Department**: Interface to monitor reservoir and water resource data.
    - **Automobile Company**: Dashboard for real-time visualization of motor sound anomalies indicating vehicle safety equipment status.
- **Documentation and Deployment Scripts**

