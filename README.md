# ij-grdl-cmp-incl-not-showing
Repro of IntelliJ problem with gradle composite project

**What steps will reproduce the issue?**

1. Clone the repository: `git@github.com:AlexCzar/ij-grdl-cmp-incl-not-showing.git`
2. In IntelliJ open `ij-grdl-cmp-incl-not-showing/app-multi-module/build.gradle.kts` as project
3. wait for everything to be imported, maybe sync manually to be sure


**What is the expected result?**

`lib-multi-module` and its modules should be shown in the Project view.

**What happens instead?**

Only app-multi-module modules are shown in the Project view.

