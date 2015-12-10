# docker-beanstalkd

This is a Docker image for [beanstalkd](https://github.com/kr/beanstalkd).

## Usage

To run `beanstalkd` on the default exposed port, 11300:

``` bash
docker run inquicker/beanstalkd
```

To specify your own arguments to `beanstalkd`:

``` bash
docker run inquicker/beanstalkd -l 10.10.10.10 -p 5678
```

## License

[MIT](http://opensource.org/licenses/MIT)
