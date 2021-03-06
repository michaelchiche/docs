## pulumi



### Synopsis


Pulumi - Cloud Native Infrastructure as Code

To begin working with Pulumi, run the 'pulumi new' command:

    $ pulumi new

This will prompt you to create a new project for your cloud and language of choice.

The most common commands from there are:

    - pulumi up       : Deploy code and/or resource changes
    - pulumi stack    : Manage instances of your project
    - pulumi config   : Alter your stack's configuration or secrets
    - pulumi destroy  : Tear down your stack's resources entirely

For more information, please visit the project page: https://pulumi.io

### Options

```
      --color colors.Colorization    Colorize output. Choices are: always, never, raw, auto (default always)
  -C, --cwd string                   Run pulumi as if it had been started in another directory
      --disable-integrity-checking   Disable integrity checking of checkpoint files
  -e, --emoji                        Enable emojis in the output (default true)
  -h, --help                         help for pulumi
      --logflow                      Flow log settings to child processes (like plugins)
      --logtostderr                  Log to stderr instead of to files
      --profiling string             Emit CPU and memory profiles and an execution trace to '[filename].[pid].{cpu,mem,trace}', respectively
      --tracing string               Emit tracing to a Zipkin-compatible tracing endpoint
  -v, --verbose int                  Enable verbose logging (e.g., v=3); anything >3 is very verbose
```

### SEE ALSO
* [pulumi cancel](pulumi_cancel.md)	 - Cancel a stack's currently running update, if any
* [pulumi config](pulumi_config.md)	 - Manage configuration
* [pulumi destroy](pulumi_destroy.md)	 - Destroy an existing stack and its resources
* [pulumi login](pulumi_login.md)	 - Log into the Pulumi service
* [pulumi logout](pulumi_logout.md)	 - Log out of the Pulumi service
* [pulumi logs](pulumi_logs.md)	 - Show aggregated logs for a stack
* [pulumi new](pulumi_new.md)	 - Create a new Pulumi project
* [pulumi plugin](pulumi_plugin.md)	 - Manage language and resource provider plugins
* [pulumi preview](pulumi_preview.md)	 - Show a preview of updates to a stack's resources
* [pulumi refresh](pulumi_refresh.md)	 - Refresh the resources in a stack
* [pulumi stack](pulumi_stack.md)	 - Manage stacks
* [pulumi up](pulumi_up.md)	 - Create or update the resources in a stack
* [pulumi version](pulumi_version.md)	 - Print Pulumi's version number
* [pulumi whoami](pulumi_whoami.md)	 - Display current logged in user

###### Auto generated by spf13/cobra on 12-Sep-2018
