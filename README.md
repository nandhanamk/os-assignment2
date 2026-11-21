# OS Scheduling Visualizer

## 1. Introduction

The OS Scheduling Visualizer is a web-based application developed using HTML, CSS, and JavaScript.

It helps students understand and visualize different Operating System scheduling algorithms. It displays the scheduling process, calculates total head movement, and compares the performance of different algorithms.

## 2. Objectives

- To understand disk scheduling algorithms.
- To understand CPU scheduling algorithms.
- To calculate total disk head movement.
- To calculate waiting time and turnaround time.
- To visualize scheduling using graphs and Gantt charts.
- To compare different scheduling algorithms.

## 3. Technologies Used

- **HTML:** Creates the structure of the web page.
- **CSS:** Provides styling and design.
- **JavaScript:** Implements scheduling algorithms and calculations.
- **Canvas:** Displays the disk seek graph.

## 4. Features

### Part A: Disk Scheduling

The application implements five disk scheduling algorithms:

1. FCFS (First Come First Serve)
2. SSTF (Shortest Seek Time First)
3. SCAN
4. C-SCAN
5. LOOK

Features:
- Enter disk size.
- Enter initial head position.
- Enter disk request queue.
- Select scheduling algorithm.
- Select disk direction.
- Display service sequence.
- Calculate total head movement.
- Compare all algorithms.
- Display seek graph.
- Next, Previous and Auto Play options.

### Part B: CPU Scheduling

The application implements two CPU scheduling algorithms:

1. FCFS (First Come First Serve)
2. SJF (Shortest Job First – Non-preemptive)

Features:
- Add process ID.
- Enter arrival time.
- Enter burst time.
- Calculate completion time.
- Calculate waiting time.
- Calculate turnaround time.
- Display average waiting time.
- Display average turnaround time.
- Display Gantt chart.

## 5. Project Structure

```text
OS Scheduling Visualizer/
│
├── index.html
└── README.md
```

## 6. How to Run the Project

1. Install Visual Studio Code.
2. Create a folder named OS Scheduling Visualizer.
3. Create an HTML file named index.html.
4. Copy the project source code into index.html.
5. Save the file.
6. Open the HTML file using Google Chrome or Live Server.
7. Enter the required input values.
8. Select an algorithm and click Run.

## 7. Sample Input

**Disk Scheduling**

- Disk Size: 200
- Initial Head Position: 50
- Request Queue: 82, 170, 43, 140, 24, 16, 190
- Direction: Right

**Expected Output**

| Algorithm | Head Movement |
|---|---:|
| FCFS | 642 |
| SSTF | 208 |

## 8. Advantages

- Easy to understand and use.
- Provides visual representation of scheduling.
- Helps compare different algorithms.
- Reduces manual calculation.
- Useful for Operating System students.

## 9. Limitations

- The application runs in a web browser.
- CPU scheduling supports only two algorithms.
- The project does not use a database.
- Results are limited to the algorithms implemented.

## 10. Future Enhancements

- Add more CPU scheduling algorithms.
- Add Round Robin scheduling.
- Improve graph animations.
- Add downloadable result reports.
- Add user login and database support.

## 11. Conclusion

The OS Scheduling Visualizer provides an easy way to learn and understand disk and CPU scheduling algorithms. It helps students observe scheduling operations, calculate performance values, and compare different algorithms through visual representation.

This project is developed as part of the Operating Systems assignment.