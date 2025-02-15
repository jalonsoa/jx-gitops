## jx-gitops helmfile report

Generates a markdown report of the helmfile based deployments in each namespace

### Usage

```
jx-gitops helmfile report
```

### Synopsis

Generates a markdown report of the helmfile based deployments in each namespace

### Examples

  # generates a report of the deployments
  jx-gitops helmfile report

### Options

```
  -b, --batch-mode              Runs in batch mode without prompting for user input
      --commit-message string   the git commit message used (default "chore: generated kubernetes resources from helm chart")
      --config-root string      the folder name containing the kubernetes resources (default "config-root")
  -d, --dir string              the directory that contains the helmfile.yaml (default ".")
      --git-commit              if set then the template command will git commit the modified helmfile.yaml files
      --helm-binary string      specifies the helm binary location to use. If not specified defaults to using the downloaded helm plugin
      --helmfile string         the helmfile to resolve. If not specified defaults to 'helmfile.yaml' in the dir
  -h, --help                    help for report
      --log-level string        Sets the logging level. If not specified defaults to $JX_LOG_LEVEL
      --namespace string        the default namespace if none is specified in the helmfile.yaml (default "jx")
  -o, --out-dir string          the output directory (default "docs")
      --verbose                 Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warn, info, debug, trace
```

### SEE ALSO

* [jx-gitops helmfile](jx-gitops_helmfile.md)	 - Commands for working with helmfile

###### Auto generated by spf13/cobra on 29-Nov-2021
