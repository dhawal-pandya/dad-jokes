If cobra- cli is not recognized, type this in the terminal :

```
go install github.com/spf13/cobra-cli@latest                
export PATH=$PATH:$(go env GOPATH)/bin     
```

this will temporarily set it up so you can run 

```
go run main.go random
```

for a dad joke.