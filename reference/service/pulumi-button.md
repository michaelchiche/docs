---
title: Creating a 'Deploy with Pulumi' Button
---

The 'Deploy with Pulumi' button provides a way to easily create new Pulumi projects without leaving your browser. The button can be embedded in README files or web pages.

Here's an example button that creates a new empty TypeScript project:

[![Deploy](https://get.pulumi.com/new/button.svg)](https://app.pulumi.com/new?template=https://github.com/pulumi/templates/typescript)

This document describes how you can make use of the Pulumi Button for your own Pulumi templates/examples/apps.

## Templates

The Pulumi Button works with template projects hosted in public GitHub repositories or public GitHub Gists. A template is a Pulumi project that has the required `Pulumi.yaml` file, which describes the project. It can be in the root of the GitHub repository or within a subdirectory.

```yaml
name: my-aws-project
runtime: nodejs
description: My AWS project description
template:
  config:
    aws:region:
      description: The AWS region to deploy into
      default: us-west-2
```

The `Pulumi.yaml` file can optionally contain a `template` property, which typically includes a `config` property used to specify any required config values for the project. Each config value can have a description and default value.


In the snippet above, there is a single required `aws:region` config value defaulted to `us-west-2`.

## Testing

You can test out a


## Creating a Pulumi Button

```markdown
[![Deploy](https://get.pulumi.com/new/button.svg)](https://app.pulumi.com/new)
```

Or, the equivalent HTML:

```html
<a href="https://app.pulumi.com/new">
  <img src="https://get.pulumi.com/new/button.svg" alt="Deploy">
</a>
```