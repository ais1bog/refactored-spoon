DESCRIPTION:
Autonomous AI-enabled local network monitoring system.
Automatically detects devices, analyzes them, and provides technical advice via a local neural network.

QUICK START:
1. Unzip the archive:
tar -xzvf strazh_v1.0.tar.gz
2. Enter the folder and run the installation:
cd Strazh_Project && sudo bash setup.sh
3. Enable aliases:
source ~/.zshrc

MANAGEMENT COMMANDS:
- boss: View the current device table (MAC/IP/Status).
- ask 'question': Ask a technical question to the AI ​​module (Ollama).
- find 'target': Quickly collect host information via Lynx/Nmap.
- start-spy: Start the monitoring daemon in the background.

IMPORTANT:
The Ollama service must be running for the AI ​​to function.
The monitoring script requires sudo privileges to operate the interface.
