# Application: TorstyVerse: Microbial genomic tools for public health and epidemiology

## [`Nullarbor`]( https://github.com/tseemann/nullarbor )

> Anders Goncalves da Silva - anders.goncalves@unimelb.edu.au Essential Open Source Software for Science (Cycle 3)
Summary
> ID: EOSS3-0000000121

### Software Project Details:

1. Software Project name: `Nullarbor`

2. Homepage URL: https://github.com/tseemann/nullarbor

3. Hosting platform: GitHub

4. Main code repository: https://github.com/tseemann/nullarbor

5. DOI of major publication(s) describing software project:

6. Social media handles: https://twitter.com/torstenseemann (?)

7. Do you or software project key personnel have commit rights to the code repositories for this software project?: Yes

8. Short description of software project (200 words maximum):

> Public health microbiology labs receive batches of bacterial isolates whenever there is a suspected outbreak.In modernised labs, each of these isolates will be whole genome sequenced, typically on an Illumina or Ion Torrent instrument. Each of these WGS samples needs to quality checked for coverage, contamination and correct species. Genotyping (eg. MLST) and resistome characterisation is also required. Finally a phylogenetic tree needs to be generated to show the relationship and genomic distance between the strains. All this information is then combined with epidemiological information (metadata for each sample) to assess the situation and inform further action.

---

### Software Project Metrics: Quality (required):


1. What is the software project license?: [GPL_2.0]( https://raw.githubusercontent.com/tseemann/nullarbor/master/LICENSE )

2. What is the main programming language?: Perl 5

3. Does the software project have a code of conduct?: ${CODE_OF_CONDUCT}
	- Link:

4. Does the software project have end-user documentation?: https://github.com/tseemann/nullarbor/README.md

5. Does the software project have an issue tracker?: https://github.com/tseemann/nullarbor/issues

6. Does the software project have a community engagement / Q&A forum (self-hosted, on Stack Exchange etc.)?: **nullarbor wiki??**

7. Does the software project have contribution / coding guidelines?: **??**

8. Are there examples or demo notebooks, scripts, and datasets?: http://tseemann.github.io/nullarbor/ **??**

9. Is there a corresponding package available in a package manager (PyPi, CRAN, etc.)?: miniconda/conda or homebrew/linuxbrew
  - https://conda.io/miniconda.html
  - http://linuxbrew.sh/

10. Does the software project support continuous integration for testing?: **??**
  - Comment (optional):

---

### Software Project Metrics: Impact (optional):

Complete the following for the open source software project listed above. Providing metrics is optional and metrics can be approximate. For each metric, please provide a source, clarify how the metric was computed, and/or provide any other comments. For monthly metrics, please provide data from the most recent month for which the corresponding metric is available.

1. Complete the following table. List the number and explanation for each, if needed:

|                   | Number  | Comment |
| :--               | :--     | :--     |
| Scholarly paper(s) (including preprints) citing or mentioning the software project |  |  |
| Monthly users, if applicable (based on one or more of the following: monthly downloads from websites, monthly downloads from package managers, monthly unique requests for updates, etc.) |  |  |
| Software projects that depend on the project (if applicable) |  |  |
| Monthly visitors to project’s website, discussion forum (e.g. Stack Overflow), or similar |  |  |


2. Size of the largest potential user base:

|                   | Number  | Comment |
| :--               | :--     | :--     |
| Estimate the potential number of unique users who could adopt this project in the relevant field/discipline. Use as guidance the number of users of comparable projects, the number of papers published in the domain to which the project is applicable, number of labs able to adopt the project, etc. |  |  |

3. List of upstream, downstream, or related software projects that the team is contributing to or receiving contributions from:


- [`Prokka`](https://github.com/tseemann/prokka)
- [`MLST`](https://github.com/tseemann/mlst)
- [`abricate`](https://github.com/tseemann/abricate)
- [`Snippy`](https://github.com/tseemann/snippy)
- [`Shovill`](https://github.com/tseemann/shovill)
- [`snp-dists`](https://github.com/tseemann/snp-dists)
  - [`VelvetOptimiser`](https://github.com/tseemann/VelvetOptimiser) **??**
- dependencies: @torsten likely catches bugs for some of these cats...?
  - [`Trimmomatic`](https://github.com/timflutre/trimmomatic)
  - [`Kraken2`](https://github.com/DerrickWood/kraken2)
  - [`SKESA`](https://github.com/ncbi/SKESA)
  - [`SPAdes`](http://cab.spbu.ru/software/spades/)
  - [`Meghahit`](https://github.com/voutcn/megahit)
  - [`Velvet`](https://github.com/dzerbino/velvet)
  - [`IQTree`](https://www.iqtree.org/)
  - [`FastTree`](http://www.microbesonline.org/fasttree/)
  - [`Roary`](https://sanger-pathogens.github.io/Roary/)

4. Additional metrics from project code repositories and package managers:

Provide a short description of any considerations or caveats we should be aware of when computing metrics (e.g. a recent change in the name or hosting of the repository), or any additional information you would like to share about the project’s impact and quality. (maximum of 500 words)
