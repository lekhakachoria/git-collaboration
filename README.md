#Both merges above are fast-forward merges. Explain.

Fast forward merges are one branch catching up to another. Merge conflicts should only occur when you have the exact same lines changed and are merging them back into the same branch.

# b. In your own words, write down a scenario that will involve a merge conflict between develop and conflict_branch. 
#Add your answer to readme.doc

A merge conflict between develop and conflict_branch would be where you modify the title in index.html to have different content for both and attempt to merge the conflict_branch back into develop. 

Alex made a commit on line 12 in conflict branch for an h2 entry, Muli did the same on line 12 in develop, after muli merges there will be a conflict because they are on the same line.

# c. In your own words, write down a scenario that will NOT involve a merge conflict between develop and conflict_branch 
#despite some change on the same file on both branches.

a merge that will not involve a conflict between develop and conflict would be where you added some differing content in both
and merged each. E.g. you added a <p> in one and <h2> in the other

An edit in line 14 in develop merge with a change on conflicts branch made on line 15; no conlficts

