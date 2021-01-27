#### Workflows

- **deploy-PPSolution-to-test.yml** : Used to move solution from developer environment to test environment using build environment to test the packaging and dependencies.
- **deploy-PPSolution-to-prod.yml** : Used to move managed solution artifact created from deploy-PPSolution-to-test.yml to production environment
- **deploy-PPSolution-to-dev.yml** : Used to import solutions from any target environment to development environment.

More details on workflows in this [wiki](https://github.com/microsoft/powerplatform-actionstemplate/wiki).

Workflows mainly uses the [microsoft/powerplatform-actions](https://github.com/microsoft/powerplatform-actions).

For triggering workflow manually you can follow this [documentation](https://docs.github.com/en/free-pro-team@latest/rest/reference/repos#create-a-repository-dispatch-event).
