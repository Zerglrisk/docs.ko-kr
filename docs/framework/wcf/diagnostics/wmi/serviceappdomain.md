---
title: ServiceAppDomain
ms.date: 03/30/2017
ms.assetid: f28e5186-a66d-46c1-abe9-b50e07f8cb4f
ms.openlocfilehash: 05be495dbfe87e7dd14b0cfbb38b30c6f8278e6d
ms.sourcegitcommit: c93fd5139f9efcf6db514e3474301738a6d1d649
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/27/2018
ms.locfileid: "50192241"
---
# <a name="serviceappdomain"></a>ServiceAppDomain
서비스를 응용 프로그램 도메인에 매핑합니다.  
  
## <a name="syntax"></a>구문  
  
```csharp
class ServiceAppDomain  
{  
  Service ref;  
  AppDomainInfo ref;  
};  
```  
  
## <a name="methods"></a>메서드  
 ServiceAppDomain 클래스는 메서드를 정의하지 않습니다.  
  
## <a name="properties"></a>속성  
 ServiceAppDomain 클래스에는 다음 속성이 포함되어 있습니다.  
  
### <a name="ref"></a>ref  
 데이터 형식: Service  
한정자: Key  
  
 액세스 형식: 읽기 전용  
  
 이 응용 프로그램 도메인의 서비스입니다.  
  
### <a name="ref"></a>ref  
 데이터 형식: AppDomainInfo  
한정자: Key  
  
 액세스 형식: 읽기 전용  
  
 응용 프로그램 도메인의 속성을 포함합니다.  
  
## <a name="requirements"></a>요구 사항  
  
|MOF|Servicemodel.mof에 선언되어 있습니다.|  
|---------|-----------------------------------|  
|네임스페이스|root\ServiceModel에 정의되어 있습니다.|
