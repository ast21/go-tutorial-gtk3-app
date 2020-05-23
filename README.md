## Go GUI gtk3 app

Tutorial from [Habr](https://habr.com/ru/post/420035/)

### Install dependencies
```shell script
# gtk3 lib
sudo apt install libgtk-3-dev

# gtk3 GUI generator
sudo apt install glade

# go get dependencies
go get github.com/gotk3/gotk3/gtk \
    && go get github.com/gotk3/gotk3/gdk \
    && go get github.com/gotk3/gotk3/glib \
    && go get github.com/gotk3/gotk3/cairo
```

### Build
```shell script
go build main.go && ./main
```

or 

```shell script
go run main.go
```