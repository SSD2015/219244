**Date:** 20 Feb 2015

I emailed and spoke to Aj. Panpiti to clarify some requirements.
This is one of them.

**Question:** Should voters be required to walk around and view projects before voting?  Some teams have created a requirement that the voter enter a code (or QR code) from each contestant's (team's) exhibit before they can judge that team.

Aj. Panpiti's Answer:

> Hard question!  ... I want students enjoy walking and watching friends' work rather 
> than wasting time and struggling on slow voting process.  
> [If its a requirement] the system could have a non-queue, fast-and-easy 
> checking at each booth. 
> QR code scanning might be efficient and fast enough to be used as a check point; 
> however, I am not sure it will work efficiently when they deploy it.  
> Theoretically, they should propose a method with response time and queue time.

**Requirement Change:**

As instructor, I decide that we should handle it like this:

* the application is not required to have a way of forcing voters to verify they have visited
the projects, such as entering a code.
* if you want to create a feature like this, that's fine. But the event administrator
(aka the Election Committee) should have a way of enabling/disabling this via admin UI before or during the voting.
If the administrator disables this feature, then it does not appear on the client's user interface.
* an implementation of this feature should be fast and easy to use.
