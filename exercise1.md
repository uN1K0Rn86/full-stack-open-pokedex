# Discussion - Development in Python

## Linting, Testing and Building

The linter I was previously most familiar with was pylint. It is easy to use and configure, and highly customizable. While searching for alternatives, the one that stood out the most was Ruff. Apparently it is extremely fast and can save large amounts of time for bigger projects. The saved time translates to saved money when CI/CD is run in the cloud.

There are several frameworks available for testing. Unittest, like the name implies, is good for unit testing and is included in the standard python installation. Pytest is a separate framework that offers a more readable and flexible alternative. For end-to-end testing, Robot framework is a good alternative.

Like the material mentioned, python takes care of the build step automatically. The interpreter translates the code to python bytecode, which is executed by the python VM.

## Alternatives to CI setup

Some alternatives for the CI setup include CircleCI, GitLab CI/CD, and Azure Pipelines. GitLab, naturally, works well with GitLab repositories, and has a good free tier. CircleCI works well with GitHub, but can become more expensive. Azure Pipelines, on the other hand, is better suited for larger projects.

## Self-hosted vs Cloud-based

Considering that the team working on the application only has 6 people, a cloud-based solution would probably be better. It is unlikely that the codebase would be large enough to warrant paying for a server. However, if the CI needs extensive computing resources, a provider that is better suited for scaling might be good. Self-hosting would require extensive configuration, and the time of the developers is better spent elsewhere. The best alternative would likely be a free clou-based environment.
