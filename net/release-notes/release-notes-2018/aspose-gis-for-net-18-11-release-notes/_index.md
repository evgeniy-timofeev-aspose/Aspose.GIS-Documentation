---
title: "Aspose.GIS for .NET 18.11 Release Notes"
type: docs
url: /net/aspose-gis-for-net-18-11-release-notes/
weight: 40
---

{{% alert color="primary" %}} 

This page contains release notes information for Aspose.GIS for .NET 18.11.

{{% /alert %}} 
## **Major Features**
Major features and improvements in this release:

- Import from WKT and WKB
- Export to WKT and WKB
## **Full List of Issues Covering all Changes in this Release**

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|GISNET-234|Translate Geometries to/from WKT and WKB|New Feature|
## **Public API and Backward Incompatible Changes**
- static Geometry.FromText method - creates geometry from WKT
- static Geometry.FromBinary method - creates geometry from WKB
- Geometry.AsText methods - translate geometry to WKT
- Geometry.AsBinary methods - translate geometry to WKB
- Geometry.ToEditable methods - converts a read-only geometry (IGeometry or one of its inheritors) to editable geometry (Geometry or one of its inheritors)
