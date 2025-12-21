---
authors:
  - name: null
---

# 4 Documenting Data from CAD Projects

## 4.1 Why Document your Data?

Those working with CAD will be very familiar with its wide range of different uses. CAD software may be used to design something new or to record existing objects and structures. CAD projects differ widely and so do their outputs, which can range from very complex three-dimensional models to simple two-dimensional drawings. Projects may involve using CAD software to capture models which are transferred into GIS, to form the basis of virtual reality models or simply to create illustrations that are incorporated into reports and other publications.

While work is underway, it is relatively easy to remember the steps that have been taken to produce a model but, even after a short time has passed, it can become increasingly more difficult to remember how data were produced or compiled from different sources. As a result, it is helpful to prepare documentation as CAD projects proceed, recording the process by which models were created. The documentation produced will help both the project team and others in the future to assess the fitness of a model and datasets for use in particular purposes. This documentation will also form a vital component of the digital archive from a CAD project.

Depositing data in an archive is often the final stage of a project. Depositing data is important, not only to ensure preservation but also because it prompts the necessary attention to documentation throughout the project. The benefit is that once the data and its supporting documentation have been deposited the information contained therein can be made available for years to come.

__Levels of Documentation and Metadata__

Documenting a large project that has produced thousands of CAD files may seem daunting. However, each individual CAD file does not necessarily require individual documentation containing thousands of pieces of information. To do so would be prohibitively expensive in terms of time and effort and would probably be unnecessary. Instead the amount of documentation can be minimised if it is produced in layers which relate to stages of the overall project. For example:

* Overall project description
* Methods and conventions of data capture
* Individual model documentation.

This system avoids duplication of information, so that details about the project, sources and the methods of data capture can be recorded once and then cross-referenced from the individual file documentation. Documentation at the individual file level can also be minimised if project managers decide to adopt standard layer-naming and other conventions at the outset of the project and there are no cross-reference files or attached databases. What is important is that the more detailed information is available within the documentation hierarchy, and that it can be easily located.

## 4.2 Project Documentation

It is important to plan the creation of digital data from the outset of a project. Projects generally begin with the preparation of a project design and it is at this stage that the tasks that are necessary to complete the intended work are planned and resources are allocated. At the design stage, it is recommended practice for project managers to define areas of responsibility for creating digital data including personnel, the acceptable file formats and naming conventions, as well as to identify both back-up and archiving strategies. Project managers are recommended to contact a digital archive at the design stage to check their recommended file formats, documentation requirements or any conditions of deposit so that these can be included in the planning process.

The project design itself forms a part of the project documentation, providing the background to why work took place and why CAD was used. The final report, written after the project's completion, should then describe the project outcomes, how the work was actually done and what was produced. Both documents describe the formats of data that were produced and factors which influenced their collection and later re-use. Both documents should be deposited as part of the project's digital archive.

### 4.2.1 File List

For each project provide a list of all files that have been produced including:

* File name
* Created date or date of last update
* Copyright
* Data format of the file, i.e. the version number
* Description of content.

It is important to record all known copyright details in each file. In cases where data has been retrospectively captured from another source (such as a map or photograph) there may be a complex trail of ownership of copyright. It makes life easier for everyone if the process of evolution is recorded, particularly as copyright permissions may be limited for some datasets (e.g. it may be permissible to use a map for research but not for publication). When preparing a CAD model for deposit in a digital archive, it is recommended practice to link any copyright-restricted datasets as external reference files rather than embedding them within a CAD model.

### 4.2.2 Project Level Documentation

