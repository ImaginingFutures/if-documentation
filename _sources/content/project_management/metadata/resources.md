# Resources

This is the description of metadata resources.

## Identification

### Unique Record Identifier

| Term name     | Unique Record Identifier  |
| ------------- | ------------------------- |
| Definition    | An alphanumeric identifier for the record created for the IF Repository. |
| Entry         | String-CV – Unique Project Identifier (Projects)  |
| DC equivalent | dc:identifier |
| Repeatable    | No  |
| Modality      | Mandatory  |
| Guideline     | The PIs of each project will receive a pre-assigned unique project identifier. Unique ID's derivered from that ID and adding 4 digit secuential numbers.  |
| Example       | UFC00800001 |

### Original Identifier

| Term name     | Original Identifier |
| ------------- | ------------------- |
| Definition    | Original/Local identifier for the record given by the local project team. |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | No |
| Modality      | Optional  |
| Guideline     | International or local identifiers associated with the original material. |
| Example       | CO 1/25 (National Archives Reference), 309.6 P.97 (Dewey Classification Number), AGN COL CI Folder 75, Document 2 (ISADG classification), 2019SG07-0239 (Unique ID of a digital collection) |

### Member Of

| Term name     | Member Of |
| ------------- | --------- |
| Definition    | Shows the parent collection or object which this record related to/part of. |
| Entry         | String-CV (Projects) |
| DC equivalent | dc:isPartOf |
| Repeatable    | Yes |
| Modality      | Mandatory |
| Guideline     | Provide the name of the project as it is on the "Projects" sheet |
| Example       | Vernacular Songs as Archives and Modes of Social Redress in Jamestown, Accra |

### Resource Title Preferred

| Term name     | Resource Title Preferred |
| ------------- | ------------------------ |
| Definition    | The name given to the resource by the Creator (depositor) in any language.  |
| Entry         | String-Free text |
| DC equivalent | dc:title  |
| Repeatable    | No  |
| Modality      | Mandatory  |
| Guideline     | Provide a short title for the resource in any language. Do not use any punctuation. Only capitalize the first alphabet of the project title, acronyms and any personal and geographic names.  |
| Example       | Aso wiwo awon obinrin ile Yoruba  |

### Resource Title Alternative

| Term name     | Resource Title Alternative |
| ------------- | -------------------------- |
| Definition    | The name given to the resource by the Creator (depositor) in other language.  |
| Entry         | String-Free text |
| DC equivalent | dc:alternative  |
| Repeatable    | No  |
| Modality      | Optional  |
| Guideline     | Provide a translation or modified version of the title attributed to the record. |
| Example       | Local-made cloth of a typical Ghanian lady  |

### Digital Representations

| Term name     | Digital Representations |
| ------------- | ----------------------- |
| Definition    | Name of the digital file or the folder of multiple files. |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | No  |
| Modality      | Mandatory  |
| Guideline     | Provide the name of the digital file. Or if you have more than one file to represent, provide the path of the folder. |
| Example       | Example_photo.jpg, UFC00800001/images/folder1 |

### External Link_Website Name

| Term name     | External Link_Website Name |
| ------------- | -------------------------- |
| Definition    | Name of the website where this resource was published. |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     |   |
| Example       |   |

### External Link_Website URL

| Term name     | External Link_Website URL |
| ------------- | ------------------------- |
| Definition    | URL of the website where this resource was published. |
| Entry         | String-Free text |
| DC equivalent | dc:source |
| Repeatable    | No |
| Modality      | Optional  |
| Guideline     |   |
| Example       |   |

## Scope and Content

### Resource Description

| Term name     | Resource Description |
| ------------- | -------------------- |
| Definition    | A textual description of the content of the resource (knowledge profile = images; documents) in any language, including event and significance connected to the resource. Content descriptions in the case of visual resources  |
| Entry         | String-Free text |
| DC equivalent | dc:description |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Provide textual description of the resource in English limited to maximum of three concise sentences. Include important keywords related to the significance of the resource. Since the description field is a potentially rich source of indexable vocabulary, care should be taken to provide this element when possible.  |
| Example       | Ile alo ti awon omode eya Arika lo ni odun to ti pe  |

