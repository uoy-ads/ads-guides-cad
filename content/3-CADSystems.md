---
authors:
  - name: null
---

# 3 CAD systems

## 3.1 Choosing CAD Software and Hardware

This section looks at some of the differences between CAD packages and emphasises the importance of choosing a system that is suitable for the proposed task. Computer hardware and software are both constantly developing and specifications change rapidly. When establishing a CAD system it is important to check that the components are compatible, including those elements that allow models to be viewed on other platforms such as the file format and layer-naming conventions used.

### 3.1.1 Choosing CAD Software

The most obvious consideration when choosing CAD software is whether it will do everything that you need it to. Different packages have different capabilities and it is not always obvious whether a specific program will meet all the requirements for a given job or how easy it is to use for your purposes. For example:

Will the software accept data input from keyboard, mouse and digitiser?

* Users intending to use CAD for design should look for programs that ease data input using the mouse and the graphical user interface
* CAD users intending to input data points using the keyboard should experiment with programs to make sure that it is easy to enter absolute data points or define points in relation to others
* CAD users intending to enter data using a digitiser require an interface system that accepts input from the digitiser in place of a mouse and permits scanned drawings to be scaled, related and traced. Not all CAD software allows this, especially cheaper packages.

Some CAD packages automate the creation of regular shapes; irregular shapes create more problems. Different CAD software has differing capabilities for two-dimensional, three-dimensional wire-frame, surface and solid modelling. Not all CAD software can be connected to external data tables and this capability is an important consideration if it is intended to link site plans or models to materials, context or artefact data. Users should experiment with inputting typical data to be sure that the proposed system meets their needs and may wish to take advice from a colleague who is familiar with the program and the intended work.

Less popular CAD software may not support the full array of peripheral equipment and users may be restricted to specific graphics cards, plotters, or input devices which in turn may have limited availability or be expensive. With most operating systems, connections to peripheral devices do not normally depend on the CAD program; however, it is important to be certain that proper use is made of data from peripheral devices.

