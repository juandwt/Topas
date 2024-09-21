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


## Rutherford experiment 
 
<p align="center">
  <img with="850" height="390" src="topas.jpg">
</p>


## Chadwick's Discovery of The Neutron

In 1932, James Chadwick discovered the neutron by bombarding beryllium with alpha particles, releasing neutral radiation. Through momentum conservation, he determined these particles had a mass similar to protons. This discovery was vital for understanding atomic nuclei, as it confirmed the existence of neutrons. Chadwick received the Nobel Prize in 1935 for this groundbreaking work. [The existence of Neutron](https://royalsocietypublishing.org/doi/epdf/10.1098/rspa.1932.0112)

$$
{}_{2}^{4}\alpha + \, {}_{4}^{9}\text{Be} \rightarrow \, {}_{6}^{12}\text{C} + \, {}_{0}^{1}\text{n}
$$
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$



<p align="center">
  <img width="500" height="250" src="/Images/experiment.jpg">
</p>


| Año  | Experimento de Chadwick                      | Descubrimiento          | Impacto                                    |
|------|----------------------------------------------|-------------------------|--------------------------------------------|
| 1932 | Bombardeo de berilio con partículas alfa      | Neutrón                  | Confirmó la existencia de partículas neutrales en el núcleo atómico |
| 1935 | Análisis mediante conservación del momento    | Masa similar a la del protón | Desarrolló el modelo moderno del núcleo atómico |
| 1935 | Nobel de Física otorgado a Chadwick           | Reconocimiento           | Contribución clave a la física nuclear     |



