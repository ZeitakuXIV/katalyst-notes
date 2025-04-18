# 📋 Tabel Cheatsheet LaTeX (Input vs Output)  

## 1. Simbol Dasar  
| Kode Input        | Tampilan Output       | Keterangan   |     |
| ----------------- | --------------------- | ------------ | --- |
| `$x^2$`           | $x^2$                 | Pangkat      |     |
| `$\sqrt{a}$`      | $\sqrt{a}$            | Akar kuadrat |     |
| `$\frac{a}{b}$`   | $\frac{a}{b}$         | Pecahan      |     |
| `$\alpha, \beta$` | $\alpha, \beta, \phi$ | Huruf Yunani |     |

## 2. Matematika Lanjut  
| Kode Input                          | Tampilan Output               |  
|-------------------------------------|-------------------------------|  
| `$\sum_{i=1}^n i^2$`               | $\sum_{i=1}^n i^2$           |  
| `$\int_a^b f(x)dx$`                | $\int_a^b f(x)dx$            |  
| `$$\begin{matrix} 1 & 2 \\ 3 & 4 \end{matrix}$$` | $$\begin{matrix} 1 & 2 \\ 3 & 4 \end{matrix}$$ |  

## 3. Format Teks dalam Math  
| Kode Input                    | Tampilan Output         |  
|-------------------------------|-------------------------|  
| `$\text{kecepatan} = v$`      | $\text{kecepatan} = v$  |  
| `$\mathbf{A}x = \vec{b}$`     | $\mathbf{A}x = \vec{b}$ |  

## 4. Contoh Lengkap  
**Input**:  
```latex
$$ \boxed{E = mc^2} $$
```
**Output**:
$$ \boxed{E = mc^2} $$
## 📌 Core Symbols
### Greek Letters
```latex
$\alpha, \beta, \gamma, \Delta, \theta, \lambda$
```

### Operators
```latex
$\times, \div, \pm, \mp, \cdot, \cap, \cup$
```

### Relations
```latex
$\leq, \geq, \neq, \approx, \equiv, \propto$
```

## 🎨 Formatting
### Text in Math
```latex
$\text{velocity} = \frac{\text{distance}}{\text{time}}$
```

### Multi-line Equations
```latex
$$\begin{align}
a &= b + c \\
  &= e^{f} \times d
\end{align}$$
```

**Referensi**: https://quickref.me/latex.html