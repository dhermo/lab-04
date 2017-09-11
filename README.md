# Laboratorio 04 - Filogenética Molecular
Diego Hermosilla Alfaro

## Responde sobre Phylogeny.fr

¿Qué cosas ofrece este portal? 
  - Este portal ofrece una plataforma que sirve como fuente de información filogenética, que puede ser ejecutada de diferentes modos.
  
¿Para qué tipo de usuario está diseñado?
  - Este portal esta diseñado principalmente para ayudar a biólogos sin experiencia en el análisis filogenético de su información recolectada.
  
Menciona 5 tipos de análsis que se pueden realizar en el portal de acuerdo a la documentación
  - Análisis filogenético, reconstrucción filogenética, visualizador de árbol,  búsqueda de secuencias homologas, alineamiento múltiple.
  

## Análisis filogenético

### Gen SRY de 26 especies

![árbol filogenetico utilizando probcons](https://raw.githubusercontent.com/dhermo/lab-04/master/probconstree.jpg "Árbol filogenético utilizando Probcons")
![afup](https://raw.githubusercontent.com/dhermo/lab-04/master/probconspdf.jpg "zoom")
**Figura 1:** Árbol filogenético utilizando Probcons

![árbol filogenético con clustalw](https://raw.githubusercontent.com/dhermo/lab-04/master/clustalwtree.jpg "Árbol filogenético utilizando clustalw")

**Figura 2:** Árbol filogenético utilizando clustalw

¿A qué se refiere el paso de *Alignment curation* y para qué sirve?
  - Se refiere a la estructuración de la alineación, donde se puede decidir entre la eliminación de secuencias pobremente alineadas de una secuencia de ADN o de proteínas o  se rellenaran con *gaps* estas malas alineaciones. Para lograrlo la plataforma utiliza *Gblock* y la opción de *remove positions with gaps*, siendo la primera opción más rigurosa que la segunda.
  
¿Cuál es la diferencia entre BioNJ y Neighbor? 
  - Se diferencian en la cantidad máxima de taxones con los que pueden realizar la reconstrucción filogenética. El *BionNJ* analiza menos de 5000 taxones, mientras que el *Neighbor* reconsytruye menos de 500 taxones.
  
Corre de nuevo las filogenias pero esta vez sin *Alignment curation*. 

![árbol filogenético,probcons sin *Alignment curation*](https://raw.githubusercontent.com/dhermo/lab-04/master/probconsinalineacion.jpg "Árbol filogenético,probcons sin *Alignment curation*")
![afpsac](https://raw.githubusercontent.com/dhermo/lab-04/master/probconsinalineacionpdf.jpg "zoom")
**Figura 3:** Árbol filogenético,probcons sin *Alignment curation*

![árbol filogenético, clustalw sin *Alignment curation*](https://raw.githubusercontent.com/dhermo/lab-04/master/clustalwsinalineacion.jpg "Árbol filogenético, clustalw sin *Alignment curation*")

**Figura 4:** Árbol filogenético, clustalw sin *Alignment curation*

¿Cuál es el efecto en las filogenias?
  - Al analizar las filogenias con *alignment curation* y sin este se puede observar un cambio en; la forma de los arboles, distancias entre especies, las posiciones de los ancestros en común y variuaciones en las distancias de las ramas.
  
Describe las diferencias entre las filogenias que has estimado: cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.  
  - Respecto a las diferencias entre las herramientas probcons y clustalw podemos observar diferencias en las posiciones de varias especies, por ejemplo *Gavia stellata* se encuentra más separado del resto de las especies en probcons que en clustalw. En la cual, la especie más alejada es la de *Neomonachus schauinslandi*.
  - 
