![PointCloudWorkshop-Oct2019](png/pozo_color_sca_label.png)

# <center>From point clouds and full-waveform data to DEM analysis (Sep-30 to Oct-4 2019) </center>
#### <center>Point-cloud workshop at the University of Potsdam</center>

Support from
- [StRATEGy](http://www.irtg-strategy.de/index/) graduate school
- [University of Potsdam](https://up-rs-esp.github.io/)
- the [US-National Science Foundation EarthCube RCN "Connecting the Earth Science and Cyberinfrastructure communities to advance the analysis of high resolution topography data"](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1642611&HistoricalAwards=false)
- [OpenTopography](https://opentopography.org/)
- [UP Transfer](https://www.up-transfer.de/)

## Description
In the past few years, the density and quality of point cloud data from lidar and photogrammetry has massively increased. This has enabled important new understanding in earth surface process science, but also has challenged our analytical tools and computational workflows. The generation of high resolution Digital Elevation Models, flow routing on point clouds, and surface roughness estimation has become more accessible and provides important measures of topography at the fine scale at which the processes operate.  This workshop presents approaches to analyzing point cloud data and producing useful derived products. It also explores future applications in earth surface processes.

The workshop will progress from point cloud analysis to appropriate filtering and gridding and then geomorphic analysis on grids and point clouds. In addition, we will spend one day on explorations of full waveform analyses for a variety of applications as these data are progressively becoming more available and useful for bathymetric, vegetation, surface roughness measurements, and material property mapping.

This course is intended for graduate students and researchers with interests in surface processes and with experience in programming (Python and Matlab).

[Workshop Flyer](https://github.com/UP-RS-ESP/PointCloudWorkshop-Oct2019/raw/master/flyer_2019_webpage.pdf)

## Organization Committee and Instructors
[Bodo Bookhagen](https://bodobookhagen.github.io/), [Ramon Arrowsmith](https://www.public.asu.edu/~arrows/), [Chris Crosby](https://connect.unavco.org/display/per508132), [Taylor Smith](tasmith@uni-potsdam.de), [Fiona Clubb](https://fclubb.github.io/), [Aljoscha Rheinwalt](https://github.com/Rheinwalt)

## Website and Documents
We will use this github website to share code and manuals and will continue to update and fill in (also during the workshop).
A list of relevant [documents and PDFs](https://github.com/UP-RS-ESP/PointCloudWorkshop-Oct2019/tree/master/PDF) are available.

## Participation will be by application (we are limited to 20 participants)
Workshop fees are 100 Euro. This includes snacks, coffee, beverages, lunch, and one workshop dinner on Monday. Thanks to support from the NSF EarthCube A^2HRT RCN, we will provide travel support for up to five early career participants from the US.

You can apply for the workshop [online](http://tiny.cc/ivg89y) and the application deadline is *August 16, 2019*. **We will inform selected participants and expect payment of the workshop fees until *August 23, 2019*. If no payment is received by then, we will offer the slot to another candidate.**

## Accomodation and Hotels
The workshop venue is the [Campus Golm](https://www.google.com/search?tbm=lcl&ei=wI85XYfFE4rRwAKr2DE&q=Karl-Liebknecht-Stra%C3%9Fe+24-25%2C+14476+Potsdam&oq=Karl-Liebknecht-Stra%C3%9Fe+24-25%2C+14476+Potsdam&gs_l=psy-ab.3..38l3.131238.133490.0.134023.2.2.0.0.0.0.87.166.2.2.0....0...1c.1.64.psy-ab..0.1.86....0.n0oBY4Efq_Q#rlfi=hd:;si:11329416506967667491;mv:!1m2!1d52.40871997731902!2d12.974945031694851!2m2!1d52.40836002268096!2d12.974354968305148!3m12!1m3!1d339.6918546312415!2d12.974649999999999!3d52.408539999999995!2m3!1f0!2f0!3f0!3m2!1i1865!2i1715!4f13.1) at the [University of Potsdam](https://www.uni-potsdam.de/en/index.html). See also the more detailed [campus plan](https://www.uni-potsdam.de/db/zeik-portal/gm/lageplan-up.php?komplex=2).

There is a list of hotels and accomodation in [Potsdam](LINK) and [Berlin](LINK). Public transport in Potsdam takes ~10 to 15 minutes to the Campus Golm, commuting via bike is also possible. Public transport takes you from Berlin downtown to the campus in 30 minutes.

# Tentative Program
**Monday, Sept 30, 2019**
- OpenTopography introduction and production implementations
  - Point cloud selection and review of basic processing workflows
  - DEM processing using neighborhood and triangulation methods to produce DSM and DTMs
  - DEM processing for flow routing using TauDEM HPC

- Desktop based (Python driven) computational workflows (I)
  - point cloud classification and filtering
  - interpolation to grids using the most appropriate methods (from triangulation to IDW and fitting green's functions and splines and other surfaces)
  - Airborne lidar to photogrammetric SFM warping example

*Evening student presentations*


**Tuesday, October 1, 2019**
- Desktop based (Python driven) computational workflows (II)
  - Flow routing on point clouds using TINs
  - Channel Head identification using point clouds with various densities
  - Other topics depending on time and participant's interests

*Evening student presentations*


**Wednesday, October 2, 2019**
- Determining optimal DEM resolutions from point pointclouds
- using point cloud data to measure surface roughness for geomorphic classification


**Thursday, October 3, 2019**
- Full waveform lidar explanation and exploration with specific applications for geomorphology
   - micro-surface roughness
   - better characterization of ground (and other) surfaces
   - material-surface characteristics
   - water-column characteristics
   - biomass estimation


**Friday, October 4, 2019**
- Topographic analysis with [LSD TopoTools](https://lsdtopotools.github.io/)
  - Introduction
  - River-profile clustering
  - Ridge-top curvature
  - Making appealing maps with GMT

***Evening student*** **presentations**
We will have short presentations by participants on Monday and Tuesday early evenings. You are STRONGLY encouraged to make one of these short (<5 minutes/<5 slides) presentations. We will have a computer and projector there and will collect the presentations in advance for quick transitions. Given the big group, we will be strict on timing, but we do look forward to hearing about your work, your ideas, or even questions. This will be very informal!
