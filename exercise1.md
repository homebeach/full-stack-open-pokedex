Let's assume that the application is coded with Python. 

For linting Python, popular tools are Pylint and Flake8. Flake8 combines functions of multiple tools such as pyflakes and pycodestyle.These tools help to automate and enforce style guidelines for projects following PEP 8 standards.

For testing, Pytest if one the most popular choices. It is flexible and has an extensive plugin ecosystem. Unittest. which is built into Python and nose2 are good options for large projects. Test automation is central to CI, as it ensures each change is validated and doesn’t break existing functionality.

Python does not need to be built as it is interpreted language. However, CI setups often involve creating virtual environments, packaging applications, and preparing dependencies. There are tools like setuptools and poetry to help package the code for deployment and manage dependencies.

In addition to Jenkins and GitHub Actions, GitLab CI and CircleCI are popular choices, offering extensive support for Python projects. Travis CI also has strong integration with GitHub, and Bitbucket Pipelines is a good option for teams using Bitbucket repositories.

Cloud-based CI solutions, like GitHub Actions, are easy to set up, scalable, and minimize infrastructure maintenance, making them ideal for small to medium-sized teams such as a team of 6 people. However, if the project involves sensitive data, has strict compliance requirements, or requires custom environments, a self-hosted setup may be more appropriate. When choosing between the two, it’s essential to understand factors like data sensitivity, team size, budget constraints, and specific project needs. If there is no need for additional security, compliance or custom environments cloud based solution would be faster and easier for 6 people to get application released soon.