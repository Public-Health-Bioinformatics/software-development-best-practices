Best Practices for Software Development
=======================================
Supporting Development of Quality Software Tools from Research to Operations
----------------------------------------------------------------------------

1. **An online version-control system must be integrated into the development process.**

For any codebase that is intended to be an ongoing project (not a one-time-use script), the code should be committed to an online version-control repository as early as possible. We normally use [GitHub](https://github.com) for this purpose. Codebases should be committed to online version control even if they are only being developed by a single developer. Each developer should have their own GitHub account, and they should also join the [Public-Health-Bioinformatics](https://github.com/Public-Health-Bioinformatics) GitHub organization . Developers are free to maintain code in their personal accounts as they see fit, but once a project is established, it should be transferred to the 'Public-Health-Bioinformatics' group and maintained according to these standards.

2. **Make a clear plan for software deployment.**

Make a plan for how your code will be installed/deployed onto the target platform. Use tools like conda and/or Docker to support simple deployment and updates. Make sure that your development environment is separate from the production environment. There should be a process in place to test, review and version the codebase before it is deployed to production. That process should be facilitated through GitHub or a similar online version control system.

3. **Use a continuous-integration testing system.**

A continuous-integration testing system allows developers to ensure that the quality and integrity of their systems are maintained while making changes to the codebase. For each commit, a set of tests are run against the new codebase to determine if any breaking changes have been made. This gives developers an opportunity to find and fix bugs before they are introduced into the master branch of the codebase. GitHub provides integrations for [TravisCI](https://travis-ci.org/) and [CircleCI](https://circleci.com/)

4. **Write simple, idiomatic code.**

Take some time to familiarize yourself with the style of code that is written for the programming language and domain of interest. Choose a well-respected style guide (Google has [style guides for several languages](https://github.com/google/styleguide)) and follow it as consistently as possible. When writing code, aim for clarity and readability. Add comments as necessary to clarify the higher-level strategy employed in a particular section of code.
