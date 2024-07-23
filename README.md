# College-Mess-wifi-admin

To achieve a seamless Wi-Fi experience with a single SSID and automatic switching between your TP-Link and D-Link routers, you need to configure them in a specific way. Here's a step-by-step guide:

1. **Set Up the Main Router (Router 1)**:
   - Connect your main router (the one connected to the internet) to your computer.
   - Access the router's admin interface (usually by entering the router's IP address in a web browser).
   - Configure the SSID (Wi-Fi network name), password, and other settings as desired.
   - Note the channel number (e.g., 1, 6, 11) used by this router's Wi-Fi network.
   - Save the settings and ensure the internet is working.

2. **Set Up the Secondary Router (Router 2)**:
   - Connect the secondary router to your computer.
   - Access the router's admin interface.
   - Change the LAN IP address of the secondary router to avoid conflicts with the main router. For example, if your main router's IP is `192.168.1.1`, set the secondary router's IP to `192.168.1.2`.
   - Disable the DHCP server on the secondary router to prevent it from assigning IP addresses (the main router will handle this).
   - Set the same SSID and password as the main router.
   - Set the Wi-Fi channel to a different non-overlapping channel from the main router (e.g., if the main router is on channel 1, set the secondary router to channel 6 or 11).
   - Save the settings.

3. **Connect the Routers**:
   - Use an Ethernet cable to connect one of the LAN ports on the main router to one of the LAN ports on the secondary router (do not use the WAN port on the secondary router).

4. **Placement**:
   - Place the routers in different locations to cover a larger area.
   - Ensure the Ethernet cable connecting them is long enough to place the secondary router where additional coverage is needed.

5. **Testing**:
   - Connect to the Wi-Fi network and move around the coverage area to ensure seamless switching between the routers.
   - Devices should automatically connect to the router with the strongest signal.

By following these steps, your devices will see a single SSID and automatically switch to the router with the best signal, providing better connectivity throughout the coverage area.
