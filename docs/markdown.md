
# Mixed

This contains all tags randomly mixed together, to make sure style changes in one does not affect others.

### A heading

**Quite a Strong statement , to make**

~~No, cross that~~

> Whose **quote** is this
>
> > And ~~this~~
> >
> > > - and
> > > - this
> > > - also

```
You encountered a wild codepen
```

```rust,editable
// The codepen is editable and runnable
fn main(){
    println!("Hello world!");
}
```

<kbd>Ctrl</kbd> + <kbd>S</kbd> saves a file.

A random image sprinkled in between

![16x16 rust-lang logo](https://rust-lang.org/logos/rust-logo-16x16.png)

---

- ~~An unordered list~~
- **Hello**
- _World_
- What
  1. Should
  2. be
  3. `put`
  4. here?
  5. **<kbd>Ctrl</kbd> + <kbd>S</kbd> saves a file.**

| col1 | col2 | col 3 | col 4 | col 5 | col 6 |
| ---- | ---- | ----- | ----- | ----- | ----- |
| val1 | val2 | val3  | val5  | val4  | val6  |

| col1 | col2 | col 3 | An Questionable table header | col 5 | col 6                                    |
| ---- | ---- | ----- | ---------------------------- | ----- | ---------------------------------------- |
| val1 | val2 | val3  | val5                         | val4  | An equally Questionable long table value |

### Things to do

- [x] Add individual tags
- [ ] Add language examples
- [ ] Add rust specific examples

And another image

![2018 rust-conf art svg](https://raw.githubusercontent.com/rust-lang/rust-artwork/461afe27d8e02451cf9f46e507f2c2a71d2b276b/2018-RustConf/lucy-mountain-climber.svg)


# MathJax

Fourier Transform

\\[
\begin{aligned}
f(x) &= \int_{-\infty}^{\infty}F(s)(-1)^{ 2xs}ds \\\\
F(s) &= \int_{-\infty}^{\infty}f(x)(-1)^{-2xs}dx
\end{aligned}
\\]

The kernel can also be written as \\(e^{2i\pi xs}\\) which is more frequently used in literature.

> Proof that \\(e^{ix} = \cos x + i\sin x\\) a.k.a Euler's Formula:
>
> \\(
\begin{aligned}
  e^x &= \sum_{n=0}^\infty \frac{x^n}{n!} \implies e^{ix} = \sum_{n=0}^\infty \frac{(ix)^n}{n!} \\\\
  \cos x &= \sum_{m=0}^\infty \frac{(-1)^m x^{2m}}{(2m)!} = \sum_{m=0}^\infty \frac{(ix)^{2m}}{(2m)!} \\\\
  \sin x &= \sum_{s=0}^\infty \frac{(-1)^s x^{2s+1}}{(2s+1)!} = \sum_{s=0}^\infty \frac{(ix)^{2s+1}}{i(2s+1)!} \\\\
  \cos x + i\sin x &= \sum_{l=0}^\infty \frac{(ix)^{2l}}{(2l)!} + \sum_{s=0}^\infty \frac{(ix)^{2s+1}}{(2s+1)!} = \sum_{n=0}^\infty \frac{(ix)^{n}}{n!} \\\\
         &= e^{ix}
\end{aligned}
\\)
>


Pauli Matrices

\\[
\begin{aligned}
  \sigma_x &= \begin{pmatrix}
  1 & 0 \\\\ 0 & 1
  \end{pmatrix} \\\\
  \sigma_y &= \begin{pmatrix}
  0 & -i \\\\ i & 0
  \end{pmatrix} \\\\
  \sigma_z &= \begin{pmatrix}
  1 & 0 \\\\ 0 & -1
  \end{pmatrix}
\end{aligned}
\\]





