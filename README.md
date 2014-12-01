Dockerfile for GrowthForecast
=============================

## SYNOPSIS 

```
    git clone https://github.com/nekoruri/docker-growthforecast.git
    cd docker-growthforecast
    docker build -t nekoruri/growthforecast:0.1 .
    docker run -it --name growthforecast -v /home/vol/gf:/data:rw -p 5125:5125 nekoruri/growthforecast:0.1
```

