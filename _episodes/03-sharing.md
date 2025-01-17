---
layout: episode
title: "Sharing code and data"
teaching: 10
exercises: 15
questions:
  - "How can I share research code and data?"
objectives:
  - "Discuss the pros and cons of open science"
  - "Learn how to mint a DOI for your project"
keypoints:
  - "Consider sharing other research outputs than articles"

---

## Sharing research data

The Open Science movement encourages researchers
to share research output beyond the contents of a
published academic article (and possibly supplementary information).

 <img src="{{ site.baseurl }}/img/Open_Science_Principles.png" style="height: 200px;"/>

Arguments in favor [(from Wikipedia)](https://en.wikipedia.org/wiki/Open_science):
- Open access publication of research reports and data allows for rigorous peer-review
- Science is publicly funded so all results of the research should be publicly available
- Open Science will make science more reproducible and transparent
- Open Science has more impact
- Open Science will help answer uniquely complex questions

Arguments against [(from Wikipedia)](https://en.wikipedia.org/wiki/Open_science):
- Too much unsorted information overwhelms scientists
- Potential misuse
- The public will misunderstand science data
- Increasing the scale of science will make verification of any discovery more difficult
- Low-quality science

---

### FAIR principles

"FAIR" is the current buzzword for data management. You may be asked
about it in, for example, making data management plans for grants:

- **F**indable
  - Will anyone else know that your data exists?
  - Solutions: put it in a standard repository, or at least a
    description of the data.
- **A**ccessible
  - Once someone knows that the data exists, can they get it?
  - Usually solved by being in a repository, but for non-open data,
    may require more procedures.
- **I**nteroperable
  - Is your data in a format that can be used by others, like csv
    instead of PDF?
  - Or better than csv. Example: [5-star open data](https://5stardata.info/en/)
- **R**eusable
  - Is there a license allowing others to re-use?

Even though this is usually referred to as "open data", it means
considering and making good decisions, even if non-open.

FAIR principles are usually discussed in the context of data,
but they apply also for research software.

Note that FAIR principles do not require data/software to be open.



> ## Exercise: Discuss open science
> - Do you share any other research outputs besides published articles and possibly source code?
> - Discuss pros and cons of sharing research data.
{: .task}

---

> ## Exercise: Get a DOI by connecting your repository to Zenodo
>
> Digital object identifiers (DOI) are the backbone of the academic
> reference and metrics system. In this exercise we will see how to
> make a GitHub repository citable by archiving it on the
> [Zenodo](http://about.zenodo.org/) archiving service. Zenodo is a 
> general-purpose open access repository created by OpenAIRE and CERN.
>
> 1. Sign in to Zenodo using your GitHub account. For this exercise, use the
>   sandbox service: [https://sandbox.zenodo.org/login/](https://sandbox.zenodo.org/login/). This is a test version of the real Zenodo platform.
> 2. Go to [https://sandbox.zenodo.org/account/settings/github/](https://sandbox.zenodo.org/account/settings/github/).
> 3. Find the repository you wish to publish, and flip the switch to ON.
> 4. Go to GitHub and create a **release**  by clicking the `release` tab and
>   `Create a new release`  (a release is based on a Git tag,
>    but is a higher-level GitHub feature),
> 5. Creating a new release will trigger Zenodo into archiving your repository,
>   and a DOI badge will be displayed next to your repository after a minute
>   or two. You can include it in your GitHub README file: click the
>   DOI badge and copy the relevant format (Markdown, RST, HTML).
{: .task}

---

### Services for sharing and collaborating on research data

To find a research data repository for your data, you can search on the
[Registry of Research Data Repositories (re3data)](https://www.re3data.org/)
platform and filter by country, content type, discipline, etc.

**International:**

- [Zenodo](https://zenodo.org/): A general-purpose open access repository
  created by OpenAIRE and CERN. Integration with GitHub, allows
  researchers to upload files up to 50 GB.
- [Figshare](https://figshare.com/): Online digital repository where researchers
  can preserve and share their research outputs (figures, datasets, images and videos).
  Users can make all of their research outputs available in a citable,
  shareable and discoverable manner.
- [EUDAT](https://eudat.eu): European platform for researchers and practitioners from any research discipline to preserve, find, access, and process data in a trusted environment.
- [Dryad](https://datadryad.org/): A general-purpose home for a wide diversity of datatypes,
  governed by a nonprofit membership organization.
  A curated resource that makes the data underlying scientific publications discoverable,
  freely reusable, and citable.
- [The Open Science Framework](https://osf.io/): Gives free accounts for collaboration
  around files and other research artifacts. Each account can have up to 5 GB of files
  without any problem, and it remains private until you make it public.

**Sweden:**

- [ICOS for climate data](http://www.icos-sweden.se/)
- [Bolin center climate / geodata](https://bolin.su.se/data/)
- [NBIS for life science, sequence –omics data](https://nbis.se/infrastructure)

**Norway:**

- [NIRD archive is also widely used by some communities](https://archive.norstore.no/)

**Denmark:**

- [opendata.dk nationwide portal](http://www.opendata.dk)
- [Danish portal for sharing geographical data](http://brugstedet.dk/)

**Finland:**

- [IDA, for general data](https://ida.fairdata.fi/login)
- [FSD for social data](https://www.fsd.uta.fi/en/)
- [more information on Finnish resources for open data](https://www.fairdata.fi/en/)

---

### Further reading on reproducibility and open science

- [The Turing way](https://github.com/alan-turing-institute/the-turing-way/)
- [Reproduciblity syllabus](http://lorenabarba.com/blog/barbagroup-reproducibility-syllabus/)
- The [reproducible research data analysis platform](http://www.reana.io/)
- Good talks on open reproducible research can be found [here](http://inundata.org/talks/index.html).
- ["FAIR is not fair enough"]([https://danielskatzblog.wordpress.com/2017/06/22/fair-is-not-fair-enough/)
- ["Top 10 FAIR Data & Software Things"](https://librarycarpentry.org/Top-10-FAIR/) are brief guides that can be used by the research community to understand how they can make their research (data and software) more FAIR.