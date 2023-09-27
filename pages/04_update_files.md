---
title: Update standard file(s)
type: steps
description: Add a plain text description here.
---


## Update recommended files

The files that we recommend you always include are detailed below:

| File | Purpose  | What you need to do!                                                                                                                                                                                                                                            |
|------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|LICENSE.md| The license that indicates how someone can reuse your software or project. | Select a license (https://choosealicense.com/) and copy the license text into this file.                                                                                                                                                                        |
|CHANGE_LOG.md| A log of the changes made for each version / release. | Update this file when you make changes to your software or project.                                                                                                                                                                                             |
|CITATION.cff| A standard file type that indicates how someone should cite your software or project. | Update this file with the citation metadata for your software or project. GitHub will auto-detect this file and create a citation export option for you. You can easily generate your own `CITATION.cff` using this resource https://citation-file-format.github.io/cff-initializer-javascript/#/ |

### Including a license


### Including a change log


### Letting people know how to cite a repository

The [documentation guidelines](https://github.com/AustralianBioCommons/doc_guidelines) include a `CITATION.cff` file to highlight 
how the repository and its contents should be cited. 

> Druskat, Stephan, Spaaks, Jurriaan H., Chue Hong, Neil, Haines, Robert, Baker, James, Bliven, Spencer, Willighagen, Egon, Pérez-Suárez, David, & Konovalov, Alexander. (2021). **Citation File Format (1.2.0)**. Zenodo. https://doi.org/10.5281/zenodo.5171937

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


## Update the optional but useful file(s)

There are other useful files that you can include in your repository. These are described in more detail here.

- `codemeta.json`: this is a standard metadata file type from the [CodeMeta Project](https://codemeta.github.io/). You can easily generate your own `codemeta.json` using this resource: https://codemeta.github.io/create/


## References

> Lee BD (2018) Ten simple rules for documenting scientific software. PLoS Comput Biol 14(12): e1006561. https://doi.org/10.1371/journal.pcbi.1006561
> 

