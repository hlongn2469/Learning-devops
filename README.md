# Learning-devops

## Why is traditional way (Waterfall model) of integrating bad? 
- [ ] Integration is exhausting and effort consuming for stakeholders
- [ ] Fixing bugs and issues at the end of iterations
- [ ] Merge issues can hold up teams
- [ ] Long feedback cycle for functional defects
- [ ] Long iterations
## Continuous Integration
- [ ] Removes integration & operations team to allow developers to self-integrate at each commit
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
