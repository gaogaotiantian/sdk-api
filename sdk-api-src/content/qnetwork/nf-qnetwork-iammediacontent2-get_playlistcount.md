---
UID: NF:qnetwork.IAMMediaContent2.get_PlaylistCount
title: IAMMediaContent2::get_PlaylistCount (qnetwork.h)
description: The get_PlaylistCount method retrieves the number of entries in an ASX file.
helpviewer_keywords: ["IAMMediaContent2 interface [DirectShow]","get_PlaylistCount method","IAMMediaContent2.get_PlaylistCount","IAMMediaContent2::get_PlaylistCount","IAMMediaContent2get_PlaylistCount","dshow.iammediacontent2_get_playlistcount","get_PlaylistCount","get_PlaylistCount method [DirectShow]","get_PlaylistCount method [DirectShow]","IAMMediaContent2 interface","qnetwork/IAMMediaContent2::get_PlaylistCount"]
old-location: dshow\iammediacontent2_get_playlistcount.htm
tech.root: dshow
ms.assetid: 6f1a388e-de23-4441-bc65-33ce13519d70
ms.date: 4/26/2023
ms.keywords: IAMMediaContent2 interface [DirectShow],get_PlaylistCount method, IAMMediaContent2.get_PlaylistCount, IAMMediaContent2::get_PlaylistCount, IAMMediaContent2get_PlaylistCount, dshow.iammediacontent2_get_playlistcount, get_PlaylistCount, get_PlaylistCount method [DirectShow], get_PlaylistCount method [DirectShow],IAMMediaContent2 interface, qnetwork/IAMMediaContent2::get_PlaylistCount
req.header: qnetwork.h
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
 - IAMMediaContent2::get_PlaylistCount
 - qnetwork/IAMMediaContent2::get_PlaylistCount
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Qnetwork.h
api_name:
 - IAMMediaContent2.get_PlaylistCount
---

# IAMMediaContent2::get_PlaylistCount


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>get_PlaylistCount</code> method retrieves the number of entries in an ASX file.



This interface is not supported.

## -parameters

### -param pNumberEntries

Pointer to a variable that receives the number of entries.

## -returns

If the method succeeds, it returns S_OK. If it fails, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/qnetwork/nn-qnetwork-iammediacontent2">IAMMediaContent2 Interface</a>