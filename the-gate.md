## URGENT IMPLEMENTATION

Note: Maintainer or Admin permissions is needed for this. Since i don't have that, my task is to document it - this needs to be implemented for "Branch Protection".

    Go to the Settings tab of the repo on GitHub.

    Navigate to Branches -> Add branch protection rule.

    Branch name pattern: main.

    Check these boxes:

        [x] Require a pull request before merging.

        [x] Require status checks to pass before merging.

        Search and add these checks:

            frontend-ci

            backend-ci

            contracts-ci (or whatever your specific workflow names are).