CAD software uses proprietary file formats and these do not necessarily transfer successfully between different programs (see [Section 3.2](cadsystems#id-3-2-cad-data-formats)). Users are recommended to check that the available file formats are appropriate for their needs. For example, drawings from a CAD model are often exported to illustration programs like Adobe Illustrator, Freehand, or CorelDraw where text and other features are added for publication. CAD users should check that the proposed program will be able to export files in appropriate formats and that an appropriate format for deposit with a data archive can be produced.

Those who are planning to use a total station for survey work should check the availability of a program to accept data from a total station and format it appropriately for the proposed CAD system. Data are often collected from a total station and converted to DXF files which may not transfer successfully into all CAD software.

CAD users should consider the medium- to long-term stability of the manufacturing company and arrangements for support, including the availability of training and instruction manuals for users. Commercial training in CAD can be very expensive and users may wish to consider the availability of alternative options.

Finally, more expensive CAD packages generally offer more facilities than cheaper packages, but these may not be necessary for the intended purpose. Users should check the facilities included against their requirements.

### 3.1.2 Choosing CAD Hardware

As computer hardware develops rapidly and costs go down, when choosing hardware it is important to check the minimum specification required to run a particular CAD program but then to check whether a higher specification machine is available. Software requirements will generally direct CAD users to PCs rather than Apple Mac computers or those using Unix, Linux or other operating systems. Factors which should be taken into consideration are processing power, RAM and the size of the hard drive. Working with large models (changing points of view, making hidden line drawings, rendering the model, etc.) requires a fast computer although the hardware requirements will be reduced if the model is solely in two dimensions or three-dimensional visualisations are not used. Upgrades to new and improved CAD software may also increase the hardware specification required. Laptops used for work on site should incorporate a good size screen and a large hard drive.

Monitors should be free from distortion and be the largest affordable. Larger screens make it easier to see larger images and to deal with small details.

Plotters produce their output with either pens, an electrostatic charge, or ink jets. Large plotters make it possible to output very large drawings, although bureau services are available if large drawings are rarely needed. Good ink jet or laser printers and colour ink jet plotters can produce excellent drawings in small sizes at modest prices.

Scanners and digitisers vary in size and in terms of the resolution at which they can process an image and it may be desirable to scan an image at a higher resolution if it contains complex detail which is later to be vectorised. In all cases it is important to check that the digitiser will offer the required output and it may be advantageous to hire bureau services rather than purchasing expensive equipment.

## 3.2 CAD Data Formats

As highlighted at a recent [DPC event](https://www.dpconline.org/news), there remains no standard open format for exchanging CAD data between different software packages and the best advice on the subject comes from @lyman1998defining who suggest that CAD users should 'save in the most common file formats, [as] the more files that exist in a given format, the more likely that file converters or emulators will be written for that format (because of economies of scale).'

At present the most commonly used CAD software is AutoCAD, made by AutoDesk and consequently it is recommended that CAD files are saved in both .dwg and .dxf formats. These formats are, however, not without their problems.

The most widely used CAD file format is .dwg, which is the proprietary format used by AutoCAD. Due to AutoCAD's market prominence, the use of the .dwg format has become dominant and other software manufacturers have implemented Autodesk software to permit their users to read and/or write .dwg files. Unfortunately this is not always effective, as incompatibilities between programs can create problems with data transfer. There are even problems of incompatibility between slightly different, although equally current, packages from the same software house. For example, AutoCAD MAP, made by Autodesk, supports additional data elements which will not be recognised by the basic AutoCAD package.

Drawing exchange format (.dxf) is another proprietary standard developed by Autodesk as an output format to allow users to exchange AutoCAD data and to transfer files into other drawing programs. The .dxf format is very widely used but it is not controlled by a standards body and Autodesk can alter the format at will. There are also incompatibility problems with .dxf and in particular the problem that software packages which do not support particular versions of .dxf may still import the data but incompletely. Thus users may be unaware of the fact that data have been lost in the migration.

Another CAD file format which may be used for dissemination is Drawing Web format (.dwf). The .dwf is a highly compressed file that is created from a .dwg file and is used purely for publication on the Web. It is not recommended that CAD files are either stored or archived as .dwf.

Given the problems of incompatibilities between different file formats, and even incompatibilities between the same file format from the same manufacturer, it is recommended that CAD files are saved in the latest possible version of .dwg and .dxf, and that this is fully documented. CAD files will consequently require active digital curation and will need to be continually migrated to new versions of .dwf/.dwg as they are brought into use. After every migration it is necessary to check the files to ensure that there has been no loss of information during the migration process. Given their somewhat problematic nature, CAD files and documentation should be passed to an appropriate digital archive at the earliest opportunity.

One possible area of development with regard to CAD files is, however, offered by the [Open Design Alliance](https://www.opendesign.com/) (ODA, formally OpenDWG). The ODA formed originally with the aim of making the .dwg format into a public standard but the Alliance now develops and provides free of charge the Teigha platform which provides read and write capabilities for both .dwg and .dxf formats. The Alliance itself consists of a number of significant [commercial members](https://www.opendesign.com/member-showcase) so it is hoped that through the development of Teigha, support for .dxf and .dwg files will become more widespread and stable in third-party applications.

__Raster Data__

Where raster images have been embedded into CAD files then it is recommended that these are also stored separately to the CAD file and are documented and archived in line with the recommendations presented in the [Raster Images](https://doi.org/10.5284/mtgj-7130) guide.

__Other Formats__

While AutoCAD formats may continue to be dominant in the foreseeable future, recent developments indicate that other formats and applications may yet still be widely adopted. The emergence of [Google Sketchup](https://sketchup.trimble.com/en) and the Linux/Unix-based [QCAD](https://www.qcad.org/en/) present possible alternatives to AutoCAD while supporting the DXF format.

## 3.3 CAD Layers, Naming Conventions and Drawing Colours

When constructing a CAD model, various portions of the model are placed on different layers. The layers should be designed to distinguish material in the model according to important criteria, for example, building part, building phase, site stratum, material, chronological standing, etc. Each layer should hold only a portion of the model as putting too much on a single layer may cause problems when the model is used for analysis. Objects can be moved from layer to layer, but this is harder to handle if many objects are held on a single layer. More importantly, the way that the model is segmented will affect its usefulness.

Using different layers requires some system for assigning portions of the model to particular layers and a naming convention for those layers. For example, a model of an historic structure may have many layers - for phases, materials, functions, designer/builder, and so on. Potentially all models can be segmented in any number of ways. The scheme chosen should make it possible to find material according to multiple criteria and in this way the layering scheme permits users to access the layers very much as they might access parts of a database.

A shortcoming of the layering systems in CAD software is that there is no facility for creating a hierarchical scheme to match hierarchical recording systems. For example, a surveyor may record the ridge board, rafters and truss beams as separate components that taken together comprise the roof of a building. This is a hierarchical system but CAD software does not allow one layer to contain other layers, thus it may be difficult to re-group the separate roof components. One way of working around this shortcoming is to use the layer or file naming conventions to create relationships between components, e.g. all names beginning with A form a set which comprises AA, AB, AC etc.

### 3.3.1 Naming Conventions for CAD Layers

It is important to adopt a systematic approach to naming layers in CAD models. CAD systems permit searches based on layer names and some systems permit searches using 'wild-cards' which enable retrieval of sets of layers with structured names. In complex CAD models or models comprising cross-referenced files, it is important to be able to bring together layers without causing confusions through inappropriate use of layer names. For example, users often begin with layer names like wall and door, then graduate to *wall1* and *door1*. As the model grows, layer names grow longer, more complicated and harder to remember. Layers cannot easily be selected from the model according to their characteristics; instead a user must know all of the layer names and type in a subset when trying to select specific portions of a model. Even then it is difficult to be sure that all the relevant layers have been accessed.

The layer-naming scheme should be designed and specified as early in the project as possible. As the model grows, the use of the scheme will become more and more important. In deciding upon a layer-naming scheme, CAD users have the option of either adopting an existing convention or developing their own system. In either case it is important to make sure that the naming convention is documented, can be consistently applied and allows some flexibility for modification as the model develops.

The CSA layer-naming convention is an example of an existing scheme. It is a systematic naming convention that is based on layer names designed to specify the contents of each layer. Each character in the layer name designates information according to its position as well as by the letter itself (see [Appendix 2](appendix2)). The CSA convention is a conceptual scheme that permits the layers of any CAD model to be accessed according to logical analytic categories that are meaningful and useful for a specific project. It is more general and more adaptable than a discipline-specific scheme, but works well only with programs that permit 'wild-card' searches for layers.

Some organisations define layer-naming conventions that are designed to meet specific, practical needs, for example architects might define conventions to be used by different professionals working on a development. @eh2005presentation has developed a systematic layer-naming convention for buildings archaeology, photogrammetric recording and topographic survey. This system accommodates CAD layers produced by other professions and has some of the features of the CSA system but with a more prescriptive list of layers.

Both the CSA and the English Heritage conventions have enough flexibility to be modified for specific projects. As a general rule any such changes should be systematically implemented throughout the model. With a complex scheme such as the CSA convention, the original model and layer-name models should be backed up and saved and checked once the new system has been established.

Documenting the layer-naming scheme is critical to a CAD project. Such documentation should include a list of the layer names or codes with a description of each. A description of how the layer-naming scheme has been developed and how it is applied is also useful, especially with a complex scheme. One method of tying the layer-naming convention to the CAD file is actually to include the scheme as a layer within the model.

### 3.3.2 Conventions for Selecting Drawing Colours

It may seem that colours should be used like layers, to specify analytic aspects of a model. For example, a specific colour might be assigned to a given structure, or to a given stratum in an archaeological site. This can be done, but different colours should not be assigned to objects on the same layer of a drawing. The objects should be placed on appropriate layers first and then a colour should be assigned to each layer. All entities on a given layer will then be the same colour. The visual result may be the same, but the process is different because the layers, not the colours, hold the analytical distinctions.

There are two reasons to resist the temptation to use colours, rather than layers, to hold meaning:

* It is easier to change colours than to change layers and inadvertent colour changes could result in loss of meaning
* The print process generally uses colours or line weights in the model to determine the line colour or weight that is printed on paper. This means that the colours in the model may need to be changed every time a paper drawing is produced, since each tends to serve a particular purpose and emphasise different points.

The danger of losing important distinctions is too great if colours have been changed, and any distinctions between portions of the model should be made using layers.
