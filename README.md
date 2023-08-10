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
Repository -> Repositories;

## Branching strategy
-> Github Flow Strategy. It is a lightweight, branch-based workflow. It focuses on Agile principles and so it is a fast and streamlined branching strategy with short production cycles and frequent releases, it also allows for quick feedback loops which makes it easier for one to identify issues and resolve them.

## .gitignore file
-> the .gitignore file is going to list the names of files that can be found in work-trees when working on the project, but should not be committed to the project(e.g sensitive information about the user)

## Storage of credentials and sensitive information
-> Credentials will be encrypted and stored in a .gitignore file which will not be committed to github to avoid licks.



