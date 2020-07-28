# Application: TorstyVerse: Microbial genomic tools for public health and epidemiology

## [`Snippy`]( https://github.com/tseemann/snippy )

> Anders Goncalves da Silva - anders.goncalves@unimelb.edu.au Essential Open Source Software for Science (Cycle 3)
Summary
> ID: EOSS3-0000000121

### Software Project Details:

1. Software Project name: `Snippy`

2. Homepage URL: https://github.com/tseemann/snippy

3. Hosting platform: GitHub

4. Main code repository: https://github.com/tseemann/snippy

5. DOI of major publication(s) describing software project (if applicable):

6. Social media handles: @torstenseemann

7. Do you or software project key personnel have commit rights to the code repositories for this software project?: Yes

8. Short description of software project (200 words maximum):

> **Rapid haploid variant calling and core genome alignment**
>
> Snippy finds SNPs between a haploid reference genome and your NGS sequence reads. It will find both substitutions (snps) and insertions/deletions (indels). It will use as many CPUs as you can give it on a single computer (tested to 64 cores). It is designed with speed in mind, and produces a consistent set of output files in a single folder. It can then take a set of Snippy results using the same reference and generate a core SNP alignment (and ultimately a phylogenomic tree).

---

### Software Project Metrics: Quality (required):

1. What is the software project license?: [GPL_2.0](https://raw.githubusercontent.com/tseemann/snippy/master/LICENSE)

2. What is the main programming language?: Perl 5

3. Does the software project have a code of conduct?:

4. Does the software project have end-user documentation?: https://github.com/tseemann/snippy

5. Does the software project have an issue tracker?: https://github.com/tseemann/snippy/issues

6. Does the software project have a community engagement / Q&A forum (self-hosted, on Stack Exchange etc.)?: in construction at https://github.com/tseemann/snippy/wiki

7. Does the software project have contribution / coding guidelines?:

8. Are there examples or demo notebooks, scripts, and datasets?:

9. Is there a corresponding package available in a package manager (PyPi, CRAN, etc.)?: miniconda/conda or homebrew/linuxbrew
  - https://conda.io/miniconda.html
  - http://linuxbrew.sh/

10. Does the software project support continuous integration for testing?: [travis-ci](https://travis-ci.org/tseemann/snippy)

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

 - [`nullarbor`](https://github.com/tseemann/nullarbor)
 - dependencies: @torsten likely catches bugs for some of these cats...?
  - [`BWA MEM`](https://sourceforge.net/projects/bio-bwa/files/)
  - [`Meghahit`](https://github.com/voutcn/megahit)
  - [`SAMtools`](http://www.htslib.org/)
  - [`freebayes`](https://github.com/ekg/freebayes)

4. Additional metrics from project code repositories and package managers:

Provide a short description of any considerations or caveats we should be aware of when computing metrics (e.g. a recent change in the name or hosting of the repository), or any additional information you would like to share about the project’s impact and quality. (maximum of 500 words)
