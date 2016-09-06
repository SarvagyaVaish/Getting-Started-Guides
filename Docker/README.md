# Docker


Running an interactive process using ```-it```

```docker run -it ubuntu /bin/bash```


Starting a container in the background (detached mode), and how to [actually keep it running](http://stackoverflow.com/questions/30209776/docker-container-will-automatically-stop-after-docker-run-d).

```docker run -d ubuntu tail -f /dev/null```
