# hello-world-refresher
This is a refresher on how to use github by redoing the hello-world exercise.


This is the first series of edits. 

The goal is to make a first series of edits. Then make another branch called "second series" or something.
Then test out merging the first series into the master branch and merge the master branch
into the "second series" branch so i can practice using github.


This is a second series of edits.


The idea here is to make a branch of the original hello-world-refresher repository,
then create a branch of first edits. 
Then create a branch of second edits. 
Merge the first edits into the master repository, 
them merge the master repository (now with first edits) into the second edits branch. 
Finally I want to merge the 2nd edits into the master repository.


Final Merge:

BOTTOM LINE: ON GITHUB DOT COM, WHEN MAKING A PR (A Pull request, which could just as easily be known as a "merge request")

BASE = FROM
COMPARE = TO

IT APPARENTLY IS DIFFERENT ON EVERYWHERE ELSE -- including GIT...for reasons.


What happened was this. I merged the First-edits branch into the Master, and deleted the First-edits branch.

Then I tried to merge the master (which had the new first edits) into the Second-edits branch. 
I had set "Base" as being Second-edits and "Compare" as being the Master branch.
It prompted me to change the master. 
I didn't want to do that. I simply wanted the updates to master to be included in the Second-edits branch.

Tried again, same prompt.

Made a copy of Master Branch called Master-Copy-Two or something. 
Tried to merge the Copy of Master-Copy-Two into Second-edits.
Set MC2 as Compare, and 2nd edits as Base.
It copies the changes of 2nd edits into MC2 

This is the OPPOSITE of what I wanted.

Made another copy of Master Branch called Master-Copy-Three.

THIS TIME: Set MC3 as BASE, and 2nd edits as COMPARE.

It worked, but everyone on discord said it isn't "the correct" way. Apparently blah blah blah. On Git it works differently.
For "reasons".

--Congratulations you just made it over your first hurdle in your journey to learn how to collaborate on code. Yay!
