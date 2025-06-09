| No | Integral                                            | Batas $x \in [0, L]$ | Hasil dalam bentuk $n$                                                               |
| -- | --------------------------------------------------- | -------------------- | ------------------------------------------------------------------------------------ |
| 1  | $\int_0^L \sin\left(\frac{n\pi x}{L}\right) dx$     | $0$ sampai $L$       | $\boxed{ \frac{2L}{n\pi} \left( 1 - (-1)^n \right) }$<br>→ hanya ≠ 0 jika $n$ ganjil |
| 2  | $\int_0^L \cos\left(\frac{n\pi x}{L}\right) dx$     | $0$ sampai $L$       | $\boxed{ \frac{2L}{n\pi} \sin(n\pi) = 0 }$                                           |
| 3  | $\int_0^L x \sin\left(\frac{n\pi x}{L}\right) dx$   | $0$ sampai $L$       | $\boxed{ \frac{L^2}{n\pi}(-1)^n }$                                                   |
| 4  | $\int_0^L x \cos\left(\frac{n\pi x}{L}\right) dx$   | $0$ sampai $L$       | $\boxed{ \frac{L^2}{n\pi} } \cdot \left[ \frac{(-1)^n - 1}{n\pi} \right]$            |
| 5  | $\int_0^L x^2 \sin\left(\frac{n\pi x}{L}\right) dx$ | $0$ sampai $L$       | $\boxed{ \frac{2L^3}{(n\pi)^2} (-1)^n }$                                             |
| 6  | $\int_0^L x^2 \cos\left(\frac{n\pi x}{L}\right) dx$ | $0$ sampai $L$       | $\boxed{ \frac{2L^3}{(n\pi)^2} (1 - (-1)^n) }$                                       |

| No | Integral                                                            | Batas $x \in \left[\frac{L}{2}, L\right]$ | Hasil dalam bentuk $n$                                                                            |
| -- | ------------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1  | $\int_{\frac{L}{2}}^L \sin\left(\frac{n\pi x}{L}\right) dx$         |                                           | $\boxed{ \frac{L}{n\pi} \left[ (-1)^{n+1} + \cos\left(\frac{n\pi}{2} \right) \right] }$           |
| 2  | $\int_{\frac{L}{2}}^L \cos\left(\frac{n\pi x}{L}\right) dx$         |                                           | $\boxed{ \frac{L}{n\pi} \left[ \sin(n\pi) - \sin\left(\frac{n\pi}{2} \right) \right] }$           |
| 3  | $\int_{\frac{L}{2}}^L x \sin\left(\frac{n\pi x}{L}\right) dx$       |                                           | $\boxed{ \frac{L^2}{n\pi}(-1)^n + \frac{2L^2}{n^2\pi^2} \sin\left( \frac{n\pi}{2} \right) }$      |
| 4  | $\int_{\frac{L}{2}}^L x \cos\left(\frac{n\pi x}{L}\right) dx$       |                                           | $\boxed{ -\frac{L^2}{n\pi} \cos(n\pi) + \frac{2L^2}{n^2\pi^2} \sin\left(\frac{n\pi}{2} \right) }$ |
| 5  | $\int_{\frac{L}{2}}^L (L - 2x)\sin\left(\frac{n\pi x}{L}\right) dx$ |                                           | $\boxed{ \frac{L^2}{n\pi}(-1)^n + \frac{2L^2}{n^2\pi^2} \sin\left( \frac{n\pi}{2} \right) }$      |
