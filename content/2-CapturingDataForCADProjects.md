---
authors:
  - name: null
---

# 2 Capturing Data for CAD Projects

## 2.1 Data Acquisition: Precision and Accuracy

One of the first decisions that must be made by the project director concerns the methods that will be used to capture data into the CAD model. This may involve a combination of field survey and digitisation or off-site data capture, yielding data with different levels of precision, and separate CAD layers or cross-referenced files may be created as the data are incorporated.

A range of different techniques are available to capture data for CAD projects. The most common sources of data for CAD models are:

* annotated lists of measurement points derived from traditional hand measurement survey techniques
* digital data logs derived from total station or GPS survey techniques
* digital data logs produced by direct object scanning e.g. laser scanning
* digitisation of maps, plans and drawings
* digitisation of photographs, including rectification and photogrammetry
* existing CAD models.

The selection of an appropriate technique and methodology will depend on a number of factors. Project planning will involve careful consideration of both the object to be modelled and the type of CAD model to be produced and its uses. For example, a two-dimensional plan or elevation will require fewer data-points to be captured than a three-dimensional wire frame or surface model. A three-dimensional solid model will require even more data-points as both visible and invisible surfaces must be modelled.

Project directors must also consider the appropriate levels of precision and accuracy required for the project, the methods of survey to be used and the availability of maps, plans or photographs for digitisation. Before commencing data capture, project directors are recommended to select an appropriate CAD layer-naming convention (see [Section 3.3](cadsystems#id-3-2-cad-data-formats)).

### 2.1.1 Precision

It is important to consider and document at the project design stage the appropriate level(s) of precision to be used. The __precision__ of a measurement refers to how exactly that measurement was made and not the correctness of the measurement. For example, a measurement made to the nearest millimetre is more precise than a measurement made to the nearest centimetre.

The precision of a measurement is reflected in the number of significant (or meaningful) digits with which it is expressed. Thus, a measurement of a block of wood known to be 2.01034 metres long, expressed with two significant digits, is 2.0 metres. If the block was measured with a micrometer precise to a tenth of a millimetre we would show it as being 2.0103m long. If the same block was measured with a steel tape precise to the nearest millimetre the measurement would be 2.010m. The trailing 0 seems to offer no information, but in fact shows that the measurement is precise to the nearest millimetre. A measurement of 2.01m would be accurate to the nearest centimetre. For a detailed discussion about precision and the relationship to significant digits see @eiteljorg2002csa, chapter 2.1.

The high precision offered by modern instruments should be used, as a rule, since data can always be degraded but cannot subsequently be improved in precision. The precision of survey control points is of particular importance, as readings taken from a control point whose coordinates are given to two decimal places can only be given to the same level of precision.

### 2.1.2 Accuracy

The __accuracy__ of a measurement refers to how correctly it was taken and not how precise that measurement is.

A measurement made at a low level of precision should be as accurate but not as precise as a measurement taken with a higher level of precision. Making certain that measurements are accurate should involve both calibration of equipment and repetition (see [Appendix 1](appendix1)). Calibration tests the accuracy with which instruments measure while repeatability tests the efficiency of personnel and procedures and project directors should develop schedules for calibrating instruments, training and evaluating personnel and procedures.

To summarise, accuracy relates to the correctness of a result while precision essentially relates to the size of the smallest unit of measurement.

### 2.1.3 Appropriate Levels of Precision

Different levels of precision are appropriate for different projects, depending on the intended uses for the model produced. Modern survey methods make it easy to obtain very high levels of precision and there may be a temptation to seek the precision that is possible rather than that which is appropriate. For example, survey instruments like total stations automatically take measurements with high levels of precision. This can yield very misleading models; for example a rendered model illustrating a reconstruction of a building may imply that the original builders and craftsmen worked to very tight tolerances. The actual tolerances, however, are more likely to have been much looser.

For example, a project to record surviving concrete walls at Pompeii might decide that measurements should be taken to the nearest centimetre, but not to the nearest millimetre. In this case, higher levels of precision were not required, since the dimensions of the buildings measured to the finished surfaces do not survive. The concrete wall cores that do survive were not constructed to tight tolerances and measuring with great precision therefore provides no useful information.

Ancient cut-stone architecture that does not involve mortar, on the other hand, was constructed to very precise tolerances because of the absence of mortar and the unforgiving, inelastic nature of stone. The precision of measurement must be similarly high. In general the rule is that high levels of precision in construction and design need to be reflected in measuring the finished product. Lower levels of precision in construction, on the other hand, call for lower levels of measurement precision.

For paper drawings a more practical approach is matching appropriate precision to drawing scale so that the most precise measurements can be expressed in a drawing at the scale to be used (see also [Section 3.2](cadsystems#id-3-3-cad-layers-naming-conventions-and-drawing-colours)). Thus measurements are taken with the scale of the final drawings in mind, to the level of precision that would be useful in those drawings. @eh2005presentation suggests that survey precision will be affected by the scale(s) at which surveyors expect drawings to be produced. This is certainly the case when surveyors are attuned to hand-drawing methods rather than CAD.

### 2.1.4 Indicating Precision on Drawings and in CAD

Precision is indicated on drawings through the use of significant digits. Where dimensions are shown, precision is clear. When dimensions are not shown on a drawing, they can be retrieved by making measurements on the drawing and, where appropriate, applying the scale factor. In such cases, the scale of the drawing is a limiting factor, and precision is limited by the double problem of scale - the accuracy with which the draughtsperson, working at reduced scale, can produce a line of appropriate length and the accuracy with which a user can measure and scale up a line on the drawing.

CAD models present a different problem for determining precision. All points are specified in a three-dimensional Cartesian grid system, and dimensions are calculated from those point locations. The precision of the point locations depends on the CAD system used but is the same for all points in any given model with trailing zeros being added or additional digits truncated. In most CAD systems, users may decide on the number of decimal places to be displayed. However, all point locations and dimensions must have the same number and will appear to have the same precision. Thus the number of decimal places displayed in a CAD model does not reflect the actual precision of any specific measurement and false precision may be suggested.

### 2.1.5 Mixed Levels of Precision

A model may contain very precise measurements alongside less precise ones because combined data capture techniques have been used. For example, a total station may be used along with steel tape measures to capture certain dimensions and, while the survey data may be accurate to the nearest millimetre, other data may have a 1cm tolerance. Separate CAD layers or cross-referenced drawings may be used to hold items with different levels of precision.

Levels of precision must be documented so that users of the model have ways to determine which measurements or locations have been more or less precisely determined. With this information the model can be used to extract additional measurements whose precision is known. The precision of any measurements can be no better than that of the reference points, but the situation is more complex still, since measurements taken from a single reference point may be very precise when compared with one another but not when compared with other points in the model. Careful documentation allows users to avoid the practice of using points from lower-tolerance data sources as reference points and also allows users to know when to expect good high-precision measurements.

### 2.1.6 Documenting Precision

Since CAD systems cannot display differing levels of precision and may indicate spurious levels of precision, CAD models must be documented (see [Section 4](documentingdatafromcadprojects)). This documentation should explain how precisely the dimensions and data points were determined, and how users can discriminate between more and less precise measurements if both are present. For example, different layers might be used for different levels of precision. The setting for displaying decimal places, if set within the model rather than the CAD program, should be appropriate to the precision used in measuring.

## 2.2 Data Capture and Field Survey for CAD Modelling: Procedures and Techniques

### 2.2.1 Planning a Survey

There are a number of factors which must be taken into account when planning a survey to capture data for a CAD model.

The first consideration is the object to be modelled and the end product that is required. An historic building, a barrow, an excavation plan, some theatre scenery flats and a garden plan each have their different aspects and might be modelled differently in CAD. However, the decision whether to undertake the work in two or three dimensions or to create a wire-frame, surface, or solid model is only partly based on the shape of the object itself. The product that is required also influences the decision. If plan views or elevations are required, then two-dimensional data may be gathered from the outset. An archaeological plan or plan of the standing remains of a building might be made with three-dimensional points but be treated as a plan only; a wire-frame model would be appropriate in such cases.

__Data Density__

Similarly the number of data-points that are recorded will depend on the type of model that is being produced and the final product(s) that are envisaged, including any visualisation that is required. A three-dimensional model will have at least twice as many points as a plan (see Figure 14). For example, a wall must be surveyed as carefully where it meets the ceiling as where it meets the floor to produce a three-dimensional model, even if it appears to be vertical. An archaeological feature recorded in two-dimensional typically involves a quite dense collection of data points for the outline but relatively few points recording the depth or profile. Such a level of recording cannot subsequently be transformed into a reasonable representation of the original three-dimensional feature unless many more points are recorded in the first place.

```{figure} ../images/g2gp-cad_fig14.gif
:alt: Figure 14


__Figure 14:__ Survey points needed for two-dimensional and three-dimensional survey<br>Points A-H (__blue__) would be needed for a plan only, two-dimensional survey<br>Points I-P (__red__) would also be needed for a three-dimensional survey
```


Details within the structure being modelled also affect the density at which data are collected. For example, a wall made of cut marble blocks might require four points for each block while an irregularly surfaced mud brick wall might require a number of points along each edge as well as points spread throughout the surface.

The intended uses of the model should also be taken into consideration when planning the density of data collection. For example, a higher data density will be required if a three-dimensional model is to be used for renderings, virtual reality presentations or other presentations that aim to give a full sense of the object. The scale of the required output also influences the number of points being captured. For example, fewer points are required for a two-dimensional landscape output at 1:10000 than for a similar survey output at 1:1000.

Considerations of time and cost will also influence the type of model that is produced and the number of data points that are captured. When considering data density, practical choices must be made as every added data point complicates the model, the model making, and the end product. Every added point creates some additional costs. However, the value of the model may be compromised if insufficient points are taken because it may not be possible to return to site at a later date. Even if it is possible to return to the site, capturing additional points at a later date represents a much greater cost than during the original survey.

__Preliminary Modelling__

Preliminary modelling of portions of the object may be undertaken to test whether appropriate levels of precision are being achieved. Similar tests may also be undertaken to check whether data are being gathered at an appropriate density, e.g. checking the digital terrain model (DTM).

### 2.2.2 Hand-measurement Surveys

Where moderate levels of precision are required, or on surveys of relatively small objects, traditional hand-measuring techniques may be appropriate. Steel tapes provide excellent precision and accuracy for short dimensions, longer dimensions inevitably introduce error from sagging tapes. Difficulties may also be experienced in measuring along oblique or curved surfaces, or along vertical lines, and so on. Determining longer dimensions by combining shorter ones creates different problems, since errors multiply.

All data-points in a three-dimensional model, of course, must have an elevation but triangulation becomes especially difficult when three-dimensional points are required. It is probably best to measure points in two steps, one to locate the position in plan view only, and another to determine elevation.

With hand-measuring processes, both note-taking to document the process and data gathering requires careful attention. If a three-dimensional model is to be produced more data points are required and these must be fully specified in all three coordinates. Line levels and plumb bobs will be needed to check the orientation on horizontal or vertical planes and, with inclined surfaces, measurements of the inclination are needed. Users should be certain that the geometry of the subject is fully specified; recording for three-dimensional modelling is much more demanding than recording for plans and elevations. It is easy to have a large number of data points with one or two crucial dimensions missing.

### 2.2.3 Total Station Surveys

A total station is an electronic theodolite with an electronic distance measuring device (EDM) and usually incorporates a data recorder or data logger. The advantage of these sophisticated surveying instruments lies in the precision that they produce for both long and short measurements. Other advantages of using a total station includes the speed of recording and digital data logging which combine to allow many more data points to be gathered at once in comparison with hand-measurement techniques.

The electronic theodolite displays swing angles (deviation from North) and the angle above or below the horizontal. The EDM sends an infrared beam to a reflector that must be positioned at the point to be surveyed and uses timing algorithms to determine the distance to the reflector. The data recorder records the position of the instrument, the swing angle, the elevation angle, and the distance to the target for each measurement. In addition, the data collector (and often the total station itself) can use simple trigonometric formulae to compute the position of a point surveyed from the known position of the total station and the horizontal and vertical angle and distance, generating a three-dimensional coordinate for the surveyed point.

Some total stations are now able to measure distance without a reflector, although they cannot necessarily make a reading from any surface (as the surface must reflect a significant portion of the light striking it). Therefore, even surveys using this sort of total station will occasionally need a reflector. Some problems are associated with using reflectors; for example, assistants are needed to hold the reflector and data points must be within reach [@eiteljorg1994using; -@eiteljorg1995new; -@eiteljorg1996new; -@eiteljorg1996pompeii].

Total stations operate at various levels of precision. Some measure angles to the nearest five seconds, others to the nearest second. Some measure distances to the nearest 2 or 3 millimetres, others to the nearest millimetre with an additional potential error factor related to the size of the measurement. Selecting the correct machine is a matter of matching the expected working distance and conditions, the precision required, the machine capabilities, and price.

The potential error due to angular mis-measurement is very small when compared to the error that may occur in the distance measurement (see [Appendix 1](appendix1)).

__Transferring Data Collected from a Total Station to CAD__

Data may be collected using a total station and transferred to CAD in two principal ways:

* __transferring data from the data logger incorporated into a total station into CAD software__. The points will be surveyed, and the coordinates transferred from the data logger to a computer and from there into a CAD model. The data consists simply of a group of numbered and annotated point coordinates and the operators connect the points to make a useful CAD model. Sketches are made on site just as they would be in a hand survey. Surveyed points must be noted so that the operators of the CAD system will know how to translate isolated data points into the surfaces, lines, arcs, and so on that are the CAD model
* __working with a total station connected directly to a computer rather than a data logger__. The computer may serve just as a data collector, in which case the system does not differ appreciably from a simple total system. However, the total station data may go directly into a CAD program in which case a CAD model can be generated interactively on screen during survey. With this type of system there is little requirement to make sketches on site during the survey.

When integrating data themes which are derived from survey data, the following should be recorded:

* The source (paper/digital map, GPS, data from mapping agency) and estimated error of survey base station coordinates
* Details of the survey, including date, time and purpose
* Details of the thematic organisation of the survey
* Make and model of instrument used
* Type of survey
* Estimated error terms for the coordinate pairs and (if appropriate) the z-coordinate
* Georeferencing information, overall accuracy of the survey data.

Full details of what to record when collecting survey data are described in [Section 4.4](documentingdatafromcadprojects#id-4-4-documenting-field-data-capture).

When transferring data from a total station or GPS the data points, two-dimensional drawing information and wire-frame lines will be brought into the CAD model. Building the model from the data points involves the following steps:

* The points are brought into the model, in their own layer(s), with numbers or other unique identifiers
* The points are used to define points in model entities, lines, surfaces, etc.
* Both the original data points and model entities exist in the model
* The data points are no longer useful to the model and may be removed but should be archived for later re-use and accuracy checks. There are a number of options available:
    * The points can be kept in a frozen and hidden layer
    * The points can be brought into a parallel model, using the same grid system and explicitly related to the principal model, and kept there
    * The original transfer files created from the total station may be archived after discussion with an appropriate repository.

### 2.2.4 Global Positioning System Receivers

The Global Positioning System (GPS) is a worldwide navigation system based on the Navstar satellite constellation, which is designed and run by the US Dept of Defense. GPS is used for a wide range of applications including navigation, time coordination and surveying. A key concept in achieving accurate positions with GPS is that of differential positioning. If data collected at a fixed GPS receiver with a known position is used in conjunction with data collected simultaneously by a second, mobile, unit the accuracy of the positions recorded by the second unit can be considerably enhanced. This technique is applied over a range of equipment through the use of geostationary satellites, beacons, Ordnance Survey (OS) Active Stations or users' own base stations. Real-time GPS uses the constantly transmitted data to correct the position reported at the mobile receiver instantaneously, while post-processing systems collect data over a period of time from reference stations and moving units and then process it later.

GPS equipment falls into three broad bands:
* single units for navigation, without recourse to transmitted correction data, produce positions accurate to approximately ten metres
* code only units, usually characterised as GIS collection, or mapping grade, produce positions to better than one metre using broadcast beacon data
* surveying grade equipment uses a range of techniques to fix positions to within one centimetre and is used for large survey control schemes and geodetic measurement.

GPS derived positions are in latitude, longitude and height within the World Geodetic System (WGS84), or equivalent local geodetic systems such as the European Terrestrial Reference System 1989 (ETRS89). In order to use surveys on base mapping, the survey data must be transformed to the local mapping grid e.g. for the UK the OS National Grid (OSGB36). Transformation to the National Grid can be done most accurately using the Precise National Transformation, which is accurate to 0.2m anywhere in the UK. This is available free on their website, or as a computer program and is incorporated in the latest versions of GPS survey resolution software.

Surveying using differential, dual frequency, real-time GPS equipment is typically carried out using a fixed base station composed of a GPS receiver with antenna and radio mounted on a tripod, or a vehicle such as a Land Rover and a rover unit carried by the surveyor in a back-pack or mounted on a pole. Available surveying techniques include the following:
* Surveying fixed points, high levels of accuracy (<5mm) can be obtained by longer occupation
* In kinematic mode the receiver can be set to fix points at a pre-set time or distance interval;
* Set in kinematic mode and either carried by the surveyor, or mounted on a moving vehicle, GPS equipment can be used to collect large numbers of three-dimensional points for landscape or terrain modelling. Such data can then be used for site interpretation or reconstruction, or for use in engineering design or for measuring erosion for conservation purposes
* Feature code libraries can be loaded into GPS data collectors, so that surveyed points can be tagged with appropriate codes. These codes can then be interpreted by survey resolution software and lines drawn between points on appropriate drawing layers and of predetermined colour and line-type. 

The [Ordnance Survey National GPS Network website](https://www.ordnancesurvey.co.uk/geodesy-positioning/os-net) offers data from the Active Station network for post-processing with the surveyor's own dual-frequency GPS observations. This allows a surveyor with a single survey grade GPS receiver (base and rover) to determine GPS latitude and longitude at any point in Great Britain and replaces the need to visit at least three trig points to get a good transition from WGS84 to OSGB coordinates.

### 2.2.5 Direct Object Scanning

It is technically possible to scan large objects and structures, just as it is possible to scan drawings (see [Section 2.3](capturingdataforcadprojects#id-2-3-digitisation-retrospective-conversion-to-cad-from-maps-plans-and-drawings)). Many kinds of equipment, including mechanical, magnetic, and optical devices are available for this process but these tend to be expensive.

Devices that are suitable for scanning large objects are heavily automated and they often make the resulting models much more complex than necessary. This is because excess data points are collected, as the points surveyed depend upon a pre-defined grid rather than on logical choices of required points made by a surveyor. Software is used to reduce (decimate) the number of data points by removing those that are not required - for example, points that are not at the edge of a large, flat surface.

It is very difficult to separate the data points collected by automated scanning processes into CAD layers. This is particularly true where large numbers of data points have been collected and they are not tied to specified points in the real world.

### 2.2.6 Using Photographs

The easiest data to obtain from photographs are details from flat surfaces, e.g., the pattern of a mosaic floor or the cracks on a wall. A single photograph can be placed on a digitiser and traced, just as if it were a drawing (see [Section 2.3](capturingdataforcadprojects#id-2-3-digitisation-retrospective-conversion-to-cad-from-maps-plans-and-drawings)).

Unlike GIS software, CAD software does not include tools to rectify and georeference the raster images produced if the photographs themselves are scanned. For a detailed bibliography and for a full discussion of the issues and techniques involved, including scanning and rectifying aerial photographs, please refer to the [GIS Guide to Good Practice](https://doi.org/10.5284/vk98-3372).

__Photo Rectification__

If photographs are taken at an oblique angle to the surface then photo-rectification software can be used to perform a mathematical process called a plane transformation.

Although CAD software cannot be used to rectify a scanned photograph, some CAD packages in combination with a digitising tablet can be used to trace and rectify details from a photograph in one step. However, the resulting trace will be a two-dimensional plan and assumes that the underlying surface represented in the photograph is flat, an assumption that may not be appropriate or reasonable in all circumstances. For example, an aerial photograph or elevation photograph may be placed on the digitising tablet, which is calibrated using at least six or more well-separated known two-dimensional coordinate points. As details are then traced from the photograph, they are automatically transformed into the underlying coordinate system. This provides a limited degree of 'rubber-sheeting' for oblique photographs. A series of statistics indicating the amount and location of error will typically be provided by the software and should be recorded as an indicator of the overall accuracy of the rectification.

__Photogrammetry__

Photogrammetry is a technique for producing scaled drawings or models from photographs. It requires, as a minimum, photographs in pairs with a known distance between the two camera positions and very sophisticated equipment. Newer methods, often called close-range photogrammetry or desktop photogrammetry, use three or more photographs and various computer algorithms to locate positions of common points, i.e. points that can be identified in multiple photographs. More information is available from the [Close-range Photogrammetry Guide](https://doi.org/10.5284/wngr-en16)

When incorporating photographs into CAD models the following information should be recorded:

* full photographic details
* details of the rectification method(s) used
* the software employed including, where possible, specific parameters chosen
* details regarding control points used in georeferencing.



## 2.3 Digitisation: Retrospective Conversion to CAD from Maps, Plans and Drawings

Maps, plans and elevation drawings are the most widely available and commonly used sources which are retrospectively converted to CAD. There are four methods of entering data into a CAD system from these sources:

* measurement
* digitising
* 'heads-up' digitising
* semi-automatic tracing.

The process of importing information from maps, plans or drawings will have implications both for data precision and accuracy, and it is important to be aware of a number of issues. The first of these concerns the source material itself. While maps, plans and drawings that originate on special plastic films, such as mylar, are reasonably stable, paper can stretch and distort over time. In addition, where the item is a copy rather than an original a number of distortions may result from the copying process used. In general, the following information should always be recorded:

* Publisher and copyright owner, which will often (but not always) be the same. For Ordnance Survey mapping, the copyright holder is the Crown
* The medium
* Scale of the original source, given as a ratio, and the original scale (where the source map is an enlargement or generalisation from another source)
* Name of the original source, e.g. map and the map series (where appropriate)
* Claimed accuracy for any specific components: map makers will often provide an estimated precision for contour lines or other sub-components of a map
* All details of the map projection and coordinate system employed. This information is usually printed on the mapsheet or else should be sought from the map source.

Whichever technique is selected, it may be necessary to experiment with the original data sources to determine the levels of accuracy, precision and reliability that can be obtained by comparing dimensions on the original source with those in the CAD model (see [Appendix 1](appendix1)).

### 2.3.1 Measurement

The information from the maps, plans or drawings can be used to provide the dimensions and locations of geometric shapes. Coordinate points are derived from the source and manually entered into the CAD package. The process is the same as making a model from a standard hand-measured survey. Assuming that all measurements are present, a full three-dimensional model can be created.

### 2.3.2 Digitising

Plans may be traced directly into a CAD package as vector data using a digitiser (also know as a digitising or graphics tablet). A digitiser is an electronic drafting board that is used instead of a mouse to provide data input to a computer. Large digitisers are available so that even drawings of considerable size can be traced easily. Drawings of any size can be traced and properly orientated, working on a portion of the whole at a time, even on small digitising tablets. However, larger tablets save time when dealing with large drawings. Scale, position, and orientation are established before tracing, and the user has complete control over the tracing process.

Digitising tablets generally offer finite resolution in both x and y directions. This can be expressed as a quoted resolution, for example 0.02 inches or 0.001 inches, or as lines per inch (lpi), e.g. 200 lpi or 1000 lpi. This information can be found within the digitiser manual. Unlike the scanning process, where a scanned map generates a single raster image, digitising a single paper plan may form the basis of a large number of discrete, thematic vector data layers.

When digitising, the following additional information should be recorded. As with the scanning process this may involve careful checking of hardware and software documentation, for example to determine the resolution of the digitiser.

* Detail of the digitising device used, such as the make and model, software driver and version
* The precision, usually specified as a quoted resolution or as lpi
* Details of any automatic vector processing applied to the theme (such as snap-to-nearest-node)
* Details of control points used to manage conversion from digitiser to real-world planar coordinate systems
* Errors incurred in the above transformation process (e.g. quoted RMS).

It is possible to use plans and elevations together to create three-dimensional effects and, with some patience, three-dimensional models. If a plan view is traced, for instance, the elevation can also be traced, starting on the proper points on the plan but placed on a vertical plane. Of course, adjustments will be necessary to accommodate the deviations from simple, planar drawings, but such adjustments are possible in some, if not all, cases.

### 2.3.3 Heads-up Digitising: A Scanning-digitising Hybrid

Another option is to create a scanned image of the source document and import it into CAD software for on-screen - or 'heads-up' - digitising. The CAD software used for this purpose must be capable of both importing and manipulating a scanned raster image.

__Scanning__

Maps, plans and drawings can be scanned, with a flatbed or drum scanner, to generate two-dimensional raster images. Scanning devices vary considerably in accuracy and resolution, with flatbed and drum scanners normally providing a resolution between 100 and 1200 dots per inch (dpi). The more expensive drum scanners claim resolutions of between 3-5000 dpi. In all cases care should be taken to distinguish between the true optical resolution of a given scanner and that obtained through interpolation procedures. If scanned, then there is likely to be a single raster file data product.

There is a very wide variety of image formats for holding raster data (see the guide on [Raster Images](https://doi.org/10.5284/mtgj-7130)), the majority of which are designed for photographic images and not spatially referenced data. It should be noted that the scanning process can result in some very large raster images.

For products that have been generated by scanning paper originals, the following additional information to the core mapsheet data should be recorded for each raster file generated. It should be noted that to retrieve some of this information will involve careful checking of the respective hardware and software documentation:

* Details of the scanning device used, such as the make and model, software driver and version
* Parameters chosen in the scanning process, such as the resolution setting of the device, the number of bits per pixel used
* Details of any pre-processing undertaken on the source mapsheet. This may include a range of options provided by the specific scanning software used
* Details of any post-processing undertaken on the data, such as noise reduction or sharpening with convolution filters, histogram equalisation, contrast adjustment.

__Heads-up Digitising__

Once the image has been imported in to the CAD software it is scaled to the correct dimensions and moved to the correct orientation and effectively it is registered in space. The image can then be used as the basis for 'heads-up' or 'on screen digitising'. This involves using the mouse pointer to trace around the elements of the image that are to be digitised. Coordinates are recorded as the mouse moves in much the same way as when moving the puck on a digitising table or tablet. A vector data layer is created and, once this is complete, the raster original is generally deleted from the CAD model.

The advantages of heads-up digitising include:

* The technique can be used when no digitising tablet is available
* Once the raster image has been orientated correctly in CAD it can be digitised in several sessions without the need for re-registration or checking the calibration of a digitising tablet. The ability to work in shorter sessions minimises errors that may result from fatigue, etc.
* As the image is displayed on the computer screen it is easy to zoom in to clarify complex areas. The limit to which an image can be enlarged is the point at which the lines in the image become jagged because the individual pixels have become visible as squares or rectangles.

A typical desktop scanner scans at 300 pixels per inch and at this resolution each pixel represents approximately a 0.085mm square of the original image. Scanning at higher resolutions retains more detail in the image. It can be useful to scan at a slightly higher resolution than you intend to digitise because the image remains clear when you zoom into complex areas. However, as a general rule, images should be digitised at approximately the scale at which the vector data will be used. This is because although the vector data can be rendered at different scales, a fixed number of data points exist and if the scale is increased too far lines may become jagged. If the data are used at a much reduced scale, an unnecessary number of data points will have been recorded resulting in a large file size.

The disadvantages of heads-up digitising include:

* Large format scanners are needed to scan large originals and these may be difficult to obtain
* CAD software may not be able to correct all of the distortions in the original source material unless this is a two-dimensional drawing with all dimensions in the same horizontal or vertical plane.

### 2.3.4 Semi-automatic Tracing

Raster images can also be made into vector data by using one of a number of software products. These include very sophisticated, semi-automatic, tracing tools which can vectorise 70-80% of the data for an ideal image without intervention. Such tools request intervention by a user when a problem, such as crossed lines, cannot be resolved automatically. They can manipulate the output from high (over 3000 pixels per inch) resolution drum scanners, as well as from desktop flatbed scanners. These programs are expensive, although they are sometimes available at discounted rates to non-profit research or educational institutions. Although there are also a number of cheap/shareware tools available for use on a PC, these have limitations in terms of the maximum scan resolution they can handle, or the size or complexity of the image.

Semi-automatic tracing programs create very large files owing to the number of separate line segments that are created. None of these programs can convert 100% of a scanned map or plan into vector data without human intervention. The amount of intervention that is required depends on the sophistication of the program, the quality of the scan and the complexity of the image. Without human intervention automatic tracing programs have limited usefulness as they become confused, e.g. by lines that cross one another. Nevertheless, cleaning and correcting an auto-trace may represent a considerable time saving over digitising a map or plan from scratch.

## 2.4 Conclusions

Producing a CAD model will generally involve more than one method of data gathering. For example, total stations do not work well at very close range and they are cumbersome to use for small details. GPS is excellent for landscape survey but works less well for the details of standing architecture. Photogrammetry is difficult and expensive but excellent for details seen well in photographs. Tapes and traditional hand-measuring systems are slow but useful in areas that are inaccessible to total stations. Digitising existing plans, drawings or photographs allow existing data to be utilised. Each system has its drawbacks and each has its strengths.

When planning a data-gathering exercise a number of issues should be taken into account:

* Equipment, procedures and personnel should be kept under review to monitor the levels of precision and accuracy that are being achieved
* Where possible, modelling should proceed in tandem with survey work to ensure that data are being collected at the appropriate precision and density for the task
* An appropriate CAD layer-naming convention should be selected and followed (see [Section 4.3](documentingdatafromcadprojects#id-4-3-documenting-cad-conventions))
* All factors affecting the collection of data should be fully and accurately documented (see [Section 5](archivingcaddata)). Potential users must be able to examine such documentation if they are to understand the quality of the data.
