---
authors:
  - name: Jeremy Huggett
    orcid: https://orcid.org/0000-0002-7535-9312
---

# Case Study 6: Symon's Castle Documentation

Symon's Castle is a 13th century AD timber and earthwork castle situated on the Welsh borders (see also [Case Study 1](casestudy1)). It was excavated in a series of one-month seasons from 1985 to 1994 by Dr Jeremy Huggett (University of Glasgow) and Dr Chris Arnold (then of University of Wales Aberystwyth) as a research and training excavation. The castle consists of two platforms separated by a ditch; the whole of the north-east platform (the 'bailey') was excavated, a section through the ditch, and the whole of the interior of the south-west platform (the 'motte') with sections through the stone-revetted clay bank on its perimeter.

As a result of the degraded nature of the soil, few archaeological contexts could be defined on any basis other than the relative density, distribution and nature of stone and artefacts alone. In the absence of distinct layers of soil over much of the excavated area, the removal of the deposits was carried out in a series of arbitrary spits. Individual context numbers were only assigned where layers and features were clearly defined (usually as a result of burning). Hence the recording of all non-artefactual material comprised a series of drawings on which the objective data were all stones larger than about 0.03m in their greatest dimension, with any apparent 'edges' in stones or soil highlighted. For any given area this record comprised a maximum of four drawings:
* Plan 1: the visible and normally amorphous surface following the removal of the vegetation; 
* Plan 2: the pattern revealed following the removal of topsoil;
* Plan 3: the distribution of stones lying directly on the subsoil or bedrock;
* Plan 4: any stones which appeared to have been set into the subsoil by human agency.

All artefacts, including burnt clay and charcoal fragments, were recorded in three dimensions, and the importance of this for the subsequent identification of structures that had no earth-fast timbers is demonstrated in Case Study 1.

Digitisation of the plan data was carried out as part of the post-excavation phase. In the absence of a large-format scanner (although a bureau service could have been used), all the original A1 (approx.) field plans in pencil on permatrace were scanned in overlapping sections using an A3 scanner. To create stone plans, the scans were sharpened and converted to 2-bit black and white images which were automatically traced. These traces were subsequently imported, scaled, rotated and positioned on the site grid in AutoCAD 2000, along with the original grey-scale scans. The overlaps between traces were removed and the plans cleaned manually with reference to the underlying scanned images. To create individual context plans, the extents of contexts were manually digitised from the scaled and rotated and positioned grey-scale scans. A series of interpretative three-dimensional models were constructed on the basis of the excavated evidence [see @huggett20003d]. An intra-site GIS was also constructed for analysis by importing the digitised stone and context plans, which had been saved in AutoCAD version 14 format for compatibility, into IDRISI and ArcView version 3.2.

The digital archive created by the Symon's Castle project is a research level archive and includes:

* Project reports covering the stratigraphic sequence
* CAD files
* Layer-naming convention.

__Project Documentation__

```{list-table}
:header-rows: 1

* - Project Name
  - Symon's Castle project.
* - Reference Number
  - None.
* - Project Purpose
  - Excavation of a 13th century AD timber and earthwork castle near Churchstoke, Powys. The project was directed by Dr C. Arnold and Dr J. Huggett over a 10 year period, on site for four weeks per year. The excavation was run as a training school for university students and other interested parties, and as a volunteer excavation. Although the site was largely undisturbed, the soil was very shallow and highly leached, requiring a modified recording procedure and full three-dimensional recording of artefacts.
* - Project Keywords
  - Excavation, Medieval, castle, motte and bailey, timber and earthwork.
* - Subject
  - Timber and earthwork castle, with stone-revetted clay rampart and timber palisades, timber buildings in interior.
* - Site Address
  - Symon's Castle, Churchstoke, Powys.
* - Administrative Area
  - Churchstoke, Powys
* - Country
  - Wales.
* - Spatial Coverage
  - (OSGB) SO 285 933
* - Size
  - Not reported.
* - Duration
  - 1985-1994.
* - Originator
  - Dr J. Huggett, Department of Archaeology, University of Glasgow, Dr C. Arnold.
* - Client
  - None.
* - Bibliography
  - [J. Huggett and C. Arnold (1998) Symon's Castle](https://www.gla.ac.uk/schools/humanities/research/archaeologyresearch/projectarchive/symonscastle/)<br>C. Arnold and J. Huggett (in prep), Symon's Castle, Churchstoke, Powys: Excavations 1985-1994.<br>[J. Huggett and Chen Guo-Yuan (2000) '3-D Interpretative Modelling of Archaeological Sites: A Computer Reconstruction of a Medieval Timber and Earthwork Castle' *Internet Archaeology* 8](https://intarch.ac.uk/journal/issue8/huggett_index.html)
* - Copyright
  - Dr J. Huggett and Dr C. Arnold
```

