---
title: Optional Fields
stub: recommend
section: metadata
section_order: 4
---

{:.py-4 .mt-4 #recommend}
***

## 4. Optional Fields

The rest of the fields in the CollectionBuilder metadata template are not required for CollectionBuilder or its visualizations to work, but their use is encouraged to ensure a richly informative collection. These remaining fields are listed below, along with their respective definitions and examples.

{% include bootstrap/alert.md color="info" text="CollectionBuilder can accommodate any field you include in your metadata once you customize your site. For example, you can display any field on item pages or on the Browse page. See the [Metadata](customize.html#config-metadata) and [Browse](customize.html#config-browse) customization sections for more information. "%}

- **creator**:
    - The creator property designates an entity primarily responsible for making the resource. Multiple creators may be input, as long as each is separated by a semicolon (`;`).
    - Example value: `Smith, John` or `Smith, John; Doe, Jane`
- **description**:
    - The description should be a brief account of the object. Each object should only have one description.
    - Example value: `Postcard of the Memorial Gymnasium on the University of Idaho campus in Moscow, Idaho.`
- **source**:
    - The source field designates a related source collection or resource from which the object is derived. This field is especially relevant for digitized archival collections. In such a situation, the name of the physical archival collection would be the input for this field. The input should be expressed as the collection name followed by a comma, then followed by the holding library.
    - Example value: `PG 5, University of Idaho Library Special Collections and Archives`
- **identifier**:
    - The identifier field is used to preserve the unique identifier assigned to the object by the object's (usually physical) source collection.
    - Example value: `ARG-02-16-1993`
- **type**:
    - An object's type distinguishes between types of image, sound, text, etc. using a one- or two-value input. At minimum, the input should contain a value chosen from the [DCMI Type Vocabulary](https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/){:target="_blank" rel="noopener"}. If using a second value, the second value does not need to relate to a controlled vocabulary, but should give further specification of the object type. The two values in a pair should be separated by a semicolon (`;`). See examples below.
    - Example value: `Image;StillImage`, `Image;MovingImage`, `Text`, `Sound`
- **language**: 
    - This field indicates the language associated with the object. Recommended best practice is to use a controlled vocabulary such as the [ISO 639-2 Codes for the Representation of Names and Languages](http://www.loc.gov/standards/iso639-2/php/code_list.php){:target="_blank" rel="noopener"} to designate language tags.
    - Example value: `en`, `fr`, `de`
- **rights**:
    - The rights field should include a free-text rights statement describing information about rights held in and over the object.
    - Example value: `Educational use includes non-commercial use of text and images in materials for teaching and research purposes. Digital reproduction rights granted by the University of Idaho Library. For other uses beyond free use, please contact University of Idaho Library Special Collections and Archives Department.`
- **rightsstatement**:
    - This field is a standardized rights statement, designated in the form of a URI. It should be presented as a [creativecommons.org](https://creativecommons.org/){:target="_blank" rel="noopener"} URI or a [rightsstatements.org](https://rightsstatements.org/en/){:target="_blank" rel="noopener"} URI.
    - Example value: `http://rightsstatements.org/vocab/NoC-US/1.0/`
