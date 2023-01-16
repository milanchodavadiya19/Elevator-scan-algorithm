# Elevator-scan-algorithm

SCAN (Elevator) algorithm 
In SCAN disk scheduling algorithm, head starts from one end of the disk and moves towards the other end, servicing requests in between one by one and reach the other end. Then the direction of the head is reversed and the process continues as head continuously scan back and forth to access the disk. So, this algorithm works as an elevator and hence also known as the elevator algorithm. As a result, the requests at the midrange are serviced more and those arriving behind the disk arm will have to wait.

The distance is used to store the absolute distance between the head and current track position. disk_size is the size of the disk. Vectors left and right stores all the request tracks on the left-hand side and the right-hand side of the initial head position respectively. 
