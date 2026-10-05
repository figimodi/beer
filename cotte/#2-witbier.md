# Cotta #2

<table>
  <tbody>
    <tr>
      <td>Data</td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>TBD</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <u>Stime e obbiettivi</u>
<table>
  <tbody>
    <tr>
      <td>Stile</td>
      <td>Witbier (24A)</td>
    </tr>
    <tr>
      <td>Litri in fermentatore</td>
      <td>9 L</td>
    </tr>
    <tr>
      <td>Efficenza Stimata</td>
      <td>70%</td>
    </tr>
    <tr>
      <td>OG Target</td>
      <td>1048</td>
    </tr>
    <tr>
      <td>FG Target</td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>IBU</td>
      <td>TBD</td>
    </tr>
  </tbody>
</table>

### Profilo dello stile

<table>
  <tbody>
    <tr>
      <td>OG</td>
      <td>1.044-1.052</td>
    </tr>
    <tr>
      <td>FG</td>
      <td>1.008-1.012</td>
    </tr>
    <tr>
      <td>IBU</td>
      <td>8-20</td>
    </tr>
    <tr>
      <td>SRM</td>
      <td>2-4</td>
    </tr>
    <tr>
      <td>ABV</td>
      <td>4.5-5.5%</td>
    </tr>
  </tbody>
</table>

## <u>Malto</u>

$$
\begin{aligned}
&V_{boll,f} = V_{fer} + V_{scr} = 9 + 2 = 11\\
&P_{tot} = GU_{boll,f} \cdot V_{boll,f} = 48 \cdot 11 = 528
\end{aligned}
$$

Fermentabili utilizzati:
- Malto d'orzo `Château Pilsen`
- Malto di frumento `Château Wheat Blanc`
- Frumento non maltato
- Fiocchi d'avena

Estratto potenziale dei fermentabili:

|Ingrediente da ammostare|Estratto potenziale|
|:---:|:---:|
|Malto Pilsener|29-31|
|Frumento maltato|31-33|
|Frumento non maltato|30|
|Avena|28|

La ricetta di pinta.it ha queste proporzioni:
- $2,5\mathrm{kg}$ Château Pilsner
- $1.2\mathrm{kg}$ Château Wheat Blanc
- $0.7\mathrm{kg}$ Torrified Wheat (Frumento non maltato)
- $300\mathrm{g}$ Fiocchi d’avena

Normalizziamo ogni peso per l'estratto potenziale:
- $2.5\mathrm{g}*30 = 75$ parti di Château Pilsner
- $38.4$ parti di Château Wheat Blanc
- $21$ parti di Torrified Wheat
- $8.4$ parti di Fiocchi d'avena

Ora le percentuali $P_i^\prime$ di ciascun malto sono:
- $\sim52.5$% Château Pilsner
- $\sim26.9$% Château Wheat Blanc
- $\sim14.70$% Torrified Wheat
- $\sim5.9$% Fiocchi d'avena

