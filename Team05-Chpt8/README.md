# Netlogo

Programming Tasks for chapter 8
Chapter 8 is about "Working Together"! That applies to multi-agents as well as to you as developers. Hence, the following programming tasks are meant to be solved by you working together with different teams. It is up to you to decide on suitable ways of coordinating your coding; - task sharing in the contract net, - result sharing with joint intentions, or the common, less recommended way - trial and error.

Task 8.5
Subtask 2: Angry citizen-agents who in their proactive states decide between 'resignation' and 'demonstrating'. Then they :

report their values of frustration, anger and fear to the global hash table.
compare the average value from the global hash table with its own and decide to either resignate or to go into the 'demonstration' waiting mode.
In the demonstration waiting mode:
they indicate their willingness to demonstrate today by writing into the global hash-table. 
they wait and read the value from the global hash table to see if it is time to go and demonstrate. (You decide about the conditions when it is the right time!)
once it is time, they go and demonstrate
