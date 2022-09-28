Python:
Some common steps in a CI setup include linting, testing, and building. 
What are the specific tools for taking care of these steps in the ecosystem of Python?
    linting tool: Pylint
    testing tool: PyUnit/UnitTest
    building tool: PyBuilder

What alternatives are there to set up the CI besides Jenkins and GitHub Actions?
    There are lot of different kind of alternatives for Jenkins ang GitHub Actions.
    Here is a list of some of them:
        GitLab
        Atlassian Bamboo
        JFrog Pipelines
        Spinnaker
        JetBrains TeamCity
        AWS CodePipeline
        Azure DevOps Server (formerly Microsoft Team Foundation Server)
        Maven and Gradle
        CloudBees CI (formerly CloudBees Core)

Would this setup be better in a self-hosted or a cloud-based environment? 
Why? What information would you need to make that decision?
    When choosing between a self-hosted or a cloud-based environment. In general, 
    the most important information about the project is the size. If you have a small to medium software project
    that doesn't have any special requirements, a cloud-based solution is probably best. 
    The configuration is simple and you don't need to go to the hassle or expense of setting up your own system.
     
    For larger projects where more resources are needed or in larger companies where there are multiple teams
    and projects to take advantage of it, a self-hosted CI setup is probably the way to go.