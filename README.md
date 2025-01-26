# Building_3-Tier_Architecture
<div align="center">
  <h4>SeSAC 강동캠퍼스의 클라우드 데이터엔지니어 교육과정에서 진행한 팀 프로젝트로,<br/><br/>
      AWS로 3-Tier 아키텍처를 구축하고, 오픈소스 모니터링 툴(Prometheus와 Grafana)로 로그를 모니터링하고,<br/><br/>
      K6로 부하테스트를 통해 유저 시나리오대로 서버가 요청처리를 잘 하는지를 테스트를 진행하였다.</h4>
  <br/>
  <img width="1000" alt="3-Tier_Architecture" src="https://github.com/user-attachments/assets/e7f98655-7efc-4fba-bc21-6c2c04744d0b"/>
  <br/>
  <br/>
  <br/>
  <br/>
</div>

## 3-Tier 인프라 구축
<div align="center">
  <img width="1000" alt="3-Tier" src="https://github.com/user-attachments/assets/f36f028c-65a6-4f06-b1bf-df4353a8fb7a" />
  <h4>
    3-Tier 인프라를 구축하는 전체 과정을 기록으로 남기기 위해서 노션으로 깔끔하게 정리하였다.
  </h4>
  👉👉👉 <a href="https://thread-street-d08.notion.site/3-Tier-13b23386ac06807abb45f62bec37f16d?pvs=4" target="_blank">
    3-Tier 인프라 구축 과정
  </a> 👈👈👈
  <br/>
  <br/>
  <br/>
  <br/>
</div>

## 오픈소스 모니터링 툴 Node Exporter, Prometheus, Grafana
<div align="center">
  <img width="1000" alt="Image" src="https://github.com/user-attachments/assets/179ae456-d2fc-4a39-9066-1048687b7ae8" />
  <h4>
    AWS에도 성능 모니터링을 할 수 있는 Cloud Watch라는 툴이 있지만,<br/><br/>
    우리 팀은 보다 다양한 로그를 모니터링을 할 수 있고, 비용절감도 가능하고 사용자가 마음대로 커스텀 할 수 있는<br/><br/>
    오픈소스 모니터링 툴인 Prometheus와 Grafana를 사용해 모니터링 하였다.<br/><br/>
  </h4>
  👉👉👉 <a href="https://thread-street-d08.notion.site/APM-Tools-13c23386ac06805989cdde936369ef03?pvs=4" target="_blank">
    모니터링 툴이란?
  </a> 👈👈👈<br/><br/>
  👉👉👉 <a href="https://thread-street-d08.notion.site/Node-Exporter-Prometheus-Grafana-13f23386ac0680ca8844e1a52912ce2e?pvs=4" target="_blank">
    Node Exporter, Prometheus, Grafana 세팅 과정
  </a> 👈👈👈
  <br/>
  <br/>
  <br/>
  <br/>
</div>

## 모니터링 한 로그 기록을 S3 버킷에 저장
