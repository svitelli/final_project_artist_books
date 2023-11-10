---
title: Metadata Application Profile
layout: about
permalink: /metadataapplicationprofile.html
---
## Metadata Application Profile (MAP)

1. ObjectID (required CollectionBuilder-GH)
  - Cardinality: 1 
  - Obligation: required
  - Content guidelines: This field refers to the unique identifier used for each item in the collection. It should be all lowercase with no spaces or special characters (dashes and underscores are acceptable, NOT slashes). Value should be written as the main title of the book (up to 5 words); if the item is a compound object, objectid should also include “_cover” or “_interior” depending on which is accurate for the object.    
  - Mapping to Dublin Core: identifier

2. FileName (required CollectionBuilder-GH)
  - Cardinality: 1 
  - Obligation: required
  - Content guidelines: This field refers to the digital object’s filename including the file extension. It must exactly match the filename of the object in the “objects” directory. Upper- and lowercase of this field should match the filename in the “objects” directory. Value should be written as the main title of the book (up to 5 words); if the item is a compound object, objectid should also include “_cover” or “_interior” depending on which is accurate for the object, and should include “.jpg” at the end of the value.
  - Mapping to Dublin Core: identifier
Format (required CollectionBuilder-GH)
Cardinality: 1 
Obligation: required
Content guidelines: This field refers to the media type of the object. Images comprise this collection, so the supported value to be used for this field should be image/jpeg.  
Mapping to Dublin Core: format
Title (required CollectionBuilder-GH)
Cardinality: 1 (up to 2)
Obligation: required
Content guidelines: This field refers to the title of the artist book. Information should be obtained from the title page of the book. Subtitles should be included if applicable, delineate from the title using a semicolon. This field is repeatable for up to 2 titles (including the subtitle). Capitalize the first letter of each major word in the title, do not capitalize any letters in the subtitle (if applicable). If working with a compound object, title should be listed as “cover” or “interior” for the corresponding child item. 
Mapping to Dublin Core: title
Creator (optional)
Cardinality: 1 (up to 3)
Obligation: required
Content guidelines: This field refers to the author of the artist book. Information should be obtained from the title page of the book. The field is repeatable for up to 3 authors, multiple authors should be delineated by semicolons (illustrator, photographer, etc. not included in this field). Capitalize the first letter of each word in the author’s name. This value should be written as First Name Last Name of the author. If there is more than one author, the names should be listed in alphabetical order by last name. If working with a compound object, title should be listed as “creator” for the child item.   
Mapping to Dublin Core: creator
Date (visualization)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to the year that the artist book was published. Information should be obtained from the copyright page of the book. The year should be formatted as YYYY.
Mapping to Dublin Core: date
ISBN (optional)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to the ISBN of the artist book. Information should be obtained from the copyright page of the book. If there is no ISBN, the value should be “none.” Include all dashes in the ISBN as written in the copyright page.
Mapping to Dublin Core: identifier
Subject (visualization)
Cardinality: 1 (up to 5)
Obligation: required
Content guidelines: This field is repeatable for up to 5 subjects. The field refers to themes/art/science subjects found in the book. Multiple subjects should be delineated by semicolons. Do not capitalize any of the subject terms.
Mapping to Dublin Core: subject
Controlled vocabulary: Use Proposed International Standard Nomenclature for Fields of Science and Technology (SKOS) for science subjects, and use Getty’s Art & Architecture Thesaurus (AAT) for art subjects. 
Place of publication (visualization)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to the geographic location in which the artist book was published. The value will be written as City, State, with the name of the city and the name of the state being capitalized. The city and state names will be written out fully exactly as they are formally named. If no publication location is listed, write “none.”
Mapping to Dublin Core: Coverage
Description (optional)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to a brief account of the artist book. Description should be no longer than one sentence. Capitalize the first letter of the description sentence.  
Mapping to Dublin Core: type
Publisher (custom)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to the publisher of the artist book. Information should be obtained from the copyright page of the book. Capitalize the first letter of each word in the publisher’s name. If the publisher is not listed, the value should be listed as “unknown”.
Mapping to Dublin Core: publisher 
Size (custom)
Cardinality: 1
Obligation: required
Content guidelines: This field refers to the physical size of the book, as defined by its dimensions. The value should be formatted as length” x width” x height”. If only two dimensions are given, list those two in the same format. 
Mapping to Dublin Core: format
Materials (custom)
Cardinality: 1 (up to 5)
Obligation: required
Content guidelines: This field refers to the materials/media used to create the artist book. Separate values should be delineated by semicolons, up to 5 materials should be listed. Do not capitalize any of the names of the materials. If materials are not listed, write “unknown”. 
Mapping to Dublin Core: Format
