# Jenkins Shared Libraries

### ​​What is a Shared Library in Jenkins?

When we are implementing CI/CD as code, it must have modularity and reusability of the code. This is where Jenkins Shared Library comes into picture.

A shared library is a collection of independent Groovy scripts which you pull into your Jenkinsfile at runtime. The best part is that this Library can be stored, like everything else, in a Git repository.

Jenkins Shared Library is the concept of having a common pipeline code in the version control system that can be used by any number of pipelines just by referring to it in the pipeline code. It reduces the effort of the developer by keeping the same logic in multiple files.