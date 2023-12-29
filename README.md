# RitikReport


### **Major Protocols:**

1. **HTTP Live Streaming (HLS):**
   - **Overview:** Developed by Apple, HLS breaks the video into small chunks and uses HTTP for delivery.
   - **Advantages:** Adaptive streaming, wide compatibility.
   - **Considerations:** Higher latency compared to some other protocols.

2. **Dynamic Adaptive Streaming over HTTP (DASH):**
   - **Overview:** An adaptive streaming protocol standardized by MPEG.
   - **Advantages:** Adaptability to changing network conditions, interoperability.
   - **Considerations:** Complex to implement compared to simpler protocols.

3. **Real-Time Messaging Protocol (RTMP):**
   - **Overview:** Originally developed by Adobe, RTMP is designed for low-latency live streaming.
   - **Advantages:** Low latency, real-time interaction.
   - **Considerations:** Declining support due to the rise of other protocols.

4. **WebRTC (Web Real-Time Communication):**
   - **Overview:** A free, open-source project that provides web browsers and mobile applications with real-time communication.
   - **Advantages:** Low latency, real-time bidirectional communication.
   - **Considerations:** May require additional server infrastructure.

### **How Video Streaming Works:**
The process involves encoding the video into various quality levels, transmitting it to a server, and then distributing it to viewers. Adaptive streaming adjusts the quality based on the viewer's internet speed.

### **Adaptive Streaming:**
Adaptive streaming dynamically adjusts the quality of the video based on the viewer's network conditions, providing a smoother viewing experience. HLS and DASH are popular adaptive streaming protocols.

### **Comparison of Protocols:**
- **Latency:** RTMP often has the lowest latency, suitable for real-time interactions.
- **Adaptability:** HLS and DASH excel in adapting to varying network conditions.
- **Browser Compatibility:** HLS is widely supported, while DASH is more adaptable but may require additional configurations.


