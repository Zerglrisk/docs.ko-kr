### <a name="entity-framework-version-must-match-the-net-framework-version"></a>Entity Framework 버전이 .NET Framework 버전과 일치해야 함

|   |   |
|---|---|
|설명|Entity Framework 버전은 .NET Framework 버전과 일치해야 합니다. .NET Framework 4.5에는 Entity Framework 5를 사용하는 것이 좋습니다. <xref:System.ComponentModel.DataAnnotations> 주변의 .NET Framework 4.5 프로젝트에서 EF 4.x와 관련된 몇 가지 알려진 문제점이 있습니다. .NET 4.5에서는 다른 어셈블리로 옮겨졌으므로 사용할 주석을 결정할 때 문제가 있었습니다.|
|제안 해결 방법|.NET Framework 4.5용 Entity Framework 5로 업그레이드|
|범위|주요함|
|버전|4.5|
|형식|대상 변경|

