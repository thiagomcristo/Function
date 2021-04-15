# Function
1. Install docker
2. Install https://github.com/Azure/azure-functions-core-tools
3. Donwload this repo
4. On CMD run `docker build -t httptriggerexample .`
5. Run `docker images` to see/find the name of the image you just created.
6. Run `docker run  -p <port> <imageName>`. E.g.: `docker run  -p 8080:80 httptriggerexample`.
7. Open a new browser tab and go to: http://localhost:8080.
8. Open a new browser tab and go to: http://localhost:8080/api/httptriggerexample?name=Thiago.
