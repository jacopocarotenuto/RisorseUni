#### Elettrostatica

Gauss: $$ \phi_E = 4\pi r^2 E = \frac{Q_{int}}{\epsilon_0}\,\,\,|\,\, \,\nabla \cdot E = \frac{\rho}{\epsilon}$$  $$V = \frac{1}{4\pi\epsilon_0}\int \frac{\rho}{r}d\tau$$  |   Discontinuità: $$\Delta E_{\perp} = \frac{\sigma_{tot}}{\epsilon_0}\,\,\,\,\,\Delta E_{\parallel} = 0$$

Energia Elettrica $$U_E = \frac{1}{2}\int\rho V d\tau = \frac{\epsilon_0}{2}\int E^2 d\tau$$ | Pressione Elettro: $$p_0 = \frac{\sigma^2}{2\epsilon_0}\hat{u}_n \,\,\,\,\,\, \frac{dP}{d\tau} = E\cdot j = \sigma E^2$$

Dipolo: $$E = \frac{2p\cos\theta}{4\pi\epsilon_0r^3}\hat{u}_r + \frac{p\sin\theta}{4\pi\epsilon_0 r^2}\hat{u}_\theta = \frac{p}{4\pi\epsilon_0}\sqrt{3\cos^2\theta +1} \,\,|\,\, U = -\vec{p} \cdot \vec{E} \,\,\,|\,\,\, M = \vec{p}\times \vec{E}$$

Conduttori: $$E_{int} = 0 \,\,\,\,|\,\,\,\, V = cost \,\,\,|\,\,\, \rho = 0 \,\,\,|\,\,\,\, E_{sup} = \frac{\sigma^2}{2\epsilon_0}\hat{u}_n$$

Condensatori: *Serie*: $$\frac{1}{C} = \sum \frac{1}{C_i}$$ _Parallelo_: $$C = \sum C_i$$ *Energia*: $$U_E = \frac{1}{2}\sum V_iQ_i$$

*Piano*: $E = \frac{Q}{\epsilon_0 S}\,\,\,|\,\,\, V = Eh = \frac{Q h}{\epsilon_0 S} \,\,\,|\,\,\, C = \frac{\epsilon_0 S}{h}$  *Sferico*: $E = \frac{Q}{4\pi\epsilon_0 R^2}\,\,\,|\,\,\,V = \frac{Q}{4\pi\epsilon_= r}\,\,\,|\,\,\, C = 4\pi\epsilon_0 \frac{R_1 R_2}{R_2 - R_1}$     				*Cilindrico*: $E =\frac{Q}{2\pi\epsilon_0 h r}\,\,\,|\,\,\, V = \frac{Q}{2\pi\epsilon_0 h}\log{\frac{R_2}{R_1}}\,\,\,|\,\,\, C =\frac{2\pi\epsilon_0 l}{\log{\frac{R_2}{R_1}}}$

**Correnti**: $$DI = j \cdot d\Sigma$$ | $$j = Nq\left< v\right>$$ |  $$j = \sigma_{conduttivita} E$$ |  $$j = \frac{N q^2 \tau E}{m}$$  | $$\sigma_{conduttività} = \frac{N Q^2 \tau}{m}$$

**Ohm**: $$V = RI$$ | $$R = \rho\frac{l}{S}$$  |  $$E = \rho_{resistività}j$$ | $$\sigma_{conduttività} = \rho^{-1}$$ | $$\rho = [\Omega m]$$ | $$RC = \rho \epsilon_0$$ | $$U = \frac{1}{2}CV^2$$

**Kirchoff**: *Nodi* $$\sum I_i = 0$$  *Maglie* $$\sum R_iI_i = 0$$ **Dielettrici**: $p = \alpha \epsilon_0 E_{agente}$ |   $$\sigma_p = P \cdot \hat{u}_n$$ | $$\rho_p = - \nabla \cdot P$$  |   $$\Delta D_{\perp} = \sigma_{lib}\hat{u}_n$$ |  $$D = \epsilon_0 E + P = \epsilon_0(1 + \chi_E)E = \epsilon_0 k E$$  | $$U = \frac{1}{2}\epsilon E^2 \tau$$  | $$w_e = \frac{1}{2}D \cdot E$$  

**Forza elettrica che un dielettrico in un condensatore**: $$F = \frac{1}{2}V^2 \frac{dC}{dx}$$

#### Magnetismo

**Lorentz**: $$F = q(E + v \times B)$$ | $$r = \frac{mv}{qB}$$ | $$\omega = - \frac{qB}{m}$$  | $$E = \frac{F}{q} = v \times B$$  | passo $$d = v_0 \frac{2 \pi m}{qB}\cos\theta$$ 

**Fili**: $$dF_m = I ds \times B$$  |  Forza tra due fili (forza per metro) $$F_d = \frac{\mu_0 I_1 I_2}{2\pi R}$$  |  $$B = \frac{\mu_0 I N}{2\pi r}$$ 

**Spira/Dipolo**: $$M = IS\times B = \mu \times B$$ |  $$B = \frac{\mu_0 N I r^2}{2(r^2+x^2)}$$ |  $$\mu = IS$$  |  $$U = -\mu \cdot B$$  |  $$d\mu = I d\Sigma$$ 

