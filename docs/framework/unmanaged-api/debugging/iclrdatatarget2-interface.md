---
title: "ICLRDataTarget2 인터페이스"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: ICLRDataTarget2
api_location: mscordbi.dll
api_type: COM
f1_keywords: ICLRDataTarget2
helpviewer_keywords: ICLRDataTarget2 interface [.NET Framework debugging]
ms.assetid: 94249397-861b-4294-a538-cf01466a66d3
topic_type: apiref
caps.latest.revision: "9"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.openlocfilehash: d1780df0a4659d232a27faf4fdc2f6c9b13db98a
ms.sourcegitcommit: 4f3fef493080a43e70e951223894768d36ce430a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/21/2017
---
# <a name="iclrdatatarget2-interface"></a><span data-ttu-id="b53ac-102">ICLRDataTarget2 인터페이스</span><span class="sxs-lookup"><span data-stu-id="b53ac-102">ICLRDataTarget2 Interface</span></span>
<span data-ttu-id="b53ac-103">서브 클래스 [ICLRDataTarget](../../../../docs/framework/unmanaged-api/debugging/iclrdatatarget-interface.md) 대상 프로세스의 가상 메모리 영역을 조작 하는 데 데이터 액세스 서비스 계층에서 사용 되는 합니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-103">A subclass of [ICLRDataTarget](../../../../docs/framework/unmanaged-api/debugging/iclrdatatarget-interface.md) that is used by the data access services layer to manipulate virtual memory regions in the target process.</span></span>  
  
## <a name="methods"></a><span data-ttu-id="b53ac-104">메서드</span><span class="sxs-lookup"><span data-stu-id="b53ac-104">Methods</span></span>  
  
|<span data-ttu-id="b53ac-105">메서드</span><span class="sxs-lookup"><span data-stu-id="b53ac-105">Method</span></span>|<span data-ttu-id="b53ac-106">설명</span><span class="sxs-lookup"><span data-stu-id="b53ac-106">Description</span></span>|  
|------------|-----------------|  
|[<span data-ttu-id="b53ac-107">AllocVirtual 메서드</span><span class="sxs-lookup"><span data-stu-id="b53ac-107">AllocVirtual Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/iclrdatatarget2-allocvirtual-method.md)|<span data-ttu-id="b53ac-108">대상 프로세스의 주소 공간에 메모리를 할당 합니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-108">Allocates memory in the address space of the target process.</span></span>|  
|[<span data-ttu-id="b53ac-109">FreeVirtual 메서드</span><span class="sxs-lookup"><span data-stu-id="b53ac-109">FreeVirtual Method</span></span>](../../../../docs/framework/unmanaged-api/debugging/iclrdatatarget2-freevirtual-method.md)|<span data-ttu-id="b53ac-110">대상 프로세스의 주소 공간에서 이전에 할당 된 메모리를 해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-110">Frees memory that was previously allocated in the address space of the target process.</span></span>|  
  
## <a name="remarks"></a><span data-ttu-id="b53ac-111">설명</span><span class="sxs-lookup"><span data-stu-id="b53ac-111">Remarks</span></span>  
 <span data-ttu-id="b53ac-112">API 클라이언트(즉, 디버거)에서는 이 인터페이스를 특정 대상 프로세스에 적절하게 구현해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-112">The API client (that is, the debugger) must implement this interface as appropriate for the particular target process.</span></span> <span data-ttu-id="b53ac-113">예를 들어 활성 프로세스의 구현은 메모리 덤프의 구현과는 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-113">For example, a live process would have an implementation different from that of a memory dump.</span></span> <span data-ttu-id="b53ac-114">대상에서 메모리 영역의 수정을 지원하지 않을 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-114">The target may not support modification of its memory regions.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="b53ac-115">요구 사항</span><span class="sxs-lookup"><span data-stu-id="b53ac-115">Requirements</span></span>  
 <span data-ttu-id="b53ac-116">**플랫폼:** 참조 [시스템 요구 사항](../../../../docs/framework/get-started/system-requirements.md)합니다.</span><span class="sxs-lookup"><span data-stu-id="b53ac-116">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
  
 <span data-ttu-id="b53ac-117">**헤더:** ClrData.idl, ClrData.h</span><span class="sxs-lookup"><span data-stu-id="b53ac-117">**Header:** ClrData.idl, ClrData.h</span></span>  
  
 <span data-ttu-id="b53ac-118">**라이브러리:** CorGuids.lib</span><span class="sxs-lookup"><span data-stu-id="b53ac-118">**Library:** CorGuids.lib</span></span>  
  
 <span data-ttu-id="b53ac-119">**.NET framework 버전:**[!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]</span><span class="sxs-lookup"><span data-stu-id="b53ac-119">**.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="b53ac-120">참고 항목</span><span class="sxs-lookup"><span data-stu-id="b53ac-120">See Also</span></span>  
 [<span data-ttu-id="b53ac-121">ICLRDataTarget 인터페이스</span><span class="sxs-lookup"><span data-stu-id="b53ac-121">ICLRDataTarget Interface</span></span>](../../../../docs/framework/unmanaged-api/debugging/iclrdatatarget-interface.md)  
 [<span data-ttu-id="b53ac-122">디버깅 인터페이스</span><span class="sxs-lookup"><span data-stu-id="b53ac-122">Debugging Interfaces</span></span>](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)