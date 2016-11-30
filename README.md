Note  everything is taking place in the directory ./workspace/farmers-css

Fork Pull Model: 
Introduction: 

Phase 1: 
Steps to branching. 
1. Determine if you should branch of silver or a branch of silver such as R12, R13... 
you can see which branhces are available by enterting the following command: 

git branch

2. Make sure you have the latest information for the branch you going to be branching off. 
git pull origin silver 


3. Follow forumla for branch name. 
BRANCH_NAME = ORIGIN_BRANCH#RallyTicketID For example 
BRANCH_NAME = silver#78239882476

3. Create the  local new branch
git checkout -b silver#78239882476

4. push branch to the cloud. Push every night before you go home. 
git push origin silver#78239882476

Phase 2:  Creating A Pull Request. 

1. Go to Github.com
2. Click 'New pull request' button

Every repository's Compare view contains two drop down menus: base and compare.

base should be considered the starting point of your comparison, and compare is the endpoint. During a comparison, you can always change your base and compare points by clicking on Edit.
Usually base should be silver or the release branch and compare should be the branch you worked on. 

3. Review changes. 

4. Add a comment. And Click  `Create pull request`.
Example of pull request: https://github.com/kamysz-farmers/farmers-css/pull/6/files

Now that you have created a pull request you  have the ticket peer reviewed.

Part 3: 

In this section we will talk about creating a Ralley ticket for code review 

1. Log into https://rally1.rallydev.com/ 
2.  Click on Portflio -> Portflio Items
3. Click f253
4. Click User Stories 
5. Click '+Add New
6.  New User Story: RALLY_TICKET_NUMBER_Code_Review
7. Click 'Add with Details. 
8. Initiative Pillar: Technical Project
9. Product: CSS- Customer SelfService.
8. In the description add the link to Pull Request in Github. 
9. Once done click 'Create' in the upper right hand coroner. 

In Github comments should be addded by the reviewer. Once the reviewer has agreeded the code is safe to be commited 
the 'Review changes'  click 'Approve'  -> Submit Review

Click 'Merge pull request'  to merge the pull request. 

Go back to Rally and close the ticket. 

If you branch of a release branch always merge back into the release branch and then into silver once you know the branch has been 
acccepted. 

To prevent issues make sure you update your branches before you go home everyday 

Please make sure that all merges go through GitHub 
Happy Coding!



Source: 
http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/
https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow
https://help.github.com/articles/comparing-commits-across-time/
