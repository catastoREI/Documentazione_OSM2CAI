# Stato avanzamento lavori

Lo **Stato avanzamento lavori (SAL**) indica la percentuale dello stato di avanzamento lavori relativo all'inserimento dei percorsi nel Catasto.&#x20;

Viene calcolato in automatico dalla piattaforma a livello di Regione, Area e Settore, come media pesata del numero dei percorsi attesi nei singoli stati di accatastamento secondo la seguente formula

$$
{n_{sda4} * 1 + n_{sda3} * 0.75 + n_{sda2} * 0.5 + n_{sda1} * 0.25 \over n_{attesi} * 100}
$$

dove

$$
\begin{align*} 
n_{sda4} : \text{numero totale percorsi in SDA=4} \\ 
n_{sda3} : \text{numero totale percorsi in SDA=3} \\ 
n_{sda2} : \text{numero totale percorsi in SDA=2} \\ 
n_{sda1} : \text{numero totale percorsi in SDA=1} \\ 
n_{attesi}: \text{numero totale percorsi attesi}
\end{align*}
$$

