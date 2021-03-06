---
title: CI/CD 파이프라인 및 클라우드에서 DevOps 도구를 사용 하 여 앱의 수명 주기 현대화
description: Azure 클라우드 및 Windows 컨테이너를 사용 하 여 기존.NET 응용 프로그램 현대화 | CI/CD 파이프라인 및 클라우드에서 DevOps 도구를 사용 하 여 앱의 수명 주기 현대화
author: CESARDELATORRE
ms.author: wiwagn
ms.date: 04/30/2018
ms.openlocfilehash: c4d3eaa50f6c7645c954ca65bf42c6c1eab3a68d
ms.sourcegitcommit: 213292dfbb0c37d83f62709959ff55c50af5560d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/25/2018
ms.locfileid: "47070788"
---
# <a name="modernize-your-apps-lifecycle-with-cicd-pipelines-and-devops-tools-in-the-cloud"></a>CI/CD 파이프라인 및 클라우드에서 DevOps 도구를 사용 하 여 앱의 수명 주기 현대화

오늘날의 비즈니스는 시장에서 경쟁력을 빠른 속도로 혁신 해야 합니다. 최신 응용 프로그램 수준 높은 제공 DevOps 도구 및 혁신의 주기적으로이 구현 하는 데 중요 한 프로세스가 필요 합니다. 적절 한 DevOps 도구를 사용 하 여 개발자는 연속 배포를 간소화 하 고 사용자에 게 혁신적인 응용 프로그램을 보다 신속 하 게 가져올 수 있습니다.

연속 통합 및 배포 사례는 잘 확립 된, 다중 컨테이너 응용 프로그램을 사용 하 여 작업 하는 경우에 특히 컨테이너 미치는 새로운 고려를 소개 합니다.

Azure DevOps 서비스는 다양 한 공식 Azure DevOps 서비스 배포 작업을 통해 환경에 다중 컨테이너 응용 프로그램의 지속적인 통합 및 배포를 지원합니다.

-   [독립 실행형 Docker 호스트 VM에 배포](https://docs.microsoft.com/azure/devops/build-release/apps/cd/deploy-docker-windowsvm) (Linux 또는 Windows Server 2016 이상)

-   [Service Fabric에 배포](https://docs.microsoft.com/azure/service-fabric/service-fabric-tutorial-deploy-app-with-cicd-vsts)

-   [Azure Container Service-Kubernetes에 배포](https://docs.microsoft.com/azure/devops/build-release/apps/cd/azure/deploy-container-kubernetes)

또한에 배포할 수 있지만 [Docker Swarm](https://blogs.msdn.microsoft.com/jcorioland/2016/11/29/full-ci-cd-pipeline-to-deploy-multi-containers-application-on-azure-container-service-docker-swarm-using-visual-studio-team-services/) 또는 DC/OS Azure DevOps 서비스 스크립트 기반 작업을 사용 하 여 합니다.

배포 민첩성을 촉진 합니다. 계속 하려면 이러한 도구는 다양 한 개발 및 CI/CD 솔루션을 사용 하 여 컨테이너 워크 로드에 대 한 개발-테스트-에-프로덕션에 배포 환경을 제공 합니다.

그림 4-12에 Azure Container Service에서 Kubernetes 클러스터에 배포 하는 지속적인 배포 파이프라인을 보여 줍니다.

![Azure DevOps 서비스 연속 배포 파이프라인을 Kubernetes 클러스터에 배포](./media/image12.png)

> **그림 4-12입니다.** Azure DevOps 서비스 연속 배포 파이프라인을 Kubernetes 클러스터에 배포

>[!div class="step-by-step"]
[이전](modernize-your-apps-with-monitoring-and-telemetry.md)
[다음](migrate-to-hybrid-cloud-scenarios.md)
