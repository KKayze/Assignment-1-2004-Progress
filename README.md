# Assignment-1 FIT2004 Algorithms and Data Structures


A deeper understanding of the implementation of  Dynamic Programming, Dijkstra Algorithm, Greedy Force Algorithm, Breadth-First Search Algorithm and Heap with constrictions of complexity. The approach of code is using the bottom-up approach while being aware about the Auxiliary Space and Time complexity.


Question 1 brief description - Ultimate Fuse
In FITWORLD, adventurers can fuse FITMONs, magical creatures with varying cuteness_scores, to create the ultimate, cutest FITMON. The input is a list of FITMONs, each with three values: affinity_left, cuteness_score, and affinity_right. The fusing process involves adjacent FITMONs, and the cuteness_score of the resulting FITMON is calculated using the given formula, taking into account the affinities and cuteness_scores of the fusing FITMONs. The challenge is to implement a function, fuse(fitmons), that fuses all FITMONs into one with the highest possible cuteness_score. The solution must handle a worst-case complexity of O(N^3) time and O(N^2) space. Examples demonstrate the fusion process and validate the solution's correctness.



Question 2 brief description - Escape from Delulu Forest
You are a bear trapped in Delulu Forest, seeking the fastest way to escape. The forest is represented as a graph of trees connected by roads, with specific trees serving as start points and exits. Some trees, called Solulu trees, must be destroyed to break the forest's seal, enabling escape. The destruction of Solulu trees may also teleport you to another tree.

The task involves implementing a TreeMap class that initializes with roads and Solulu trees. The class must support an escape method to find the quickest escape route, considering travel times and the need to destroy exactly one Solulu tree. The method returns the total time and route taken or None if no valid route exists. The solution should handle various scenarios and optimize the escape route, adhering to specified time and space complexities.




