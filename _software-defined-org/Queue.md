# Queues
Queues can have two items:
1. Light items - all the info required to do these are in the queue item itself
1. Heavy items - info required is linked to from the queue - typically jobs of 4 hours or more warrant this type of depth of description

Queues have one - and only one - queuemaster.  This is the disptcher of tasks and is ultimately responsible for flow.  The dispatchers rulings regarding the queue are final.

Queues have a set of rules that govern 
1. what can be placed on them
   1. what format is required
1. when things can be placed on them
1. Who manages them
1. who can service them
1. who the queuemaster is

## Types of Queue
1. Expense processing - booking travel, purchasing equipement
1. External support - law and accounting requests
1. Docs
1. Product Definitions
## Queue Example for Core Planning
> Queue depth items: 43 items  
> Queue weight hours: 503hrs

1. CORE-53 Spec Crypto
1. CORE-23 Spec Test Harness
1. CORE-12 Spec network io object
1. RnD--10 