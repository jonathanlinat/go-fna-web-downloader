# Simple Go FNA HTTP Downloader

This is a really simplistic Go script that allows you to automatically download all available Fleuve Noir Anticipation ebooks from "http://zookd.free.fr/ZookdFN/Epub/".

## Details

This project uses [CavalierCoder's Grab package](https://github.com/cavaliercoder/grab) to as download manager.

### Prerequisites

- Go 1.17

## First steps

Clone locally the repository.

```
cd <path/to/your/desired/folder/>
git clone git@github.com:jonathanlinat/simple-go-fna-http-downloader.git
```

Install the dependencies.

```
cd simple-go-fna-http-downloader/
npm install
```

### Specific commands

Run the script.

```bash
go run main.go
```

Downloaded files will be available at root directory. In case of any error, you will be notified.