__Layer-naming Convention__

The project defined three layer-naming conventions, for the stone plans, the context plans and for three-dimensional models. Each convention is described below, with AutoCAD Colour Index (ACI) being used to define the colours used.

```{list-table}
:header-rows: 2

* - Convention:
  - Stone plans
* - Layer Name
  - Description
* - Bedrock
  - Layer content: Extent of exposed bedrock<br>Source: Project files<br>Colour: Green (AutoCAD Colour Index 100)<br>Line type: Continuous
* - Exc_edge
  - Layer content: Edge of excavation<br>Source: Project files<br>Colour: Magenta (ACI 211)<br>Line type: Continuous
* - Scan
  - Layer content: Links to original scanned images of stone plans<br>Source: Project files<br>Colour: Grey-green (ACI 54)<br>Line type: Continuous
* - aXbY
  - Layer content: Stone plan where a = area of site (m=motte, b=bailey, t=terrace, d=ditch); X = plan level (1, 2, 3 etc.), b = sheet of plan X, Y = scanned element of sheet b<br>Source: Project files<br>Colour: White (ACI 249)<br>Line type: Continuous
```

```{list-table}
:header-rows: 2

* - Convention:
  - Context plans
* - Layer name
  - Description
* - Bedrock
  - Layer content: Extent of exposed bedrock<br>Source: Project files<br>Colour: Green (ACI 100)<br>Line type: Continuous
* - Exc_edge
  - Layer content: Edge of excavation<br>Source: Project files<br>Colour: Magenta (ACI 211)<br>Line type: Continuous
* - Context X<br>(X = context number)
  - Layer content: Context extent.<br>Source: Project files<br>Colour: Red (ACI 240)<br>Line type: Continuous
```

```{list-table}
:header-rows: 2

* - Convention
  - Three dimensional models
* - Layer name
  - Description
* - Topography
  - Layer content: Surface mesh of topographic survey<br>Source: Project files<br>Colour: Green (ACI 84)<br>Line type: Continuous
* - Palisade
  - Layer content: Palisade posts<br>Source: Project files<br>Colour: Brown (ACI 14)<br>Line type: Continuous
* - Planktimber
  - Layer content: Palisade planking<br>Source: Project files<br>Colour: Yellow (ACI 50)<br>Line type: Continuous
* - Road
  - Layer content: Roadway on bailey to bridge<br>Source: Project files<br>Colour: Mustard (ACI 52)<br>Line type: Continuous
* - Bridge
  - Layer content: Bridge between motte and bailey<br>Source: Project files<br>Colour: Gold (ACI 40)<br>Line type: Continuous
```

__File-naming Convention__

Each stone plan file is named by its area and plan level - hence Motte Plan 1, Motte Plan 2, Bailey Plan 1, etc. and standard file extensions. Each individual context plan file is named using the site context number and standard file extensions, e.g. 12345.dwg.

__On-site Data Capture Documentation__

```{list-table}
:header-rows: 0

* - Project Name
  - Symon's Castle
* - Reference Number
  - None
* - Survey Type
  - Planning
* - Survey Purpose
  - Standard site planning on permatrace, employing 1m square drawing frames and hand tapes. All plans drawn to a scale of 1:20.
* - Duration
  - 1985-1994 (approx. 10 months in total)
* - Surveyor
  - Dr J. Huggett and Dr C. Arnold
* - Survey Keywords
  - Hand measurement, level
* - Instrumentation
  - Level
* - Coverage
  - Entire excavated area
* - Precision and Accuracy
  - Measurements to nearest centimetre, estimated accuracy ±5cm
* - Data Transfer Files
  - N/A
```

```{list-table}
:header-rows: 0

* - Project Name
  - Symon's Castle
* - Reference Number
  - None
* - Survey Type
  - Topographic survey
* - Survey Purpose
  - Approx. 5000 spot heights measured across area of site at 1m intervals. Grid reconstructed in local areas using tapes anchored by permanent steel pins.
* - Duration
  - 1985-1986 (approx. 2 weeks in total)
* - Surveyor
  - Dr J. Huggett and Dr C. Arnold
* - Survey Keywords
  - Hand measurement, level
* - Instrumentation
  - Level
* - Coverage
  - Entire area of earthworks
* - Precision and Accuracy
  - Measurements to nearest centimetre, estimated accuracy ±10cm
* - Data Transfer Files
  - Symondem.img - IDRISI image format, heights in centimetres at one-metre intervals, 76 columns x 72 rows, 0 is null value<br>Symon.asc - ASCII text format, heights in centimetres at one-metre intervals, 76 columns x 72 rows, 0 is null value.
```

__Off-site Data Capture Documentation__

