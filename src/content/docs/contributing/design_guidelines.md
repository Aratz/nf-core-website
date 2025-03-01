---
title: Graphic design guidelines
subtitle: Templates, common images, and design-related content for nf-core.
---

## Introduction

nf-core has a variety of recognisable images and other graphic designs for the community project.
To help facilitate the identification of nf-core pipelines and related material, we provide here a variety of files that can be used for all nf-core-related content, such as pipeline logos, presentations, or workflow diagrams.

All files are released under various forms of 'open' licenses, meaning you can re-use and re-model as you see fit.

## Logo

All information for the nf-core logo can be seen at the [nf-core/logos GitHub repository](https://github.com/nf-core/logos) and are released under the MIT license.

| Type                         | Logo                                                                                                                                                 | Links                                                                                                                                                                                                                                                                                                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Main nf-core logo            | <img src="https://raw.githubusercontent.com/nf-core/logos/master/nf-core-logos/nf-core-logo.png" width="300">                                        | [PNG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo.png) <br> [SVG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo.svg) <br> [Adobe Illustrator `.ai`](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo.ai)                                  |
| Dark backgrounds             | <img class="bg-dark d-block p-2" src="https://raw.githubusercontent.com/nf-core/logos/master/nf-core-logos/nf-core-logo-darkbg.png" width="300">     | [PNG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-darkbg.png) <br> [SVG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-darkbg.svg) <br> [Adobe Illustrator `.ai`](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-darkbg.ai)             |
| Monochrome - dark background | <img class="bg-dark d-block p-2" src="https://raw.githubusercontent.com/nf-core/logos/master/nf-core-logos/nf-core-logo-mono-white.png" width="300"> | [PNG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-mono-white.png) <br> [SVG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-mono-white.svg) <br> [Adobe Illustrator `.ai`](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-mono-white.ai) |
| Square                       | <img src="https://raw.githubusercontent.com/nf-core/logos/master/nf-core-logos/nf-core-logo-square.png" width="60">                                  | [PNG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-square.png) <br> [SVG](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-square.svg) <br> [Adobe Illustrator `.ai`](https://github.com/nf-core/logos/blob/master/nf-core-logos/nf-core-logo-square.ai)             |

The `nf-core create` command will generate a logo for your pipeline automatically.
However, you can also do this yourself by visiting [https://nf-co.re/logo/pipelinename](https://nf-co.re/logo/pipelinename), where `pipelinename` can be anything.

Please note that nf-core is a separate entity from Nextflow.
You can find information about the Nextflow trademark with associated logo files at [https://github.com/nextflow-io/trademark](https://github.com/nextflow-io/trademark)

## Font & Colours

The font used in nf-core designs is _Maven Pro Bold (700)_, available at [Google Fonts](https://fonts.google.com/specimen/Maven+Pro), under the Open Font License.

The nf-core green colour is as follows:

- RGB: <span class="badge" style="background-color: rgb(36,176,100);">36,176,100</span>
- Hex: <span class="badge" style="background-color: rgb(36,176,100);">#24B064</span>

## Presentation Templates

nf-core regularly host [community events](https://nf-co.re/events), such as hackathons, and encourage training (e.g. [nf-core tutorials](https://nf-co.re/docs/usage/tutorials/nf_core_usage_tutorial)) the wider bioinformatics community in creating nextflow and nf-core pipelines.

<!--
If you wish to introduce or run training sessions to your group or network, you can access a Google Doc template **here**.
-->

## Workflow Schematics

It is often useful to have simplified diagrams that outline the main functionality and steps of a pipeline.
This helps new users get an overview of a workflow when visiting a pipeline webpage or repository for the first time.

Most workflow diagrams are made by hand using vector image editors such as the open-source [Inkscape](https://inkscape.org/) or commercial suites such as [Adobe Illustrator](https://www.adobe.com/products/illustrator.html). Useful tools for collaborative prototyping include [Google Drawings](https://docs.google.com/drawings/) or [LucidChart](https://www.lucidchart.com/pages/). All examples and components below can be opened in these editors, and various parts borrowed and/or modified as necessary.

The components are also made available on [bioicons](https://bioicons.com), which offers extensions for [Inkscape](https://inkscape.org/) and [draw.io](https://app.diagrams.net/) to directly import them there.

### Examples

See below for some examples of nf-core workflow schematics that can be re-used and modified for your own pipeline.

:::warning
Please make sure to check for any attributions to be included within any derivative images, as defined by the corresponding license! We provide suggestions below.
:::

Click the schematic image to see the original.

|                                                                                                                               Workflow Example                                                                                                                                | nf-core Pipeline                                  | License/Publication                                                                                                                                                      | Suggested attribution                           |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- |
|                     <a href="https://github.com/nf-core/sarek/blob/master/docs/images/sarek_workflow.png"><img src="https://raw.githubusercontent.com/nf-core/sarek/master/docs/images/sarek_workflow.png" alt="nf-core/sarek workflow" height="300"></a>                     | [nf-core/sarek](https://nf-co.re/sarek)           | From [Garcia _et al._ (2020, F1000 Research)](https://doi.org/10.12688/f1000research.16665.1) under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |                                                 |
|           <a href="https://github.com/nf-core/eager/blob/master/docs/images/usage/eager2_workflow.png"><img src="https://raw.githubusercontent.com/nf-core/eager/master/docs/images/usage/eager2_workflow.png" alt="nf-core/eager workflow simple" width="400"></a>           | [nf-core/eager](https://nf-co.re/eager)           | From [Fellows Yates _et al._ (2021, PeerJ)](https://doi.org/10.7717/peerj.10947) under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license               | CC-BY 4.0. Design originally by Zandra Fagernäs |
|  <a href="https://github.com/nf-core/eager/blob/master/docs/images/usage/eager2_metromap_complex.png"><img src="https://raw.githubusercontent.com/nf-core/eager/master/docs/images/usage/eager2_metromap_complex.png" alt="nf-core/eager workflow detailed" width="400"></a>  | [nf-core/eager](https://nf-co.re/eager)           | From [Fellows Yates _et al._ (2021, PeerJ)](https://doi.org/10.7717/peerj.10947) under a [MIT](https://github.com/nf-core/dualrnaseq/blob/master/LICENSE) license        |                                                 |
| <a href="https://github.com/nf-core/dualrnaseq/blob/master/docs/images/Workflow_diagram_dualrnaseq.png"><img src="https://raw.githubusercontent.com/nf-core/dualrnaseq/master/docs/images/Workflow_diagram_dualrnaseq.png" alt="nf-core/dualrnaseq workflow" width="400"></a> | [nf-core/dualrnaseq](https://nf-co.re/dualrnaseq) | By Regan Hayward under [MIT](https://github.com/nf-core/dualrnaseq/blob/master/LICENSE) license                                                                          |                                                 |
|                    <a href="https://github.com/nf-core/circrna/blob/master_old/docs/images/workflow.png"><img src="https://raw.githubusercontent.com/nf-core/circrna/master_old/docs/images/workflow.png" alt="nf-core/circrna workflow" width="400"></a>                     | [nf-core/circrna](https://nf-co.re/circrna)       | By Barry Digby under [MIT](https://github.com/nf-core/circrna/blob/master/LICENSE) license                                                                               |                                                 |
|                          <a href="https://github.com/nf-core/mag/blob/master/docs/images/mag_workflow.png"><img src="https://raw.githubusercontent.com/nf-core/mag/master/docs/images/mag_workflow.png" alt="nf-core/mag workflow" width="400"></a>                           | [nf-core/mag](https://nf-co.re/mag)               | By Sabrina Krakau under [MIT](https://github.com/nf-core/mag/blob/master/LICENSE) license                                                                                | CC-BY 4.0. Design originally by Zandra Fagernäs |
|                <a href="https://github.com/nf-core/bactmap/blob/master/docs/images/Bactmap_pipeline.png"><img src="https://raw.githubusercontent.com/nf-core/bactmap/master/docs/images/Bactmap_pipeline.png" alt="nf-core/bactmap workflow" width="400"></a>                 | [nf-core/bactmap](https://nf-co.re/bactmap)       | By Anthony Underwood under [MIT](https://github.com/nf-core/mag/blob/master/LICENSE) license                                                                             |                                                 |
|     <a href="https://github.com/nf-core/cutandrun/blob/3.1/docs/images/cutandrun-flow-diagram-v3.0.png"><img src="https://raw.githubusercontent.com/nf-core/cutandrun/3.1/docs/images/cutandrun-flow-diagram-v3.0.png" alt="nf-core/cutandrun workflow" width="400"></a>      | [nf-core/cutandrun](https://nf-co.re/cutandrun)   | By Chris Cheshire under [MIT](https://github.com/nf-core/cutandrun/blob/master/LICENSE) license                                                                          |                                                 |
|                           <a href="https://github.com/nf-core/sarek/blob/dev/docs/images/sarek_subway.png"><img src="https://raw.githubusercontent.com/nf-core/sarek/dev/docs/images/sarek_subway.png" alt="nf-core/sarek subway" width="400"></a>                            | [nf-core/sarek](https://nf-co.re/sarek)           | By Maxime U Garcia under [MIT](https://github.com/nf-core/sarek/blob/master/LICENSE) license                                                                             |                                                 |
|  <a href="https://github.com/nf-core/rnaseq/blob/master/docs/images/nf-core-rnaseq_metro_map_grey.png"><img src="https://raw.githubusercontent.com/nf-core/rnaseq/master/docs/images/nf-core-rnaseq_metro_map_grey.png" alt="nf-core/rnaseq metro map grey" width="400"></a>  | [nf-core/rnaseq](https://nf-co.re/rnaseq)         | By Sarah Guinchard under [MIT](https://github.com/nf-core/sarek/blob/master/LICENSE) license                                                                             |                                                 |
|       <a href="https://github.com/nf-core/isoseq/blob/master/docs/images/Isoseq_pipeline_V2.1-metro_clean.png"><img src="https://raw.githubusercontent.com/nf-core/isoseq/1.1.4/docs/images/Isoseq_pipeline_metro.png" alt="nf-core/isoseq metro map" width="400"></a>        | [nf-core/isoseq](https://nf-co.re/isoseq)         | By Sébastien Guizard under [MIT](https://github.com/nf-core/isoseq/blob/master/LICENSE) license                                                                          |                                                 |

### Components

Some components that may be useful are shown below:

|                                                                Object                                                                 | Description              | Link                                                                                                                                                                                       | Source                                                                                                              |
| :-----------------------------------------------------------------------------------------------------------------------------------: | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| <img title="Single FASTQ Icon" src="/images/graphic_design_assets/workflow_schematics_components/sarek/single_fastq.png" height="50"> | Single FASTQ File Icon   | [SVG](/images/graphic_design_assets/workflow_schematics_components/sarek/single_fastq.svg) <br> [PNG](/images/graphic_design_assets/workflow_schematics_components/sarek/single_fastq.png) | [nf-core/sarek](https://nf-co.re/sarek); under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |
| <img title="Double FASTQ Icon" src="/images/graphic_design_assets/workflow_schematics_components/sarek/double_fastq.png" height="50"> | Multiple FASTQ File Icon | [SVG](/images/graphic_design_assets/workflow_schematics_components/sarek/double_fastq.svg) <br> [PNG](/images/graphic_design_assets/workflow_schematics_components/sarek/double_fastq.png) | [nf-core/sarek](https://nf-co.re/sarek); under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |
|   <img title="Single BAM Icon" src="/images/graphic_design_assets/workflow_schematics_components/sarek/single_bam.png" height="50">   | Single BAM File Icon     | [SVG](/images/graphic_design_assets/workflow_schematics_components/sarek/single_bam.svg) <br> [PNG](/images/graphic_design_assets/workflow_schematics_components/sarek/single_bam.png)     | [nf-core/sarek](https://nf-co.re/sarek); under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |
|   <img title="Double BAM Icon" src="/images/graphic_design_assets/workflow_schematics_components/sarek/double_bam.png" height="50">   | Multiple BAM File Icon   | [SVG](/images/graphic_design_assets/workflow_schematics_components/sarek/double_bam.svg) <br> [PNG](/images/graphic_design_assets/workflow_schematics_components/sarek/double_bam.png)     | [nf-core/sarek](https://nf-co.re/sarek); under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |
| <img title="Multiple VCF Icon" src="/images/graphic_design_assets/workflow_schematics_components/sarek/multiple_vcf.png" height="50"> | Multiple VCF File Icon   | [SVG](/images/graphic_design_assets/workflow_schematics_components/sarek/multiple_vcf.svg) <br> [PNG](/images/graphic_design_assets/workflow_schematics_components/sarek/multiple_vcf.png) | [nf-core/sarek](https://nf-co.re/sarek); under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. |

### Component Cheatsheets

|                                                                                              Object                                                                                              | Description                                        | Link                                                                                                                                                                                                                                                         | Source                                                                                                                                     |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| <img title="Metromap style pipeline workflow components" src="/images/graphic_design_assets/workflow_schematics_components/generic/metromap_style_pipeline_workflow_components.svg" width="200"> | Components for a metro-map style pipeline workflow | [SVG](/images/graphic_design_assets/workflow_schematics_components/generic/metromap_style_pipeline_workflow_components.svg) <br> [PDF](/images/graphic_design_assets/workflow_schematics_components/generic/metromap_style_pipeline_workflow_components.pdf) | James A. Fellows Yates & nf-core; under a [CC0](https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1) license (public domain) |

### Use draw.io

The web app [draw.io](https://app.diagrams.net/) helps you create, render and export different diagrams including metro-maps.
For even more convenience you can use the following asset library [NF-Core xml item library](https://github.com/LouisLeNezet/phaseimpute/blob/dev/docs/NfCore_library.xml). It contains all of the components from the cheatsheet above.
To import it to draw.io use "File / Open library from / URL..." and paste:

```plaintext
https://github.com/LouisLeNezet/phaseimpute/raw/dev/docs/NfCore_library.xml
```

Additionally, the components can be used via [bioicons](https://bioicons.com).
