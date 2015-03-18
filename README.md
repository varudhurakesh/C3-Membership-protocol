# C3-Membership-protocol
This code implements a membership protocol in a emulated Peer to Peer network

To compile the code, 
run make.

To execute the program, 
from the program directory run: ./Application testcases/<test_name>.conf. 
The conf files contain information about the parameters used by your application

There is a grader script Grader.sh. It tests the implementation of membership protocol in 3 scenarios and grades each of them on 3 separate metrics. The scenarios are as follows:
1. Singlenodefailure
2. Multiplenodefailure
3. Single node failure under a lossy network

Prerequisites:
1. C++11 (gcc version 4.7 and onwards).
2. Python 2.7 version