**Flusso**: $$\Phi = MI$$ | $$\Phi = LI$$  |  $$\varepsilon = -\frac{d\Phi_B}{dt}$$  |  $$\int_{\gamma} E\cdot ds = -\frac{d\Phi_B}{dt}$$  |  $\varepsilon = \int E \cdot ds = \int v \times B \cdot ds$

**Solenoide Toroidale**: $$ B = \frac{\mu_0 I N}{2\pi r}$$  |  **Solenoide rettilineo indefinito**: $$B = \frac{\mu N I}{d}$$  |  **Solenoide rettilinea finito**: $$B(0,0,z) = \frac{\mu_0 N I}{2}\left(\frac{h/2 -z}{\sqrt{(h/2 -z )^2 + R^2}} + \frac{h/2 + z}{\sqrt{(h/2 + z)^2 + R^2}}\right)\hat{u}_z$$

**Energia**: $$U_L = \frac{1}{2}LI^2$$  |  $$U_B = \frac12\frac{B^2}{\mu_0}$$  |  $$U_{tot,circ,B} = \frac12\sum LI_j^2 + \sum_{i > j} M I_iI_j$$ 

**Correnti:** $j_m = \nabla \times M$  |  $\oint B \cdot dl = \epsilon_0 \mu_0 \frac{\partial \Phi_E}{\partial t}$  |  $\nabla \times B = \mu_0 j_m$  |  $\nabla \cdot B = 0 = \oint B \cdot d\Sigma$  |  $$\oint B \cdot ds = \mu_0 I_{conc}$$

**Material Magnetici**: $M = \frac{du}{d\tau}[A/m]$ |  $k_{m,(condu \,\,superf)} = M \times \hat{u}_n$  | $H = \frac{B}{\mu_0} -M$  |  $\nabla \times H = j_c(conduzione)$  |  $\oint H \cdot ds = I_c$  | $M = \chi_m H$  | $B = \mu_0(1+\chi_m)H = \mu_0 kH$ 

**Discontinuità**: $\Delta H_{\parallel} = K_c \times \hat{u}_n$  |  $\Delta B = -\Delta M$

**Cavità nei materiali:** *parallela* $H_{in} = H_{out}$  |  $B_{in} = B_{out} - \mu_0M$  *perpend*  $B_{in} = B_{out}$  |  $H_{in} = H_{out} + M$

**Diamagnetici**: $M = \frac{-e^2n\left<r^2\right>B}{6m_e} = \frac{\chi_m}{\chi_m +1}\frac{B}{\mu_0}$  **Paramagnetici:** $M = \frac{N \mu^2 B}{3 k T}$  |  $\chi_m = \frac{N \mu^2 \mu_0}{3kT}$

#### Onde

**Fondamentali**:  $k = \frac{2\pi}{\lambda}$  |  $\omega = \nu k = 2\pi v$  |  $\lambda = \frac{v}{\nu}$  |  $E = cB$  |  $n = \frac{\lambda_0}{\lambda} = \frac{c}{v}$  | $c^2 = \frac{1}{\epsilon_0\mu_0}$ |  (pressione tot ass)  $p = \frac{I}{c}\cos^2\theta$  | $I = \frac12\epsilon_0 c E$  | *Antenna Dipolare* $I = \frac{1}{r^2}I_0\sin^2\theta$ ,  $I = \frac{3P\sin^2\theta}{8\pi r^2}$  , $P = \int Id\Sigma$ 

**Riflessione/Trasmissione** : *Polarizzazione* :  *Parallela* $R = \left(\frac{\tan(\theta_i - \theta_t)}{\tan(\theta_i + \theta_t)}\right)^2$ *Perpendicolare* $R = \left(\frac{\sin(\theta_i -\theta_t)}{\sin(\theta_i + \theta_t)}\right)^2$ | $T = 1 - R$ | *Incidenza Normale:* $R = \left(\frac{n_1 -n_2}{n_1 +n_2}\right)^2$

**Interferenza**: $I = I_1 + I_2 + 2\sqrt{I_1I_2}\cos(\frac{2\pi}{\lambda}(r_2 - r_1))$ |$MAX: \sin\theta = \frac{\lambda}{d}m$  $MIN: \sin\theta = \frac{m\lambda}{Nd}$  $MAX SECOND: \sin\theta = \frac{(2m +1)\lambda}{2Nd}$ 

**Diffrazione**: $MAX: \sin\theta = \frac{(2m+1)\lambda}{2aN}$  $MIN: \sin\theta = \frac{m\lambda}{a}$

#### Roba Immaginaria

**Impedenze Complesse**: $Resistenza: Z_R = R$  $Induttanza: Z_L = i\omega L$  $Condensatore: Z_C = \frac{1}{i\omega C}$

**Circuito RLC in serie**: $\omega_0^2 = \frac{1}{LC}$  |  $\hat{V}=ZI$  | $\hat{V} = V_0e^{i\omega t}$  |  $\hat{I} = I_0 e^{i(\omega t + \phi)}$  |  $Z = Z_0e^{i\phi} = Z_R + iZ_x$ | $Z_0 = \sqrt{Z_R^2 + Z_x^2}$  | $Z_R = R$  | $Z_x = \omega L - \frac{1}{\omega C}$  | $\left<P\right> = \frac12I_0^2\Re{(Z)} = \frac{1}{T}\int_0^T P(t)dt$  | $\hat{I} = \frac{\hat{V}}{Z} = \frac{V_0}{z_0}e^{i(\omega t -\phi)}$ | $I_{max} = \frac{V_0}{|\Re(Z)|}$

