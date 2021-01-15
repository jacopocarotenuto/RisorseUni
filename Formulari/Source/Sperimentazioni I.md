# Le formule della Statistica

### Funzione di Distribuzione

$$
F(x) = \int_{-\infty}^{x}f(t)dt
$$

Probabilità di trovare valori *non* superiori a x

### Propagazione Errori

Se f(x) è combinazione lineare allora teorema delle Varianze = propagazione errori
$$
\sigma_{f(\overline x)} \approx \sqrt{\left(\frac{df}{df}\right )^2 \sigma_{x}} \\
\text{se } z = z(x,y) \\
var(z) = \sigma^2_{z} \approx \left (\frac{\part z}{\part x}\biggr \rvert_{x^*,y^*} \right)\sigma^2_{x} + \left ( \frac{\part z}{\part x} \biggr \rvert_{x^*,y^*} \right)\sigma^2_{y} + 2\frac{\part z}{\part x} \cdot \frac{\part z}{\part y} \cdot cov(x,y)
$$

### Media Pesata

$$
\overline{x} = \frac{1}{\sum^n_i\frac{1}{\sigma_i^2}} \sum^N_i \frac{x_i}{\sigma_i^2} \\
\sigma_{\overline{x}} = \frac{1}{\sum^{N}_i \frac{1}{\sigma_i^2}}
$$

### Correlazione

$$
r = \frac{\sum(x_i - \overline{x})(y_i - \overline{y})}{\sqrt{\sum(x_i - \overline{x})^2 \sum(y_i - \overline{y})^2}} \\
r = \frac{N\sum x_i y_i - \sum x_i\sum y_i }{\sqrt{N\sum x_i^2 - (\sum x_i)^2}\sqrt{N\sum y_i^2 - (\sum y_i)^2}} \\
y = a + bx + \delta \\
\rho = \frac{cov(x,y)}{\sqrt{var(x)var(y)}}
\\
\rho = \frac{b var(x)^2}{\sqrt{b^2 var(x)^2 + var(\delta)var(x)}}
$$

### T Student

In generale
$$
t = \frac{\overline x - \eta}{\frac{s}{\sqrt N}} \\
s^2 = \sum \frac{x_i - \overline x}{N - 1}
$$
Se ho due campioni e voglio sapere se i valor veri sono compatibili
$$
t = \frac{\overline a - \overline b}{s\sqrt{\frac1N + \frac1M}} \\
s^2 = \frac{(N-1)s_a^2 + (M-1)s_b^2}{N + M -2}
$$

$$
t = \frac{r \sqrt{N -2}}{\sqrt{1 - r^2}}
$$

### Bernoulli

$$
f(x) = p^x(1 - p)^{n-x}\frac{N!}{x!(N-x)!}
$$

### Poisson

$$
f(x) = \frac{\alpha^x}{x!}e^{-\alpha} \\ E(x) = \alpha \\ var(x) = \alpha\\ \sigma_x = \sqrt{\alpha}
$$

### Esponenziale

Quindi Poisson con x = 0
$$
P(0) = \frac{(\lambda t)^0}{0!}e^{-\lambda t} = e^{-\lambda t}\\ var(t) = \frac{1}{\lambda^2} \\ \sigma_t = \frac1\lambda \\ E(t) = \frac1\lambda
$$

### Massima Verosomiglianza

$$
L = \prod f(x_i,\theta) \\ 
max(L) \Rightarrow \frac{dL}{d\theta} = 0 \;\;\; \& \;\;\; \frac{d^2L}{d\theta^2} < 0
$$
