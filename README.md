# crispy-octo-meme
Fysikklab gruppe 212 t2

fysikklab 2:
endret skruehøyder til : 300, 260, 187, 186, 245, 239, 192, 203
vi vet: massen m = 31g, c=2/5 og raduis r=11mm

finner farten ved hjelp av formelen oppgitt v(y) = sqrt((2g(yo-y))/(1+c))
setter g= 9.81*10**-3
og y0= 300 (startposisjon)
c=2/5 (som oppgitt i formelarket)
setter disse verdiene inn i 

treghetsmomentet I=cmr^2
potensiell energi i startpunkt-> mgyo
kinetisk energi i gitt punkt y-> mgy+(1/2)mv^2+(1/2)Iw^2
vinkelhastighet w=v/r
formel: mgy+(1/2)mv^2+ (c/2)mv^2   (erstatter (1/2)Iw^2 med (c/2)mv^2)

v= farten
b=helningsvinkel




t= tidsendring 
bruker metode 2, 
lager en list med farten, fra lista med fart som vi hadde fra før,inn i formel 14 fra teoriarket.
med denne lista lager vi en for-løkke som itererer gjennom alle x-punktene i lista, 
og for hver gang legger til tiden for hvert intervall, som til slutt gir tiden fra start til slutt
