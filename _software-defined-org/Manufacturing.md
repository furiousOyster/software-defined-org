# Manufacturing of Objects

This is the planned structure for using an elastic work force to develop modules that meet a strict specification.  The goals of this approach are that we can scale capacity smoothly, up or down, and that we can preserve our IP by never having any manufacturer be able to see the full Core.

Process:

1. Spec is defined by the architects
1. A new repo is created for the module, that includes the spec
1. Work begins, completely isolated to the module repo
1. Issues are raised anywhere more info is needed
1. Manufacturers communicate internally using issues
1. When module is complete, ticket raised in the repo to signal completion
1. Once received, module is added to the assembly area in protected Canadian space as a git submodule
1. Top level program is run, and integration tests made to assure correct overall functionality
1. As errors are discovered, spec is altered in the module, and work continues on it, possibly once enough requirements have accumulated
1. If architects change any code, commits are made back to the module repo
1. If significant additional work is requested, new work order created, process begins again
1. If bug fixes found, issues opened in repo, work order reopened, extra hours added in there

Spec required for Interbit Objects:
1. 


Spec required for Interbit Solutions:


Spec required for UI components:


Spec required for UI Solutions:
