# Chrome for Dev
chrome or chromium for each platform with docker

```.sh
$ git clone https://github.com/Nakanoamane/chrome_for_dev.git

$ cd chrome_for_dev
```


## Build

### M1 chip

```.sh
$ docker-compose build
```

### intel chip

```.sh
$ docker-compose build --build-arg CHROME_REPOSITORY=selenium/standalone-chrome
```

## Confirm

```.sh
$ docker-compose up
```

[http://localhost:4444](http://localhost:4444)

