# nm-mesh-tool
Connect to 802.11s networks with NetworkManager

NetworkManager supports connections to 802.11s mesh networks, but the related tools such as nmtui do not.

This tool automates the process of scanning for and connecting to a mesh Wi-Fi network.

To use, simply download the script, and make it executable with

```https://raw.githubusercontent.com/dB-SPL/nm-mesh-tool/refs/heads/main/nm-mesh-tool
chmod +x nm-mesh-tool
./nm-mesh-tool```

Once you have sucessfully connected to a network, it will persist across reboots and automatically reconnect at startup.
