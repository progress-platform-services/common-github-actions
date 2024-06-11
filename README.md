# Common Github Actions for Progress-Platform-Services
Location for reusable workflows

## Naming convention
Typical workflows are stored in the `.github\workflows` directory.

Naming convention:
<workflow type>-<application>-<language>[-<action> || -<branch>][-<stub>].yml

- ci-utility-go-echo.yml
- ci-utility-go-echo-stub.yml - place this in the using repo to call the shared workflow above

- ci-agent-go-main.yml - does CI tasks (build, test, package) for Go-based agents on merges to main 
- cd-cli-go-dev.yml