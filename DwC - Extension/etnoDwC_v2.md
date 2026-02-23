# [Vernacular Name Core](https://rs.gbif.org/extension/gbif/1.0/vernacularname.xml)
| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| vernacularID | An identifier for vernacular name. May be a global unique identifier or an identifier specific to the data set. |  |  |
| vernacularName | A common or vernacular name | gabiroba |  |
| source | Bibliographic citation referencing a source where the vernacular name refers to the cited species. |  |  |
| language | Language used for the vernacular name value. | Tupi |  |
| locality | The specific description of the area from which the vernacular name usage originates. Vernacular names may have very specific regional contexts. A name used for a species in one area may refer to a different species in another. |  |  |
| countryCode | The standard code for the country in which the vernacular name is used. Recommended best practice is to use the ISO 3166-1-alpha-2 country codes available as a vocabulary at http://rs.gbif.org/vocabulary/iso/3166-1_alpha2.xml |  |  |
| organismPart | The part of the organism to which the vernacular name refers. Best practice is to utilise a controlled vocabulary for this term although it is likely that multiple controlled lists for different organism groups may be the best implementation for this term. |  |  |
| taxonRemarks | A description of any context that qualify the specific usage of the vernacular name. | This name applies only when the fruit has been blessed by the tribal shaman |  |


# [Taxon](https://rs.gbif.org/core/dwc_taxon_2024-02-19.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  | 
| kingdom | The full scientific name of the kingdom in which the dwc:Taxon is classified. |  |  |
| family | The full scientific name of the family in which the dwc:Taxon is classified. |  |  |
| genus | The full scientific name of the genus in which the dwc:Taxon is classified. |  |  |
| specificEpithet | The name of the first or species epithet of the dwc:scientificName |  |  |
| infraspecificEpithet | The name of the lowest or terminal infraspecific epithet of the dwc:scientificName, excluding any rank designation. |  |  |
| scientificName | The full scientific name, with authorship and date information if known. When forming part of a dwc:Identification, this should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the dwc:identificationQualifier term. |  |  |
| vernacularID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  |
| source | Bibliographic or other source citation referencing a source where the scientificName name refers to the cited vernacular name. |  |


# [Taxon (vernacular) Description](https://rs.gbif.org/extension/gbif/1.0/description.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| vernacularID | An identifier for vernacular name. May be a global unique identifier or an identifier specific to the data set. |  |  |
| description | Any descriptive free text | Planta de florzinha roxa que dá na beira da praia, utilizada para dor de cabeça |  |
| creator | The author(s) of the textual information provided for a description | Dona Maria, da comunidade da Serra da Cuxixola |  |
| contributor | An entity responsible for making contributions to the textual information provided for a description | Comunidade da Serra da Cuxixola |  |
| license | Official permission to do something with the resource. Please use Creative Commons URIs if you can |  |  |
| rightsHolder | A person or organization owning or managing rights over the description | Comunidade da Serra da Cuxixola |  |
| localContextLabel |  |  | https://localcontexts.org/labels/traditional-knowledge-labels/  |

# Ethnobotany

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| vernacularID | An identifier for vernacular name. May be a global unique identifier or an identifier specific to the data set. |  |  |
| source |  |  |  |
| useTo |  | medicinal:sistema circulatório | Based on: [Classificação Internacional de Cuidados Primários - ICPC2](https://pdfding.dalc.in/pdf/shared/6d623c53-c6dc-4bf1-9b32-915d0c0aad35) |
| useToDescription | Verbatim description from the source | feridas com dificuldade de cicatrização |  |
| usePart |  | leaves:young leaves | Based on Cook, 1995 - Appendix A - Table 43  |
| usePartDescription | Verbatim plant part from the source |  |  |
| useForm |  | infusão |  |
| useFormDescription | Verbatim use form description from the source | macera a folha com sal grosso e aplica topicamente no local afetado |  |
| usedBy |  | Pataxós |  |
| usedWhere |  | norte de Minas Gerais |  |
| localContextLabel |  |  | https://localcontexts.org/labels/traditional-knowledge-labels/  |
