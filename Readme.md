# Git revert will keep commit history but it is also dangerous  



## Case: revert unwanted branch merge commit(catch up)



## revert-a-faulty-merge (You must read it!! Very important!!)
https://github.com/git/git/blob/master/Documentation/howto/revert-a-faulty-merge.txt

### People comment/soltuion
1. https://stackoverflow.com/questions/19379034/force-merge-after-reverting-merge-commit-int-git
 ```
 David Deutsch: There is no way to force a merge; indeed, reverting the revert is the correct way to do it. 
 ```


2. https://stackoverflow.com/questions/1078146/re-doing-a-reverted-merge-in-git
```
So from a technical angle, there's nothing wrong with reverting a merge, but from a workflow angle it's something that you generally should try to avoid.

If at all possible, for example, if you find a problem that got merged into the main tree, rather than revert the merge
```




