# Nextflow Plugins index

This repository stores the index of plugins that can be used by 
[Nextflow](https://github.com/nextflow-io/nextflow).

The index is contained in the [plugins.json](plugins.json) file, 
which is organised with the following structure:

```json
[
  {
    "id": "nf-hello", 
    "releases": [
      {
        "version": "0.1.0",
        "date": "2021-07-25T11:54:13.481+02:00",
        "url": "https://github.com/nextflow-io/nf-hello/releases/download/0.1.0/nf-hello-0.1.0.zip",
        "requires": ">=21.04.0",
        "sha512sum": "7abcf988117f5148622609750b30ae35b1dcaa4f532f205f160c64ec215caafb6fa8bccefc8a90cc9dba60fc68f285769c9e897808b9d925313fc375952e4547"
      }
    ]
  }
]
```

The top-most JSON array lists all available plugins. The `releases` array
lists all the available versions for the corresponding plugin.

Learn more about Nextflow plugins in the [Nextflow documentation](https://www.nextflow.io/docs/latest/plugins.html).