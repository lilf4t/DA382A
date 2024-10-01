# Netlogo

Programming Tasks for chapter 8
Chapter 8 is about "Working Together"! That applies to multi-agents as well as to you as developers. Hence, the following programming tasks are meant to be solved by you working together with different teams. It is up to you to decide on suitable ways of coordinating your coding; - task sharing in the contract net, - result sharing with joint intentions, or the common, less recommended way - trial and error.

Task 8.5

Main task: Organize a demonstration by frustrated citizens on the Town Square, using joint intentions and global information. The tasks by the individual groups are not completed until the maintask is working!

Subtask 1: Implement the core idea of a global shared hash table for the joint coordination of demonstrations. Citizen-agents can read and write to this global hash table. Meaningful information could be (needs to be investigated further):

the average level of frustration, anger and fear based on the information sent to the platform (OBS this is not necessary the same as the information that the observer is gathering and plotting on the user interface! The difference is that only already frustrated or angry agents will read and write to the global hash table.)
the number of agents ready to demonstrate, based on the information sent to the platform
a value indicating the willingness to go and demonstrate today (resets every day)
the decision to go and demonstrate now
...
Build a software interface to this global table in form of a global function that citizen agents can use to write and read to and from the table.

Subtask 2: Angry citizen-agents who in their proactive states decide between 'resignation' and 'demonstrating'. Then they :

report their values of frustration, anger and fear to the global hash table.
compare the average value from the global hash table with its own and decide to either resignate or to go into the 'demonstration' waiting mode.
In the demonstration waiting mode:
they indicate their willingness to demonstrate today by writing into the global hash-table. 
they wait and read the value from the global hash table to see if it is time to go and demonstrate. (You decide about the conditions when it is the right time!)
once it is time, they go and demonstrate
