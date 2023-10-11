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



