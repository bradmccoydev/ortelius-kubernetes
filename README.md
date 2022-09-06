![passing](https://github.com/ortelius/ortelius-kubernetes/actions/workflows/ci.yml/badge.svg) ![GitHub](https://img.shields.io/github/license/ortelius/ortelius-kubernetes)
# ortelius-kubernetes
This Project Is for The Ortelius Kubernetes manifests, helm charts, deployments etc

# Pre commit hook
To make use of the pre commit hook please run the following command to enable it on your computer.
```bash
pre-commit install
```

## Become a contributor

1) Review the [Ortelius Contributor Guide](https://docs.ortelius.io/guides/contributorguide/)
2) Add yourself to the [Ortelius Google Group](https://groups.google.com/g/ortelius-dev)
3) Join the [Discord community channel](https://discord.gg/ZtXU74x)

Contributors:
* Brad McCoy ([@bradmccoydev](https://github.com/bradmccoydev)), Odysseycloud
* Amit Dsouza ([@checksumz](https://github.com/checksumz)), Odysseycloud
* Ben Poh ([@benhpoh](https://github.com/benhpoh)), Moula
* Ujwal Yelmareddy ([@interasujwal](https://github.com/interasujwal)), Interas Labs
* Hamid Gholami ([@hamidgholami](https://github.com/hamidgholami)),EGS

keptn create project ortelius --shipyard=$SHIPYARD_FILE --git-user=$GIT_USER --git-token=$GITHUB_TOKEN --git-remote-url=$GIT_REPO

GITHUB_TOKEN=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 && GIT_USER=bradmccoydev && GIT_REPO=https://github.com/bradmccoydev/keptn-argo-demo && SHIPYARD_FILE=/Users/bradmccoy/Development/bradmccoydev/ortelius-kubernetes/kube-infra/kustomize/test/keptn/overlays/production/shipyard.yaml
