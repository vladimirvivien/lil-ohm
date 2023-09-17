# lil-ohm

The lil-om is a Go module for calculating electrical circuit values using Ohm’s law. The module was created as part of a course for LinkedIn Learning.

### Installation
You use the `go get` command to install the package:

```
go get github.com/vladimirvivien/lil-ohm@v0.1.0
```

### Using the module
This is a simple example of how to use package `volt` to calculate total voltage in a circuit arranged in series.

```go
volts := []float64{2, 4, 6, 8}
vtot := volt.Vser(volts…)
```
