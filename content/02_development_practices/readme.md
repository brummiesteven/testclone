![Banner](../../resources/WelcomeBanner.png)

- [Introduction](/../..)
- [Challenge 1: Visualise Work](../../content/01_visualise_work)
- Challenge 2: Development Practices
- [Challenge 3: Continuous Integration](../../content/03_continuous_integration)
- [Challenge 4: Security & Test Automation](../../content/04_security_and_test_automation)
- [Challenge 5: Automated Deployment & Continuous Delivery](../../content/05_automated_deployment)
- [Challenge 6: Monitoring & Feedback](../../content/06_monitoring_and_feedback)

# Challenge 02: Development Practices  
_Duration: XX minutes_  

In our challenge we will use our GitHub repository to version all code, configuration files, Infrastructure as Code or scripts. We will use Trunk-based development for the challenge as it has been shown to be a predictor for high performance in software delivery.  Fewer branches, short branch/fork lifetimes, avoid code freeze and merge debt.

GitHub flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly.  It involves protecting our main branch, making frequent, short lived branches and utilising Pull Requests to communicate and review code changes before merging and releasing.

Read more about GitHub flow [here](https://guides.github.com/introduction/flow/)

Microsoft Developer Division use a similar process they call `Release Flow` which differs slightly from `GitHub Flow` in how releases to production are completed.

Read more about Microsoft's Release Flow [here](https://docs.microsoft.com/en-us/azure/devops/learn/devops-at-microsoft/release-flow)

## Task 1: Branch Protection

- Familiarise yourselves with GitHub Flow and/or Release Flow and discuss how you will work with code changes and deployments in the project.  
- Document your approach to branching in a **CONTRIBUTING** file
- Review the options to protect the `main` branch and ensure that at least one review is required on all Pull Requests before they are merged to `main`

## Task 2: Required Review

- Add a **CODEOWNERS** file and update your branch protection to require a review from the relevant specialist or owner.

## Extension

- Write/install GitHub App to perform some action.  Possibly hosted in Azure Functions
- [GitHub Apps](https://docs.github.com/en/free-pro-team@latest/developers/apps)
- [Probot](https://github.com/probot/probot)

| :question: Can you host your GitHub app in Azure? :question: |
| --- |

# Resources

- [Setting guidelines for repository contributors](https://docs.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors)
- [Defining the mergeability of pull requests](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/defining-the-mergeability-of-pull-requests)  
- [About Pull Requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
- [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
- [About protected branches](https://docs.github.com/en/github/administering-a-repository/about-protected-branches)
- [About code owners](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners)
