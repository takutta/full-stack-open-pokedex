My language would be Python. I would lint it with pylint and test it with pytest. I think pytest is quite simple and includes many features. With building I would probably code my own "build" script which would include copying only certain files etc.

Alternatives for Jenkins and Github Actions:

Travis CI:
* Easy integration with GitHub repositories.
* Provides a cloud-based environment, reducing the need for infrastructure management.
* Some users may find the configuration syntax less intuitive compared to others.

CircleCI:
* Offers cloud-based CI/CD with easy integration into popular version control platforms.
* Provides flexibility with a customizable configuration using YAML.
* Requires understanding of CircleCI-specific concepts like workflows and orbs.

Azure Pipelines:
* Supports building, testing, and deploying applications on various platforms.
* May have a steeper learning curve for teams not familiar with Azure DevOps.
* Can be perceived as more complex for simpler projects.

Bamboo:
* Supports build and deployment plans with a graphical interface.
* Allows for easy configuration and management of build environments.
* Licensing costs can be a consideration for smaller teams.

If the project would be quite small cloud-based enviroment would be sufficient enough. If the project would go larger I should consider moving it to self-hosted enviroment. Cloud-based CI/CD services would easily scale with my project's needs but Self-hosted environments might have lower ongoing costs.