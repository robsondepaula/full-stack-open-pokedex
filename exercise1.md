For the Go programming language the tools to lint, test and build are built-in. In order to test we have to issue "go test", to lint we have "golint", "gofmt" and "go vet" and finally to build we use "go build".

Some other alternatives to set up CI other than the ones mentioned in the course are: Circle CI, Travis CI, AWS CodeBuild, Google Cloud Build and Azure DevOps.

The decision between a self-hosted or cloud-based env is better answered knowing who and where these 6 people work. If it is a distributed team with persons from different parts of the world in a startup a cloud-based solution would be best, due to the nature of their enterprise.
On the other hand, a big company which is usually slow to adopt technologies for any particular reason might impose to this team of 6 people that their only option is a self-hosted setup.

In other words, the information needed would be: type of the project, team structure, project target audience, stakeholder opinion.

With the liberty to decide I would choose hosting the setup with GitHub Actions and if the project that we would work on would be a web app deployed on a particular cloud vendor I would carefully verify if their alternative offers more value to the team.
