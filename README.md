# CT1-PPS-041
Q1. Problem Description:
Nathan has the following two types of taxis:
OLA taxi: It can be booked by using an online application from phones Fastrack taxi: It can be booked anywhere on the road
The CLA taxis cost 'Oc' for the first 'Of km and 'Od' for every km afterward. The Fastrack taxis travel at a speed of 'Cs' km per minute.
The cost of Fastrack taxis are 'Cb', 'Cm', 'Cd'and that represents the base fare, cost for every minute that is spent in the taxi, and cost for each kilometer that you ride.
You are going to the office from your home. Your task is to minimize the cost that you are required to pay.
The distance from your home to the office is D. You are required to select whether you want to use OLA or Fastrack taxis to go to your office. If both the taxis cost the same, then you must use an online taxi.
Constraints:
1 <= D,Oc,Of,Od,C₁,Cb, Cm,Cd <= 10^9
Input Format:
First line: Single integer 'D' that denotes the distance from your house to the office
Next line: Three integers Oc, Of, and Od
Next line: Four integers Cs, Cb, Cm, and Cd
Output Format:
If Nathan selected an OLA taxi to travel, then print a string OLA Taxi.
Otherwise, print the string Fastrack Taxi
