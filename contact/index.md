---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# Contact 

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/lanase.png"
  caption="LANASE at ENES Morelia, UNAM"
%}




## Laboratorio Nacional de Análisis y Síntesis Ecológica (LANASE)
Escuela Nacional de Estudios Superiores Unidad Morelia, UNAM 
(ENES, UNAM)<br>
Antigua Carretera a Pátzcuaro 8701 <br>
Ex hacienda de San José de la Huerta, Morelia, Michoacán<br>
MEXICO

{%
  include button.html
  type="address"
  tooltip="See on map"
  link="https://maps.app.goo.gl/b835hAhzGqBK1oQf6"
%}

{%
  include button.html
  type="email"
  text="lanase@enesmorelia.unam.mx"
  link="lanase@enesmorelia.unam.mx"
%}
{%
  include button.html
  type="phone"
  text="+52 (443) 689 3500 Ext. 37317"
  link="+52 (443) 689 3500 Ext. 37317"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/palacky.png"
  caption="Palacky University"
%}

## Dept. Zoology, Palacky University
<a href="https://zoologie.upol.cz/">https://zoologie.upol.cz/</a>

Department of Zoology<br>
Faculty of Science, Palacký University<br>
17 listopadu 50<br>
771 46 Olomouc<br>
<br>s
<br>

{%
  include button.html
  type="address"
  tooltip="See on map"
  link="https://maps.app.goo.gl/b835hAhzGqBK1oQf6"
%}



{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


