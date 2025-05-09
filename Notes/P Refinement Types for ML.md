---
tags:
  - seedbox
type: paper
status: inprogress
priority: 2
publish: true
aliases:
---

# Title: **[[P Refinement Types for ML]]**

## Hypothesis:

- Added refinement to the existing type systems for getting more errors at the compile time. 
- This types can addition to the well-typed program in ML that preserves its [[decidability]] 
## Result(s):

- 


## Notes

- To be able to detect runtime error you can specify subtype for ML basic type using `rectype` ```
```ML
datatype α list = nil | cons of α * α list
rectype α singleton = cons (α, nil)
```

#### [[contravariance]]
$$
\sigma_1 \to \tau_1  \preceq \sigma_2 \to \tau_2 \quad if \quad \tau_1 \preceq \tau_2 \quad and \quad \sigma_2 \preceq \sigma_1 
$$
- Covariance suggests that if we consider of 
## Context:

==(How this article relates to other work in the field; how it ties in with key issues and findings by others, including yourself)==

- 

## Significance:

==(to the field; in relation to your own work)==

- 

## Important Figures and/or Tables:


## Cited References 


## Metadata:

- `Type:` [[&]]
- `Author:` [[Tim Freeman]], [[Frank Pfenning]]
	- `Notable Authors:` 
- `Keywords:` [[refinement type]], [[type system]], [[ML language]]
- `Specific Subject:` 
- `General Subject:` 
- `DOI:` [DOI]
- `Zotero URL:` [Zotero]
- `Publish Date:` 
- `Reviewed Date:` [[2025-02-28]]

## Citation

```latex

```
