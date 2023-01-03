# GO-DSP

go-dsp is a digital signal processing package for the [Go programming language](http://golang.org).

## Packages

* **[dsputils](http://godoc.org/github.com/NectGmbH/go-dsp/dsputils)** - utilities and data structures for DSP
* **[fft](http://godoc.org/github.com/NectGmbH/go-dsp/fft)** - fast Fourier transform
* **[spectral](http://godoc.org/github.com/NectGmbH/go-dsp/spectral)** - power spectral density functions (e.g., Pwelch)
* **[wav](http://godoc.org/github.com/NectGmbH/go-dsp/wav)** - wav file reader functions
* **[window](http://godoc.org/github.com/NectGmbH/go-dsp/window)** - window functions (e.g., Hamming, Hann, Bartlett)

## Installation and Usage

```$ go get github.com/NectGmbH/go-dsp/fft```

```
package main

import (
        "fmt"

        "github.com/NectGmbH/go-dsp/fft"
)

func main() {
        fmt.Println(fft.FFTReal([]float64 {1, 2, 3}))
}
```
