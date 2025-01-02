# Port Scanner 👁️

This is a Python-based port scanner that allows you to scan a target or multiple targets for open ports. It's a simple yet powerful tool for network administrators and enthusiasts.

---

## Features 🔬
- Scan single or multiple targets.
- Specify the range of ports to scan.
- Clean output displaying open ports.
- Lightweight and easy to use.

---

## Requirements 🛠️
Ensure you have the following installed on your system:
- Python 3.x

To check if Python 3 is installed, run:
```bash
python3 --version
```

---

## Installation ⬇️
1. Clone the repository:
```bash
git clone https://github.com/mohammedmehdio/OpenPorts.git
```

2. Navigate to the project directory:
```bash
cd OpenPorts
```


3. Install the required library:
```bash
pip install termcolor
```

---

## Usage ⚙️
1. Run the script:
```bash
python3 OpenPorts.py
```

2. Input the targets you want to scan:
   - For a single target: Enter the IP or domain (e.g., `192.168.1.1`).
   - For multiple targets: Separate them with commas (e.g., `192.168.1.1, 192.168.1.2`).

3. Enter the number of ports to scan (e.g., `1000` to scan ports from 1 to 1000).

4. The script will display the open ports for each target.

---

## Example 📊
### Single Target Scan:
```bash
[*] Enter Targets To Scan (Split Them By  , ) : 192.168.1.1
[*] Enter how many Ports You Want To Scan : 100
```
**Output:**
```
Starting Scan For 192.168.1.1
[+] Port Opened 22
[+] Port Opened 80
```

### Multiple Targets Scan:
```bash
[*] Enter Targets To Scan (Split Them By  , ) : 192.168.1.1, 192.168.1.2
[*] Enter how many Ports You Want To Scan : 50
```
**Output:**
```
[*] Scanning Multiple Targets
Starting Scan For 192.168.1.1
[+] Port Opened 22

Starting Scan For 192.168.1.2
[+] Port Opened 80
```

---

## Notes ⚠️
- Ensure you have permission before scanning any network or system.
- Scanning ports without authorization may violate local laws or regulations.

---

## License 📜
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author 🔍
Developed by **Boudir Mohammed Mehdi**

Feel free to contribute, report issues, or suggest enhancements!

