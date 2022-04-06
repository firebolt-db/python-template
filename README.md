# Template for Firebolt Python repositories

This template is designed to quickly setup new Python repositories for Firebolt connectors.

It includes:
* Suggested direcotry structure.
* pre-commit hooks and set of linter rules.
* Fossa and SonarCloud setting files.
* CONTRIBUTING.MD
* gitignore file.

## After the setup

Once a new repository is setup remember to tailor it to the project:
1. Populate project information in setup.cfg
1. Create SonarCloud project and add its key to sonar-project.properties
1. Add a License

The rest of functionality should work out of the box with the recommended settings and sets of rules. However, each project is different so feel free to customise the relevant configs.
