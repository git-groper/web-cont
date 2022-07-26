# web-cont
테스트용 웹 컨텐츠

Kubernetes Sidecar Patten 연습

Pod에 nginx, github에서 파일 긁어오는 puller를 사이드카 패턴으로 배포
동일 볼륨을 사용 하도록 하고 puller는 1분마다 긁어와서 공유 볼륨에 저장
