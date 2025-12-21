---
authors:
  - name: null
---

# 1 A Brief Introduction to CAD

## 1.1 An introduction to the CAD guide

This Guide is designed for individuals and organisations involved in the creation, maintenance, use, and long-term preservation of Computer-Aided Design (CAD) datasets in archaeology and constitutes a revision of the original CAD Guide to Good Practice published in 2002. The first edition of this guide highlighted, using results from *Strategies for Digital Data* [@condron1999strategies], that CAD files and other three-dimensional models formed a significant and unique component of many archaeological digital archives. While from a certain point of view little has changed over the last decade - CAD software is still used by archaeologists to produce much the same type of files and formats - the growth of other technologies such as GIS, laser scanning and photogrammetry have subtly changed the way in which CAD is used and interacts with other project datasets and workflows.

This guide is intended to provide:

* a basic description of computer-aided drafting or computer-aided design (CAD) software
* discussions on the use of CAD in a variety of situations
* descriptions of data acquisition and capture methods used
* good practices in the use of the software, and information about archival practices with CAD files.

As well as providing a source of useful generic information, the guide emphasises the processes of long-term preservation, archiving, and effective data re-use. As a result, the importance of adhering to recognised standards and the documentation of essential pieces of information about a given resource are dominant recurring themes.

In outlining the aims of the document, it is important to state what the current guide does not cover. It does not aim to be an exhaustive introduction to the underlying origin, theory and technical implementation of CAD. Nor is it in any way a definitive and prescriptive manual on how 'best' to do CAD. The aim of the guide is to introduce practitioners to areas and issues for which applicable standards and frameworks already exist and to identify the relevant sources of information that may be consulted. The guide does not rigidly advocate any single standard or narrow set of options, nor does it recommend any particular software product. Instead, it adopts a generic approach, with the aim of encouraging and developing the routine use of standards and data frameworks as a whole. In this sense it is important to realise that the present document constitutes a *guide* as opposed to a *manual*.

__Structure of this Guide__

To enable practitioners to target the individual sections most relevant to the particular task at hand, the aims of each section are summarised here:

* Section 1 provides a brief introduction to CAD, including how CAD programs have developed, important features of the ways that CAD can be used and its relationship to drawing programs, virtual reality and GIS. The aim of this section is to provide a contextual background to CAD in archaeology and architectural recording.
* Section 2 looks at common sources of data for CAD models, including field survey and data capture from maps, plans and photographs, and looks at the twin issues of precision and accuracy.
* Section 3 describes methods and techniques used in preparing CAD models including transferring survey data, creating CAD layers and naming conventions, choosing CAD hardware and software and CAD data formats.
* Section 4 looks at the procedures and considerations involved in planning and documenting CAD projects. This covers project design, specification, methodologies, preparing to model, segmenting the model into layers and the documentation required at each stage.
* Section 5 describes the need for good working practices in managing CAD (and other digital data) both during the working life of a project and in archiving the data.

__How to use this Guide__

Ideally any individual or institution involved with, or planning, a CAD-based exercise with the long-term aim of depositing the resultant data with a digital archive should read the guide in its entirety. In many cases, practitioners will only be dealing with one particular aspect of the overall potential of CAD, and to reflect this the guide has been structured into clear thematic sections and individuals are advised to read the sections relevant to the task at hand carefully.

Throughout the sections, information is listed which it is critical to record if a well-documented CAD data file is to be produced, and to ensure that the resources produced can be effectively archived and re-used via a digital archive. For clarity, this information is presented as a number of bulleted lists within the main body of the sections, but it is important to realise that all stages in the process should be documented. In many cases the CAD dataset will be a stage in a much larger workflow - from project planning, survey and digitisation to modelling and publication - and, where relevant, links to other guides (e.g. Laser Scanning, GIS, Vector Images, Photogrammetry) in this series have been provided.

## 1.2 The Development of CAD

