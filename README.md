# jp-dimension-parser


## Installation
```shell
$ go get -u github.com/k-yomo/jp-dimension-parser
```

## Example
```go
    dimension, ok := jp_dimension_parser.Parse("幅62cm×奥行73cm×高さ189cm")
    if ok {
        fmt.Println("width(cm):", dim.Width)
        fmt.Println("depth(cm):", dim.Depth)
        fmt.Println("height(cm):", dim.Height)
        // => width(cm): 62 
        // => depth(cm): 73 
        // => height(cm): 189
    }
}
```
