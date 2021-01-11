![Banner](../../resources/WelcomeBanner.png)

- [Introduction](/../..)
- [Challenge 1: Visualise Work](../../content/01_visualise_work)
- [Challenge 2: Development Practices](../../content/02_development_practices)
- Challenge 3: Continuous Integration
- [Challenge 4: Security & Test Automation](../../content/04_security_and_test_automation)
- [Challenge 5: Automated Deployment & Continuous Delivery](../../content/05_automated_deployment)
- [Challenge 6: Monitoring & Feedback](../../content/06_monitoring_and_feedback)

# Challenge 03: Continuous Integration  
_Duration: XX minutes_  

Continuous integration is the first step towards continuous delivery.  Branches should be short lived and code integrated with the main branch regularly (use feature flags if necessary).  Every code change should trigger a build and execute required checks (linting/unit testing) and any errors/issues fixed immediately.  

In our GitHub Flow process we will build the code that is proposed for merging to `main` and execute 

## Task 1: Build every Pull Request

a) Create a new GitHub Actions workflow (or integrate another CI tool) and build code.

b) Edit the workflow to only build on the submission of a Pull Request to the main branch

c) Add a manual trigger to the workflow

## Task 2: Publish to GitHub Packages/Container Registry

- Workflow to deploy built package

**TODO** Check that app will be containerised 

## Extension 

- Create a Workflow which will add a comment (or gif perhaps?) to any Issue which is labeled with the label `Hello`

| :question: Can you think of any other fun things to do with Actions Workflows? :question:|
| --- |

## Resources

- [About continuous integration](https://docs.github.com/en/free-pro-team@latest/actions/guides/about-continuous-integration)
- [GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
- [GitHub Learning Lab: Continuous integration with GitHub Actions](https://lab.github.com/githubtraining/github-actions:-continuous-integration)
