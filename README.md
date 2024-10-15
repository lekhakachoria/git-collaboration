#Both merges above are fast-forward merges. Explain.

Fast forward merges are one branch catching up to another. Merge conflicts should only occur when you have the exact same lines changed and are merging them back into the same branch.

# b. In your own words, write down a scenario that will involve a merge conflict between develop and conflict_branch. 
#Add your answer to readme.doc

Alex made a commit on line 12 for an h2 entry, Muli did the same, and there will be a conflict because they are on the same line.

A merge conflict between develop and conflict_branch would be where you modify the title in index.html to have different content for both
and attempt to merge the conflict_branch back into develop. 

# c. In your own words, write down a scenario that will NOT involve a merge conflict between develop and conflict_branch 
#despite some change on the same file on both branches.

a merge that will not involve a conflict between develop and conflict would be where you added some differing content in both
and merged each. E.g. you added a <p> in one and <h2> in the other

