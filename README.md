# chef

# chef

**what is chef?**
chef is a configuration management tool
	
**what is configuration management tool?**
	It is maintain number(100 and 1000's) of machines with automation.

**what is maintain?**
	It maintain the system resources such as
	1)Install a application
	2)Configuration
	3)Updates
	4)Maintain and so on..

**Why Configuration management tool?**
	-> reduce management complexity
	-> save time

**configuration management tools?**
	puppet ------> 2005		pull mechanism
	chef 	--------> 2008		pull mechanism
	ansible ------> 2011		push mechanism

Infrastructure as a code
-------------------------
->chef ensures each node compiles with policy.
->policy determined by the configurations in each node's runlist.
->reduce management complexity through abstraction.
->your policy states what state each resource should be in.

**what is resource?**
	Resource is a piece of system and it's desired state.

file---> create,delete
user---> create,delete
package--> install/not


managing complexity
-------------------
1)organization
2)environment
3)roles
4)nodes
5)recipes
6)cookbooks
7)runlist

**1)Organization**
	It is independent tenant.
	eg: companies, department.
**2)Environment**
	environment reflect your patterns and workflow, and can be used to model the life stages of your applications.
	->development env
	->testing env
	->staging env
	->production env

**3)Roles**
	Roles represents the type of servers in your infrastructure.
	-> LB server
	-> web server
	-> DB server
**4)Nodes**
	Nodes represents the servers  in your infrastructure, it could be a physical server or virtual server.
	Could also be a network hardwares, switches, routes, etc...
**5)Receipe**
	Receipe is a collection of resources
	file creation, installing app
**6)Cookbooks**
	Collection of receipes and templates and custom resources..
**7)Runlist**
	runlist is a collection of cookbooks, and every machine has it's own runlist.




	
