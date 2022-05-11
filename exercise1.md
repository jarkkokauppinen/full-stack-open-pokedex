Let's assume that an application is made up with Java.

LINTING

There are many options for linting Java code. Most linters aren't better or worse than others, but there are certainly some differences in debugging, error-checking, and issue prevention for example. To mention a few: Lightrun, PMD, Uncrustify, Error Prone, Tattletale, UCDetector, Coala and Checkstyle, which is propably the most popular linter available.

TESTING

Like Jest in JavaScript, Java has a testing framework called JUnit. A JUnit test case is exactly what it sounds like: a test scenario measuring functionality across a set of actions or conditions to verify the expected result.

BUILDING

Maven is a popular Java build automation tool. One common option for Maven is Gradle. Both of these tools takes care of compiling, dependency management, automated tests and packaging app for deployment.

SETTING UP CONTINUOUS INTEGRATION

For setting up CI, besides Jenkins and GitHub Actions, the following CI/CD platforms are popular: GitLab, Atlassian Bamboo, JFrog Pipelines, Spinnaker, JetBrains TeamCity, AWS CodePipeline and Azure DevOps Server.

But how to choose the right continuous integration tool?

If you are self-hosting your CI/CD systems, you will be responsible for making infrastructure decisions, keeping the underlying servers healthy by servicing hardware and patching software, and ensuring the services are available, secure, and performing adequately.
When someone else manages your CI/CD pipeline, you have less control, but in general it could be better choice because of its ease.
