---
title: EcoResNomenclatureSegmentColorDimensionValueName - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Color name

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResNomenclatureSegmentColorDimensionValueName.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResNomenclatureSegmentColorDimensionValueName/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Nomenclature segment</td></tr><tr><td>en</td><td>Color name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResNomenclatureSegmentColorDimensionValueName.md" target="_blank">Group/EcoResNomenclatureSegmentColorDimensionValueName</a>|
|[Nomenclature](#Nomenclature)||<a href="EcoResNomenclatureSegmentColorDimensionValueName.md" target="_blank">Group/EcoResNomenclatureSegmentColorDimensionValueName</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="EcoResNomenclatureSegmentColorDimensionValueName.md" target="_blank">Group/EcoResNomenclatureSegmentColorDimensionValueName</a>|
|[SegmentNumber](#SegmentNumber)||<a href="EcoResNomenclatureSegmentColorDimensionValueName.md" target="_blank">Group/EcoResNomenclatureSegmentColorDimensionValueName</a>|
|[Relationship_NomenclatureRelationshipId](#Relationship_NomenclatureRelationshipId)||<a href="EcoResNomenclatureSegmentColorDimensionValueName.md" target="_blank">Group/EcoResNomenclatureSegmentColorDimensionValueName</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/EcoResNomenclatureSegmentColorDimensionValueName (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResNomenclatureSegmentColorDimensionValueName/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Nomenclature name="Nomenclature">Nomenclature</a>

First included in: Group/EcoResNomenclatureSegmentColorDimensionValueName (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Nomenclature attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Group/EcoResNomenclatureSegmentColorDimensionValueName (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SegmentNumber name="SegmentNumber">SegmentNumber</a>

First included in: Group/EcoResNomenclatureSegmentColorDimensionValueName (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_NomenclatureRelationshipId name="Relationship_NomenclatureRelationshipId">Relationship_NomenclatureRelationshipId</a>

First included in: Group/EcoResNomenclatureSegmentColorDimensionValueName (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NomenclatureRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EcoResNomenclature.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Miscellaneous/EcoResNomenclature.cdm.json/EcoResNomenclature</a></td><td><a href="../Miscellaneous/EcoResNomenclature.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>