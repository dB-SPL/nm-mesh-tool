# nm-mesh-tool
Connect to 802.11s networks with NetworkManager

NetworkManager supports connections to 802.11s mesh networks, but the related tools such as nmtui do not.

This tool automates the process of scanning for and connecting to a mesh Wi-Fi network.

Your Wi-Fi adapter (and its driver) must support 802.11s mesh.  To see if your hardware includes mesh support, use the `iw list` command, and look in the "Supported Modes" section for "mesh point".

Once you have sucessfully connected to a network, it will persist across reboots and automatically reconnect at startup.

To use, simply download the script, and make it executable with

```
wget https://raw.githubusercontent.com/dB-SPL/nm-mesh-tool/refs/heads/main/nm-mesh-tool
chmod +x nm-mesh-tool
./nm-mesh-tool
```