### Resource Description Alternative

| Term name     | Resource Description Alternative |
| ------------- | -------------------------------- |
| Definition    | A textual description of the content of the resource in other language, including event and significance connected to the resource. Content descriptions in the case of visual resources  |
| Entry         | String-Free text |
| DC equivalent | dc:description |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Provide textual description of the resource in other language limited to maximum of three concise sentences. Include important keywords related to the significance of the resource. Since the description field is a potentially rich source of indexable vocabulary, care should be taken to provide this element when possible.  |
| Example       | Story book used for play by Pandalong children to understand the direction of the moon and sun. Created between 1908 and 1910.  |

### Primary Language

| Term name     | Primary Language |
| ------------- | ---------------- |
| Definition    | The primary language spoken by the participant (if video or audio resource). The primary language written on the image or in the document.  |
| Entry         | String-CV (Language) |
| DC equivalent | dc:language  |
| Repeatable    | Yes |
| Modality      | Mandatory if |
| Guideline     | Select the primary language spoken in the audio or video file. Select the primary language written on the image or in the document.  |
| Example       | English;Yoruba;Arabic  |

### Other Language

| Term name     | Other Language |
| ------------- | -------------- |
| Definition    | The other language spoken by the participant (if video or audio resource). The other language written on the image or in the document.  |
| Entry         | String-CV (Language) |
| DC equivalent | dc:language  |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Select the other language spoken in the audio or video file. Select the other language written on the image or in the document.  |
| Example       | English;Yoruba;Arabic  |

### Themes

| Term name     | Themes  |
| ------------- | ------- |
| Definition    | Descriptive words that are most significant and unique to the resource  |
| Entry         | String-CV (Themes) |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Provide maximum of five most significant and unique words that can describe the content of the resource. Separate each word with comma  |
| Example       | Colonised;Forgotten;Inclusion;Post-conflict;Refugee |

### Keywords 

| Term name     | Keywords  |
| ------------- | --------- |
| Definition    | Descriptive words that are most significant and unique to the resource  |
| Entry         | String-Free text |
| DC equivalent | dc:subject |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Provide maximum of five most significant and unique words that can describe the content of the resource. Separate each word with comma  |
| Example       | Migration;Conflict;Community  |

### Notes

| Term name     | Notes |
| ------------- | ----- |
| Definition    | Any information that you want to add about this data, if you can not find a metadata field according to your need. |
| Entry         | String (Free text) |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional |
| Guideline     |   |
| Example       |   |

## Geographical Coverage

### Country

| Term name     | Country  |
| ------------- | -------- |
| Definition    | The name of the country connected to the resource, where the content of the resource took place.  |
| Entry         | String-CV (Countries) |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Provide the name of the country that is connected to the resource.  |
| Example       | Argentina, Ghana, South Africa  |

### Region

| Term name     | Region  |
| ------------- | ------- |
| Definition    | The name of the region or state connected to the resource, where the content of the resource took place.  |
| Entry         | String-Free text |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Provide the name of the region/state/province that is connected to the resource.  |
| Example       | Osun, Chaco, Cape coast  |

### City

| Term name     | City |
| ------------- | ---- |
| Definition    |   |
| Entry         | String-Free text |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Optional |
| Guideline     |   |
| Example       |   |

### Address

| Term name     | Address |
| ------------- | ------- |
| Definition    | The name of the place/street name/area connected to the resource, where the content of the resource took place.  |
| Entry         | String-Free text |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Provide the name of the place/street name/area that is connected to the resource.  |
| Example       | Gbongan, Kishi, Sidwell Street  |

### Coordinates

| Term name     | Coordinates |
| ------------- | ----------- |
| Definition    | Coordinates of the resource. |
| Entry         | Integer  |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Optional |
| Guideline     | IT should be written as [lang,lat] |
| Example       | [10.77555,106.701944] |

