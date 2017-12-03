---
title: "IMetaDataEmit::SetModuleProps 메서드"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: IMetaDataEmit.SetModuleProps
api_location: mscoree.dll
api_type: COM
f1_keywords: IMetaDataEmit::SetModuleProps
helpviewer_keywords:
- SetModuleProps method [.NET Framework metadata]
- IMetaDataEmit::SetModuleProps method [.NET Framework metadata]
ms.assetid: b74d7629-5f46-458f-8d67-2456a1e7030c
topic_type: apiref
caps.latest.revision: "11"
author: mairaw
ms.author: mairaw
manager: wpickett
ms.openlocfilehash: 0653f0407486e09ab51ef05e74218207268b6e8c
ms.sourcegitcommit: 4f3fef493080a43e70e951223894768d36ce430a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/21/2017
---
# <a name="imetadataemitsetmoduleprops-method"></a><span data-ttu-id="69515-102">IMetaDataEmit::SetModuleProps 메서드</span><span class="sxs-lookup"><span data-stu-id="69515-102">IMetaDataEmit::SetModuleProps Method</span></span>
<span data-ttu-id="69515-103">이전 호출에서 정의 된 모듈에 대 한 참조를 업데이트 [imetadataemit:: Definemoduleref](../../../../docs/framework/unmanaged-api/metadata/imetadataemit-definemoduleref-method.md)합니다.</span><span class="sxs-lookup"><span data-stu-id="69515-103">Updates references to a module defined by a prior call to [IMetaDataEmit::DefineModuleRef](../../../../docs/framework/unmanaged-api/metadata/imetadataemit-definemoduleref-method.md).</span></span>  
  
## <a name="syntax"></a><span data-ttu-id="69515-104">구문</span><span class="sxs-lookup"><span data-stu-id="69515-104">Syntax</span></span>  
  
```  
HRESULT SetModuleProps (   
    [in]  LPCWSTR     szName  
);  
```  
  
#### <a name="parameters"></a><span data-ttu-id="69515-105">매개 변수</span><span class="sxs-lookup"><span data-stu-id="69515-105">Parameters</span></span>  
 `szName`  
 <span data-ttu-id="69515-106">[in] 유니코드의 모듈 이름입니다.</span><span class="sxs-lookup"><span data-stu-id="69515-106">[in] The module name in Unicode.</span></span> <span data-ttu-id="69515-107">파일 이름만 전체 경로 이름이 아닌입니다.</span><span class="sxs-lookup"><span data-stu-id="69515-107">This is the file name only and not the full path name.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="69515-108">요구 사항</span><span class="sxs-lookup"><span data-stu-id="69515-108">Requirements</span></span>  
 <span data-ttu-id="69515-109">**플랫폼:** 참조 [시스템 요구 사항](../../../../docs/framework/get-started/system-requirements.md)합니다.</span><span class="sxs-lookup"><span data-stu-id="69515-109">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
  
 <span data-ttu-id="69515-110">**헤더:** Cor.h</span><span class="sxs-lookup"><span data-stu-id="69515-110">**Header:** Cor.h</span></span>  
  
 <span data-ttu-id="69515-111">**라이브러리:** MSCorEE.dll에서 리소스로 사용</span><span class="sxs-lookup"><span data-stu-id="69515-111">**Library:** Used as a resource in MSCorEE.dll</span></span>  
  
 <span data-ttu-id="69515-112">**.NET framework 버전:**[!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span><span class="sxs-lookup"><span data-stu-id="69515-112">**.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="69515-113">참고 항목</span><span class="sxs-lookup"><span data-stu-id="69515-113">See Also</span></span>  
 [<span data-ttu-id="69515-114">IMetaDataEmit 인터페이스</span><span class="sxs-lookup"><span data-stu-id="69515-114">IMetaDataEmit Interface</span></span>](../../../../docs/framework/unmanaged-api/metadata/imetadataemit-interface.md)  
 [<span data-ttu-id="69515-115">IMetaDataEmit2 인터페이스</span><span class="sxs-lookup"><span data-stu-id="69515-115">IMetaDataEmit2 Interface</span></span>](../../../../docs/framework/unmanaged-api/metadata/imetadataemit2-interface.md)