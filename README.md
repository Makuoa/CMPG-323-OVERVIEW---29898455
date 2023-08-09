# CMPG-323-OVERVIEW---29898455
CMPG 323 PROJECTS
## Repositories
-> Repository For Agile and Scrum project : CMPG-323-OVERVIEW---29898455/

## Diagram explaining how explaining project and repository context and how they are integrated
'''mermaid
graph TD;
CMPG 323 Projects ->Repositories;
Repositories -> Project 1;
Repositories -> Project 2;
Repositories -> Project 3;
Repositories -> Project 4;
Repositories -> Project 5;
POE -> Project 1;
POE -> Project 2;
POE -> Project 3;
POE -> Project 4;
POE -> Project 5;
Project 1 -> Projects;
Project 1 -> Issues;
Project 1 -> Code;
Code -> README.md;
Issues -> Labels;
Issues -> Milestones;
Milestones -> Project1SubmissionDeadline10August;
Milestones -> Project2SubmissionDeadline31August;
Milestones -> Project3SubmissionDeadline21September;
Milestones -> Project4SubmissionDeadline19October;
Milestones -> Project5SubmissionDeadline02November;
Milestones -> Exam(POE)SubmissionNoDeadline;
Projects -> TabularView;
Projects -> StatusView;
Projects -> SprintView;
Projects -> LinkedAssessmentView;
Projects -> TabularView;
Projects -> Backlog
Projects -> ByPriority;
TbularView -> PopulateTabularView;
TabularView -> Repository;
TabularView -> LinkedPullRequest;
PopulateTabularView -> Milestones;
PopulateTabularView -> Labels;
SprintView -> GroupedBySprint;
LinkedAssessmentView -> GroupedByLinkedAssessment;
StatusView -> GroupedByStatus;
ByPriority -> GroupedByPriority;



