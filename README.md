# PRIYA-AI NORMAL VERSION
EMOTIONAL FRIEND USING GEMINI FREE API KEY
she can make your notes and talk and also she can motivate you with voice 


How the Downloaded Application Controls Your PC on Kali & Windows
When you click "DOWNLOAD FULL REPO (.ZIP)" in the Project Files tab, the downloaded package now includes the standalone Python desktop automation suite:
How It Works:
actions/mouse_control.py: Controls your actual PC mouse pointer (moving to coordinates, left click, right click, double click, dragging, scrolling, and typing) using pyautogui and xdotool.
actions/computer_control.py: Automatically launches your desktop applications (Wireshark, QTerminal, Burp Suite, Metasploit, Nmap) and executes terminal commands under your orders.
main.py: The interactive execution engine that takes your typed or voice orders and dispatches the mouse/terminal actions on your operating system.
Built-in Fail-safe: Standard pyautogui.FAILSAFE = True protection is enabled—moving your physical mouse cursor to any corner of the screen immediately pauses/aborts actions so you always maintain physical control over your machine.
3. Step-by-Step Instructions to Run on Your PC
On Kali Linux:
Extract the downloaded ZIP:
code
Bash
unzip priya_kali_sentinel_project.zip -d priya_sentinel
cd priya_sentinel
Run the automated setup (installs xdotool, python3-tk, and Python libraries):
code
Bash
sudo python3 setup.py
Run Priya:
code
Bash
chmod +x run.sh && ./run.sh
# Or directly:
  python3 main.py
On Windows:
Right-click the downloaded .zip file and select Extract All.
Open PowerShell or Command Prompt in that extracted folder.
Run setup:
code
Cmd
    python setup.py
Run Priya:
code
Cmd
  run.bat
# Or directly:
python main.py
Once started, Priya runs in your terminal, greets you, and executes desktop mouse movements, clicks, application launches, and terminal commands upon your order.
