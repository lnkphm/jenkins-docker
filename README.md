# jenkins-docker

Yes, this is just docker-compose version from [Jenkins Documentation](https://www.jenkins.io/doc/book/installing/docker/)

## Installation

1. Install [Docker](https://docs.docker.com/engine/install/)

2. Create a bridge network

   ```bash
   docker network create jenkins
   ```

3. Build image for jenkins (you can change to another name, remember to change on `docker-compose.yml` too)

   ```bash
   docker build -t lnkphm-jenkins:lts-jdk17
   ```

4. Run `docker-compose.yml`

   ```bash
   docker compose up -d
   ```

5. Go to `http://localhost:8080` to continue setup
6. Enjoy

## Usage

RTFM

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
