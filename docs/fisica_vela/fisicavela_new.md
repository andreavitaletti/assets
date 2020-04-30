---
presentation:
  width: 1024
  height: 768
---
<!-- slide -->

# La Fisica della Vela
## A gentle introduction

<img src="assets/einstein.jpg" height=300pt >

Andrea Vitaletti

<img src="assets/vlv.png" height=80pt ><img src="assets/akua.png" height=80pt>

<!-- slide -->

# Disclaimer

* I'm an engineer ... sorry for that ;-)
* I'm a modest sailor ... sorry also for that ;-)
* A lot of simplifications
* I tried to credit the work by others on links. If something is missing, first of all I'm really sorry, then please point it out

<img src="assets/by-sa.png">

<!-- slide -->

# Evoluzione 

<img src="assets/evoluzione.jpg" height=500pt>

[source](https://www.velavventura.com/storia-della-vela/) and [source](http://sailingtrivia.ravenyachts.fr/2015/06/little-americas-cup-book-four-side.html)

<!-- slide -->

# Le andature

<a href="https://ormeggionline.com/blog/wp-content/uploads/2013/08/ANDAURE.jpg">
<img src="assets/andature.jpg" height=500pt>
</a>


<!-- slide -->

# Cominciamo da un treno trainato da una fune!

<img src="assets/binari.png" height=500pt>

Next slides inspired by [this video](https://www.youtube.com/embed/jJtvGF8vZbE)

<!-- slide -->

# Chi sono i binari?

<img src="assets/derfissa.jpg">

<!-- slide -->

# La Fune?

<img src="assets/vento.jpg">

<!-- slide -->

# Vento in poppa

<img src="assets/ventoinpoppa.jpg">

<!-- slide -->

# Al più la velocità del vento

<img src="assets/poppa.jpg">

<!-- slide -->

# Al più la velocità del vento

<img src="assets/poppa1.jpg">

Forza minore: 

* La vela intercetta meno vento
* Forza perpendicolare alla vela non parallela al moto

<!-- slide -->

# Più della velocità del vento

<img src="assets/apparente.jpg">

Il vento apparente genera forza propulsiva

<!-- slide -->

# La vela è un'ala

<a href="https://media-cdn.tripadvisor.com/media/photo-s/13/8f/11/aa/il-protagonist-750-della.jpg">
<img src="assets/sailwing.jpg" height=400pt>
</a>

<!-- slide -->

# Ala esposta ad un flusso d'aria

<iframe width="560" height="315" src="https://www.youtube.com/embed/UqBmdZ-BNig" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- slide -->

# L'ala devia il flusso

<a href="http://utenti.quipo.it/volare/flow-past.gif">
<img src="assets/flusso_ala.png" height=250pt>
</a>
<a href="https://upload.wikimedia.org/wikipedia/commons/9/99/Karman_trefftz.gif">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Karman_trefftz.gif" height=250pt>
</a>

<!-- slide -->

# [La portanza (lift) per la NASA](https://www.grc.nasa.gov/www/k-12/airplane/lift1.html)

> Lift occurs when a moving flow of gas is turned by a solid object. The flow is turned in one direction, and the lift is generated in the opposite direction, according to Newton's Third Law of action and reaction. Because air is a gas and the molecules are free to move about, any solid surface can deflect a flow. For an aircraft wing, both the upper and lower surfaces contribute to the flow turning. Neglecting the upper surface's part in turning the flow leads to an incorrect theory of lift.

* NIENTE FLUIDO (ARIA), NIENTE PORTANZA
* NIENTE MOVIMENTO, NIENTE PORTANZA

<!-- slide -->

# [Isaac Newton (1642-1726)](https://en.wikipedia.org/wiki/Isaac_Newton)

<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/GodfreyKneller-IsaacNewton-1689.jpg" height=400pt>

<!-- slide -->

# Spostare il flusso

La portanza è la **forza** generata dallo spostamento del flusso d'aria


$$ F = ma = m \frac{(V_1-V_0)}{t_1-t_0} $$

<!-- slide -->

# Lo abbiamo sperimentato da piccoli

<a href="https://www.foothillsumc.org/s/78cRKhB6h0yb9KQnAOAo2g/car-window-hand.jpg">
<img src="assets/mano_finestrino.jpg" height=400pt>
</a>

<!-- slide -->

# Sperimentiamolo da grandi ;-) 

<img src="assets/foilsimflat.png" height=400pt>  

[FoilSim by NASA](https://www.grc.nasa.gov/www/k-12/airplane/foil3.html)

<!-- slide -->

# [Qualche approssimazione](https://youtu.be/WHHS3wWVf-U)
<img src="assets/sailnewton1.jpg" height=300pt>  



Nota che: $ \frac{\Delta V}{V} \simeq \frac{\Delta h}{c} $

$m=\rho \text{Vol} = \rho c L v \Delta t = \rho A v \Delta t $

Quindi: $F= m a = m \frac{\Delta V}{\Delta t} \simeq \rho A v \Delta t \frac{\frac{v \Delta h}{c}}{\Delta t} = \rho v^2 A \frac{\Delta h}{c}$

<!-- slide -->

# [Niente male](https://www.grc.nasa.gov/www/k-12/airplane/lifteq.html)

$F=\rho v^2 A \frac{\Delta h}{c}$

* $\rho$ è la densita dell'aria
* $v^2$ è il quadrato della velocità
* $A$ è la superficie dell'ala
* $\frac{\Delta h}{c}$ è l'angolo d'attacco

<!-- slide -->

# Hydrofoil: la vela sotto!!!


<img src="assets/ac75.jpg" height=450pt>

<!-- slide -->

# La densità!

$F=\rho v^2 A \frac{\Delta h}{c}$

<img src="assets/densita.jpg">

<!-- slide -->

# [Daniel Bernoulli (1700-1782)](https://it.wikipedia.org/wiki/Daniel_Bernoulli)

<img src="assets/Bernoulli.jpeg" height=400pt>

<!-- slide -->

# Pressione statica e dinamica

<a href="https://i.stack.imgur.com/VAuRG.png">
<img src="assets/VAuRG.png" height=400pt>
</a>

<!-- slide -->

# [ecco perchè!](http://www.gizio.it/aerodinaelicottero/aerodinamica.htm)

<a href="http://www.gizio.it/aerodinaelicottero/illustrazioni/tuboventuri.jpg">
<img src="http://www.gizio.it/aerodinaelicottero/illustrazioni/tuboventuri.jpg" height=400pt>
</a>

$$ p_t =  p_s + p_d = costante $$

<!-- slide -->

# Probabilmente lo usate spesso!

<img src="assets/innaffiare.jpg" height=400pt>


<!-- slide -->

# Un semplice esempio 

<img src="assets/sovrasottop1.jpg" height=400pt>

<!-- slide -->

# In sintesi  

<img src="assets/sovrasottop.png" height=400pt> 

<!-- slide -->

# Giochiamoci 

<img src="assets/flowexample.png" height=400pt> 


<!-- slide -->

# Sperimentiamo  

<img src="assets/simmetricV.png" height=400pt>  

[FoilSim by NASA](https://www.grc.nasa.gov/www/k-12/airplane/foil3.html)

<!-- slide -->

# Sperimentiamo  

<img src="assets/simmetric.png" height=400pt>  

[FoilSim by NASA](https://www.grc.nasa.gov/www/k-12/airplane/foil3.html)

<!-- slide -->

# Sperimentiamo  

<img src="assets/flat_bottomV.png" height=400pt>  

[FoilSim by NASA](https://www.grc.nasa.gov/www/k-12/airplane/foil3.html)

<!-- slide -->

# Sperimentiamo  

<img src="assets/flat_bottom.png" height=400pt>  

[FoilSim by NASA](https://www.grc.nasa.gov/www/k-12/airplane/foil3.html)

<!-- slide -->

# [Un errore consolidato](https://www.grc.nasa.gov/www/k-12/airplane/wrong1.html)

<img src="assets/Equal_transit-time_NASA_wrong1.gif" height=400pt>

<!-- slide -->

# Sveliamo il mistero

<iframe width="560" height="315" src="https://www.youtube.com/embed/UqBmdZ-BNig" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- slide -->

# I due flussi non arrivano insieme!

<img src="assets/flusso_ala.png" height=250pt><img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Karman_trefftz.gif" height=250pt>

<!-- slide -->

# La realtà è molto complessa

<iframe width="560" height="315" src="https://www.youtube.com/embed/LrSoNICufBA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- slide -->

# Basta Bernoulli?

<a href="https://www.foothillsumc.org/s/78cRKhB6h0yb9KQnAOAo2g/car-window-hand.jpg">
<img src="assets/mano_finestrino.jpg" height=400pt>
</a>

<!-- slide -->

# [Definizione di portanza della NASA](https://www.grc.nasa.gov/www/k-12/airplane/lift1.html)

> **Lift occurs when a moving flow of gas is turned by a solid object.** The flow is turned in one direction, and the lift is generated in the opposite direction, according to Newton's Third Law of action and reaction... any solid surface can deflect a flow. For an aircraft wing, both the upper and lower surfaces contribute to the flow turning. Neglecting the upper surface's part in turning the flow leads to an incorrect theory of lift.

<!-- slide -->
# Portanza e angolo di attacco

<a href="https://www.incoaching.it/wp-content/uploads/2016/10/2.png">
<img src="assets/portanza_attacco.png" height=400pt>
</a>



<!-- slide -->

# Effetto Coanda

<iframe width="560" height="400" src="https://www.youtube.com/embed/w_Q1T0Y0mUU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> <img src="https://www.cicap.org/new/images/a/m/Q05_p19.jpg?i=54675" height=400pt>

<!-- slide -->

# [Henry Coanda (1886-1972)](https://en.wikipedia.org/wiki/Henri_Coand%C4%83)

<img src="https://upload.wikimedia.org/wikipedia/commons/6/6c/IICCR_G240_Ceausescu_Coanda_crop.jpg" height=400pt>

<!-- slide -->

# [Effetto Coanda](https://en.wikipedia.org/wiki/Coand%C4%83_effect)

<img src="assets/c1.png" height=400pt>
<img src="assets/c2.png" height=400pt>

<!-- slide -->

# Effetto Coanda sull'ala

... ecco perchè ha un profilo arrotondato!

<img src="assets/effetto_coanda_new.jpg" height=400pt> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Coanda_Spoon.jpg/220px-Coanda_Spoon.jpg" height=400pt>

<!-- slide -->

# A questo punto non resta che costruire un ala 

<iframe width="560" height="315" src="https://www.youtube.com/embed/ufeky6EIXQ4?start=206" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>