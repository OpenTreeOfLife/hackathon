Tree-for-All: A hackathon to access OpenTree’s phylogeny resources
==================================================================

Call for participation
----------------------

### Synopsis

We encourage interested individuals (programmers and non-programmes)
to apply for participation in a hackathon focused on facilitating
access to [OpenTree] resources, including its synthetic tree (Tree of
Life), its database of annotated source trees, and its integrated
taxonomy.

### Rationale and aims

Once assembled, a global “tree of life” will possess the capacity to
transform biological research in disciplines ranging from ecology and
systematics to bioengineering and epidemiology.  Just as the
transformative power of genomic data depends, not just on access to
files with sequence data, but on tools that make an ever-changing body
of data easy to access and use, the transformative potential of a tree
of life depends on tools and standards that facilitate the flow of
phylogenetic information.

Recently, the NSF-supported [OpenTree] project has (1) gathered, encoded
and annotated >4000 published phylogenies (“source trees”), (2)
combined several taxonomic hierarchies into a reference taxonomy, and
(3) used this information to generate a synthetic tree covering >2.5
million species. OpenTree provides access to all of this information
via raw downloads, and also via queryable online interfaces that can
be invoked by external software. However, tools that actually use
these interfaces to deliver phylogenetic knowledge into the hands of
scientists have not been developed yet.


To facilitate the development of tools that use its resources,
OpenTree, together with the [Arbor] project (phylogenetic workflows) and
NESCent’s [HIP (Hackathons, Interoperability, Phylogenies) working
group][HIP] is holding a 1-week hackathon (Sept 15 to 19, U. Michigan, Ann
Arbor). We invite interested programmers and non-programmers to engage
in pre-hackathon planning, and apply for participation in the
hackathon.

### Resources and Development Targets 

Long-term, we aim to link supply and demand to allow useful
information to flow from phylogeny producers to phylogeny
consumers. We envision a future in which the OpenTree data, as well as
other sources of phylogenies and related data, are linked in an
interoperable web of data and services. As a step toward this future,
the OpenTree project has developed
[online application programming interfaces][OpenTree APIs] (APIs) that
allow anyone to write programs to access their data directly and
automatically. The upcoming hackathon is an opportunity to learn these
interfaces, and to work with a team to generate some product
(typically a software tool) that incorporates OpenTree interfaces.

We encourage participation of anyone with an idea for a project that
uses, tests, expands, or simply documents the APIs providing access to
OpenTree data and services. Proposed products may represent end-user
tools or library code; they may focus on the synthetic tree, the
source trees, or the taxonomy; they may harvest data, submit data
(e.g., add a source tree) or annotate data. For purposes of
sustainability, we prefer project ideas that extend existing packages
rather than develop standalone tools. Products may be tied to a
specific research objective, but should hold promise of usefulness to
a broader community. Relevant ideas could include:

* novel ways to index and search OpenTree to find trees matching user
  criteria
* converting OpenTree output into various formats
* searching for trees relevant to resolving some ancestral branch order
* extracting species names from an input file, and then extract a tree
  covering only those species
* adding structured annotations to trees in OpenTree
* visualizing OpenTree data in new and creative ways
* combining (in a generalized way) OpenTree phylogeny with trait (or
  other) data to perform a comparative analysis in R (or Mesquite or
  other tool)

Many other ideas are possible. 

### Application 

#### Who may apply 

Anyone may apply regardless of position or level of experience.  Women
and underrepresented minorities are especially encouraged to apply. We
expect a mixture of programmers, scientists, and programmer-scientists
who have a specific interest in leveraging OpenTree
resources. Applicants should understand basic concepts of
phylogenetics. Those who consider themselves non-programmers should be
able to talk about code and discuss design ideas with a
programmer. All applicants are encouraged to participate in
collaborative idea development prior to applying (below).

#### Idea development

Hackathon projects generally are the work of a team of 3 to 7
people. Teams and projects are not decided in advance: they will
emerge by a guided self-organization process on the first day of the
hackathon. This process is greatly aided if participants have sifted
ideas and identified potential team-mates in advance. We invite you to
sign in to our [online repository] to post ideas, and offer comments on
others’ ideas. Participation in this process is not required, but is
strongly encouraged.

#### Application process

[Online applications] will be considered through July 8, 2014, and
successful applicants will be notified by July 25. The application
consists of contact information, a statement describing how your
training and experience prepare you to participate successfully, and a
short description of a potential project idea.

### Travel support

Applicants who are invited to participate in the face-to-face meeting
typically will be offered full travel support.

### Open-Source Requirement 

All software produced at the hackathon will have an
[OSI-approved open source license][OSI License], and will be developed
in the open with code on a public repository such as [GitHub] or
[SourceForge] from the beginning of the event.

### Sponsors 

This project is sponsored by [OpenTree], [Arbor] and the Hackathons,
Interoperability, Phylogenies ([HIP]) working group of the National
Evolutionary Synthesis Center ([NESCent]).

### For more information

If you have questions about any aspect of this project, feel free to contact 

* Karen Cranston (karen.cranston@nescent.org, @kcranstn, OpenTree)
* Arlin Stoltzfus (arlin@umd.edu, HIP)
* Julie Allen (juliema@illinois.edu, HIP)
* Luke Harmon (lukeh@uidaho.edu, Arbor)

[OpenTree]: http://opentreeoflife.org
[Arbor]: http://www.arborworkflows.com/
[HIP]: http://www.evoio.org/wiki/HIP
[NESCent]: http://nescent,org
[Github]: http://github.com
[SourceForge]: http://sf.net
[OSI License]: http://opensource.org/licenses/
[Online applications]: http://bit.ly/RyklMn
[OpenTree APIs]: https://github.com/OpenTreeOfLife/opentree/wiki/Open-Tree-of-Life-APIs
[online repository]: https://github.com/OpenTreeOfLife/hackathon
