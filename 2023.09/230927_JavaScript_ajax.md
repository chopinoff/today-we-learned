# JavaScript Ajax

## Ajax에 대해 가능한 한 자세히 설명하세요.

Ajax(asynchronous JavaScript and XML)는 비동기 웹 응용 프로그램을 만들기 위해 클라이언트 측에서 사용되는 웹 개발 기술의 집합입니다. Ajax를 사용하면 웹 애플리케이션은 기존 페이지의 화면 및 동작을 방해하지 않으면서 백그라운드에서 비동기적으로 서버로 데이터를 보내고 서버에서 데이터를 받아올 수 있습니다. Ajax는 프리젠테이션 레이어에서 데이터 교환 레이어를 분리함으로써, 웹페이지 및 확장 웹 애플리케이션이 전체 페이지를 다시 로드 할 필요 없이 동적으로 컨텐츠를 변경할 수 있도록 합니다. 실제로 최근에는 일반적으로 네이티브 JavaScript의 장점 때문에 XML대신 JSON을 사용합니다.

XMLHttpRequest API는 비동기 통신에 자주 사용되며, 최근에는 fetch API가 자주 사용됩니다.

## Ajax를 사용하는 것의 장단점은 무엇인가요?

### 장점

상호작용성이 좋아집니다. 서버의 새로운 컨텐츠를 전체 페이지를 다시로드할 필요 없이 동적으로 변경할 수 있습니다.
스크립트나 스타일 시트는 한 번만 요청하면 되므로 서버에 대한 연결을 줄여줍니다.
상태를 페이지에서 관리 할 수 ​​있습니다. 메인 컨테이너 페이지가 다시 로드되지 않기 때문에 JavaScript의 변수와 DOM의 상태가 유지됩니다.
기본적으로 SPA의 대부분의 장점과 같습니다.

### 단점

동적 웹 페이지는 북마크하기 어렵습니다.
브라우저에서 JavaScript가 비활성화된 경우 작동하지 않습니다.
일부 웹 크롤러는 JavaScript를 실행하지 않으며 JavaScript에 의해 로드된 콘텐츠를 볼 수 없습니다.
SPA의 대부분의 단점과 같습니다.