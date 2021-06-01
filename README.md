# HTR-model-SpanishRedonda_XVI-XVII_extended-DATASET (v. 1.0.0)
The following Transkribus platform (READ Coop) Dataset is available on Zenodo: https://zenodo.org/record/4889218#.YLX6xKgzY2w
***
## General information

The SpanishRedonda_XVI-XVII_extended DATASET is conceived to be uploaded inside Transkribus
platform (READ Coop) to perform a training and create an HTR+ model for the automated
recognition of printed Spanish documents in Round script published between XVI-XVII Century.

For system requirements and information about Transkribus platform, go to:

https://readcoop.eu/transkribus/

https://readcoop.eu/transkribus/resources/

https://github.com/Transkribus
***
## Responsability
***
### Authors:
Stefano Bazzaco (coord.)

Gaetano Lalomia

Daniela Santonocito

Manuel Garrobo Peral

Mónica Martín Molares

Carlota Cristina Fernández Travieso
***
### Projects:

**Progetto Mambrino - Università degli Studi di Verona**

resp. Anna Bognolo, Stefano Neri

https://www.mambrino.it/it

**BIDISO (Biblioteca Digital Siglo de Oro) - Universidade da Coruña**

resp. Sagrario López Poza, Nieves Pena Sueiro

https://www.bidiso.es/index.htm

**COMEDIC (Catálogo de obras medievales impresas en castellano) - Universidad de Zaragoza**

resp. María Jesús Lacarra

https://comedic.unizar.es/

**Progetto di Eccellenza: Le Digital Humanities applicate alle lingue e letterature straniere - Università degli Studi di Verona**

resp. Paolo Frassi

https://www.dlls.univr.it/?ent=progetto&id=5327
***
### Publisher:
Stefano Bazzaco
***
## SpanishRedonda_XVI-XVII_extended DATASET description:

The dataset is based on the following Spanish books:

- *Restauración de España*, Cristóbal de Mesa (Madrid, Juan de la Cuesta, 1607)
- *Las navas de Tolosa*, Cristóbal de Mesa (Madrid, Viuda de P. Madrigal, 1594)
- *Historia de las hazañas y hechos del invencible caballero Bernardo del Carpio*, Agustín Alonso (Toledo, Pero Lóper de Haro, 1585) 
- *Las lágrimas de Angélica*, Luis Barahona de Soto (Granada, Hugo de Mena, 1586)
- *Libro del Orlando determinado*, Don Martín de Bolea y Castro (Lérida, Miguel Prats, 1578)
- *Relación de la solemne entrada hecha en Ferrara [...]*, Ioan Paolo Mocante (Roma, Nicolás Mucio, 1598)
- *Relación del aparato que se hizo en la ciudad de Valencia [...]*, Juan Bautista Confalionero (Valencia, Patricio Mey, 1599)
- *Relación verdadera del […] bautismo de la serenísima princesa Margarita*, Anónimo (Madrid, Diego Flamenco, 1623)
- *Relación de un nuevo milagro obrado por intercesión de […]*, San Francisco Xavier (Palermo, 1663)
- *Fiesta que se hizo en Aranjuez a los años del rey nuestro señor don Felipe IIII [...]*, D. Antonio de Mendoza (Madrid, Juan de la Cuesta, 1623)
- *Primera Parte de la Relacion de las Reales disposiciones[...] Cristianísimo Luis Dezimoquarto de Francia, su Esposo*, Anónimo (Sevilla, Juan Gómez de Blas, 1660)
- *Segunda parte de la relacion diaria del itinerario [...] el Excelentissimo Don Luis Mendez de Haro y Guzman*, Anónimo (Sevilla, Juan Gómez de Blas, 1660)
- *Relación verdadera, en que se da quenta de todo el daño [...] natural de la misma ciudad de Seuilla*, Juan Beltran de la Cueva (Lima, Gerónimo Contreras, 1626)
- *Relacion del nacimiento del nueuo Infante y de la muerte de la Reyna [...]*, Andres de Claramonte (Cuenca, Salvador Viader, 1612)
***
### Transcription criteria:

semi-diplomatic transcription

abbreviations: expanded

accents: mantained as in the source text

punctuation: mantained as in the source text
***
## How to upload SpanishRedonda_XVI-XVII_extended DATASET to Transkribus platform

**On your local machine:**

Extract HTR_TrainSet_SpanishRedonda_XVI-XVII_extended zip folder

Extract HTR_TrainSet_SpanishRedonda_XVI-XVII_extended zip folder
***
**Inside Transkribus platform:**


**1. Load TrainSet:**

Server > Document > Import document(s) > Upload single document

Local folder: [find and select the DataSet folder HTR_TrainSet_SpanishRedonda_XVI-XVII_extended]

Title on server: [choose a title]

Add to collection: [choose a collection]

Upload


**2. Load ValidationSet:**

Server > Document > Import document(s) > Upload single document

Local folder: [find and select the DataSet folder HTR_ValidationSet_SpanishRedonda_XVI-XVII_extended]

Title on server: [choose a title]

Add to collection: [choose a collection]

Upload


**3. Perform Training**

Tools > Text Recognition

Method: HTR (CITLab HTR+ & PyLaia)

Train...


**4. Add Training Details**

Model Name: [choose a name]

Language: [choose a language]

Description: [choose a description]

CITLab HTR+ - Nr. of Epochs: 300

select TrainSet from the document list > click +Training

select ValidationSet form the document list > click +Validation

Train
***
## SpanishRedonda_XVI-XVII_extended HTR+ model description

Document type: printed

Nr. of Words: 61˙938

Nr. of Lines: 7˙675

CER on Train Set: 0.21%

CER on Validation Set: 1.07%
***
## How to simply use SpanishRedonda_XVI-XVII_extended HTR+ model

If you want to perform automated text recognition using SpanishRedonda_XVI-XVII_extended
HTR+ model, just go inside Transkribus platform, import your image files and apply the
model (stored inside Public Models folder).
***
## How to add your own transcriptions to SpanishGothic_XV-XVI_extended HTR+ model

If you want to add your Ground Truth materials to SpanishRedonda_XVI-XVII_extended HTR+ model,
just create your own Ground Truth pages following the transcription criteria we used and
share that content with Dr. Stefano Bazzaco, e-mail: stefano.bazzaco.1@gmail.com
***
## Copyright statement
The SpanishRedonda_XVI-XVII_extended DataSet and model belongs to the authors.
Their usage is freely Open Access, but you have to give appropriate credits to authors and publisher.
Their remixing, changing and distribution for commercial use is not possible without authors
and publisher acceptance, as stated by the Creative Commons License CC BY-NC-ND 4.0
(Attribution-NonCommercial-NoDerivatives 4.0 International).

More information here: https://creativecommons.org/licenses/by-nc-nd/4.0/
