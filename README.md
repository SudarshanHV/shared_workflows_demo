# shared_workflows_demo
## Usage Examples

Frontend based repos using the workflow: https://github.com/SudarshanHV/sw_hello_frontend_demo

Backend based repos using the workflow: https://github.com/SudarshanHV/sw_hello_backend_demo
## Key Points

* Reusable workflows with input parameters (inputs and secrets)
* Conditional execution depending on which branch calls it. (deploy on main)
* Workflow dependencies (Run deploy only after test)
* Different app types using the same workflow (ideal for cov collection type jobs)
* Cross-repository calling

## Reusable WorkFlows

The test workflow in ci-yml. Called through "uses" keyword in any other repo
Note that the repo needs to be public within the org to be usable elsewhere.

NOTE:

## Workflow Templates

Starter templates appearing in Github Actions tab

## Shared Workflows (General Term)

Can refer to:
a) Reusable workflows (as mentioned above)
b) Any workflow shared across multiple repos