Computer-Aided Design software is used worldwide by designers, architects, surveyors and others. It is used in a wide range of applications, from producing development plans for construction or industrial prototypes in manufacturing to producing visual effects in games/films or describing vehicle movement in traffic accidents. Within archaeology the use of CAD has included building and site recording, archaeological survey, interpretative modelling, visualisation and reconstructions.

There are several important reasons to consider using CAD:

* The use of layers in a CAD model makes it possible to record and organise complex material in a way which supports numerous ways of presenting the information visually.  For example, thematic layering of a landscape or site, by period or feature type, enables specific characteristics to be presented in isolation from a mass of otherwise complex and visually overlapping drawing objects.

* CAD models can be rotated to view a structure, object or site from different aspects.  Three-dimensional CAD models provide an essential framework for any recording of complex spatial information and as such allow the viewer to explore the model from viewpoints which may not normally be experienced in situ.

* Dimensions of objects and coordinates of data points may be retrieved from a CAD model with the same precision used to take the original measurement, whereas in a scaled drawing the original measurements have to be re-calculated.  Measurement data held in digital form may also be projected into alternative coordinate systems or site grids with ease.

* Data may be attached to items in CAD models, making the combination of CAD model and textual data more powerful than either alone.

* CAD files may be used by many other program types, such as GIS and virtual reality programs, to provide the base data for other applications.

CAD can be used to create simple drawing objects or more complex two-dimensional or three-dimensional models. This section will look at:

* How CAD has developed
* Important CAD features, layers, wire-frame, surface and solid models
* Rendering surfaces
* Multiple CAD files and connected data tables
* Differences between CAD, drawing programs and virtual reality
* Relationships between CAD and GIS
* Examples of how CAD has been used at the Acropolis in Athens, Deansway in Worcester, Symon's Castle in Powys and the York Minster.

### 1.2.1 How CAD Developed

CAD programs initially mimicked the world of two-dimensional paper drawings, but with the advances in both computer hardware and software, designing in three dimensions has become commonplace. CAD programs have an interesting parentage that helps to explain why they work as they do and which has bequeathed specific qualities to contemporary users. In fact 'Paper Space' is still used in CAD terminology to describe the two-dimensional presentation space for organising the plotting and printing of CAD models.

### 1.2.2 Paper Drawing Conventions

Paper drawings of objects are two-dimensional representations of the real world and such technical drawings use a series of conventions. For example, engineering drawings generally show the front, right side, and top of an object (see Figure 1). Broken lines are used to indicate lines that are hidden in the particular view, another line type is used to indicate the centre of a circle, another for the longitudinal axis of a cylinder and so on.


```{figure} ../images/g2gp-cad_fig01.jpg
:alt: Figure 1


__Figure 1:__ Two-dimensional engineering-style drawing of child's block with inset letters on six faces.
```


Archaeologists and architectural historians also developed a series of drawing conventions to indicate meaning when recording real world objects. For example, hachured lines are used to indicate the steepness of a slope on a plan, specific line types are used to indicate wear marks on drawings, etc.

### 1.2.3 Pin-bar Drafting

A process known as *pin-bar drafting* was developed by architects to permit convenient draughting of multi-storied or very complex buildings. Multi-storied buildings have identical exteriors for many floors but might have different interiors. Similarly, complex buildings, whether multi-storied or not, required separate electrical plans, plumbing plans, plans for heating and air-conditioning ducts, and so on. To eliminate duplication of effort, architects could draw the structural outline of the building (and common features like elevator shafts) on one sheet of paper, position a transparent sheet over the base sheet (on registration pins, hence the term), and then draw the interior of a specific storey on a transparent overlay. In the same fashion, electrical diagrams, plumbing diagrams, and so on could each be put on a transparent sheet, and a large number of such individual overlays could be put together on the registration pins so that many drawings could be viewed at once - making all features or only a few visible at one moment, as required.

### 1.2.4 Computer-assisted Drafting and Computer-aided Design

