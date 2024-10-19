# What's Topas?

<div style="text-align: center;">
  <p style="text-align: justify;"> TOPAS is a Monte Carlo simulation software based on Geant4, designed for simulating particle interactions in materials. It is useful in medical physics, radiation protection, and nuclear science. TOPAS enables users to define geometries, materials, and particle types, offering tools for result analysis. Its user-friendly interface and scripting features make it accessible to researchers and practitioners..
  </p>
</div>

## Geometry 

```bash
########### WORLD ###########
### GUI (5. half leght) and air

s:Gr/ViewA/Type             = "OpenGL"
Ts/UseQt = "True"  # gui
#b:Gr/ViewA/IncludeAxes = "True"
d:Ge/World/HLX         = 1. m
d:Ge/World/HLY         = 1. m
d:Ge/World/HLZ         = 1. m
b:Ge/World/Invisible   = "False"
s:Ge/World/Material    = "Vacuum"
```

## Sources 

## Detectors 
## Physics 

## Descripción de los decaimientos de Co-60

En función de las reacciones presentadas (ver anexos), se observa que todos los decaimientos ocurren en el origen del sistema de referencia (ver Figura). En cada historia, se repite la misma reacción en la que el Co-60 decae mediante radiación beta negativa (β⁻), generando un electrón (e⁻) que deja una traza de color rojo y un antineutrino electrónico (ν̅ₑ). La suma de energías en cada historia es:

**E_{e⁻ + ν̅ₑ} ≈ 0.317 MeV**

Además, se forma un estado excitado de Ni-60[2505.753].

Este último, al poseer un exceso de energía, emite un fotón gamma (γ) que deja una traza de color verde y tiene una energía de 1.17 MeV, resultando en la formación del estado excitado Ni-60[1332.514]. Este estado excitado, Ni-60[1332.514], posteriormente decae, emitiendo otro fotón gamma (γ) de 1.33 MeV, lo que lleva a la formación de Ni-60, un isótopo estable.

Al estudiar 100 historias, se observó la generación de:

- 100 fotones gamma (γ) con energía de 1.17 MeV.
- 100 fotones gamma (γ) con energía de 1.33 MeV.

Esto corresponde a un 100% de coincidencia, resultado que es coherente con lo reportado en la literatura (Collins & Ottinger, 2003).



<p align="center">
  <img with="850" height="330" src="/Images/esquema desintegracion.jpg">
</p>


## Rutherford experiment 1919 Nitrogen 

<p align="center">
  <img width="600" height="300" src="/Images/1919.jpg">
</p>

 
<p align="center">
  <img with="850" height="390" src="topas.jpg">
</p>


## Chadwick's Discovery of The Neutron

In 1932, James Chadwick discovered the neutron by bombarding beryllium with alpha particles, releasing neutral radiation. Through momentum conservation, he determined these particles had a mass similar to protons. This discovery was vital for understanding atomic nuclei, as it confirmed the existence of neutrons. Chadwick received the Nobel Prize in 1935 for this groundbreaking work. [The existence of Neutron](https://royalsocietypublishing.org/doi/epdf/10.1098/rspa.1932.0112)

<p align="center">
  <img width="600" height="300" src="/Images/Chadwich.jpg">
</p>

## Radiation 

<p align="center">
  <img width="600" height="300" src="/Images/radiation.jpg">
</p>

## Peak's Bragg

<p align="center">
  <img width="600" height="300" src="/Images/peak's bragg.jpg">
</p>




