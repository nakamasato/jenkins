# Jenkins

## Setup

1. Run jenkins

    ```
    docker run -p 8080:8080 -p 50000:50000 -v ${PWD}/jenkins_home:/var/jenkins_home jenkins/jenkins
    ```

1. New item for your repo

    - Create item
    - Set up the credentials using `deploy key` in case of github repo

