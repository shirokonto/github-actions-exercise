# GitHub Actions Exercise

An exercise for 'DevOps and SRE' on HTW Berlin

## Execute Tests

```bash
go test ./...
```

## Build the Container

```bash
docker build . -t my-app
```

## Run the Container

```bash
docker run -p 8080:8080 my-app
```
