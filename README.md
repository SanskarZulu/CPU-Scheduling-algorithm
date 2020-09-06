# CPU-Scheduling-algorithm
C++ Implementation of the following algorithms:

1. Non-Preemptive:FCFS and SJF
with their respective Gantt Charts
2. Preemptive: Round Robin

Output: 
Problem 1: Solved by FCFS and SJF respectively.


                        OS CPU Process Scheduling Assignment
                                By Sanskar Sharma
                                 PRN 0120180381
        Enter the number of processes: 4

                Enter the process 1 name: Task1

                Enter the arrival time of process 1 : 2

                Enter the burst time of process 1 : 3

                Enter the process 2 name: Task2

                Enter the arrival time of process 2 : 4

                Enter the burst time of process 2 : 2

                Enter the process 3 name: Task3

                Enter the arrival time of process 3 : 5

                Enter the burst time of process 3 : 1

                Enter the process 4 name: Task4

                Enter the arrival time of process 4 : 7

                Enter the burst time of process 4 : 4

        Choose an Algorithm to schedule the processes:
                Non-Preemptive Algorithms:
                  1. First Come First Served (FCFS).
                  2. Shortest Job First (SJF).
                Preemptive Algorithms:
                  3. Round Robin Algorithm.
        4. Exit
        Enter your choice: 1
*******************First Come First Served Algorithm*******************

        Process:        :Turnaround Time: Waiting Time

        Process: Task1  :       3       :       0
        Process: Task2  :       3       :       1
        Process: Task3  :       3       :       2
        Process: Task4  :       5       :       1

                Gantt Representation of FCFS algorithm is as follows:
                Order of processes is as follows: Task1-->Task2-->Task3-->Task4
                2 _ _ _5 _ _7 _8 _ _ _ _12
                        Average Waiting time is: 1
                        Average Turn Around time is: 3.5
        Choose an Algorithm to schedule the processes:
                Non-Preemptive Algorithms:
                  1. First Come First Served (FCFS).
                  2. Shortest Job First (SJF).
                Preemptive Algorithms:
                  3. Round Robin Algorithm.
        4. Exit
        Enter your choice: 2
*******************Shortest Job First Algorithm*******************

        Process:        :Turnaround Time: Waiting Time

        Process: Task1  :       3       :       0
        Process: Task3  :       1       :       0
        Process: Task2  :       4       :       2
        Process: Task4  :       5       :       1

                Gantt Representation of SJF algorithm is as follows:
                Order of processes is as follows: Task1-->Task3-->Task2-->Task4
                2 _ _ _5 _6 _ _8 _ _ _ _12
                        Average Waiting time is: 0.75
                        Average Turn Around time is: 3.25
        Choose an Algorithm to schedule the processes:
                Non-Preemptive Algorithms:
                  1. First Come First Served (FCFS).
                  2. Shortest Job First (SJF).
                Preemptive Algorithms:
                  3. Round Robin Algorithm.
        4. Exit
        Enter your choice: 4

--------------------------------
Process exited after 87.25 seconds with return value 0
Press any key to continue . . .

Problem 2: Solved by Round Robin


                        OS CPU Process Scheduling Assignment
                                By Sanskar Sharma
                                 PRN 0120180381
        Enter the number of processes: 4

                Enter the process 1 name: Task1

                Enter the arrival time of process 1 : 1

                Enter the burst time of process 1 : 4

                Enter the process 2 name: Task2

                Enter the arrival time of process 2 : 2

                Enter the burst time of process 2 : 3

                Enter the process 3 name: Task3

                Enter the arrival time of process 3 : 3

                Enter the burst time of process 3 : 5

                Enter the process 4 name: Task4

                Enter the arrival time of process 4 : 4

                Enter the burst time of process 4 : 7

        Choose an Algorithm to schedule the processes:
                Non-Preemptive Algorithms:
                  1. First Come First Served (FCFS).
                  2. Shortest Job First (SJF).
                Preemptive Algorithms:
                  3. Round Robin Algorithm.
        4. Exit
        Enter your choice: 3

                Enter the time slice/quantum for RR algorithm: 2
*******************Round Robin Algorithm*******************

        Process:        :Turnaround Time: Waiting Time

        Process: Task1  :       9       :       5
        Process: Task2  :       9       :       6
        Process: Task3  :       13      :       8
        Process: Task4  :       15      :       8

                        Average Waiting time is: 6.75
                        Average Turn Around time is: 11.5
        Choose an Algorithm to schedule the processes:
                Non-Preemptive Algorithms:
                  1. First Come First Served (FCFS).
                  2. Shortest Job First (SJF).
                Preemptive Algorithms:
                  3. Round Robin Algorithm.
        4. Exit
        Enter your choice: 4

--------------------------------
Process exited after 48.91 seconds with return value 0
Press any key to continue . . .

