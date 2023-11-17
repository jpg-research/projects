# Thesis. Urban Knowledge Hub for Evolving Cities

The description of this thesis is published on [my LIRIS page](https://liris.cnrs.fr/en/thesis/thesis-jey-puget-gil). 

## Idea
### Graph versioning
[Graph versioning for evolving urban data](https://hal.science/hal-04257528) is a key feature of the Urban Knowledge Hub for Evolving Cities. The graph versioning is made by the [SPARQL-to-SQL](https://github.com/VCityTeam/SPARQL-to-SQL) project.

### Condensed representation of the versioning
Our proposition is to use a vector of bits to represent the data versioning. Each bit represents the existence of the data inside the associated version.
A graphic representation of the versioning is available [in the poster](https://hal.science/hal-04257528).


## Organization
### Roadmap

```mermaid
gantt
	title SPARQL-to-SQL translator roadmap 2023-2024
	dateFormat YYYY-MM-DD
	excludes 2023-12-25, 2023-12-26, 2023-12-27, 2023-12-28, 2023-12-29, 2023-12-30, 2023-12-31, 2024-01-01, 2024-01-02, 2024-01-03, 2024-01-04, 2024-01-05, 2024-01-06, 2024-01-07
	axisFormat %m-%d
	
	section Context
	Spec report             : sp1, 2023-11-06, 9d
	Spec delivery           : milestone, m0, after sp1, 0d
	RDF course              : sp2, after sp1, 7d

	section State of the art
	Readings                : s1, 2023-11-20, 14d
	Présentations 1         : milestone, pr1, 2023-11-26, 0d
	Présentations 2         : milestone, pr2, 2023-12-03, 0d
	Delivery                : milestone, s0, 2023-12-08, 0d

	section Brainstorming
	Design                  : b1, 2023-12-11, 7d
	Algorithm               : b2, after b1, 7d

	section Development
	Operators               : d1, 2024-01-08, 35d
	Test                    : d2, 2024-01-28, 15d
	Reproducibility         : d3, 2024-01-28, 15d
	Delivery                : crit, milestone, d4, after d1 d2, 0d

	section Presentations
	Reporting               : r1, 2024-02-04, 26d
	Report draft            : milestone, r0, 2024-02-19, 0d
	Video draft             : milestone, r1, 2024-02-19, 0d
	Training session        : milestone, t0, 2024-02-19, 0d
	Report delivery         : crit, milestone, m3, 2024-02-29, 0d
	Video delivery          : crit, milestone, m1, 2024-02-29, 0d
	Presentation            : crit, milestone, m2, 2024-02-29, 0d
```

### Kanban

The Kanban is available on [the SPARQL-to-SQL fork](https://github.com/orgs/jpg-research/projects/2).