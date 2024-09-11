## VictoriaMetrics module for Deckhouse Kubernetes Platform

##### To Do:

- [ ] Helm things...
- [ ] Can I easily deploy module to registry?
- [ ] Can I easily enable module in Deckhouse without problems with pulling?
- [ ] Use OpenApi, Hooks

After module deploys in cluster:
- [ ] VictoriaMetrics can scrape targets? Or I need to modify SA and Roles?
- [ ] Additional configmap for extra targets
- [ ] Check how service discovery works (how VictoriaMetrics can parse targets from podMonitor of Deckhouse components)

# Deckhouse Kubernetes Platform module template

This repository is a template for building a module for [Deckhouse Kubernetes Platform](https://github.com/deckhouse/deckhouse). It uses GitHub Actions workflows and GitHub Packages for building and deploying modules for the Deckhouse Kubernetes Platform.

Read the Deckhouse Kubernetes Platform [documentation](https://deckhouse.io/there-will-be-a-link) for more information about using this template.

Add necessary permissions to the repository to use the workflows:
- Open _Settings -> Actions -> General_ page.
- Set _Read and write permissions_ in the _Workflow permissions_ section.
