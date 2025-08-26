In this file we create a python program and it minor project
🕒 Digital Clock using Tkinter
📌 Overview
This project is a lightweight digital clock built with Python's Tkinter library. It displays the current time in HH:MM:SS format and updates every second. The interface is styled with a black background and cyan-colored digits for a sleek, modern look.
🚀 Features
- Real-time clock display
- Auto-updating every second
- Minimalist GUI design
- Custom font and color styling
- Fixed window size for consistency
🧱 Requirements
- Python 3.x
- Tkinter (usually included with Python)
📦 Installation
No installation required beyond Python. Just clone or download the script and run it:
python digital_clock.py


🧠 How It Works
- Tk() initializes the main application window.
- Label() creates a text widget to display the time.
- time.strftime("%H:%M:%S") fetches the current system time.
- after(1000, update_time) schedules the update_time function to run every 1000 milliseconds (1 second), refreshing the clock.
🎨 Customization
You can tweak:
- font=("Helvetica", 40) to change font style or size
- fg="cyan" to change text color
- bg="black" to change background color
- geometry("300x100") to resize the window
📸 Screenshot
(You could include a screenshot of the clock window here if available)
📄 License
This project is open-source and free to use under the MIT License.


