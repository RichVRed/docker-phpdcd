## PHP Copy/Paste Detector (PHPCPD).
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/phpdcd.svg)](https://hub.docker.com/r/rvannauker/phpdcd/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/phpdcd.svg)](https://hub.docker.com/r/rvannauker/phpdcd/) [![](https://images.microbadger.com/badges/image/rvannauker/phpdcd:latest.svg)](https://microbadger.com/images/rvannauker/phpdcd:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-phpdcd.svg)](https://github.com/RichVRed/docker-phpdcd) [![license](https://img.shields.io/github/license/RichVRed/docker-phpdcd.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run phpdcd

### Installation / Usage
1. Install the rvannauker/phpdcd container:
```bash
docker pull rvannauker/phpdcd
```
2. Run phpdcd through the phpdcd container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="phpdcd" "rvannauker/phpdcd" {destination}
```

### Download the source:
To run, test and develop the PHPCPD Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-phpdcd.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/phpdcd" --file phpdcd.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/phpdcd --help
```