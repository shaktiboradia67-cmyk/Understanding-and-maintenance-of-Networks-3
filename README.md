# Understanding-and-maintenance-of-Networks-3
# Q1.Log in to your home Wi-Fi router's admin panel using its default IP address (usually 192.168.0.1 or 192.168.1.1) and take a screenshot of the login page.<br><br><em><strong>Hint:</strong> If you don't know your router's IP, open Command Prompt and run 'ipconfig' — look for 'Default Gateway'.</em>
Ans.>
## Scenario: Setting Up a Gaming Café Network

### Network Setup

Imagine I am setting up a small gaming café with 8 gaming PCs for IPL streaming and multiplayer gaming.

First, I would connect the ISP (Internet Service Provider) line to the modem or ONT, and then connect it to the **WAN port of the router**. The router provides internet access and manages traffic between the café's local network and the internet.

Next, I would connect one of the router's LAN ports to an **Ethernet network switch**. Then, I would connect all 8 gaming PCs to the switch using Ethernet cables.

### Network Diagram

ISP Line → Modem/ONT → Router → Network Switch → 8 Gaming PCs

### Justification

1. **Router:** Connects the café's network to the internet and routes data between the local network and external networks.
2. **Network Switch:** Provides enough Ethernet ports to connect all 8 gaming PCs, even if the router has only a few LAN ports.
3. **Ethernet Cables:** Provide stable, low-latency connections that are suitable for multiplayer gaming and reliable IPL streaming.
4. **Performance:** A Gigabit Ethernet switch and a suitable internet plan help support multiple gaming sessions and video streams simultaneously.

### Conclusion
# Q2.Find and note down the current IP address, subnet mask, and default gateway assigned to your laptop or mobile device when connected to your Wi-Fi network.
Ans.>
## Task: Accessing the Wi-Fi Router Admin Login Page

### Objective
To find the router's default gateway IP address and open its admin login page.

### Procedure

1. Connect the computer or laptop to the home Wi-Fi network.
2. Open Command Prompt by pressing `Windows + R`, typing `cmd`, and pressing Enter.
3. Type the following command:

   ```bash
   ipconfig
   ```

4. Find the **Default Gateway** under the active Wi-Fi or Ethernet adapter. It is commonly `192.168.0.1` or `192.168.1.1`.
5. Open a web browser and enter the gateway IP address in the address bar.
6. The router's administrator login page should appear.
7. Take a screenshot of the login page for the practical record.

### Screenshot

Insert your own screenshot of the router admin login page here.

**Result:** The router's admin login page was accessed using the default gateway IP address.

I would connect the router to the ISP connection first, followed by a network switch, and then connect all 8 gaming PCs to the switch. This setup provides reliable internet access and efficient communication between the gaming PCs.