```{list-table}
:header-rows: 0

* - Project Name
  - Symon's Castle
* - Reference Number
  - N/A
* - Source Name
  - Plans (stones)
* - Source Reference
  - None
* - Type of Source
  - Drawing
* - Source Medium
  - Permatrace
* - Publisher
  - None
* - Copyright
  - Dr J. Huggett and Dr C. Arnold
* - Scale
  - 1:20
* - Accuracy
  - ±5cm (estimated)
* - Techniques
  - Scanning
* - Equipment
  - Scanner = Umax Mirage IISE
* - Software
  - MagicScan 4.2
* - Software
  - PaintShop Pro 6.0
* - Software
  - RasterVect 5.2
* - Parameters
  - Scanner maximum resolution = 9800 dpi x 9800 dpi; scan resolution = 150 dpi;<br>filter used = sharpen
* - Post-processing
  - Outlines sharpened (Image/Sharpen/Sharpen more) if needed and converted to 2-bit black and white images (Colours/Decrease Colour Depth/2 Colours). Software used: PaintShop Pro 6.0
* - Automatic Processing
  - Auto-traced using centrelines with arc and circle recognition turned off. Software used: RasterVect 5.2
* - Control Points
  - Site grid fixed points on plans.
* - Data Precision and Accuracy
  - Tracing precision: 1.5 pixels, minimal length of line: 1 pixel. Resulting plans cleaned manually, though polylines representing the smallest stones (c. 5cm or less) were not closed.
* - Data Files
  - AutoCAD dxf/dwg, version 14
```

```{list-table}
:header-rows: 0

* - Project Name
  - Symon's Castle
* - Reference Number
  - N/A
* - Source Name
  - Plans (contexts)
* - Source Reference
  - None
* - Type of Source
  - Drawing
* - Source Medium
  - Permatrace
* - Publisher
  - None
* - Copyright
  - Dr J. Huggett and Dr C. Arnold
* - Scale
  - 1:20
* - Accuracy
  - ±5cm (estimated)
* - Techniques
  - Digitising
* - Equipment
  - Digitising tablet = A3 Summagraphics Summasketch III
* - Software
  - AutoCAD 2000
* - Parameters
  - Tablet claimed accuracy ±0.010 inches; resolution: 2540 lines per inch.
* - Post-processing
  - N/A
* - Automatic Processing
  - N/A
* - Control Points
  - Site grid fixed points on plans
* - Data Precision and Accuracy
  - Not given
* - Data files
  - AutoCAD dwg, version 14
```

__List of All Files__

```{list-table}
:header-rows: 1

* - File Name
  - Date
  - Copyright
  - Format
  - Content
* - Motte Plan 1.dwg
  - 12/08/2001
  - JWH/CJA
  - dwg version 14
  - Motte stone plan at Plan 1 stage
* - Motte Plan 2.dwg
  - 12/08/2001
  - JWH/CJA
  - dwg version 14
  - Motte stone plan at Plan 2 stage
* - ...
  - 
  - 
  - 
  - 
* - 41.dwg
  - 20/01/2002
  - JWH/CJA
  - dwg version 14
  - Extent of context 41
* - 42.dwg
  - 20/01/2002
  - JWH/CJA
  - dwg version 14
  - Extent of context 42
```

N.B. These details would be repeated for each file in the archive.

__Documenting the CAD Models__

```{list-table}
:header-rows: 0

* - Project Name
  - Symon's Castle
* - Project Reference number
  - None
* - Name of CAD Model
  - Interpretative reconstruction
* - Creator
  - Chen Guo-Yuan and J. Huggett
* - CAD Software
  - AutoCAD 14
* - Files Used
  - Sym_22.dwg (topographic surface)<br>Hall_1.dwg (version 1 of the hall)<br>Tower_2.dwg (version 2 of the tower)<br>Symlisp.lsp (AutoLISP programs for construction of timber palisades, wallwalks, roadway and bridge)
* - Layer Convention
  - 3D models layer convention with additional layers as follows:
     * Hallrftimber: Colour = brown (ACI 33); Line type = continuous (rooftimbers of hall)
     * Hallroof: Colour = gold (ACI 41); Line type = continuous (roof of hall)
     * Hallwall: Colour = red (ACI 10); Line type = continuous (walls of hall)
     * Hallwindow: Colour = maroon (ACI 242); Line type = continuous (windows/doorway of hall)
     * Towerroof: Colour = gold (ACI 41); Line type = continuous (roof of tower)
     * Towerstair: Colour = orange (ACI 30); Line type = continuous (stair within tower)
     * Towertimber: Colour = brown (ACI 42); Line type = continuous (timber framework of tower)
     * Towerwall: Colour = red/brown (ACI 12); Line type = continuous (planked walls of tower)
```

N.B. This documentation would be repeated for each model in the archive.
