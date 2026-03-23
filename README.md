
# Práctica-Diversidad-COI
En la presente práctica desarrollaremos el flujo de trabajo a seguir desde el alineamiento de secuencias hasta la obtención de índices de diversidad para genes mitocondriales y la construcción de redes de haplotipos.

#### Programas a emplear: Mega, DNAsp y Popart

## **Actividad 1**

Utilizando el alineamiento de COI proporcionado, calcula los siguientes índices de diversidad genética:

a.Número de sitios polimórficos

b.Número de haplotipos

c.Diversidad haplotípica

d.Diversidad nucleotídica

#### Programas

**Mega** para visualizar el alineamiento

**DNAsp** para calcular los índices de diversidad y exportar archivo.nex

#### Flujo de trabajo

1. Abre el alineamiento con DNAsp.
2. En DNAsp selecciona la opción _Analysis/DNA polymorphism_. 

Aquí obtendrás el número de sitios polimórficos, el número de haplotipos, la diversidad haplotípica y la diversidad nucleotídica.

3. En DNAsp selecciona la opción _Analysis/Polymorphic Sites_. 

Aquí obtendrás el número de sitios variables únicos y los parsimoniosamente informativos.



## **Actividad 2**
Construye una red de haplotipos. Utiliza la información de las localidades proporcionada a continuación: 

**PBC**: Pacífico de Baja California

**GC**: Golfo de California

**PS**: Pacífico Sur

#### Programas

**DNAsp** para generar el archivo.nex

**PorArt** para construir la red

#### Flujo de trabajo
 1. En DNAsp selecciona la opción _DATA/Define sequence sets_. Define los sets utilizando la información de las localidades.
 2. Selecciona _Update all entries_
 3. En DNAsp selecciona la opción _Generate/Haplotype data files_.
    
 Marca las opciones gaps not considered, removed invariable sites y generate nexus.
 
 4. Guarda el archivo.nex y luego modifícalo siguiendo el ejemplo proporcionado.
 5. Abre PopArt.
 6. En PoprArt selecciona la opción _File/Open/archivo.nex_.
 7. Una vez abierto el archivo.mex, selecciona la opción _Network/Median Joining Network/OK_
 
 Aquí obtendrás la red de haplotipos. Puedes editarla seleccionando diferentes colores, posición de los haplotipos y etiquetas, etc.
