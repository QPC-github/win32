---
description: The put\_Similarity method specifies the range of color data that becomes transparent. At higher values, a wider range of similar colors is transparent. This property applies only when the key type is DXTKEY\_RGB or DXTKEY\_NONRED.
ms.assetid: f033b226-f36d-4288-b17e-e173546caee1
title: IDxtKey::put_Similarity method (Qedit.h)
ms.topic: reference
ms.date: 4/26/2023
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtKey.put_Similarity
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
ms.custom: UpdateFrequency5
---

# IDxtKey::put\_Similarity method

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `put_Similarity` method specifies the range of color data that becomes transparent. At higher values, a wider range of similar colors is transparent. This property applies only when the key type is DXTKEY\_RGB or DXTKEY\_NONRED.

## Syntax


```C++
HRESULT put_Similarity(
  [in] int newVal
);
```



## Parameters

<dl> <dt>

*newVal* \[in\]
</dt> <dd>

Specifies the similarity value. The valid range is from 0 to 100.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://msdn.microsoft.com/windowsvista/bb980924.aspx). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



| Requirement | Value |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IDxtKey Interface**](idxtkey.md)
</dt> <dt>

[**IDxtKey::put\_KeyType**](idxtkey-put-keytype.md)
</dt> </dl>

 

 




