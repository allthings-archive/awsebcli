# AWS Elastic Beanstalk Command Line Interface Dockerfile

## Usage

```sh
docker run --rm -it -v "$PWD:$PWD" -w "$PWD" \
  -e AWS_ACCESS_KEY_ID -e AWS_SECRET_ACCESS_KEY \
  allthings/awsebcli --help
```

## License
Released under the [MIT license](https://opensource.org/licenses/MIT).
