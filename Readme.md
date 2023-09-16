# For Local Development:
### First install the dependencies:
```
    go install github.com/cosmtrek/air@latest
```

### Then run the following command:
```
    air init
```

<em>Don't forget configure the .air.toml file it will be created after running the above command. But in this repository it is already configured for windows so if you are using any other OS then you have to configure it manually. This https://github.com/gofiber/recipes/blob/master/air/.air.linux.conf is the link for linux configuration.</em>

### Then run the following command:
```
    air
```

# If you just looking what is going on in the project then you can run the following command:

### For Docker Image Build:
```
docker build -t <image-name> .
``` 

### For Docker Image Run:
```
docker run -p 8080:8080 --name <app-name> <image-name>
```