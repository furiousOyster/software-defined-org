# software-defined-orgs
Infrastructure is better as software.  Organizations too.

# Goals
1. Work towards an API style interaction with Helix, to support the Helix1, Helix2, HelixN as BTL builds its partner networks
1. Formalize all the interactions of all the departments, so that any shortfalls or advice can be applied holistically
1. Measure performance of all individuals, so that bonuses can be applied
1. There should be no difference in how we treat external expenditure and how we treat our own staff
1. All acitivities must be either contribute to selling, or building something to sell - anything not moving these goals forwards must be stopped instantly
1. This system should be simple enough that it could be run with paper cards - the system encourages thoughtfulness and economy of communication beyond trying to generate huge volumes of data as a substitue for knowledge
1. As few queues as possible, but one queue per team of specialists
1. The `code` that runs the org should be transparent to all.  The `state` resulting from that execution should be permissioned.

# Execution
Code is the rules of any system.  State is what results from that execution.
To implement the SDO or any part thereof, fork the base repository, then mutate state through git commits following the rules of operation.
When a new version of the SDO comes out, pull request it over to update the code.

# Config
The code of the org is the same throughout all instances, and is an attempt to capture and define fundamental business practices and decision making where the sole aim of a business is to match supply with demand.

The instancing of an org or faction of an org will necessarily have slightly different parameters depending on the exact situation.  These parameters are represented in the [CONFIG](./CONFIG.md) file.

All the operating code that can be tuned in this way will refer to the config file.s
# File formats and Housekeeping
All formats

# Queues, functions, and work
All functions have a queue of work.

# Features
Orgs ultimately have features that matter to their users.  Users of an org are:
1. Customers
5. Staff
3. Shareholders
The purpose of all orgs is to supply demands - this is called sales - an org is measured on how quickly it can identify demand and supply it with as little of its own resources as possible - this is margin maximization

Features are met by functions.

The overall functionality of an org is always measured by Sales.  Therefore everything within an org can be measured relative to increasing sales performance.

Unless we can measure the change, we're not going to implement it.

1. Personnel Competency Program
   1. Series of skills the company values that personnel possess
   1. Career path to help those who want more competencies to attain them

# Functions that fulfill the Features of the SDO and dependencies
1. Market awareness 
1. Contacts
1. Prospects
   1. Contacts
1. Work
1. Recruiting
   1. Contacts
1. Sales
   1. Market awareness
1. Demand forecasting
   1. Market awareness
1. Core dev
   1. Market awareness
   1. Sales
1. Factory Dev (Soviet)
   1. Core dev
   1. Platform dev
   1. App dev
1. App dev (Helix dev)
1. Core R&D
   1. Demand forecasting
1. Accounting
   1. Sales
1. Command

## Types of Job in our system
1. Product Definition
1. Product Planning
1. UI Planning
1. System Planning
1. UI Building
1. System Building
1. Assembly


# Data
As software is used, it creates data.  Data MAY be mixed with logic in some circumstances.  In this case, we separate the configuration of the org from the running data, but use the same repository.  Each instanciation of the SDO forms a Fraction, which is the execution of the SDO code in a specific region.  There are 4 levels of data:
1. Global SDO - Code that governs the operation of the organism PUBLIC
1. Fraction Intel - Data generated from executing governing code - this is the business knowledge PRIVATE
1. Fraction Source - Source code resulting from the output of the dev machine PRIVATE
1. Fraction HR - Sensitive personnel data PRIVATE

## Data Objects


# Function execution time
All functions, as a rule, execute on the global clock, which is normally 2 weeks.

# Message passing
All inputs to all functions are tickets / issues, which result in a change of state as the output of the function, and possibly more tickets passed to other functions.  This is so the messages can be audited and queue length analyzed.  Tickets can include dependencies so there is a call stack.

# Fractions and visibility
1. Fleet Command
1. BTL
1. Helix
1. Helix2
1. Helix3

# Issues
Tickets serve two purposes here:
1. Highlighting faults in the configuration or performance of the org.  This will include requests for new features / capabilities of the org
1. Highlighting faults in the execution of the org - ie: the data contained within the org

# Structure of the SDO code
One md file per feature of the SDO.  This md file describes how to fulfill that feature - inputs, outputs, dependencies, formats, metrics.

# Changelog
Each sprint close, we publish a changelog describing the changes that have been applied in the last sprint in two parts:
1. Changes to the org config
1. Changes to the execution of the org: ie: the data that changed within the org

# Roadmap
Here we describe what features of the org will be delivered when, what features are in progress, and briefly describe why they are need.  We also talk about what features will see sunset.

# UNSORTED
## Interbit modelled using git
Any interbit system can be modeled using github repo permissions, issues, and git commits.

> `issues === actions`

> `commits === blocks`

> `prs, branches, merges === chain forks and merges`

> `git submodules === read joins`

> `ability to create issues === write join access`

Revenue is generated ONLY by apps.  Apps are not built by BTL.  Apps need an environment around them to allow their production.  BTL resources are only deployed on things that support the production of the highest revenue generating apps, and nothing else.

## A note on humanity
It is very important to draw the distinction between the functions required by the organization, and the human beings supplying those functions.  The functions are cold and precise, but the humans warm and approximate.  We encourage humans to rotate functions periodically, and value most continual improvement in clean execution of function, and strict adherence to the cross function API that makes the organization work.  
