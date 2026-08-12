# Slack Inviter application stack for Kubernetes on Wodby

Deploy Slack Inviter applications on Kubernetes with Wodby.

This repository defines the Wodby stack manifests and default service
composition for Slack Inviter.

- [Slack Inviter stack on Wodby](https://wodby.com/stacks/slack-inviter)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Start from a boilerplate

Use one of the compatible boilerplates exposed by this stack's services to
start with Wodby CI build configuration:

- [Slack Inviter](https://github.com/wodby/slack-inviter)

## Service definitions

- [Slack Inviter service](https://github.com/wodby/service-slack-inviter)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Slack Inviter<br>`slack-inviter` | required; enabled by default |

## Deploy this stack

Start from [Slack Inviter](https://github.com/wodby/slack-inviter), or connect your own compatible source
repository.

Review service versions, storage, links, and optional components when creating
the application. The same stack can be reused across development, staging, and
production environments.

## Maintain a custom version

1. Fork this repository.
2. Edit the stack manifest.
3. Import the repository as a [Git-backed stack](https://wodby.com/docs/2.0/stacks/create/#create-a-git-backed-stack).

When replacing or renaming a stack service, update every related link target
and derivative reference. Stack-local names and referenced service names are
distinct identifiers.

Validate the manifests with:

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

See the [stack manifest reference](https://wodby.com/docs/2.0/stacks/template/) and the [managed services index](https://github.com/wodby/services).