### Non-Geolocated Place

| Term name     | Non-Geolocated Place |
| ------------- | -------------------- |
| Definition    | This element captures the names of places that do not have specific geographical coordinates or are of imaginary or mythical nature. |
| Entry         | String-Free text |
| DC equivalent | dc:coverage |
| Repeatable    | Yes |
| Modality      | Optional |
| Guideline     | Provide the name of a place or space |
| Example       | Aztlán, Atlantis, Tattooine |

## Socio-cultural Context

### Cultural Group

| Term name     | Cultural Group |
| ------------- | -------------- |
| Definition    | The cultural or ethnic group connected to the resource.  |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Provide the names of all the cultural or ethnic group/community connected to the resource. This could be more than one.  |
| Example       | Arabs;Assyrians;Balanta  |

### Cultural Context

| Term name     | Cultural Context |
| ------------- | ---------------- |
| Definition    | The cultural event or context associated with the resource.  |
| Entry         | String-CV (Cultural Context) |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Describe the cultural context or event associated with the resource. This descriptor responds to ‘What was happening when the resource was produced?’, ‘What event or practice is the resource recording?’ A list of suggested events is provided but add additional, more specific values to the vocabulary.  |
| Example       | Dancing;Migration;Singing |

### Social Group Setting

| Term name     | Social Group Setting |
| ------------- | -------------------- |
| Definition    | The social group associated with or recorded by the resource.  |
| Entry         | String-CV (Social Group) |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Describe the social group associated with the resource. This descriptor responds to ‘What is the description of the people recorded by the resources?’ A list of suggested social group is provided but add additional, more specific values to the vocabulary.  e.g. https://simplicable.com/society/social-groups |
| Example       | Classmates;Family;Committees |

## Technology

### Production Technique

| Term name     | Production Technique |
| ------------- | -------------------- |
| Definition    | The defined way adopted to produce the resource.  |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Describe the technique used in producing the resource. This descriptor responds to ‘How was the resource produced?’ A list of relevant production technique is provided but additional techniques can be added.  |
| Example       | Photography;Report writing;Audio recording;Video recording |

### Equipment used

| Term name     | Equipment used  |
| ------------- | --------------- |
| Definition    | The equipment used directly for the production of the resource.  |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | List all the equipment used for the production of the resource. Provide the general names of each equipment, separated with commas.  |
| Example       | Tripod stand;DSLR camera;Video recording |

## Dates

### Date of creation

| Term name     | Date of creation  |
| ------------- | ----------------- |
| Definition    | A point or period of time associated with the creation of the resource.  |
| Entry         | Integer  |
| DC equivalent | dc:created |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Enter the date the resource was created. Recommended practice is to express date using the format YYYY-MM-DD [ISO 8601-1]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used.  |
| Example       | 2022-01-04 or 2022-01 or 2022  |

### Date of digitisation

| Term name     | Date of digitisation |
| ------------- | -------------------- |
| Definition    | A point or period of time associated with the digitisation of the resource. E.g. scanning, photographing date. |
| Entry         | Integer  |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Enter the date the resource was created. Recommended practice is to express date using the format YYYY-MM-DD [ISO 8601-1]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used.  |
| Example       | 2022-01-04 or 2022-01 or 2022  |

### Date of publication

| Term name     | Date of publication |
| ------------- | ------------------- |
| Definition    | A point or period of time associated with the publication of the resource. |
| Entry         | Integer  |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | Enter the date the resource was created. Recommended practice is to express date using the format YYYY-MM-DD [ISO 8601-1]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used.  |
| Example       | 2022-01-04 or 2022-01 or 2022  |

## Access and Sensitivity

### Rights Ownership

