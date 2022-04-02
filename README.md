# nelua_pi

Formulas/Algorithms for calculating "Digits of Pi" implemented in [Nelua](https://nelua.io) programming language!

### Formulas

| Formula/Algorithm                   | Implementation                    | Lines |
|-------------------------------------|-----------------------------------|-------|
| [Abraham Sharp formula][1]          | [abraham_sharp.nelua][2]          | 41    |
| [Bailey-Borwein-Plouffe formula][3] | [bailey_borwein_plouffe.nelua][4] | 44    |
| [Bellard formula][5]                | [bellard.nelua][6]                | 51    |
| [Chudnovsky algorithm][7]           | [chudnovsky.nelua][8]             | 44    |
| [Newton/Euler (Horner Form)][9]     | [euler.nelua][10]                 | 42    |
| [Gauss-Legendre algorithm][11]      | [gauss_legendre.nelua][12]        | 53    |
| [Gregory-Leibniz formula for Pi][13]| [leibniz.nelua][14]               | 44    |
| [Madhava series][15]                | [madhava.nelua][16]               | 45    |
| [Rabinowitz series][17]             | [rabinowitz.nelua][18]            | 41    |
| [Ramanujan-Sato series][19]         | [ramanujan.nelua][20]             | 45    |
| [David E. Smith formula][21]        | [smith.nelua][22]                 | 45    |
| [Viète's formula][23]               | [viete.nelua][24]                 | 43    |
| [Wallis product][25]                | [wallis.nelua][26]                | 44    |

> NOTE: The file called `globals.nelua` which required by the implementations, Contains a bit of C externs and some functions that serves as supplementary...

[1]: https://mathworld.wolfram.com/PiFormulas.html
[2]: https://github.com/Rabios/nelua_pi/blob/main/abraham_sharp.nelua

[3]: https://en.wikipedia.org/wiki/Bailey%E2%80%93Borwein%E2%80%93Plouffe_formula
[4]: https://github.com/Rabios/nelua_pi/blob/main/bailey_borwein_plouffe.nelua

[5]: https://en.wikipedia.org/wiki/Bellard%27s_formula
[6]: https://github.com/Rabios/nelua_pi/blob/main/bellard.nelua

[7]: https://en.wikipedia.org/wiki/Chudnovsky_algorithm
[8]: https://github.com/Rabios/nelua_pi/blob/main/chudnovsky.nelua

[9]: https://mathworld.wolfram.com/ConvergenceImprovement.html
[10]: https://github.com/Rabios/nelua_pi/blob/main/euler.nelua

[11]: https://en.wikipedia.org/wiki/Gauss%E2%80%93Legendre_algorithm
[12]: https://github.com/Rabios/nelua_pi/blob/main/gauss_legendre.nelua

[13]: https://en.wikipedia.org/wiki/Leibniz_formula_for_pi
[14]: https://github.com/Rabios/nelua_pi/blob/main/leibniz.nelua

[15]: https://en.wikipedia.org/wiki/Madhava_series
[16]: https://github.com/Rabios/nelua_pi/blob/main/madhava.nelua

[17]: https://www.cut-the-knot.org/Curriculum/Algorithms/SpigotForPi.shtml
[18]: https://github.com/Rabios/nelua_pi/blob/main/rabinowitz.nelua

[19]: https://en.wikipedia.org/wiki/Ramanujan%E2%80%93Sato_series
[20]: https://github.com/Rabios/nelua_pi/blob/main/ramanujan.nelua

[21]: http://www.amazon.com/exec/obidos/ASIN/0486204294/ref=nosim/ericstreasuretro
[22]: https://github.com/Rabios/nelua_pi/blob/main/smith.nelua

[23]: https://en.wikipedia.org/wiki/Vi%C3%A8te%27s_formula
[24]: https://github.com/Rabios/nelua_pi/blob/main/viete.nelua

[25]: https://en.wikipedia.org/wiki/Wallis_product
[26]: https://github.com/Rabios/nelua_pi/blob/main/wallis.nelua

### Build

To run each example simply do `nelua <filename>.nelua` and it should works as expected...

### Configuration

The following options can be enabled via Nelua's `--define` flag when running the examples:

1. `WRITE_OUTPUT_RESULTS = 1` will let the program write calculation results to `<filename>_res.txt`
2. `NO_LOOP_LIMIT = 1` Disables loop limit (By default loop limit set to 20 times...)

### License

Public Domain (Unlicense), Do whatever you wanna with the source code... ;)

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
```
