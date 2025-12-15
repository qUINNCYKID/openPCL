# OpenPLC Control Logic Project

## Overview
This repository contains **OpenPLC program files** developed for simulation and educational use in **industrial automation and ICS lab environments**.  
The project is compatible with the **OpenPLC Runtime** and follows the **IEC 61131-3** standard.

---

## Technologies
- OpenPLC Runtime (v3)
- OpenPLC Editor
- IEC 61131-3 Languages:
  - Structured Text (ST)
  - Ladder Diagram (LD)
- Modbus TCP (optional)

---

## Project Structure\

openplc/
├── programs/
│ └── main_program.st / .ld
├── build/
│ └── generated_files
├── webserver/
│ └── project_configuration
└── README.md



---

## Requirements
- OpenPLC Runtime
- OpenPLC Editor
- Web browser (for OpenPLC Web UI)

Optional:
- Modbus client
- SCADA / HMI software

---

## Setup & Usage

### Load the Project
1. Open **OpenPLC Editor**
2. Import or open the project files
3. Compile the program

### Run (Simulation)
1. Start OpenPLC Runtime
2. Open the web interface:
http://localhost:8080


3. Start the PLC program

### Hardware Deployment (Optional)
1. Configure I/O mapping
2. Upload compiled logic
3. Start runtime on target device

---

## Monitoring
- OpenPLC Web Interface
- Modbus TCP clients
- External SCADA/HMI tools

---

## Security Notice
This project is intended for **educational and lab use only**.  
Do not deploy to production systems without proper OT security controls such as:
- Network segmentation
- Authentication
- Firewall rules
- Monitoring and logging

---

## Author
**Quindarius Booker**  
Computer Science & Cybersecurity  
Industrial Control Systems | OT Security

---

## License
Educational use only. Modify and use responsibly.
