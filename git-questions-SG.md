# 

---


## Questions to be resolved
- Scenario: two people are working in separate branches on separate files, call them contributor 1, working in file a, and contributor 2 working in file b.  Contributor #1 finishes their edit in file A and merges their branch into the main branch.  A day later contributor #2 finishes their edit and goes to merge their branch with the main.  But their branch has an old version of file A.  So when they go to merge - I assume a merge conflict will arise?  Is this true, or how does git / github protect against overwriting and other issues that will arise in this scenario
- How do you work with local databases that will differ in terms of access / data from other people?
- How do you protect credentials when using github.  For example database login information being used in code?
- I can envision different workflows for collaborating - one where everybody forks a repo to their own accounts, and works on them then initiates pull requests with their changes.  The other where everybody has access to and creates branches of the main repository.  Can the difference of these and their pros and cons be explained, or perhaps, more likely, this is an inaccurate understanding of how collaboration in Github works.