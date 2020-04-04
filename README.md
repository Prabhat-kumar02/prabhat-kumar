longest remaining time first(lrtf)


Algorithm –

Step-1: Create a structure of process containing all necessary fields like AT (Arrival Time), BT(Burst Time), CT(Completion Time), TAT(Turn Around Time), WT(Waiting Time).

Step-2: Sort according to the AT;

Step-3: Find the process having Largest Burst Time and execute for each single unit. Increase the total time by 1 and reduce the Burst Time of that process with 1.

Step-4: When any process have 0 BT left, then update the CT(Completion Time of that process CT will be Total Time at that time).
