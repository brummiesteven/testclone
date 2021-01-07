![Banner](../../resources/WelcomeBanner.png)

- [Introduction](../..)
- [Challenge 1: Visualise Work](../../content/01_visualise_work)
- Challenge 2: Development Practices
- [Challenge 3: Continuous Integration](../../content/03_continuous_integration)
- [Challenge 4: Security & Test Automation](../../content/04_security_and_test_automation)
- [Challenge 5: Automated Deployment & Continuous Delivery](../../content/05_automated_deployment)
- [Challenge 6: Monitoring & Feedback](../../content/06_monitoring_and_feedback)

# Challenge 01: Development Practices  
_Duration: XX minutes_  
_Docs:_ 
_[Defining the mergeability of pull requests](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/defining-the-mergeability-of-pull-requests)_  
_[About Pull Requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests)_  

In our challenge we will use our GitHub repository for all version control, storing any code, IaC or scripts. We will use Trunk-based development for the challenge as it has been shown to be a predictor for high performance in software delivery.  Fewer branches, short branch/fork lifetimes, avoid code freeze and merge debt.

GitHub flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly.  It involves protecting our main branch, making frequent, short lived branches and utilising Pull Requests to communicate and review code changes before merging and releasing.

Read more about GitHub flow [here](https://guides.github.com/introduction/flow/)

## Task 1: Branch Protection

- Understand GitHub Flow
- Protect **main** branch

## Task 2: Required Checks

- Required Build using GitHub Actions or other
- Codeowner review

## Other things to work into this section

- Dependabot
- Codespaces/Liveshare
- Repository Members and permissions
- Repository Visibility
- GitHub Teams
- Integration with Microsoft Teams

## Extension

- Write/install GitHub App to perform some action.  Possibly hosted in Azure Functions
- [GitHub Apps](https://docs.github.com/en/free-pro-team@latest/developers/apps)
- [Probot](https://github.com/probot/probot)

| :warning: Can you host your GitHub app in Azure? |
| --- |

# Resources

- [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
- [Resource](https://github.com)
- [Resource](https://github.com)
- [Resource](https://github.com)
