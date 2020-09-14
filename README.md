# Docker Container Name

A docker container to build mulesoft apps using Maven and deploy muleosft apps to Design Center, Exchange, API Manager, Cloudhub Runtime Manager using Anypoint-CLI. Also uses Azure CLI to integrate with Azure Keyvault. This container can be used by build pipeline like BitBucket, GitLab, etc.


## Getting Started

For local usage, you can spin the container
```shell
docker run --rm -it -v ~/.anypoint/:/root/.anypoint -v `pwd`:/mycode docker-maven-anypointcli-v1:latest bash
```


### Prerequisities


In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

#### Container Parameters


#### Environment Variables


#### Volumes

* `/root/.anypoint` - Path to anypoint-cli credentials

#### Useful File Locations


## Built With


## Find Us

* [GitHub](https://github.com/nabsha/docker-maven-anypointcli-v1)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the 
[tags on this repository](https://github.com/your/repository/tags). 

## Authors

* **Nabeel Shaheen** - *Initial work* - [Nabsha](https://github.com/nabsha)

See also the list of [contributors](https://github.com/nabsha/docker-maven-anypointcli-v1/graphs/contributors) who 
participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* People you want to thank
* If you took a bunch of code from somewhere list it here