Computer-assisted drafting (CADD) programs were developed for architectural use and featured capabilities such as layering, mimicking the transparent overlays used in pin-bar drafting so that traditional architectural practices could continue.

Computer-aided design (CAD) programs were developed for engineering, to make it possible to move directly from product design specifications to manufacturing and to permit the visualisation of products in advance of production.

## 1.3 Common Features of CAD Programs

CAD programs are used to create a model of the real world. The term *model* is used in this guide to refer to the product of a CAD project, that is a computer file which can be re-used to create many individual drawings. The term *draw* will be avoided in this Guide because it implies the process of making a single drawing rather than the more flexible and complex digital product of a CAD project.

CAD software is widely used for two-dimensional drafting but most CAD software is now capable of creating three-dimensional models, complete with all the complexity of the real world. Whether a model is two-dimensional or three-dimensional it will be a complex layered version of the object under study.

### 1.3.1 Layering

CAD programs enable the parts of a drawing to be held in layers which can be displayed or suppressed on demand. The separate drawing layers created by CAD practitioners can be spatially, temporally or conceptually distinct from one another. For example, in Figure 2 different CAD layers have been used to hold different materials.

```{figure} ../images/g2gp-cad_fig02.jpg
:alt: Figure 2


__Figure 2:__ The use of CAD layers for different materials
```

This is particularly valuable when building a CAD drawing which may be used in a multi-disciplinary setting and/or by many different professions.  For example, Figure 3 illustrates key structural layers of a York Minster model which make up part of a much more extensive layering scheme.  The complete range of 73 layers are not intended to be viewed at once but represent the many professional requirements which the model has been designed to fulfill.  For example, the layers evident in this detail include pier detailing, metal furniture, timber panelling, tomb memorials and internal walls.

```{figure} ../images/g2gp-cad_fig03.png
:alt: Figure 3


__Figure 3:__ CAD model of York Minster (Field Archaeology Specialists)
```


