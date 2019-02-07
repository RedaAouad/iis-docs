---
title: IManagementService.DeleteJobTemplate Method  (Microsoft.Web.Media.TransformManager)
TOCTitle: DeleteJobTemplate Method
ms:assetid: M:Microsoft.Web.Media.TransformManager.IManagementService.DeleteJobTemplate(System.String)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.imanagementservice.deletejobtemplate(v=VS.90)
ms:contentKeyID: 35521190
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.IManagementService.DeleteJobTemplate
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.ServiceLibrary.dll
api_name:
- Microsoft.Web.Media.TransformManager.IManagementService.DeleteJobTemplate
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# DeleteJobTemplate Method

Deletes a [JobTemplate](jobtemplate-class-microsoft-web-media-transformmanager.md) object from IIS Transform Manager.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.ServiceLibrary (in Microsoft.Web.Media.TransformManager.ServiceLibrary.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Sub DeleteJobTemplate ( _
    jobTemplateId As String _
)
'Usage

  Dim instance As IManagementService
Dim jobTemplateId As String

instance.DeleteJobTemplate(jobTemplateId)
```

``` csharp
[OperationContractAttribute]
void DeleteJobTemplate(
    string jobTemplateId
)
```

``` c++
[OperationContractAttribute]
void DeleteJobTemplate(
    String^ jobTemplateId
)
```

``` fsharp
[<OperationContractAttribute>]
abstract DeleteJobTemplate : 
        jobTemplateId:string -> unit 
```

``` jscript
  function DeleteJobTemplate(
    jobTemplateId : String
)
```

#### Parameters

  - jobTemplateId  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The ID of the [JobTemplate](jobtemplate-class-microsoft-web-media-transformmanager.md) object to delete.  

## Exceptions

|Exception|Condition|
|--- |--- |
|[InvalidOperationException](https://msdn.microsoft.com/en-us/library/2asft85a(v=vs.90))|The specified job template is in use.|


## Remarks

A [JobTemplate](jobtemplate-class-microsoft-web-media-transformmanager.md) object contains a set of sequential tasks that are run during the transform process.

## See Also

#### Reference

[IManagementService Interface](imanagementservice-interface-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
