# Schedular

This Schedular segments your tasks against their allocated time and alerts you on time lapse.

## Installation & Setup

This project uses Python's built-in `time` module, so **no external dependencies are required**.

### Prerequisites
* Python 3.6 or higher

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Schedular
   cd Schedular
   ```

2. **(Optional) Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Run the script:**
   ```bash
   python main.py
   ```


## Usage 
* Takes your tasks against their allocated hours
* Schedules them out on a scale of importance and difficulty 
* It tracks your time and how long to take on tasks
* Alerts you on time lapse and reminds you on the next task to take. 
* Holds in place your completion percentage of every task and kick starts right there 
when you restart your schedular against tasks


```sh
import time

start_time = time.perf_counter()

# Your event or code goes here
time.sleep(1.5) 

end_time = time.perf_counter()
elapsed_time = end_time - start_time

print(f"Elapsed time: {elapsed_time:.4f} seconds")
```