A key development in the increased functionality of CAD has been the potential to incorporate additional raster image data as an integral part of the layering schema.  In Figure 4, image data obtained from a Ground Penetrating Radar (GPR) survey provides a valuable additional layer of information. The incorporation of raster image data introduces further archiving considerations for a CAD project.  In this case, image data which may be embedded within a CAD layer will also need to be archived separately - ideally adhering to the recommendations of the [Raster Images](https://doi.org/10.5284/mtgj-7130) guide.


```{figure} ../images/g2gp-cad_fig04.png
:alt: Figure 4


__Figure 4:__ Raster GPR data incorporated as a layer into a CAD model
```

 
Using layers to build up a model is a crucial part of the successful application of CAD to problems in the humanities. Layers can be used in a variety of ways, for example:

* In archaeology different layers might hold materials from different phases or time periods
* In historic building survey, the masonry of a wall may be shown on one layer, the windows on another, doors on another, and roofing on yet another. Different layers can be used for original parts versus additions, and any missing pieces might be reconstructed on yet another layer
* In theatre design, the different parts of the set may be shown on different layers - for example the stage, the flats, the designs for the scenes painted on the flats, the props and so on.

A thoughtful design of the layering system is one of the most important parts of creating a good CAD model (see [Section 3.3](cadsystems#id-3-3-cad-layers-naming-conventions-and-drawing-colours) and [Appendix 2](appendix2)). This segmentation into layers makes real analytical use of the model possible and the way that the model is constructed has an enormous impact on the kind of analysis that can be done. Of course, the analysis of CAD layers differs from the types of analysis that can be done with GIS layers (see [Section 1.5](abriefintroductiontocad#id-1-5-cad-and-gis)).

### 1.3.2 Multiple CAD Files

With large projects, such as an archaeological site or building complex, a single CAD file may become cumbersome and difficult to manage. Where the size of the file causes slow display and manipulation times it may be better to create separate CAD files for the individual elements that make up a large project. Alternatively, separating the elements of a project may also be necessary if the CAD model is being created primarily as a means to build data for another software package to process. For example, it may be desirable to compile the elements at a later stage in the case of virtual reality/animation or GIS projects.

Where separate files are created, links may be established to cross-reference the files (often called cross-references or xref files) to one another to create a composite model. Any number of CAD files linked in this way can be displayed together as if they are part of a single model and, although only one CAD file can be edited at any one time, any changes will be reflected in the composite model.

An advantage of using cross-referenced files lies in the ability of the CAD practitioners to work on small files as they create the elements that make up a large model. Different people may work on different parts of the model at the same time. There are also disadvantages, as editing common aspects of a group of files is more time-consuming than making the same edits in a large file. It is also important to make sure that the layer-naming convention is consistently applied across all of the linked files.

It can also be advantageous to use cross-referenced files for elements whose copyright owner is different from that of the rest of the model, for example where a map is used to provide a background to a plan in a two-dimensional model. The model may be viewed with the element where copyright permission has been granted, e.g. in a publication, but the copyright restricted element may also be removed prior to distribution e.g. when the model is deposited in an archive.

The most significant problem with using multiple CAD files is maintaining the links when files are transferred to a different computer or to a digital archive. If links are established by explicit directory pathways that are specific to the host computer (e.g. c:\projects\pompeii\2000\p211.dxf), when the files are moved to a new computer the links no longer point to the files. Secondary users must re-establish the links between the files by specifying the correct directory pathway. An alternative method is to specify relative directory pathways (e.g. ..\..\p211.dxf), which may ease the problem of moving linked files to a new computer; however, files must be copied in their directories with all relevant sub-directories to maintain the relationship. In addition, some CAD packages enable collections of drawings to be gathered together into projects. Changing the project's search path can also facilitate the exchange of drawings between users, or deal with different drive mappings to a server location. It is important to document the relationships between cross-referenced files, particularly when depositing a CAD project in a digital archive (see [Section 4.6](documentingdatafromcadprojects#id-4-6-documenting-cad-models)).

The key issues in considering the use of cross-referenced files are the size of the files and how the elements of the model will be produced. There is no rule of thumb; CAD practitioners will need to experiment with their models to see if they have become too large for current equipment. If speed is not a problem, using cross-referenced files offers no benefit to the end user except where the files are being worked on individually. In that case, it may be desirable to model the individual elements and then to copy these into a single composite model for distribution to others.

### 1.3.3 Full Dimensional Precision

Early design systems developed for engineering needed to hold precise dimensions, which were passed to machine tools and used to cut parts. The locations of all points had to be maintained in the computer file as real-world coordinates so that the tool could determine exactly where to cut a part. The computer display was scaled so the user could see the drawing, but underlying the display remained real-world numbers.

CAD programs developed for engineers separated the display of drawings from the underlying numeric data and modern CAD programs also hold the coordinates and measurements for the data-points used to create models in separate data tables. CAD models at different scales may be created from the data-points without the precision of the original data being affected.

### 1.3.4 Connected Data Tables

In addition to storing data-points, some CAD programs also allow users to connect individual items within a model to additional information held in external data tables. Such information might include simple annotations or detailed information about items in the model. For example, the individual stones in a building might be connected to a data table that specifies material, date of construction, surface textures, tooling marks, and Munsel colour.

The data table may be linked directly to an element in the model or a layer may be created in the model containing icons. These icons can then be linked to an external file containing explanatory notes. For instance, notes about the prior use of a specific group of blocks, or the blocks used in a certain wall, could be attached to an icon - perhaps an arrow pointing to the blocks in question.

Connecting CAD models to external data tables gives an opportunity to expand on the information in the model or contained in the layer-naming system. Such links are two-way connections and they can add useful analytic capabilities. For example, starting with the database one might obtain the set of all the re-used blocks and then highlight those blocks in the model to display their distribution. Considerable use may be made of such capabilities in excavation recording and intra-site studies, for example by linking context and artefact files to site plans.

## 1.4 Two and Three-dimensional Drawings and Models

### 1.4.1 Two-dimensional Models

The difference between two-dimensional drawings and two-dimensional CAD models is that a drawing offers a single representation of the world while a model may be structured into layers that can be viewed together or separately. In addition a model can be produced on paper at virtually any scale. A two-dimensional CAD model (as described in the [Deansway case study](casestudy1)) may look similar to a two-dimensional drawing of the same plan but in fact the model offers much more flexibility. A series of different views can be produced from the model highlighting different layers. With thoughtful structuring of the CAD layers it is possible to use the model for analysis. For example, the locations of features with given characteristics (e.g. period, phase, material) can be compared, as is illustrated in the Deansway case study.

### 1.4.2 Three-dimensional Drawings and Models

The difference between a two-dimensional drawing and three-dimensional drawings or three-dimensional models is enormous. Figure 1 ([Section 1.2.2](abriefintroductiontocad#id-1-2-2-paper-drawing-conventions)) shows a two-dimensional engineering drawing of a child's wooden block with inset letters on each face. An isometric drawing of the same block (i.e. a drawing showing its three-dimensional nature without foreshortening the sides of the block as they recede) is shown in Figure 5 below. Most people would find the isometric drawings easier to understand than the engineering drawing.

```{figure} ../images/g2gp-cad_fig05.gif
:alt: Figure 5


__Figure 5:__ Three-dimensional isometric drawing of child's block
```

There are essentially three ways of constructing three-dimensional models in CAD:
* Wire-frame modelling
* Surface modelling
* Solid modelling.

Different CAD packages implement these to varying degrees.

### 1.4.3 Wire-frame Models

A wire-frame model consists simply of points and lines drawn in three-dimensional space. These define the edges of objects, but there are no defined faces or surfaces. Figure 6 illustrates that these models can be very difficult to use. For example, it can be difficult to tell which lines in a wire-frame model are at the front and which are at the back from a particular viewpoint (the Necker cube effect). A wire-frame model of the older propylon on the Athenian Acropolis would be even more difficult to understand.

Wire-frame models should not be confused with the wire-frame representation of three-dimensional models which have defined surfaces. Surface and solid models may be viewed in CAD software as wire-frames for speed of viewing and manipulation.

```{figure} ../images/g2gp-cad_fig06.gif
:alt: Figure 6


__Figure 6:__ Wire-frame version of child's block
```


Wire-frame models can provide the basis for other kinds of models. For example, the edges of complex objects can be precisely digitised as a collection of wire-frames and subsequently have surfaces applied to them or be converted into solid objects. For example, Figure 7 is a wire-frame model of part of a castle, derived from an elevation drawing and placed on the floor plan. There is no solidity to the model, it exists only in outline as a series of interconnected three-dimensional points.

```{figure} ../images/g2gp-cad_fig07.gif
:alt: Figure 7


__Figure 7:__ Wire-frame version of castle wall
```

### 1.4.4 Surface Models

Surface models are more complex than wire-frame models - as well as defining the edges of objects, the surfaces of the objects are also defined. Hence Figure 5 is a drawing based on explicitly defined surfaces to give the appearance of their real-world shape. These surfaces are opaque so that the lines and faces that would not show in a real-world view are suppressed (a hidden line drawing) - compare Figure 5 and Figure 6. An important CAD feature is that when asked to produce a drawing from a specific vantage point, the program can calculate which lines and surfaces should not appear in the drawing because they would be hidden by intervening surfaces.

There are many ways of creating surfaces, though in most cases these involve combining small surfaces to create larger, more complex objects. One method involves the construction of small, discrete surfaces that are then combined to make more complex objects (see Figure 8). These may be constructed as wire-frames and surfaces fitted between the edges. For example, Figure 9 shows the same model of a castle wall, but this time the edges have had a (greatly simplified!) surface fitted between them. As a result, when hidden line is applied, the wall now looks more solid.

```{figure} ../images/g2gp-cad_fig08.gif
:alt: Figure 8


__Figure 8:__ Small surfaces used together to make a single, larger surface
```

```{figure} ../images/g2gp-cad_fig09.gif
:alt: Figure 9


__Figure 9:__ Surface model of the castle wall, derived from Figure 7
```

A combination of these approaches is to create templates for surfaces, which can then be swept along pathways to create more complex shapes. For instance, a wire-frame cross-section of a pot could be swept through 360 degrees to create the inner and outer surfaces of the complete vessel. Similarly, Figure i in [Case Study 5](casestudy5) (a Digital Terrain Model of Hambledon Hill) is an example of a surface constructed by linking together an array of three-dimensional points to form a mesh.

An alternative method is to use the CAD program's ability to construct standard geometric solids (boxes, cones, spheres, etc.) automatically, which provides the components that make up the overall shape. Virtually any regular geometric solid can be constructed by most CAD programs and assembled (by Boolean operations of addition, subtraction, etc.) to create more complex solids, a facility that is widely used in design. However, the real world is not made up of regular geometric shapes and recording real-world objects usually requires the construction of large, complex surfaces from small, simple ones. These small surfaces must lie in a single plane; therefore the simplest surfaces are triangular as three points may always be placed in a single plane. Even if a CAD program permits construction of more complex irregular surfaces without using individual planar facets, small surfaces are crucial when modelling very complex geometry.

### 1.4.5 Solid Models

Surface models are constructed from the faces of an object leaving the interior of the object undefined or hollow. In a solid model the composition of the interior is defined - hence it is solid. Although in most views a solid model seems identical to a surface model, a CAD program can produce a cross-section through it. Solid models are created using boolean geometry - adding, subtracting, and 'differencing' simple shapes to create more complex ones. In general, solid models are easier to work with than surface models. For example, it is topologically difficult to cut a hole in a surface mesh, but it is easy to 'carve' features out of a solid model by subtracting elements from each other. Furthermore, materials can be assigned to solid models and their properties analysed - for example, the mass and centre of gravity of an object can be calculated or its load-bearing capacity determined.

```{figure} ../images/g2gp-cad_fig10.gif
:alt: Figure 10


__Figure 10:__ An apparently solid model of a wall
```

The central block in the middle of the wall depicted in Figure 10 consists of only two visible surfaces. However, all six sides of that stone would need to be surveyed for a solid model to be created. In Figure 11, the original surface model of the wall has been extruded to create a solid wall, and the windows have been created by subtracting them from the wall. The same effect would have been very complex to achieve using a surface model.

```{figure} ../images/g2gp-cad_fig11.gif
:alt: Figure 11


__Figure 11:__ Solid model of the castle wall, derived from Figure 9
```


Solid models are also commonly created using a standard 'toolkit' of geometric shapes - boxes, wedges, cones, spheres, etc. - which are again combined using boolean algebra to form more complex shapes. For example, Figure 12 is a solid model of a timber tower, which, apart from the roof, is created entirely from boxes using boolean addition and subtraction

```{figure} ../images/g2gp-cad_fig12.gif
:alt: Figure 12


__Figure 12:__ Solid model of a timber tower (wire-frame and shaded representations) [@huggett20003d]
```

The value of visualisation in public presentations is being increasingly recognised in the humanities, especially in archaeology and architectural history. At the same time, three-dimensional modelling tools are increasingly found in even relatively basic CAD packages. However, it is important to be clear about the purpose of such models. For example, the wall in Figure 11 is a greatly simplified representation of the real world, and while it may provide an adequate visualisation it is far from accurate. It is, however, simple to construct, manipulate, and, with the addition of appropriate surface textures, can provide an effective small-scale model. On the other hand, a fully detailed solid model can rarely be made without dismantling standing structures and the gain from creating such a highly detailed model is often minimal. Such models are complex to make and demanding of computer hardware and are generally only used to address specific structural questions. For example, they might be used in reconstructions of missing structural elements of an historic building, such as in the reconstruction model of the Roman baths in Bath, where the heights and cross-section of the masonry vault were remodelled as a result of the application of physical principles to the solid model [@lavender1990solid]. Additionally, solid modeling of reconstructions may form the basis of other analytical techniques, for example, acoustic modeling [@campos2002acoustic].

Programs may permit some cross-over between techniques, and users should be familiar with the processes before beginning to build an important model. Learning the intricacies of CAD modelling is best done with one's own objects and survey data than through any tutorial or sample process. Trying to match real geometry requires the user to understand it at the outset and have a sense of what a good finished model should look like. Although regular solids (boxes, cones, spheres, cylinders, etc.) can often be created with a CAD program, easy-to-use creation tools are rarely useful for modelling real-world objects.

### 1.4.6 Rendering

Technically, rendering refers to the process whereby a model is displayed on screen from the associated data files. However, the term has come to be used specifically to refer to the process of applying colour, texture and so on to the surface of CAD models. A series of sophisticated processes has been developed for CAD software to illustrate the appearance of objects. These are used to study the results of design choices that affect appearance, e.g. colour, texture, and subtle changes in shape. These programs are particularly important for designing consumer products and in reconstructions, as they enable models to be given a real-world appearance. For example:

* Lighting can be adjusted to see objects under different conditions
* Surface treatments can be applied, e.g. the child's block could be treated to appear if it were made from wood with white paint to highlight the letters
* Surface textures can be applied, e.g. a photograph can be used to create a bitmap which is applied to the model giving a real-world appearance.

The use of CAD software to render a model allows more 'realistic' reconstructions of archaeological monuments. For example, the tower in Figure 12 has been rendered using basic colours and shading, while in Figure 13 more complex textures have been applied. The realistic appearance of such images, however, can be deceptive if read uncritically [@eiteljorg2000compelling].

```{figure} ../images/g2gp-cad_fig13.gif
:alt: Figure 13


__Figure 13:__ Model of the older propylon which has been rendered with complex textures and shadows to create a realistic impression of stone walls, steps and of the floor.
```

## 1.5 CAD and GIS

Geographic Information Systems (GIS) have some similarities with CAD programs in that they represent spatial objects that are linked to data held in tables. GIS software was developed for geographers, cartographers and others working with maps and, of course, maps have some similarities with architectural plans. While GIS can incorporate scanned paper maps or digitised vector maps, early versions in particular offered only limited drawing facilities. CAD programs are much more sophisticated in this respect and, as a result, they are often used to create maps that are subsequently imported into GIS. These factors have encouraged confusion about the differences between CAD and GIS programs. Despite that confusion, they are very different in terms of their aims, offer different features and have very different internal data structures.

CAD systems were developed for representing geometric objects. These objects can be described in more detail by tabular data that is attached to the CAD model. For example, it is possible to attach an element in a CAD model to the data in an external data table (see [Section 1.3.4](abriefintroductiontocad#id-1-3-4-connected-data-tables)). However, the aim is descriptive: the data simply augment the geometric representation of objects with additional information beyond that which is implied by its shape, position and layer designation in the model. For example, an artefact in an excavation may be shown in a CAD model and linked to additional data that describe its material, surface treatment and so on. Essentially, CAD is limited to representing geometric space and, unlike a GIS, does not include tools for cartographic projection.

GIS can incorporate a series of different maps (vector and raster) linked to data and overlying one another in layers or coverages. GIS emphasises the link between a graphic object (a feature such as a point or defined area on a map) drawn on a layer or coverage and associated data. The graphic object and data can be taken together as parts of a set on which the GIS can perform mathematical and other functions. GIS offers considerable powers of analysis both within and between sets. For example, a GIS could find all settlement areas that were associated with a particular type of sherd. These results could then be compared to another set to find which of those settlements were located on a particular type of soil. In addition, GIS includes many features that allow interpretations of and calculations based on terrain, such as calculations of the steepness of a hill or of the areas that can be seen from a specific vantage point.

In short, the connection between spatial information and tabular data is more robust and more central to the functions of GIS than CAD; the resulting analytic possibilities are therefore much greater. However, GIS cannot be used to model complex three-dimensional objects adequately, such as buildings or excavation trenches. Although height data can be recorded in GIS, no point can have more than a single elevation and at best 2.5-D effects can be produced.

Many projects can benefit from the use of both CAD and GIS, although the distinction between the two can be expected to disappear as CAD features are increasingly added to GIS software and GIS features are added to CAD software, driven by commercial interests. In the meantime, the [Symon's Castle case study](casestudy2) illustrates the use of both CAD and GIS, emphasising where GIS departs from CAD.

## 1.6 Data Visualisation: Rendering Techniques & Analysis Methods

In addition to GIS applications, CAD files may also be passed to other kinds of programs to be used in different ways. Two of those program types, rendering software and virtual reality software, have the potential to transform the rather prosaic line art of a CAD model into startlingly lifelike images. CAD files may also be passed to drawing programs to produce final publication standard illustrations with appropriate labels and graphics. It is important, however, that CAD should not be confused with virtual reality, or vector and raster drawing programs.

### 1.6.1 Rendering Software

Rendering software provides tools to add surface materials, textures, and colours to CAD models. In addition, lighting - even the light of the sun in a particular place on the globe - can be simulated, complete with reflections, shadows, and more subtle effects of reflected light. The results can be realistic views of structures, images that make such structures come to life for the viewers. Rendering software has become so popular that CAD programs often include good rendering tools, but the best renderings are produced with specialised rendering programs.

### 1.6.2 Virtual Reality

The other kind of program for producing more realistic views, virtual reality software, has received a great deal of attention in the archaeological community. It has the potential to take photorealism to another level, creating virtual worlds with all the effects of rendering programs plus the ability to mimic moving through or around the model, seeing it from any angle and watching things change as the viewpoints change. Stereo views are even possible. Although the promise of virtual reality software has been recognised for some time, the computer power needed to provide the best level of verisimilitude and the ability to move freely in three-dimensional space is not yet widely enough available to provide high quality results outside research laboratories.

CAD models are often used as the basis for many virtual worlds. The virtual world used in a VRML model, for example, can be described as a series of coordinates in a text editor. Such a process, however, is difficult and time consuming and it is best to develop the world initially as a CAD model and then to convert the CAD model into VRML using a convertor. The CAD model should remain the core data source for archaeological materials.

### 1.6.3 Painting and Drawing Programs

Drawing programs and paint programs are also sometimes confused with CAD. However, there are important differences which are most significant when comparing CAD and paint programs.

CAD programs store lines, arcs and circles using mathematical formulae (vectors) so that they can be represented at any scale, on screen or on paper, at any time. While 'Paint programs' permit users to draw lines, arcs, and circles, they store the results as individual dots (pixels or rasters). Once drawn the results are only isolated, independent dots that cannot be understood as composing larger entities. Enlarging or reducing such drawings often results in computer images with jagged lines in some places and blotchy, unclear shapes in others. Editing such drawings must be done one dot at a time. These programs are not designed for line art, nor are they able to deal with precise dimensions unrelated to the scale of the drawing.

'Drawing programs' are closer to CAD programs as they also use vectors to store drawings. However, unlike CAD data, the vectors are not tied to real-world numbers. Instead, they are related to the drawing page and are scaled implicitly. Furthermore, the three-dimensional features are very limited. These programs are capable of making excellent presentation drawings, using CAD output as the starting point, but they lack many of the precision and three-dimensional features of CAD programs.

Both paint and drawing programs lack some of the features that can make a CAD model so much more complex than a drawing or illustration - when CAD files are passed to any of these programs (rendering, virtual reality, paint or drawing) it is generally without the layers and attached data tables that give CAD models their flexibility.
