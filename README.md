# K8S-Apps-Values

Repository that mocks the lc-k8s-apps-values.</br></br>
Here resides our values to apply for our charts that can be found in our [lc-k8s-apps repository](https://github.com/dom-lc/lc-k8s-apps).</br>

## Structure

We have a folder for every application, and in each forlder resides the values like values-<clustername>.yaml</br>
We could of created folders with cluster names at the root instead and in each cluster a sub-folder with each application name and then the values inside it.

## Adding an Application

When you are ready to deploy a new application, meaning you have completed the step to define your Chart in the [lc-k8s-apps](https://github.com/dom-lc/k8s-apps.git), and tested the deployment with workflow in the [lc-k8s-apps-deployments](https://github.com/dom-lc/k8s-apps-deployments.git) repository, you can now create a folder by your apps name. As a helmpre you cancopy the ```./_templates/new-app``` repository and paste in in the root of our repository. Then rename the folder from new-app to your apps name and copy/paste your values in the values-surveillance-green.yaml