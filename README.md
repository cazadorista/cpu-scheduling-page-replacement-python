# OS Algorithm Simulator

A Python-based implementation of fundamental Operating System algorithms covering **CPU Process Scheduling** and **Memory Page Replacement**.

---

## 🚀 Implemented Algorithms

### 1. Process Scheduling (`processScheduling.py`)
*   **Shortest Job First (SJF)**: Non-preemptive scheduling algorithm that selects the waiting process with the smallest execution time.
*   **Round Robin (RR)**: Preemptive scheduling algorithm where each process is assigned a fixed time quantum in a cyclic order.

### 2. Page Replacement (`pageReplacement.py`)
*   **Least Frequently Used (LFU)**: Replaces the page that has been used the least number of times.
*   **Least Recently Used (LRU)**: Replaces the page that has not been referenced for the longest period of time.

---

## 📂 Project Structure

```text
├── processScheduling.py     # CPU scheduling logic (SJF & RR)
├── pageReplacement.py       # Page replacement logic (LFU & LRU)
├── processes.txt            # Input data for process scheduling
├── rr.txt                   # Input data for Round Robin (includes quantum)
├── sjf.txt                  # Input data for SJF
├── pages.txt                # General configuration/pages input
├── lfu.txt                  # Input data for LFU
└── lru.txt                  # Input data for LRU
```
## ⚙️ How to Run
1. Clone the repository:
  ```bash
    git clone https://github.com/cazadorista/cpu-scheduling-page-replacement-python.git
    cd os-algorithm-simulator
  ```

2. Run the process scheduling simulation:
  ```bash
    python processScheduling.py
  ```

3. Run the page replacement simulation:
  ```bash
  python pageReplacement.py
  ```

Results will be automatically generated and saved into respective output text files (e.g., sjfResults.txt, rrResults.txt, lfuResults.txt, lruResults.txt)
