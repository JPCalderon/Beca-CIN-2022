# Título
Caracterización de galaxias en contexto de big data

# Objetivo específico
Desarrollar un paquete de [Python](https://www.python.org/) que permita calcular el perfil de brillo de una galaxia y obtener sus propiedades estructurales. Además, debe brindar la posibilidad de ajustar modelos numéricos al perfil en forma interactiva. 

# Objetivo general
El cálculo de perfiles de brillo a través de ajustes de isofotas es una técnica que permite estudiar la evolución de los parámetros estructurales de una galaxia desde la zona central hasta sus radios más externos. En particular, para galaxias de tipo temprano, esta técnica es de gran importancia y es un muy buen punto de partida como introducción al estudio de galaxias en el contexto de cúmulos y grupos, como así también, para ejercitar el desarrollo de código informático aplicado a astronomía.

Por otro lado, a medida que las imágenes CCD extienden su cobertura espacial proyectada y las bases de datos de los observatorios y surveys se vuelven más accesibles, aumenta la importancia de desarrollar software específico para el procesamiento de grandes volúmenes de datos (big data).

El material observacional propuesto para este plan de trabajo corresponde a imágenes de distribución libre del [DESI Legacy Imaging Surveys](https://www.legacysurvey.org/) (muestra reducida) y de la colaboración [S-PLUS](https://www.splus.iag.usp.br/). El punto de partida para el desarrollo del código será el paquete isophote de Astropy y código propios producidos en otros lenguajes informáticos ([Calderón et al. 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.1760C/abstract)).

En este plan se propone: 
- Realizar un análisis resumido de los software existentes ([GALfit](https://users.obs.carnegiescience.edu/peng/work/galfit/galfit.html) e [isophote](https://photutils.readthedocs.io/en/stable/isophote.html), etc.)
- Establecer e implementar tareas específicas que aún no hayan sido desarrolladas en los softwares analizados (p. ej., corrección por nivel de cielo y fotometría simultánea en varios filtros)
- Aplicar el código propuesto sobre una muestra reducida de galaxias de tipo temprano de alguno de los cúmulos ricos cercanos (Fornax y/o Antlia).
- Comparar los resultados con los publicados en la literatura.
- Implementar el código testeado para que pueda ser utilizado sobre un gran volumen de datos (p. ej. conexión a bases de datos públicas con el fin de descargar recortes de imágenes sobre las cuales correrá el código).
- Publicar el código en algún repositorio de software (Github). 
-  En el caso de cumplir dichos objetivos antes del tiempo estipulado para la beca, el código será aplicado a imágenes en 12 filtros de galaxias ubicadas en 98 campos de la colaboración S-PLUS. Dichos campos cubren un área de ~192 grados cuadrados centrados en NGC 1399, la galaxia dominante del cúmulo de Fornax (~400.000 objetos).

# Contacto
Dr. Juan Pablo Calderón (jpcalderon@fcaglp.unlp.edu.ar) <br />
Dra. Analia Smith-Castelli (asmith@fcaglp.unlp.edu.ar)

# Información sobre la Beca CIN
- https://evc.cin.edu.ar/

# Referencias
[1] https://github.com/legacysurvey/legacysurvey <br />
[2] https://www.splus.iag.usp.br/  <br />
[3] https://sextractor.readthedocs.io/en/latest/Introduction.html  <br />
[4] https://users.obs.carnegiescience.edu/peng/work/galfit/galfit.html  <br />
[5] https://photutils.readthedocs.io/en/stable/isophote.html  <br />
[6] https://www.astropy.org/  <br />
[7] https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.1760C/abstract  <br />
