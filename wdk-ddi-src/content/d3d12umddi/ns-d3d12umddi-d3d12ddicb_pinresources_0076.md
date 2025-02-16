---
UID: NS:d3d12umddi.D3D12DDICB_PIN_RESOURCES_0076
title: D3D12DDICB_PIN_RESOURCES_0076
ms.date: 03/24/2020
ms.topic: language-reference
tech.root: display
targetos: Windows
description: The D3D12DDICB_PIN_RESOURCES_0076 structure contains a list of resources to pin. This structure is a parameter of the PFND3D12DDI_PINRESOURCES_CB_0076 function.
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: d3d12umddi.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: Windows 10, version 2004
req.target-min-winversvr: 
req.target-type: 
req.typenames: D3D12DDICB_PIN_RESOURCES_0076
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3d12umddi.h
api_name:
 - D3D12DDICB_PIN_RESOURCES_0076
f1_keywords:
 - D3D12DDICB_PIN_RESOURCES_0076
 - d3d12umddi/D3D12DDICB_PIN_RESOURCES_0076
dev_langs:
 - c++
---

## -description

Argument structure for [**PFND3D12DDI_PINRESOURCES_CB_0076**](nc-d3d12umddi-pfnd3d12ddi_pinresources_cb_0076.md) that provides the list of resources to pin.

## -struct-fields

### -field NumResources

Size of the **hResources** handle array.

### -field hResources

The list of D3D12DDI_HRTRESOURCE resources to pin.

## -remarks

## -see-also

[**PFND3D12DDI_PINRESOURCES_CB_0076**](nc-d3d12umddi-pfnd3d12ddi_pinresources_cb_0076.md)

