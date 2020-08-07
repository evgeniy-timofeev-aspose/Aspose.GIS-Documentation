---
title: "Aspose.GIS for .NET 18.10 Release Notes"
type: docs
url: /net/aspose-gis-for-net-18-10-release-notes/
weight: 50
---

{{% alert color="primary" %}} 

This page contains release notes information for Aspose.GIS for .NET 18.10.

{{% /alert %}} 
## **Major Features**
Major features and improvements in this release:

- [Reading OBJECTID from FIleGDB Layers](/gis/net/working-with-layers/#workingwithlayers-readobjectidfromfilegdbdatasetlayer)
- [](/gis/net/working-with-geometries/#workingwithgeometries-getdistancebetweengeometries)[Computing distance between Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getdistancebetweengeometries)
- [Computing areas and lengths of Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getareaofgeometry)
- [Computing convex hull of Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getconvexhullofgeometry)
- [Computing centroid of Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getcentroid)
- [Building a buffer of Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getgeometrybuffer) 

Fixes:

- Shape writing into FileGDB.
- Compute Union
## **Full List of Issues Covering all Changes in this Release**

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|GISNET-210|[Geometry Buffer Operation](/gis/net/working-with-geometries/#workingwithgeometries-getgeometrybuffer)|New Feature|
|GISNET-213|[Compute Distance between Geometries](/gis/net/working-with-geometries/#workingwithgeometries-getdistancebetweengeometries)|New Feature|
|GISNET-214|[Geometry Convex Hull Operation](/gis/net/working-with-geometries/#workingwithgeometries-getconvexhullofgeometry)|New Feature|
|GISNET-215|[Geometry Area and Length Operations](/gis/net/working-with-geometries/#workingwithgeometries-getareaofgeometry)|New Feature|
|GISNET-216|[Geometry Centroid Operation](/gis/net/working-with-geometries/#workingwithgeometries-getcentroid)|New Feature|
|GISNET-217|[A point on Surface Operation](/gis/net/working-with-geometries/#workingwithgeometries-getpointonsurface)|New Feature|
|GISNET-218|[Covers and CoveredBy operations](/gis/net/working-with-geometries/#workingwithgeometries-determineifonegeometrycoversanother)|New Feature|
|GISNET-221|[Read OBJECTID from FileGDB layers](/gis/net/working-with-layers/#workingwithlayers-readobjectidfromfilegdbdatasetlayer)|Improvement|
|GISNET-222|Unable to Compute Union|Bug|
|GISNET-226|Shape distortion in GDB|Bug|
## **Public API and Backward Incompatible Changes**
New methods in IGeometry interface (and overloads in Geometry class):

IGeometry.GetBuffer

IGeometry.GetDistanceTo(IGeometry)

IGeometry.GetConvexHull()

IGeometry.GetLength()

IGeometry.GetArea()

IGeometry.GetCentroid()

ISurface.GetPointOnSurface()

IGeometry.Covers(IGeometry)

IGeometry.CoveredBy(IGeometry)


