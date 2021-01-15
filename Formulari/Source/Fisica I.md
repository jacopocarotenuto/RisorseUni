# Le Equazioni Della Fisica

## Il Punto Materiale

### Le equazioni Del Moto

$$
x(t) = x_0 + v_0t + \frac{1}{2}at^2
$$

$$
v(t) = at
$$

#### Moto Verticale

$$
v(x) = \sqrt{2g(h - x)} \\ t(x) = \sqrt{\frac{2(h-x)}{g}} \\ t_c= \sqrt{\frac{2h}{g}} \\ \text{Velocita' al suolo }v_s =\sqrt{2gh} 
$$

### Moto Armonico Semplice

$$
x(t) = Asen(\omega t + \phi) \\ v(t) = \omega A cos(\omega t + \phi) \\ a(t) = -\omega^2 A sen(\omega t + \phi) = -\omega^2x \\ \text{Equazione differenziale del moto armonico} \\ 
\frac{d^2x}{dt^2} + \omega^2x = 0
$$

### Moto Circolare

$$
a_c = \frac{v^2}{r} \\ \alpha = \frac{a_t}{r}
$$

### Moto Parabolico

$$
x(t) = v_0cos(\theta) t \\ y(t) = v_0sen(\theta)t - \frac{1}{2}gt^2 \\ y(x) = xtg(\theta) - \frac{g}{2v_0^2cos^2(\theta)}x^2 \\ x_G = \frac{2v_0^2cos(\theta)sen(\theta)}{g} \\ y_M = \frac{v_0^2sen^2(\theta)}{2g}
$$

## Energie

$$
\text{Cinetica }E_k = \frac{1}{2}mv^2 \\ \text{Elastica } E_{el} = \frac{1}{2}kx^2 \\ \text{Gravitazionale } U_g = mgh      \\ \text{Attrito } E_a = N\mu x              \\
\text{Rotazionale }E_{kr} = \frac{1}{2}I_z\omega^2
$$



## Gravitazione

$$
SemiAssi\\ \rightarrow a = -\frac{GMm}{2E_{tot}} = - \frac{GM}{v^2 + \frac{GM}{r^2}}\\ \rightarrow b^2 = \frac{L^2a}{Gm^2M}\\Periodo\\ T = \sqrt{\frac{2\pi^2a^3}{GM}} \\ \text{Velocita' di fuga}\\v_f = \sqrt{2\gamma\frac{M}{R}} \\ \text{Periodo}\\T^2 = \frac{4\pi^2r^3}{M\gamma} = \frac{4\pi^2 r^2}{v^2} \\ \text{Velocita' orbitale} \\ v_{orb}^2 =\frac{GM}{r} \\ \text{Equazione dei razzi} \\ M_f = M_ie^{-\frac{\Delta V}{v_{gas}}} \text{ oppure } \Delta V = v_{gas}\ln{\frac{M_i}{M_f}}
$$

## Sistema Di Punti Materiali

**Centro di massa**: Il punto geometrico la cui posizione è individuata, nel sistema di riferimento considerato, dal raggio vettore 
$$
r_{CM} = \frac{\sum_i m_i r_i}{\sum_i m_i}
$$

#### Equazioni Di Konig

$$
L_{tot} = L' + L_{CM}\\E_{k,tot} = E_{k}' + E_{k,CM}\\X' = rispetto\;al\;centro\;di\;massa\\X_{CM} = del\;centro\;di\;massa
$$

## Corpi Rigidi

## Equazioni Fondamentale

$$
\frac{dL}{dt} = \Gamma^{(e)}_{\Omega} - v_{\Omega} \times mv_{CM} \\ \frac{dP}{dt} = Ma_{CM} = R^{(e)} \\ E_k = \frac12Mv_{CM}^2 + E'_k \\ L_{\Omega} = r \times Mv_{cm} + L' \\ \Gamma^{(e)}_z = I_z\alpha
$$

### Teorema di Steiner

$$
I'_z = I_z + Md^2
$$



### Momenti

$$
\text{Disco } I_z = \frac{1}{2}Mr^2 \\ \text{Sfera } I_z= \frac{2}{5}Mr^2 \\ \text{Lastra Rettangolare } I_z = \frac{1}{12}M(a^2 + b^2) \\ \text{Sbarra per estremo } I_z = \frac13ML^2 \\ \text{Cubo } I_z = \frac16Ma^2
$$



### Puro Rotolamento

$$
\left\{ 
\begin{array}
 fF - F_{att} = Ma'_0 \\
 F_{att}R = I'_0\alpha \\
 a'_0 = \alpha R
\end{array} 
\right.
$$

## Fluidi

Legge di Stevino
$$
p(h) = p_0 + \rho g h
$$
Forza di Archimede
$$
F_A = -\rho V g
$$
Forza di Attrito Interno Viscosita
$$
dF = \eta dS\frac{dv}{dn}
$$
Teorema di Bernoulli (Regime Stazionario)
$$
p +\frac12\rho v^2 +\rho g h = costante
$$

$$
E = \frac{1}{2}\rho v^2 \\
Portata = Q = Sv
$$

## Calorimetria

Se due corpi si toccano:
$$
\Delta Q = mc\Delta T \\
T_e = \frac{m_1c_1T_1 + m_2c_2T_2}{m_1c_1 + m_2c_2} \\
1\; Cal= 4,184\; J
$$

### I Principio Della termodinamica

Se *f* funzione di stato
$$
\oint df = 0 \\
dU + dW = nc_v dT + pdV = 0
$$

### II Principio della dinamica

Gli scambi di calore spontanei sono solo da una temperatura più bassa ad una più calda, mai viceversa.

### Enunciato di Kelvin-Planc

Non può esistere un ciclo mono-termo con **produzione** di lavoro

## Gas

Legge Principale:
$$
PV = nRT
$$

$$
Isoterma \\
W_{ab} = \int^b_aPdV = \int^b_a \frac{nRT}{V}dV = nRT \log\frac{V_b}{V_a} \\
Isobara \\
Q = nc_p\Delta T \\
c_p = \frac1n \frac{dQ}{dt}\\
W = p\Delta V = nR\Delta T\\
Isocora \\
dQ = nc_vdT \\
Adiabatica \\
T_fV_F^{\gamma - 1} = T_iV_i^{\gamma -1} \;\; \gamma = \frac{c_p}{c_v}
$$

### PER QUALSIASI GAS

$$
\Delta U = nc_v \Delta T \\
Q = nc_V\Delta T [V = cost]\\
Q = nc_p\Delta T [P = cost]\\
c_p - c_v = R \\
pV = nRT \\\
$$



### Trasformazioni

**Isoterma**
$$
W = nRT\log(\frac{V_b}{V_a}) = Q \\
\Delta U = 0
$$
**Isobara**


$$
\Delta U = Q - W \\
W = \int^b_apdV = p\Delta V\\
Q = nc_p\Delta T
$$
**Isocora**
$$
\Delta U = Q - W\\
W = 0 \\
Q = nc_v\Delta T
$$


### Relazione di Meyer

$$
c_p -c_v = R \\
c_v = \frac l 2 R
$$

### Equazioni di Poisson

$$
\gamma = \frac{c_p}{c_v}\\
TV^{\gamma - 1} = cost \\
PV^{\gamma} = cost\\
TP^{\frac1\gamma - 1} = cost
$$

### Macchine Termiche

$$
\eta = \frac{W}{Q_{ass}} = 1 - \frac{|Q_{ced}|}{Q_{ass}} \\
\text{Quando e' una macchina di Carnot}\\ 
\eta = 1 - \frac{T_f}{T_c} \Rightarrow \frac{Q_f}{T_f} + \frac{Q_c}{T_c} = 0
$$

### Teorema di Clausius

$$
\sum \frac{Q_i}{T_i} \le 0\\
\oint \frac{dQ}{T} \le 0\\
S = \frac{dQ}{T}rev \Rightarrow \oint dS \le 0 \Rightarrow S(B) - S(A) = \Delta S \le 0
$$

### Entropia del gas ideale

$$
\Delta S = S(B) - S(A) = \int^{T_B}_{T_a}nc_v\frac{dT}{T} + \int^{V_b}_{V_a}nR\frac{dV}{V} = nc_v\log\frac{T_b}{T_a} + nR\log\frac{V_b}{V_a} = nc_v\log{\frac{P_bV_b^{\gamma}}{P_aV_a^\gamma}}
$$

# 	Appendice Sulle Equazioni Differenziali

$$
\frac{d^2x}{dt^2} + \omega^2x = 0 \Longrightarrow x(t) = Asen(\omega t + \phi)
$$

------


$$
\frac{dv}{dt} = -kt \\ \Longrightarrow v(t) = -\frac12kt^2 \\ \Longrightarrow x(t) = \frac{V_0}{k}(1 - e^{-kt})
$$

------


$$
\frac{dv}{dt} = - kv \\ \Longrightarrow v(t) = c_1e^{-kt}\\ \Longrightarrow x(t) = -\frac{1}{k}v_0e^{-kt} + x_0 + \frac{1}{k}v_0
$$

# Le Costanti

$$
G[\gamma] = 6,67 \cdot 10^{-11} \;\;\frac{Nm^2}{kg^2}
$$

$$
R = 8,314 \frac{J}{K mol} = 8.205 \cdot 10^{-5} \frac{m^3atm}{Kmol} = 8314 \frac{lPa}{Kmol} \\ 1 \;l = 0.001 \;m^3
$$

$$
p_{atm} = 1 \;atm = 101235\; Pa\\
1 \; cal = 4,184\; J
$$

$$
\text{Calore specifico acqua: }c = 4186\; \frac{J}{kg K} 
$$

