---
title: "ICorDebugModule::GetProcess 메서드"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: ICorDebugModule.GetProcess
api_location: mscordbi.dll
api_type: COM
f1_keywords: ICorDebugModule::GetProcess
helpviewer_keywords:
- GetProcess method, ICorDebugModule interface [.NET Framework debugging]
- ICorDebugModule::GetProcess method [.NET Framework debugging]
ms.assetid: 5e13446c-0271-446c-924a-9072c0e6eeae
topic_type: apiref
caps.latest.revision: "11"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.openlocfilehash: 8770a4978ba0410d6df825320446f4ea4817e04a
ms.sourcegitcommit: bd1ef61f4bb794b25383d3d72e71041a5ced172e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2017
---
# <a name="icordebugmodulegetprocess-method"></a><span data-ttu-id="1415a-102">ICorDebugModule::GetProcess 메서드</span><span class="sxs-lookup"><span data-stu-id="1415a-102">ICorDebugModule::GetProcess Method</span></span>
<span data-ttu-id="1415a-103">이 모듈의 포함 하는 프로세스를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="1415a-103">Gets the containing process of this module.</span></span>  
  
## <a name="syntax"></a><span data-ttu-id="1415a-104">구문</span><span class="sxs-lookup"><span data-stu-id="1415a-104">Syntax</span></span>  
  
```  
HRESULT GetProcess (  
    [out] ICorDebugProcess **ppProcess  
);  
```  
  
#### <a name="parameters"></a><span data-ttu-id="1415a-105">매개 변수</span><span class="sxs-lookup"><span data-stu-id="1415a-105">Parameters</span></span>  
 `ppProcess`  
 <span data-ttu-id="1415a-106">[out] 이 모듈을 포함 하는 프로세스를 나타내는 ICorDebugProcess 개체의 주소에 대 한 포인터입니다.</span><span class="sxs-lookup"><span data-stu-id="1415a-106">[out] A pointer to the address of an ICorDebugProcess object that represents the process containing this module.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="1415a-107">요구 사항</span><span class="sxs-lookup"><span data-stu-id="1415a-107">Requirements</span></span>  
 <span data-ttu-id="1415a-108">**플랫폼:** 참조 [시스템 요구 사항](../../../../docs/framework/get-started/system-requirements.md)합니다.</span><span class="sxs-lookup"><span data-stu-id="1415a-108">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
  
 <span data-ttu-id="1415a-109">**헤더:** CorDebug.idl, CorDebug.h</span><span class="sxs-lookup"><span data-stu-id="1415a-109">**Header:** CorDebug.idl, CorDebug.h</span></span>  
  
 <span data-ttu-id="1415a-110">**라이브러리:** CorGuids.lib</span><span class="sxs-lookup"><span data-stu-id="1415a-110">**Library:** CorGuids.lib</span></span>  
  
 <span data-ttu-id="1415a-111">**.NET framework 버전:**[!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span><span class="sxs-lookup"><span data-stu-id="1415a-111">**.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]</span></span>