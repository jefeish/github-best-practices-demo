# GitHub Repository Hygiene Recommendations :sweat_drops:

A document on GitHub recommended Repository Hygiene, what do we considered part of Repo-Hygiene and what should you use to maintain it. 

There are multiple ways to looks at Repository Hygiene and we do not claim to have the "one size fits all" solution, it depends on what you consider your "hygiene" priorities, but we do want to point out some very important (useful) areas that can help you when you need to decide how to keep things clean.

:warning: We purposely don't go too deep in to the 'how' of the Repo-Hygiene, since the implementation can heavily depend on individual company standards. 

---

## :bulb: Keep a clean Repository clean = Repo-Hygiene!

 The task to get a Repository in to "clean" state is a pre-requirement. 
 The Repository-Hygiene process goal is to maintain a clean environment.

### The scope of **Repo-Hygiene** for this document

  ![hygiene](images/repo-hygiene.png)
  
  |Security|Protection|Standards|
  |---|---|---|
  |Ensure that no secrets and <br>no vulnerabilities get committed|Enforce collaboration policies|Compliance rules to maintain a clean Repository|

---

## :bulb: Templates + Policies + Standards = Repo-Hygiene



||Checks|Description|Hygiene Task|
|---|---|---|---|
|**Security**||||
||Dependabot Alerts|Monitor vulnerabilities in dependencies used in your project and keep your dependencies up-to-date|GitHub Platform feature / User configurable|
||Code Scanning||GitHub Platform feature / User configurable|
||Secret Scanning||GitHub Platform feature / User configurable|
||Secret Push Prevention||GitHub Platform feature / User configurable|
|**Protection**||||
||Teams|Repository access permissions|GitHub Platform managed|
||Branch Protection|Control how people can interact with branches in your repository|GitHub Platform feature / Admin configurable|
||Branch Limits|Overall number of Branchces in a Repository|GitHub App/Action managed|
||Stale Branch Limits|A Branch with no activity over the defined period of time|GitHub App/Action managed|
||.gitignore|Prevent the push of specific files at the GIT level|GitHub App/Action managed|
||Repository Policies||GitHub Platform managed|
|||||
|**Standards**||||
||Issue Templates|Templates and forms to create standardized collaboration|PR check for template files|
||Pull Request Templates|Standardize Pull Request description content|PR check for template files|
||Default Community Health Files||PR check for health files|
|||||


