# Docker Ghost

Docker powered infrastructure hosting http://writing.veryaustin.com

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Production deployment will be updated soon.

### Prerequisites

- Docker
- NodeJS

## Deployment

Run locally in development mode:
```
docker-compose -f docker-compose.yml
```
Run locally in production mode:
```
docker-compose -f docker-compose.yml -f docker-compose.prod.yml 
```

## Built With

* [Ghost](http://ghost.org) - The blog framework used
* [Docker](https://www.docker.com/) - Container Platform
* [Amazon Web Services](https://aws.amazon.com/) - Storage for images & content


## Author

* **Austin Lauritsen** [Github: veryaustin](https://github.com/veryaustin) [Website](http://veryaustin.com)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Acknowledgments

* Thanks to the [Ghost](http://ghost.org) for the simple and clean blogging platform.
* Thanks to the team at [Docker](https://www.docker.com/) for the amazing technology that you build that makes the internet go!
