# pullreq_ci
The dataset of our FSE2015 submission, which can be used to study the influence of CI adoption in GitHub. 

##Data description
The data is presented in CSV format and can be directly imported in R.

all_projects.csv: The summary of all the raw projects. 
* `n_pr`: Total number of pull requests;
* `n_ci_after`: Number of pull requests received after CI adoption;
* `n_ci_after_tested`: Number of pull requests tested by CI; 

team_productivity.csv: The data of productivity study in project level.
* `ci_age_month`: the relative time of CI adoption in months, ranging from −12 to +12;
* `proj_age`: Project age in month at that time;
* `n_pr_open`: Number of pull requests received during that month;
* `n_pr_core`: Number of pull requests submitted by core developers;
* `n_pr_merged`: Number of pull requests have been merged into the master branch;
* `n_pr_unmerged`: Number of pull requests have been rejected;
* `n_core_merged`: Number of pull requests, which are submitted by core developers, have been merged into the master branch;
* `n_core_unmerged`: Number of pull requests, which are submitted by core developers, have been rejected;
* `team_size`: Number of developers on the project’s core team at that time;
* `test_files & test_loc`: Number of test files and the number of source lines of code in test files;
* `src_files & src_loc`: Number of source files and the number of source lines of code in source files;
* `n_star`: Number of stars received by the project’s main repository at that time;
* `n_fork`: Number of project forks at that time;

project_quality.csv: The data of quality study.
* `n_issues`: Number of issues received during that month;
* `n_tag_issues`: Number of issues tagged by developers;
* `n_bug_issues`: Number of bug related issues;
* `n_core_issues`: Number of issue submitted by core developers;
* `n_core_bugs`: Number of bug related issues submitted by core developers;

We will publish our programs later, which can be used to analyse our dataset.