| Term name     | Rights Ownership  |
| ------------- | ----------------- |
| Definition    | Information about the individual/community/groups/organisation who owns the rights in and over the resource.  |
| Entry         | String-CV (Participants) |
| DC equivalent | dc:rightsHolder |
| Repeatable    | Yes |
| Modality      | Mandatory  |
| Guideline     | Select the participant or community that owns the rights in and over the resource from the participants vocabulary. You can add names of individual/community/organisation that are not on the list to the vocabulary list, then here.  |
| Example       | Name Surname;University of Ghana;Ilesa community |

### Rights

| Term name     | Rights  |
| ------------- | -------- |
| Definition    | Information about the shareability, distribution and adaptation of the resource  |
| Entry         | String-CV (Licence) |
| DC equivalent | dc:licence |
| Repeatable    | Yes |
| Modality      | Mandatory  |
| Guideline     | Select which licence is applicable to the resource. Consider this carefully before making your selection. |
| Example       | CC BY-NC; In Copy Right|

### Cultural Sensitivity

| Term name     | Cultural Sensitivity |
| ------------- | -------------------- |
| Definition    | This refers to the attributed standard that governs the content and knowledge of the resources and who can access the resource. |
| Entry         | String-CV (Cultural sensitivity) |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Mandatory |
| Guideline     | Select the level of cultural sensitivity of the content and knowledge of the resource. Consider this carefully before making your selection. ---Highly sensitive – refers to resource that cannot be viewed, downloaded, print nor accessed. The resources in this category are confidential. The depositor, persons connected to the project and repository administrators may have access to the resource. ;Moderately sensitive – refers to resources that are to be viewed only, not to be downloaded and print. Retrievers interested in accessing the resource need to fill ‘Data Retrieval Form’ to justify the need for the resource. Data Retrieval Form to be assessed and approved by the Principal Investigator and co-PIs ;Low sensitivity – refers to resources that are to be shared openly. Retrievers will be able to view, download, print and use  |
| Example       | Highly sensitive, Medium sensitivity, Low sensitivity  |

### Access restriction

| Term name     | Access restriction |
| ------------- | ------------------ |
| Definition    | This refers to availability of the resource.  |
| Entry         | Boolean – Access  |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Mandatory if |
| Guideline     | Select the level of access that is appropriate to the resource. Consider this carefully before making your selection. ---Yes – refers to resources that are restricted. If you choose ‘Yes’, you need to justify ;No – refers to resources with no access restriction. Resources will be made openly available.  |
| Example       | Yes, No  |

### Reasons for restriction

| Term name     | Reasons for restriction |
| ------------- | ----------------------- |
| Definition    | Justification for limiting access to the resources  |
| Entry         | String-Free text |
| DC equivalent |   |
| Repeatable    | Yes |
| Modality      | Mandatory if  |
| Guideline     | The field is mandatory if the value for ‘Access restriction’ is Yes. Provide justifications for limiting the access to the resource and specify the consequences and potential impacts of making the resource accessible. Specify if access to the resource should ne restricted permanently or for a specific period of time.  |
| Example       | The image records various civil protests and disobedience is countries that are repressive. Making the image accessible could make the persons connected to the image targets. Therefore, access to the image should be permanently restricted.  |

## Intellectual Property

### Creator

| Term name     | Creator  |
| ------------- | -------- |
| Definition    | The individual that is primarily responsible for the production of the resource.  |
| Entry         | String-CV (Participants) |
| DC equivalent | dc:creator |
| Repeatable    | Yes |
| Modality      | Strongly Suggested |
| Guideline     | Select the participant that is primarily responsible for the production of the resource. If many participants are involved, select the lead person for the production of the resource and list other as contributors.  |
| Example       | Name Surname;Name2 Surname2 |

### Contributors

| Term name     | Contributors  |
| ------------- | ------------- |
| Definition    | The individuals that supported the creator or contributed to the production of the resource. |
| Entry         | String-CV (Participants) |
| DC equivalent | dc:contributor |
| Repeatable    | Yes |
| Modality      | Optional  |
| Guideline     | List all the individuals that contributed or supported the production of the resources. Separate each contributor with commas.  |
| Example       | Name Surname;Name2 Surname2  |
