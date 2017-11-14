# Architecture: The key to modern app success
# info
Brent Edwards
@brentledwards
gitub.com/brentedwards
brentedwards.net

* MyVote dev goals
** distributed team effectivly used
** well designed architecture, works across many platforms
** Maintainability, maximize code reuse

* foundation, Layered Architecture
** organize app code, test plans and execution, development team
** organize your team to focus on strengths
** Manage complexity to by grouping related functions and have things in isolation
** layers communicate

* Logical layers
** break apps up, provides maintainability, readability, flexibility, resure, etc.

* N-Layer Architecture
** Presentation layer -> Presentation Logic -> business Logic -> data access -> data
** Program to the interface to reduce coupling

* Physical Tiers
** deploy logical layers to physical tiers
** trade offs -> performance, scalability, fault tolerance, security
** Data access could be seperate logical layer on different physical layer
** validation on client and server side is good

* CSLA .Net business object framework [cslanet.com]
