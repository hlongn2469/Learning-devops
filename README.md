# Learning-devops

## Why is traditional way (Waterfall model) of integrating bad? 
- [ ] Integration is exhausting and effort consuming for stakeholders
- [ ] Fixing bugs and issues at the end of iterations
- [ ] Merge issues can hold up teams
- [ ] Long feedback cycle for functional defects
- [ ] Long iterations
## Continuous Integration (CI)
- [ ] Removes integration team to allow developers to self-integrate at each commit
- [ ] Each commit will be checked by the build server in terms of compilation, automated unit test, and automated UI test.
- [ ] Cardinal princple of CI
  * A single central repo where the code lives
  * Developers check in/commit their code frequently
  * Build should be triggered every time a developer checks in code
  * Build should be automated and fast
  * Build should compile the code as well as run automated
  * Fixing a failed build should be top priority for developers
  * Build results should always be communicated to all developers
- [ ] **BENEFITS**:
  * Integration is automated and quick
  * Issues show up early since frequent integration
  * Broken builds are fixed with immediate priority by developers
  * Shorter feedback cycle since developers are notified immediately
  * Shorter interations thus faster time-to-market
- [ ] Needs a **build pipeline** to generate the build server
## Pipeline
- [ ] Maximize efficiency and avoid idles within each phase of CI/CD

## Why is traditional way (Waterfall model) of operating bad? 
- [ ] Incorrectness of instructions
- [ ] Difference in instructions across environment
- [ ] Error prone nature of manual tasks
- [ ] Deployments are sophisticated, high-impact with downtime
## Continous Delivery (CD)
- [ ] Software development practice where software can be released to product at any time
- [ ] Removes manual task of reading instructions and preparing environment with automated script
- [ ] **BENEFITS**:
  * Correctness of automated scripts can be verified at creation time
  * Automated scripts can easily pick the tasks for each environment
  * Automation prevents the occurence of human errors
  * Automated deployment, easily repeatable, thus lesser time to market
- [ ] Needs a **release pipeline** to generate the build server
## Continuous deployment (CD)
- [ ] Software development practice where software is automatically released to production continously

## So what is CI/CD?
- [ ] Commonly, continous integration/continious delivery
- [ ] Uncommonly, continous integration/continious deployment
  * Only enterpises whose IT department has reached a very high maturity level that implement continous deployment due to its risks.
## Devops
- [ ] Development(CI) and operations (CD)
- [ ] CI/CD is seperated into 2 branches. CI Branch for dev and CD branch for ops
- [ ] New culture and new way of thinking as an improvement to traditional development and operations
