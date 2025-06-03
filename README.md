
# 🔧 MAC Address Changer (Python)

A simple Python tool to change the MAC (Media Access Control) address of a network interface on Linux-based systems.

## 📌 Features
- Change the MAC address of any network interface.
- Lightweight and easy to use.
- Works directly from the command line.

## 🛠️ Requirements
- Python 3.x
- `ifconfig` (usually available via the `net-tools` package)

## ⚙️ Installation
Make sure Python and `ifconfig` are installed on your system.

```bash
sudo apt update
sudo apt install net-tools
```

Clone the repository:

```bash
git clone https://github.com/ehumairsaeed/mac-changer.git
cd mac-changer
```

Make the script executable (optional):

```bash
chmod +x mac_changer.py
```

## 🚀 Usage

```bash
sudo python3 mac_changer.py -i <interface> -m <new_mac_address>
```

### 🔄 Example

```bash
sudo python3 mac_changer.py -i eth0 -m 00:11:22:33:44:55
```

## ⚠️ Notes
- You **must** run the script with `sudo` or as root to change MAC addresses.
- This tool is for **educational** and **ethical hacking** purposes only. Do not use it for malicious intent.

## 📁 Example Output

```
[+] Changing Mac Address for eth0 to 00:11:22:33:44:55
[+] Successfully Changed
```

## 📄 License
MIT License
