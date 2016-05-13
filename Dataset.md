#Dataset

Para hacer este trabajo se elegio como dataset a los documentos liberados de panamapapers para hacer un pequeno analisis un poco mas cercano a la realidad y que sirva de respuesta para afirmar que la corrupcion es lo que coadyuva a tener mas pobreza a nuestros paises y que los circulos de poder son los mas beneficiados por siempre.

La ruta de donde se obtuvo los datos es: 

- https://github.com/amaboura/panama-papers-dataset-2016

##Datos de Panama Papers

Todos los datos fueron obtenidos originalmente del sitio oficial ICIJ website 
 - https://panamapapers.icij.org/graphs/

posteriormente se obtiene un csv en espanol de datos The power Players que son los nombres mas influyentes de los datos de panama papers.
El archivo se obtuvo de un dataset de github el cual se puede encontrar en varios idiomas en este mismo repositorio.

- https://github.com/amaboura/panama-papers-dataset-2016

Adiocionalemente se trabajo en los datos un poco para poder obtener otros datos que se puedan evaluar mas facilmente, por el inconveniente que los datos
de origen son en su mayoria texto.

y se genero otro csv con el nombre de panamapapers.csv

###Información de la fuente
 **Toda la informacion de la fuente**
- https://www.icij.org/about#_ga=1.15609587.436613505.1463148148

###Información Relevante
####Información de los campos: (nombre de tipos de atributo y el valor de dominio)

1. id
2. story-title 				Polynominal El titulo de la historia.
3. story-subtitle 			Polynominal El titulo de quien es la historia
4. story-country-1-code			Polynominal El Codigo de Pais
5. story-country-1-name			Polynominal El Nombre del Pais	
6. story-narrative			Texto Narra un poco la historia
7. story-summary 			Texto Un sumario de la historia
8. story-biography			Text Biografia al que pertenece la historia
9. document_url				Text La url de la copia de documentos encontrados
10. name				Text Nombre del personaje power Player
11. politicians				Text Si es Politico el cargo que ocupo si No solo dice No.
12. publico				Binominal Si es publico (Si o No)
13. Relacion				Polynominal Si no es politico indica el tipo de relacion con otro cargo politico
14. Tipo Relacion			Polynominal El grado de parentesco o cercania(No, Pariente o Socio)


