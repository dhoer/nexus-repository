# Nexus Repository 

Adds [apt](https://github.com/sonatype-nexus-community/nexus-repository-apt) and [conan](https://github.com/sonatype-nexus-community/nexus-repository-conan) plugins to Nexus3 docker image.

### Build 

    docker build -t nexus-repository .

### Run 

    docker run -d -p 8081:8081 --name nexus-repo nexus-repository
