# GitHub Repository Hygiene Recommendations :sweat_drops:

A document on GitHub recommended Repository Hygiene, what do we considered part of Repo-Hygiene and what should you use to maintain it. 

There are multiple ways to look at Repository Hygiene and we do not claim to have the "one size fits all" solution, it depends on what you consider your "hygiene" priorities, but we do want to point out some very important (useful) areas that can help you when you need to decide how to keep things clean.

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



||Checks|Description|Hygiene Task*|
|---|---|---|---|
|**Security**||||
||Dependabot Alerts (GHAS)|Monitor vulnerabilities in dependencies used in your project and keep your dependencies up-to-date|GitHub Platform feature / User configurable|
||Code Scanning (GHAS)|Use code scanning to find security vulnerabilities and errors in the code for your project|GitHub Platform feature / User configurable|
||Secret Scanning (GHAS)|Scanning repositories for known types of secrets|GitHub Platform feature / Admin configurable|
||Secret Push Prevention (GHAS)|Use secret scanning to prevent supported secrets from being pushed into your repository|GitHub Platform feature / Admin configurable|
|**Protection**||||
||Teams|Repository access permissions|GitHub Platform managed / Admin configurable|
||Branch Protection|Control how people can interact with branches in your repository|GitHub Platform feature / Admin configurable|
||Branch Limits|Limit the overall number of Branchces in a Repository|GitHub App/Action managed|
||Stale Branch Limits|Limit the number of Branches with no activity over the defined period of time|GitHub App/Action managed|
||.gitignore|Prevent the push of specific files at the GIT level|GitHub App/Action managed / User configurable|
||Repository Policies||GitHub Platform managed|
|||||
|**Standards**||||
||Issue Templates|Templates and forms to create standardized collaboration|PR check for template files|
||Pull Request Templates|Standardize Pull Request description content|PR check for template files|
||Default Community Health Files||PR check for health files|
|||||


\* How to set it up and how to maintain it for Repo-Hygiene


## Repository Hygiene and Trust-Level

In GitHub Organization owners have the same control over a Repository as the Repo owners or Repo adminstrators. Many of the policy features show here allow for modifications on an adminstrator level.
If you want to enforce Repo-Hygiene standards even for that access level, you would need to use Apps or Actions to control this.
Keep in mind that using GitHub WebHook events are reactionary and do not prevent the intial push to a Repository.
The process here is,

- Detect
- Report
- Correct