As described in the general [Project Documentation](https://doi.org/10.5284/h0p2-5584) and [Project Metadata](https://doi.org/10.5284/h0p2-5584) sections of these guides, project level documentation provides summary information about the project for others. This information is often used to provide an index for resource discovery to support the retrieval of project reports and associated data files. The following information should be collected:

```{list-table}
:header-rows: 1


* - Element
  - Description
* - Project Title
  - The project name or title may be the name that is used in the written report (e.g 'The Athens Propylaea project') or a familiar/published place or monument name (e.g. 'Symon's Castle')
* - Project Description
  - A brief summary (200-300 words) of the main aims and objectives of the project including a description of the work flow, data collection processes, personnel, with specific notes regarding successful or problematic portions of the work
* - Subject
  - A brief description of the subject being recorded, i.e. the monument or structure surveyed. Use of a controlled vocubulary (e.g. the Thesaurus of Monument Types) is recommended to achieve consistency in terminology.
* - Project Keywords
  - Keywords indexing the subject of the project. They can be drawn from the index fields listed below (e.g. survey type, capture method, monument type, etc.) with reference to appropriate terminology standards.
* - Language
  - E.g. English
* - Site Address
  - The postal address of the subject being recorded (if any).
* - Administrative area
  - In the United Kingdom record the District/County/Unitary Authority in which the subject lies (in the United States this record will be the Town/County/State). The administrative boundaries that are current at the time of the survey should be used and, for consistency, the use of the standard names from Appendix 4 is recommended.
* - Country
  - The country in which the study area lies (England, Scotland and Wales should be recorded separately).
* - Spatial Coverage
  - The map coordinates of the SW and NE corner of a bounding box enclosing the study area. For Britain, Ordnance Survey National Grid coordinates are recommended. It should be noted that the Ordnance Survey of Great Britain (OS) holds copyright over the reproduction of OS maps and retains Intellectual Property Rights in all information derived from such maps.
* - Size
  - The size of the study area.
* - Originator
  - The name, address and role of the organisation or individual(s) responsible for the project.
* - Client
  - The name and address of the organisation or individual(s) who sponsored or commissioned the project.
* - Depositor
  - The name, address and role of the organisation or individual(s) depositing data from the project.
* - Contributor
  - The name and address of the person(s) or organisation who deposited the data file.
* - Identifier / Reference Number
  - The project reference number or code used by the organisation responsible to refer to the project or to the data
* - Duration
  - The dates when the project took place, i.e. the dates of the first and last day on which the fieldwork took place. If separate periods of fieldwork are related to the same project they should be listed individually.
* - Copyright
  - A description of any known copyrights associated with the digital collection.
* - Primary Archive
  - The name, address and role of the organisation or individual(s) holding primary data from the project.
* - Source / Related Archives
  - References to the original material for any data derived in whole or in part from published or unpublished sources, whether printed or machine-readable. Details should be given of where the sources are held and how they are identified there (e.g. by accession number). If a CAD model is derived from other sources it should be indicated whether the data represent a complete or partial transcription/copy, and the methodology used for their computerisation.
* - Bibliography
  - The title, author, date and publisher of any report(s) or publication(s) about the project
* - Format
  - A Brief description of the format of the data file, e.g. DWG and DXF files.
```

## 4.3 Documenting CAD Conventions

As discussed, CAD projects often involve bringing together datasets captured both in the field and at the desk-top. Several different people may be involved in the project in different roles at different times (e.g. surveyors, digitisation operators, CAD operators etc.). The data that they capture may be brought together as separate layers within a CAD model or as cross-referenced files. For instance, a CAD model may include both field survey data and data that have been digitised from maps, plans and photographs.

It is recommended practice for project managers to agree standard layer-naming (see [Section 3.3](cadsystems#id-3-3-cad-layers-naming-conventions-and-drawing-colours)) and file-naming conventions at the start of the project. These conventions facilitate the process of both data capture and in building CAD models.

### 4.3.1 Project Layer-naming Convention

Documentation should be provided for the layer-naming convention that has been adopted for the project. This should include:

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Name of Convention
  - The name of the layer-naming convention; this may be an agreed standard convention used by an organisation (e.g. the English Heritage layer-naming convention, [@eh2005presentation]) or a local convention agreed for a specific project. Full details of the layer name, content and drawing conventions should be documented unless details have been published, in which case it may be sufficient to provide a publication reference.<br> 
    Repeat this information for each layer used.
* - Layer Name
  - The name or code associated with the layer (e.g. OA-ROOF is the layer name associated with all roof timbers in the English Heritage convention).
* - Layer Content
  - A brief description of the content of the layer (e.g. roof timbers).
* - Drawing Conventions
  - Drawing conventions or any special icons and characters used in this layer. These can include specific font type, line type, drawing element and colour
```

### 4.3.2 Project File-naming Convention

Many organisations and individuals use file-naming conventions to identify details such as the project to which the file relates, its content, the version number and format. When depositing data in an archive it is helpful to provide documentation for these conventions. The information recorded should include:

```{list-table}
:header-rows: 1

* - Element
  - Description
* - File Names
  - It is important to include some means of identifying the relevant activity in the file name, e.g. a unique reference number, project number or project name and to provide a brief explanation of any abbreviations used. For example, 'GPS survey files start with a 'g' and are then indexed with a subsequent number: g1, g2...' etc. Include version number information in the file name where necessary.
* - File Extensions
  - It is recommended that you reserve the 3-letter file extension and that standard file extensions are used to reflect the format of the data contained in the file, e.g., .dwg, .txt.
* - File Formats
  - Provide an explanation of which internal format is associated with a particular file extension, e.g. which version of .dwg or .dxf file format has been used.
```

## 4.4 Documenting Field Data Capture

Those involved in the survey will generally begin recording information about data as soon as they begin to create or use it. __Log books__ are often used to record information as the project proceeds. It is normal to record details of the equipment and software used, any problems that were encountered or modifications that were made to standard procedures or naming conventions.

Some information about each on-site survey technique used is required. This helps to assess the suitability of the archived results for later use in a CAD model. Such information would enable the precision and accuracy of the data to be assessed to determine, for example, if it was suitable for use in producing a three-dimensional model.

The following is a general list of the forms of documentation that might be useful to record for each survey technique. For [Laser Scan](https://doi.org/10.5284/rt5g-dm24) and [Photogrammetric](https://doi.org/10.5284/wngr-en16) surveys, please see the relevant guides for more specific metadata requirements.

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Project Name
  - Include the project name or title with the documentation to cross-refer to the project level documentation.
* - Reference Number
  - Include the project reference number (if any) with the documentation to cross-refer to the project level documentation.
* - Survey Type
  - The type of survey technique should be recorded, e.g. total station survey, GPS survey, direct object scanning, hand measurement survey etc.
* - Survey Purpose
  - Provide a brief summary (200-300 words) describing the survey, the techniques used, including training procedures, and equipment checks as appropriate.
* - Duration
  - The dates when the survey took place, i.e. the dates of the first and last day of the survey. If separate pieces of fieldwork took place they should be listed separately.
* - Surveyor
  - The name and address of the organisation or individual(s) who carried out the survey.
* - Survey Keywords
  - Keywords indexing the type of survey technique.
* - Instrumentation
  - Specific information about the make and model of the instruments used and their test and repair records as appropriate.
* - Coverage
  - Describe the area covered and the methods used (e.g. fixed grid) for each technique.
* - Precision and Accuracy
  - This should provide a commentary on the accuracy and precision of the data captured by a particular technique. This might include:
    * The estimated error of survey base station coordinates
    * Data precision
    * Data accuracy
    * Data density
    * The estimated error terms for the coordinate pairs and (if appropriate) the z-coordinate
    * Georeferencing information.
* - Data Transfer Files
  - The data transfer files (if any) used to move survey data from a total station to a computer and any intermediate files used in that process. Record the following information:
    * File name
    * Date
    * A summary of the work done
    * Data points + numbers, etc.
```

### 4.4.1 Additional Information for GPS Data

In addition, the following information is recommended for data captured using GPS equipment:

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Location Method
  - Record the method that was used to locate stations, C/A or P code pseudorange measurements, carrier phase measurements and whether a single measurement or averaging (include the time period) was used.
* - Coordinate Transformation
  - Record the software used for any coordinate transformation and give the associated error estimates.
* - Satellite
  - The satellites used in obtaining fix and observed GDOP (Geometric Dilution of Precision, a measure of the quality of the fix indicating the suitability of satellite positions for triangulation).
* - Differential Correction
  - The nature of any differential correction undertaken together with error estimates
* - Broadcast
  - The broadcast differential: name of the service provider and the name and location of base station
* - Base Station
  - The local base station: instrument details, location (including error estimate) of base station
* - Post-processing
  - Post-processing software used and the source of correction data.
```

### 4.4.2 Notes and Hand Measurements

Most forms of survey involve taking notes and making annotated drawings as part of the process. Much survey work also involves some hand measurements with tapes and line levels, even if the major part of the work is done using electronic equipment. For example, hand measurements may be used in inaccessible areas while fixed points are surveyed with electronic equipment to specify the relationships between the different areas of the site.

Notes and drawings form part of the project archive, although not part of the digital archive unless they are retrospectively digitised. They include:

* Drawings of the survey subject with markers showing the data points
* Specifying data points with three coordinates for three-dimensional models
* Date produced
* Name of the originator.

## 4.5 Documenting Data Sources

As outlined in [Section 2.3](capturingdataforcadprojects#id-2-3-digitisation-retrospective-conversion-to-cad-from-maps-plans-and-drawings), numerous sources can be used to capture data retrospectively into CAD models, including survey plans, Ordnance Survey and other maps, aerial photographs or ground photographs. Each of these sources is of value for a different purpose and each brings with it a different set of problems. For example, data acquired at 1:50,000 scale may be ideally suited for plotting a distribution map but is unsuited for recording the location of individual excavation trenches.

Ownership of data may well prove quite complex. For example, data originating from the Ordnance Survey may be used by North Yorkshire County Council to derive a new dataset 'owned' by the County Council. These data may in turn be used by York Archaeological Trust to derive a further new dataset. Although little of the original resource may survive, the Ordnance Survey continues to hold intellectual property rights which must be recognised and which may well affect later uses of the data, e.g. publication on the Internet.

To support future uses of project data that have been captured by desk-top techniques it is important to record information both about the original source and the digitisation process. The following information should be recorded for each data source that is digitised:

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Project Name
  - Include the project name or title with the documentation to cross-refer to the project level documentation.
* - Reference number
  - Include the project reference number (if any) with the documentation to cross-refer to the project level documentation.
* - Source Name
  - Record the name of the original source, e.g. map and the map series.
* - Source Reference
  - Record the reference number for the source, if any.
* - Type of Source
  - Keyword indexing the general type of the source material, e.g. map, plan, photograph, drawing.
* - Source Medium
  - Keyword describing the medium of the source, i.e. paper, mylar, acetate.
* - Publisher
  - The name and address of the publisher of the original source, if any.
* - Copyright
  - A description of any known copyrights held on the source material including details of the permitted uses of copyright data, e.g. an organisation may have copyright clearance to use a map in a CAD model and publish an illustration incorporating map details in the project report but not to publish the same illustration on the Internet.
* - Scale
  - Scale of the original source, given as a ratio, and the original scale (where the source is an enlargement or generalisation from another source).
* - Accuracy
  - Claimed accuracy of the source. For maps, map makers will often provide an estimated precision for contour lines or other sub-components of a map.
* - Map Projection (Maps only)
  - All details of the map projection and coordinate system employed. This information is usually printed on the mapsheet or else should be sought from the map source.
* - Photographic Details (Photographs only)
  - Full photographic details including camera position, focal length, distance from object/flying height (for vertical aerial photographs) etc.
* - Ground Control (Photographs only)
  - Details regarding the ground control points (GCPs) used in georeferencing.
```
__Documenting Retrospective Data Capture__

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Techniques
  - The generic category of conversion technique used, e.g. digitising, scanning etc.
* - Equipment
  - The make and model of hardware device used, e.g. scanner.
* - Software
  - Software driver and version used.
* - Parameters
  - The parameters of the device, e.g. scan resolution, no. of bits per pixel or line precision.
* - Post-processing
  - Details of any post-processing on the data, e.g. noise reduction.
* - Automatic Processing
  - Details of any automatic vector processing applied to the theme (such as snap-to-nearest-node).
* - Control Points
  - Details of control points used to manage conversion from digitiser.
* - Data Precision and Accuracy
  - Brief assessment of the precision and accuracy or any errors that occurred during automatic vectorisation processes.
* - Copyright
  - A description of any known copyrights held in the digitised material including details of the permitted uses of copyright data.
* - Data Files
  - File name<br>Date<br>A summary of the work done<br>Data-points, numbers, etc.
```

## 4.6 Documenting CAD Models

Each project may produce a number of CAD models. Where standard file and layer-naming conventions are used these will be documented as part of the overall project metadata (see [Section 4.3](documentingdatafromcadprojects#id-4-3-documenting-cad-conventions)). If new or modified layer-naming conventions are used in the creation of the model then these must be documented at this stage.

For each model the documentation should include:

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Project Name
  - Include the project name or title with the documentation to cross-refer to the project level documentation.
* - Reference Number
  - Include the project reference number (if any) with the documentation to cross-refer to the project level documentation.
* - Creator
  - Record the name and address of the organisation or individual(s) responsible for creating the CAD model.
* - Name of CAD Model
  - The name of the CAD model, which will often be the name of the site.
* - CAD Software
  - The type and version number of the CAD software used, e.g. AutoCad release 10. Give details of any updates or revisions to the software and portions of the model associated with each version.
* - Files Used
  - Provide a list of files used in the model. For cross-referenced files the full file name with directory path must be recorded.
* - Layer Convention
  - Note the name of the layer-naming convention used by the project and document any amendments made to this convention in the model, including changes to line type, colour, drawing elements etc.
```

### 4.6.1 Documentation for Attached External Databases

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Project Name
  - Include the project name or title with the documentation to cross-refer to the project level documentation.
* - Project Reference
  - Include the project reference number (if any) with the documentation to cross-refer to the project level documentation.
* - Database
  - Type and version number of database used, e.g. MS Access version 2.0.
* - Name
  - The name of the database, data table or data file. This would incorporate the project reference number.
* - Data Field
  - For each data field:
     * field name
     * any codes used
     * description, if coded data is used a complete list of any codes with a description of each code should be provided.
* - CAD File
  - The name of the CAD file with which the database is linked.
* - Link Field
  - Name of the linking field between the database and CAD model.
* - File Format
  - The format in which the database has been saved.
* - Creation Date
  - The date when the database was created.
```

Back-up files that are created while work is in progress should be stored separately, in case there is any need to restore the CAD model from a back-up during the life of the project.
