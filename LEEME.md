<h1>Post-procesamiento-datos-tesis</h1>

Los ficheros que se incluyen en este repositorio son para llevar a cabo un primer proyecto de colaboración MGEP/UPM-ETSIAE centrado en analizar los datos experimentales obtenidos mediante medidas en túnel de viento sobre un perfil NACA0021 en distintas configuraciones fluidas.

<h2>Propósito del proyecto de colaboración</h2>

El propósito principal del proyecto de colaboración será tratar los datos experimentales y realizar un análisis temporal de los mismos, para ver si se pueden obtener indicadores o patrones que puedan dar cuenta de la naturaleza dinámica de las burbujas de separación laminar (<i>LSB</i>, por sus siglas en inglés).

En principio, los datos experimentales obtenidos en el túnel de viento se han enmarcado dentro de una tesis doctoral, cuya memoria está disponible en <a href=10.13140/RG.2.2.30499.17445>este enlace</a>. Las configuraciones fluidas contempladas en dicha tesis abarcan cuatro escenarios físicos posibles, a saber:
<ol>
  <li><b>Configuración limpia:</b> es la configuración que se tiene por defecto en el túnel. No se incluyen efectos de turbulencia o rugosidad, y el flujo que entra en la sección de testeo es lo suficientemente uniforme como para despreciar efectos perturbadores. Es la configuración base, en comparación con la cual se van a tratar de ver el efecto que tienen tanto la turbulencia como la rugosidad.</li>
  <li><b>Configuración turbulenta:</b> es la configuración que reproduce efectos turbulentos mediante la inclusión de una malla pasiva a la entrada de la sección de testeo. Se obtienen intensidades de turbulencia de hasta 4%.</li>
  <li><b>Configuración rugosa:</b> es la configuración que reproduce efectos rugosos sobre el perfil mediante la implementación de una banda rugosa en el 10% de la cuerda que se encuentra en el borde de ataque.</li>
  <li><b>Configuración real:</b> es la configuración que reproduce tanto los efectos turbulentos como los rugosos, y el que se supone que es más fiel a lo que ocurre en aplicaciones reales.</li>
</ol>
Además de esas cuatro configuraciones, que se realizan sobre el perfil NACA limpio, también se llevan a cabo mediciones sobre el perfil equipado con elementos discretos de rugosidad como técnica de control de flujo. Esos elementos discretos tienen forma triangular, parecida a los llamados <i>vortex generators</i>, y la idea es ver si son capaces de obtener alguna mejora en el comporatmiento aerodinámico del perfil. Para ello, las mediciones con el perfil equipado con elementos discretos se han realizado sobre las cuatro configuraciones fluidas mencionadas anteriormente. Los datos, en su totalidad, comprenden, así, ocho configuraciones distintas:
<ol>
  <li><b>Configuración limpia</b><ul>
    <li>Perfil limpio</li>
    <li>Perfil equipado</li>
    </ul>
  </li>
  <li><b>Configuración turbulenta</b><ul>
    <li>Perfil limpio</li>
    <li>Perfil equipado</li>
    </ul>
  </li>
  <li><b>Configuración rugosa</b><ul>
    <li>Perfil limpio</li>
    <li>Perfil equipado</li>
    </ul>
  </li>  
  <li><b>Configuración real</b><ul>
    <li>Perfil limpio</li>
    <li>Perfil equipado</li>
    </ul>
  </li>  
</ol>

Las medidas realizadas, en cambio, se corresponden con tres distribuciones principales:
<ol>
  <li>Coeficienetes de sustentacion (c<sub>l</sub>) obtenidos para distintos ángulos de ataque (&alpha;) y números de Reynolds (Re). En realidad, lo que se tienen son curvas &alpha;-c<sub>l</sub> para distintos Re. Los coeficientes de sustentación se adquieren mediante medición directa con una balanza piezoeléctrica.</li>
  <li>Coeficientes de resistencia aerodinámica (c<sub>d</sub>) obtenidos para distintos &alpha; y Re. Se tienen curvas &alpha;-c<sub>d</sub> para distintos Re. Los coeficientes de resistencia aerodinámica se adquieren mediante el método de déficit de momento, empleando, para ello, un dispositivo <i>wake-rake</i> acoplado a un escáner de presión.</li>
  <li>Coeficientes de presión (c<sub>p</sub>) obtenidos a lo largo de la superficie del perfil en la dirección de la cuerda, para distintos &alpha; y Re. Para cada número de Reynolds, se disponen de distintas distribuciones x'-c<sub>p</sub>, una para cada &alpha;, siendo x' el coeficiente adimensional a lo largo de la cuerda del perfil.</li>
</ol>
La información pertinente a la protocolización de los distintos ensayos y mediciones puede encontrarse en la memoria de la tesis mencionada anteriormente.

Por el momento, la fase inicial del proyecto de colaboración consistirá en analizar las series temporales de las distribuciones x'-c<sub>p</sub> obtenidas para distintos valores de &alpha; y Re en la configuración limpia con el perfil limpio (sin equipar con elementos de rugosidad discretos).

<!---[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/azarketa/Post-procesamiento-datos-tesis.git/HEAD)--->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/azarketa/Post-procesamiento-datos-tesis.git/main?urlpath=tree%2Fpost-proc.ipynb)
