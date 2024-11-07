Repo templating xep is too early mention that its coming
Each of this must have reference to build ref
Within Build CRD have an option to call another workflow
Build CRD reference another Build CRD
1 to 1 relationship

Non lifecycle managed must not be done at CRD level
Do this at repo templating XGHA Gen

We should give access to push to releases
Tagging and releases need another XEP
we allow users access artifact

MoM

- Repo templating is too early to be presented yet, however good to be mentioned
- 1. Answered above
- 2. Non-lifecycle managed actions must not be bootstrapped from xCRs, These should be either team provided or templated using repo templates.
- 3. Flexible with this one, can leave out for first iterations and be tackled later. One idea is to use GitHub artifacts to allow users to do anything with the artifacts using post actions.
- 4. All Build CRs will be compiled into 1 GHA Workflow, if seperate image builds are required these can be configured using inputs.
