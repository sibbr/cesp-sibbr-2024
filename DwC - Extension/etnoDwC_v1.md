
# [Darwin Core Taxon](https://rs.gbif.org/core/dwc_taxon_2024-02-19.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  | 
| nameAccordingTo | The reference to the source in which the specific taxon concept circumscription is defined or implied - traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to"). For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given. | Pataxós |  |
| kingdom | The full scientific name of the kingdom in which the dwc:Taxon is classified. |  |  |
| family | The full scientific name of the family in which the dwc:Taxon is classified. |  |  |
| genus | The full scientific name of the genus in which the dwc:Taxon is classified. |  |  |
| specificEpithet | The name of the first or species epithet of the dwc:scientificName |  |  |
| infraspecificEpithet | The name of the lowest or terminal infraspecific epithet of the dwc:scientificName, excluding any rank designation. |  |  |
| vernacularName | A common or vernacular name. | gabiroba |  |

# [Darwin Core Resource Relationship](https://rs.gbif.org/extension/resource_relationship_2024-02-19.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| resourceID | Definition: An identifier for the resource that is the subject of the relationship |  | p.ex. TaxonID da "gabiroba" |
| relatedResourceID | An identifier for a related resource (the object, rather than the subject of the relationship) |  | p.ex. TaxonID da Campomanesia guazumifolia |
| relationshipOfResource | The relationship of the subject (identified by dwc:resourceID) to the object (identified by dwc:relatedResourceID) | - identificadoComo<br>- conhecidoComo | p.ex. identificadoComo |
| relationshipAccordingTo | The source (person, organization, publication, reference) establishing the relationship between the two resources |  | p.ex. citação do voucher ou do botânico que identificou |
| relationshipRemarks | Comments or notes about the relationship between the two resources. |  |

# [Species Distribution](https://rs.gbif.org/extension/gbif/1.0/distribution_2022-02-02.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  |
| countryCode | ISO 3166 alpha 2 or alpha 3 country codes the area belongs to or as an alternative for a locationID if the area is a country |  |  |
| locality | The verbatim name of the area this distributon record is about. | - Amazônia<br>- Restinga de Massambaba |  |

# [Taxon Description](https://rs.gbif.org/extension/gbif/1.0/description.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  |
| description | Any descriptive free text | Planta de florzinha roxa que dá na beira da praia, utilizada para dor de cabeça |  |
| creator | The author(s) of the textual information provided for a description | Dona Maria, da comunidade da Serra da Cuxixola |  |
| contributor | An entity responsible for making contributions to the textual information provided for a description | Comunidade da Serra da Cuxixola |  |
| license | Official permission to do something with the resource. Please use Creative Commons URIs if you can |  |  |
| rightsHolder | A person or organization owning or managing rights over the description | Comunidade da Serra da Cuxixola |  |
| localContextLabel |  |  | https://localcontexts.org/labels/traditional-knowledge-labels/  |

# [Literature References](https://rs.gbif.org/extension/gbif/1.0/references.xml)

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  |
| identifier | DOI, ISBN, URI, etc refering to the reference. This can be repeated in multiple rows to include multiple identifiers, e.g. a DOI and a URL pointing to a pdf of the article. |  |  |
| bibliographicCitation | A text string referring to an un-parsed bibliographic citation. | Hartge, P., Genetics of reproductive lifespan. Nature Genetics 41, 637 - 638 (2009) |  |
| title | Title of book or article |  |  |
| creator | The author or authors of the referenced work |  |  |
| date | Date of publication, recommended ISO format YYYY or YYYY-MM-DD |  |  |


# [Vernacular Names](https://rs.gbif.org/extension/gbif/1.0/vernacularname.xml)
| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  |  |
| source | Bibliographic citation referencing a source where the vernacular name refers to the cited species. |  |  |
| language | Language used for the vernacular name value. | Tupi |  |
| locality | The specific description of the area from which the vernacular name usage originates. Vernacular names may have very specific regional contexts. A name used for a species in one area may refer to a different species in another. |  |  |
| countryCode | The standard code for the country in which the vernacular name is used. Recommended best practice is to use the ISO 3166-1-alpha-2 country codes available as a vocabulary at http://rs.gbif.org/vocabulary/iso/3166-1_alpha2.xml |  |  |
| organismPart | The part of the organism to which the vernacular name refers. Best practice is to utilise a controlled vocabulary for this term although it is likely that multiple controlled lists for different organism groups may be the best implementation for this term. |  |  |
| taxonRemarks | A description of any context that qualify the specific usage of the vernacular name. | This name applies only when the fruit has been blessed by the tribal shaman |  |

# Ethnobotany

| Propriety | Definition | Example | Comments |
| --- | --- | --- | --- |
| taxonID | An identifier for the set of dwc:Taxon information. May be a global unique identifier or an identifier specific to the data set. |  | p.ex. TaxonID da gabiroba |
| source | 
| useTo |  | medicinal:sistema circulatório | Based on: WORLD HEALTH ORGANIZATION (WHO). International Classification of Diseases (ICD-11). [s. d.]. World Health Organization. Disponível em: https://icd.who.int/browse/2024-01/mms/en?secondLanguageCode=pt. Acesso em: 8 nov. 2024. |
| useToDescription | Verbatim description from the source | feridas com dificuldade de cicatrização |  |
| usePart |  | leaves:young leaves | Based on Cook, 1995 - Appendix A - Table 43  |
| usePartDescription | Verbatim plant part from the source |  |  |
| useForm |  | infusão |  |
| useFormDescription | Verbatim use form description from the source | macera a folha com sal grosso e aplica topicamente no local afetado |  |
| usedBy |  | Pataxós |  |
| usedWhere |  | norte de Minas Gerais |  |
| localContextLabel |  |  | https://localcontexts.org/labels/traditional-knowledge-labels/  |
