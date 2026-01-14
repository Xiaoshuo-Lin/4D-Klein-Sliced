# 4D-Klein-Sliced [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xiaoshuo-lin/4D-Klein-Sliced/main?urlpath=pluto/open?path=4D-Klein-Sliced.jl)

## Code for visualizing hyperplane sections of the embedded Klein bottle in 4D.

We embed the Klein bottle into $\mathbb{R}^4$ using the parametrization

$$\Phi(u,v)=\left(\sin v\sin\frac{u}{2},\sin v\cos\frac{u}{2},(2+\cos v)\sin u,(2+\cos v)\cos u\right)$$

for $(u,v)\in[0,2\pi)\times[0,2\pi)$.

https://github.com/user-attachments/assets/5441a3ac-be22-454a-b279-bb704de825e7

In the visualization above, the *height* being scanned corresponds to the coordinate along the **fourth dimension** of $\mathbb{R}^4$. Interpreted as a [**Morse function**](https://ncatlab.org/nlab/show/Morse+function) on the Klein bottle, this height function has two index-one critical points at height values $\pm1$.

For more details, please refer to [my note on topology](https://xiaoshuo-lin.github.io/001707E/Tut-8.pdf).
