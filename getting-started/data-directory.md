# Creating a new directory for figure data

Describe the structure and components of a data directory.

## Naming your directory

As you create data and figures for the report, it's unlikely you'll know what the published figure number will be, so name your directory using the title you'd give the figure, even though this won't be its definitive name.

``IPCC_AR7_<report>_<chapter>_<working title>``

Where ``report`` and ``chapter`` can be one of the abbreviations listed below: 

:::{table} IPCC AR7 abbreviations.
:label: table
:align: center

| Type        | Full name                                | Abbreviation  |
|-------------|------------------------------------------|---------------|
| ``report``  |                                          |               |  
|             | Working Group I                          | WG1           |
|             | Working Group II                         | WG2           |
|             | Working Group III                        | WG3           |
|             | Synthesis Report                         | SYR           |
|             | Special Report on Cities                 | SRC           |
| ``chapter`` |                                          |               |
|             | Summary for Policymakers                 | SPM           |
|             | Technical Summary                        | TS            |
|             | Chapter 1                                | Ch1           |
|             | Cross-Chapter Paper 1                    | CCP1          |
|             | Annex III                                | Ann3          |

:::

## Directory structure

The minimal directory structure should be as follows:

```
README.md
metadata.yml
LICENSE
data/
    <data files>
figures/
    <figure files>
src/
    <source code>
```

You'll find a template repository at https://github.com/IPCC-AR7/example-repo

:::{glossary}
README.md
: A simple text file using the Markdown markup. Intended for other scientists who want to understand and reproduce your work. Should minimally include ...  

metadata.yml
: A YAML file that contains metadata about the figure. This file should minimally include ...

LICENSE
: A text file that specifies the terms of use for the data and figures in the directory. Unless the original data license does not allow it, the data and figures in this directory should be licensed under the Creative Commons Attribution 4.0 International License.

:::

