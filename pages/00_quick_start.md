---
title: Using the documentation guidelines
type: quick_start
description: An abbreviated guide for using the documentation guidelines to create documentation for an existing, or new, software project.
---


These are the steps required to use the documentation guidelines templates to create documentation for an existing, or new, software project:

{% include callout.html type="important" content="Using the templates in this repository is not the only option! See [this page](options) for more details." %}


1. [Create a new repository](01_create) in your account / organisation, using [this repository]() as a template
2. [Update your README contents](02_readme)
3. [Update the metadata files](03_update_files)
4. [Tidy repository](04_tidy)
5. [Register your repository in a suitable place (e.g. Zenodo, WorkflowHub, bio.tools)](05_register)

Done!


A `README.md` is the explainer file for your software or project. 

You have two options for updating its contents depending on if you have cloned the documentation guidelines to create a new repository, or if you need to update an existing repository. 

## Creating a new repository

In this case:

1. Select a template from the `documentation templates` directory 
2. Move the template file into the root directory of the repository, 
3. Complete the necessary sections of the template, 
4. Delete the other headings, and
5. When ready, delete the original `README.md` file from the template repository and rename your completed documentation as `README.md`.


## Updating an existing repository

You can do two things here, either copy the contents of one of the template documentation files into your existing `README.md` file, or you can use existing resources like https://readme.so/ to create your own custom README content. 

These are the current templates that are available in `documentation_templates/`:
- `tools.md`: template for documenting software tools.
- `workflows.md`: template for documenting computational workflows.
- `infrastructure_optimisation.md`: template for documenting software optimisation required for specific compute infrastructures (cloud, HPC, other).
- `benchmarking.md`: template for documenting benchmarking outcomes for software.


## Update recommended files

The files that we recommend you always include are detailed below:


### `LICENSE`

The license indicates if, and how, someone can reuse your software or project.
You need to select a license (https://choosealicense.com/) and copy the license text into the `LICENSE.md` file. 


### `CHANGE_LOG.md`

A log of the changes made for each version / release.
Make sure to update `CHANGE_LOG.md` when you make changes to your software or project.   


### `CITATION.cff`

A standard file type that indicates how someone should cite your software or project ([Druskat 2021](https://doi.org/10.5281/zenodo.5171937), [Lee 2018](https://doi.org/10.1371/journal.pcbi.1006561)).

1. Update this file with the citation metadata for your software or project. 
2. GitHub will auto-detect this file and create a citation export option for you. 
3. You can easily generate your own `CITATION.cff` using this resource https://citation-file-format.github.io/cff-initializer-javascript/#/

The [documentation guidelines](https://github.com/AustralianBioCommons/doc_guidelines) include a `CITATION.cff` file to highlight 
how the repository and its contents should be cited. 

Below is an example of this file format being used by the [Sydney Informatics Hub](https://www.sydney.edu.au/research/facilities/sydney-informatics-hub.html). 
The file is available [here](https://github.com/Sydney-Informatics-Hub/GermlineShortV_biovalidation/blob/main/CITATION.cff).

```
cff-version: 1.0.0
message: "If you use this software, please cite it as below."
authors:
  - family-names: "Samaha"
    given-names: "Georgina"
    orcid: "https://orcid.org/0000-0003-0419-1476"
  - family-names: "Willet"
    given-names: "Cali"
    orcid: "https://orcid.org/0000-0001-8449-1502"
  - family-names: "Deshpande"
    given-names: "Nandan"
    orcid: "https://orcid.org/0000-0002-0324-8728"
  - family-names: "Chew"
    given-names: "Tracy"
    orcid: "https://orcid.org/0000-0001-9529-7705"
title: "GermlineShortV_biovalidation"
version: 1.0
doi: 10.48546/workflowhub.workflow.339.1
date-released: 2022-05-05
url: "https://github.com/Sydney-Informatics-Hub/GermlineShortV_biovalidation"
```


## Update optional file(s)

There are other useful files that you can include in your repository. These are described in more detail here.

### `codemeta.json`

This is a standard metadata file type from the [CodeMeta Project](https://codemeta.github.io/). 

You can easily generate your own `codemeta.json` using this resource: https://codemeta.github.io/create/


## Keep it simple

Only add the directories and structures that are needed, and highlight the purpose of each one.


## Ensure your documentation is straightforward and easy to understand



## Delete elements of the template that you do not need

These are guidelines only, and that means you can modify, update or delete elements of the file and directory structure to suit your specific use case.


## Register your repository

Below are some suggestions for where to register, based on the type of software you have created.


### Tools

- [bio.tools](https://bio.tools/)
- [Zenodo](https://zenodo.org/)


### Computational workflows

- [WorkflowHub](https://workflowhub.eu/)
- [Dockstore](https://dockstore.org/)


## References

> Druskat, Stephan, Spaaks, Jurriaan H., Chue Hong, Neil, Haines, Robert, Baker, James, Bliven, Spencer, Willighagen, Egon, Pérez-Suárez, David, & Konovalov, Alexander. (2021). **Citation File Format (1.2.0)**. Zenodo. https://doi.org/10.5281/zenodo.5171937

> Lee BD (2018) Ten simple rules for documenting scientific software. PLoS Comput Biol 14(12): e1006561. https://doi.org/10.1371/journal.pcbi.1006561