$$
\begin{aligned}
& \text{Château Pilsner}: P_1 = P_{tot} * P_i^\prime = 528\cdot0.525=272.2 \\
& \text{Château Wheat Blanc}: P_2 = 142.032\\
& \text{Torrified Wheat}: P_3 = 77.616\\
& \text{Fiocchi d'avena}: P_4 = 31.152
\end{aligned}
$$

$$
\begin{aligned}
& \text{Château Pilsner}: W_1 = \dfrac{P_1}{e^\prime_1 \cdot 10 \cdot \varepsilon} = \dfrac{272.2}{30 \cdot 10 * \cdot 0.7} \approx 1.3\mathrm{kg} \\
& \text{Château Wheat Blanc}: W_2 \approx 630\mathrm{g}\\
& \text{Torrified Wheat}: W_3 \approx 370\mathrm{g}\\
& \text{Fiocchi d'avena}: W_4 \approx 160\mathrm{g}
\end{aligned}
$$

## <u>Luppolo</u>

Luppoli utilizzati:
- Luppolo `Bobek` in pellet $\alpha=4.2$%
- Luppolo `Saaz` in pellet con $\alpha=3.5$%

Da ricetta abbiamo queste proporzioni:
- $25\mathrm{g}$ luppolo Bobek $\alpha=4.5$ (60min)
- $25\mathrm{g}$ luppolo Saaz $\alpha=3.2$ (15 min)

Siccome i luppoli comprati hanno $\alpha$ diversi calcoliamo la vera proporzione dei due luppoli in termini di amaro:
- $25\cdot4.5 /4.2\approx26.8\mathrm{g}$ effettivi di Bobek
- $25\cdot3.2/3.5\approx22.8\mathrm{g}$ effettivi di Saaz

$$
\dfrac{W_{amr}}{W_{aro}}=1.17
$$

$$
\begin{cases}
IBU_1 + IBU_2 = IBU \\
\dfrac{W_1}{W_2} = 1.17
\end{cases}
$$

$$
\begin{cases}
\dfrac{W_1 \cdot 0.3 \cdot 0.042 \cdot 1000}{11}+\dfrac{W_2 \cdot 0.15 \cdot 0.035 \cdot 1000}{11} = 15 \\
\dfrac{W_1}{W_2} = 1.17
\end{cases}
$$

$$
\dfrac{63}{55}W_1+\dfrac{21}{44}W_2 = 1.34W_2+0.48W_2= 15 \\
$$

$$
\begin{cases}
W_1 \approx 9.64 \\
W_2 \approx 8.24
\end{cases}
$$

Scegliamo per semplicità $W_1=10\mathrm{g}$ e $W_2=8\mathrm{g}$.

## <u>Lievito</u>

$10\mathrm{g}$ lievito `M21 Belgian Wit Yeast`<br>
Il produttore dice di usarlo fino a $23\mathrm{L}$ di mosto.

|Descrizione|Valore|
|:---:|:---:|
|Classificazione|`Saccharomyces cerevisiae`|
|Attenuazione apparente ($\alpha$)|alta ($70$-$75$%)|
|Tolleranza alcolica|$8$% $ABV$|
|Temperatura di fermentazione| $18$-$25\mathrm{°C}$|
|Cellule per grammo|$>5 \cdot 10^9 \mathrm{cells/g}$|
|Flocculazione|2 su 5|

Al momento dell'inoculo abbiamo ottenuto una $OG=TBD$
Considerando un valore di attenuazione apparente di $73$% possiamo stimare $FG$:

$$
\begin{aligned}
&FG=OG-(OG-1)\cdot\alpha=xxx\\
\end{aligned}
$$

## <u>Acqua</u>

Abbiamo usato acqua X.

$$
\begin{aligned}
&V_{tot}=V_{fer}+V_{scr}+V_{evp}+V_{ass} = xxx \mathrm{L}\\
\end{aligned}
$$

### Suddivisione acqua di sparge e acqua di mash

$$
\begin{aligned}
&\rho^{-1}=1\mathrm{L/kg}\\
&V_{msh}=\rho^{-1}\cdot W_{tot}=xxx\mathrm{L}\\
&V_{tot} = V_{msh} + V_{spg}=xxx\mathrm{L}\\
\end{aligned}
$$

### Tipologia di acqua

Il profilo dell'acqua risultante è circa:

|Ione|Quantità in $\mathrm{mg/L}$|
|:---:|:---:|
|Calcio $\mathrm{Ca^{2+}}$|$xxx$|
|Magnesio $\mathrm{Mg^{2+}}$|$xxx$|
|Sodio $\mathrm{Na^+}$|$xxx$|
|Cloruro $\mathrm{Cl^-}$|$xxx$|
|Solfato $\mathrm{SO_4^{2-}}$|$xxx$|
|Bicarbonato $\mathrm{HCO_3^-}$|$xxx$|

Con un residuo fisso di $xxx\mathrm{mg/L}$.

## <u>Altri ingredienti</u>

Altr ingredienti in bollitura:
- Arancia amara (15min)
- Coriandolo in semi (5min)

## <u>Fermentazione</u>

Dopo $n\mathrm{gg}$ a $x\mathrm{°C}$ abbiamo ottenuto una $FG=TBD$, per cui:

$$
\begin{aligned}
&ABV=(OG-FG)\cdot 131.25=xxx\\
\end{aligned}
$$

## <u>Imbottigliamento</u>

I `volumi di CO2` target che abbiamo impostato sono di $V_{CO_{2}}^F=TBD\mathrm{vol}$.<br>
Considerato che $T_{fer}=TBD\mathrm{°C}$, e seguendo la tabella qua sotto, si può ottenere che il mosto in fermentatore ha già $V_{CO_{2}}^I\approx TBD \mathrm{vol}$.

$$
\begin{aligned}
&W_{s}^L=(V_{CO_{2}}^F-V_{CO_{2}}^I) \cdot 3.86\\
&W_{s} = W_{s}^L\cdot V_{fer}\\
&V_w=2 \cdot W_{s} - (W_s \cdot 0.63)\\
&V_{sol}^{L} = \dfrac{W_{s}^L}{\rho}\\
&V_{sol}^{33cL} = \dfrac{W_{s}^L}{\rho}\cdot 0.33\\
&{\Delta}ABV={W_s^L}\cdot 0.0648\\
\end{aligned}
$$

Il grado alcolico totale è $ABV=xxx$%.
