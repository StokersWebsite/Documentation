[[Learning Outcomes]]
4. You **design and implement** a (semi)automated software release process that matches the needs of the project context.

_Design and implement_: 
You design a release process and implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).

## github actions / docker
I used github actions to create a CI/CD pipeline. So everyime I pushed something to github it would check the code and then deploy it on docker.

![[GithubActions.png]]
![[DockerRunning.png]]
## Sonarcloud
Also when I pushed my API to github it ran a sonarcloud static code analysis.
![[Sonarcloud github action.png]]
