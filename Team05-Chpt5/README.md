# NetLogoDev
 
Programming Tasks for Chapter 5

Task 13. 
1) reactive behavior with subsumption:
- citizens walking to a destination, escaping from cops, prisoned (finite state machine)
- additional proactive behavior with hybrid architecture:deciding to either go to university or expresso house (finite state machine)
 

We will need a hybrid agent architecture for our project that combines the reactive behavior with the proactive behavior of our citizens- and cops agents. The purpose of the two programming sessions in this week is to find out possible ways to implement this with NetLogo.

There are three major challenges that we need to investigate and solve:

1. How to implement the subsumption hiearchy for reactive behaviors, so that:
the agent can perceive its environment and react with appropriate actions in critical situations
the reactive actions are executed in the right order, e.g. higher priority actions before lower priority ones, at all time
the committment to an intention should play a role whether or not an action should repeatedly be executed or not.
2. How to implement a hybrid agent architecture that combines the reactive behavior from the subsumption hierachy with the proactive behaviors, so that:
the proactive part is only entered if there are no more reactive actions that need to be executed
the actions from the proactive part need to be coordinated with the actions from the reactive part. In the vertically layered hybrid architecture this means that the actions from the proactive part are executed in the reactive part. For the horizontally layered hybrid architecture some 'mediator' or 'control system' will be needed.
3. The agents need to react in real-time, meaning that their 'decision making loop' needs to be as short as possible, so that changes in their environment, brought about by other agents, can be detected in time. For the implementation in NetLogo, this means that:
Only one action (reactive or proactive) per agent is allowed per to-go loop.
the environment of an agent needs to be perceived in every loop and beliefs and actions need to be updated to react on new situations, but-
- intentions to which the agent is committed to should be perceived until the reason for the committment no longer is valid.
- this means that if higher-priority actions need to be executed before the action belonging to a committed intention, then the action belonging to the committed intention should be reactivated again.
