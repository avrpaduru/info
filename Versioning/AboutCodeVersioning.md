**<span style="color:Green">Q. What is version control?</span>**

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter.

**<span style="color:Green">Q. What happens if we don't use version control?</span>**

Software teams that do not use any form of version control often run into problems like not knowing which changes that have been made are available to users. Or the creation of incompatible changes between two unrelated pieces (may be worked by 2 people) of work that must then be reworked. If you're a developer who has never used version control, you may have added versions to your files with suffixes like "final" or "latest" and then had to later deal with a new final version. Perhaps you've commented out code blocks because you want to disable certain functionality without deleting the code, fearing that there may be a use for it later. Version control is a way out of these problems.

**<span style="color:Green">How does version control works?</span>**

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

Software developers working in teams are continually writing new source code and changing existing source code. The code for a project, app or software component is typically organized in a folder structure or "file tree". One developer on the team may be working on a new feature while another developer fixes an unrelated bug by changing code, each developer may make their changes in several parts of the file tree.

Version control helps teams solve these kinds of problems, tracking every individual change by each contributor and helping prevent concurrent work from conflicting. Changes made in one part of the software can be incompatible with those made by another developer working at the same time. This problem should be discovered and solved in an orderly manner without blocking the work of the rest of the team.

**<span style="color:Green">Benefits of version control systems</span>**

1. A complete long-term change history of every file. This means every change made by many individuals over the years. Changes include the creation and deletion of files as well as edits to their contents. This history also includes the author, date and written notes on the purpose of each change. Having the complete history enables going back to previous versions to help in root cause analysis for bugs and it is crucial when needing to fix problems in older versions of software.
2. Branching and merging: A branch is technically a copy of the source code. One can create a branch from the source code and work independently on their own branch (this means they are working on a copy of the source code instead of directly making changes to the main source code). Creating a "branch" in VCS tools keeps multiple streams of work independent from each other while also providing the facility to merge that work back together by merging their code separately to the main source code. This enables developers to verify that the changes on each branch do not conflict. If developer A merged his/her code to main source code prior to developer B, then developer B is not allowed to merge their code main source code unless he/she updates their code with the latest main source code (this is usally done by pulling the latest changes and resolving conflicts from the latest code if there are any). If you are thinking about the scenario where two or more branches getting merged at the same fraction of second, then forget about that scenario :P It won't happen, only one merge at a time and others will be blocked
3. Traceability: We can connect a version control tool to project management tools like Jira and trace the exact changes that were made to achieve a given functionality/requirement. You can learn more about tracing the code later when you dig deep about how branching and merging works (like using commits and pull requests).


**<span style="color:Gray">References:**</span>
https://stackoverflow.com/questions/7249871/what-is-a-build-tool