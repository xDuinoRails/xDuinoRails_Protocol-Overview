### Model Railway Protocol & System Comparison

| Feature | **Motorola** | **mfx** | **DCC (Base)** | **DCC + RailCom** | **Selectrix (SX)** | **s88** | **XpressNet** | **LocoNet** | **BiDiB** | **SUSI** | **JMRI** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Primary Type** | Track Protocol | Track Protocol | Track Protocol | Track Protocol | Track Protocol & Bus | Feedback Bus | Layout Bus | Layout Bus | Layout Bus | Decoder Interface | Software Suite |
| **Standard** | Proprietary | Proprietary | **Open** | **Open** | **Open** | Proprietary | Proprietary | Proprietary | **Open** | **Open** | **Open Source** |
| **Data Direction** | 1-Way | **2-Way** | 1-Way | **2-Way** | Partial (Bus is 2-Way) | 1-Way | **2-Way** | **2-Way** | **2-Way** | **2-Way** (Local) | **2-Way** (to HW) |
| **Data Rate** | Low | Medium | Low | Low | Medium | Very Low | Medium | Medium | **Very High** | Medium | High (via USB) |
| | | | | | | | | | | | |
| **Loco Address Space** | Low (80) | High (16k) | High (10k) | High (10k) | Medium (112/10k) | N/A | N/A (Bus) | N/A (Bus) | N/A (Bus) | N/A | Manages All |
| **Speed Steps** | Low (14) | High (128) | High (128) | High (128) | Medium (31/127) | N/A | N/A (Bus) | N/A (Bus) | N/A (Bus) | N/A | Manages All |
| **Function Count** | Low (F0-F4) | High (32+) | High (F0-F28) | High (F0-F28) | Medium (F0 / F0-F15) | N/A | N/A (Bus) | N/A (Bus) | N/A (Bus) | N/A | Manages All |
| | | | | | | | | | | | |
| **Loco Auto-Registration** | No | **Yes** | No | **Yes** | No | N/A | N/A | N/A | N/A | N/A | **Yes** (If HW supports) |
| **Real-Time Loco Data** | No | **Yes** | No | **Yes** | No | N/A | N/A | N/A | N/A | N/A | **Yes** (If HW supports) |
| **Layout Feedback (Sensors)** | No (Needs s88) | No (Needs s88) | No (Needs Bus) | No (Needs Bus) | **Yes (SX-Bus)** | **Yes (Only)** | **Yes (RS-Bus)** | **Yes** | **Yes** | N/A | **Yes** (Reads bus) |
| | | | | | | | | | | | |
| **Service Track (R/W)** | Partial | N/A (Params) | **Yes** | **Yes** | **Yes** | N/A | N/A (Bus) | N/A (Bus) | N/A (Bus) | Partial (via Decoder) | **Yes (DecoderPro)** |
| **POM (Write on Main)** | Partial | **Yes** | **Yes** | **Yes** | **Yes** | N/A | N/A (Bus) | N/A (Bus) | N/A (Bus) | Partial (via Decoder) | **Yes** |
| **POM (Read on Main)** | No | **Yes** | No | **Yes** | No | N/A | N/A | N/A | N/A | Partial (via Decoder) | **Yes** (If HW supports) |
| | | | | | | | | | | | |
| **Topology** | Star (Track) | Star (Track) | Star (Track) | Star (Track) | Daisy-Chain (Bus) | Daisy-Chain | Daisy-Chain | Daisy-Chain | Daisy-Chain | Point-to-Point | Star (PC) |
| **Device Communication** | Master/Slave | Master/Slave | Master/Slave | Master/Slave | Peer-to-Peer (Bus) | Master/Slave | Master/Slave | Peer-to-Peer | Peer-to-Peer | Master/Slave | N/A (Software) |
