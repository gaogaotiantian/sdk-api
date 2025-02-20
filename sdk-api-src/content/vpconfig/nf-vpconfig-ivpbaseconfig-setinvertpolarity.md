---
UID: NF:vpconfig.IVPBaseConfig.SetInvertPolarity
title: IVPBaseConfig::SetInvertPolarity (vpconfig.h)
description: The SetInvertPolarity method reverses the current polarity the device uses.
helpviewer_keywords: ["IVPBaseConfig interface [DirectShow]","SetInvertPolarity method","IVPBaseConfig.SetInvertPolarity","IVPBaseConfig::SetInvertPolarity","IVPBaseConfigSetInvertPolarity","SetInvertPolarity","SetInvertPolarity method [DirectShow]","SetInvertPolarity method [DirectShow]","IVPBaseConfig interface","dshow.ivpbaseconfig_setinvertpolarity","vpconfig/IVPBaseConfig::SetInvertPolarity"]
old-location: dshow\ivpbaseconfig_setinvertpolarity.htm
tech.root: dshow
ms.assetid: 2c33cea2-2c83-4978-9059-c15706f14f85
ms.date: 4/26/2023
ms.keywords: IVPBaseConfig interface [DirectShow],SetInvertPolarity method, IVPBaseConfig.SetInvertPolarity, IVPBaseConfig::SetInvertPolarity, IVPBaseConfigSetInvertPolarity, SetInvertPolarity, SetInvertPolarity method [DirectShow], SetInvertPolarity method [DirectShow],IVPBaseConfig interface, dshow.ivpbaseconfig_setinvertpolarity, vpconfig/IVPBaseConfig::SetInvertPolarity
req.header: vpconfig.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IVPBaseConfig::SetInvertPolarity
 - vpconfig/IVPBaseConfig::SetInvertPolarity
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Vpconfig.h
api_name:
 - IVPBaseConfig.SetInvertPolarity
---

# IVPBaseConfig::SetInvertPolarity


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>SetInvertPolarity</code> method reverses the current polarity the device uses.



## -returns

Returns an <b>HRESULT</b> value.

## -remarks

Reversing polarity means asking the decoder or capture device to treat even fields as odd fields and vice versa.

Include Dvp.h and Vptype.h before Vpconfig.h.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/vpconfig/nn-vpconfig-ivpbaseconfig">IVPBaseConfig Interface</a>
