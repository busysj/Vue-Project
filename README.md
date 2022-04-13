# Vue-Project

## 이 프로젝트를 진행한 이유, 프로젝트 속 및 사용한 기능
 우리가 프론트엔드 작업을 하다 보면 색상을 골라야 할 때가 종종 발생하는데 
 색에 민감하거나 완벽주의적인 성향이 있다면 색상코드까지 찾아서 신중하게 고를 때가 생긴다.
 나 역시 그러한 성향이 강하여 color picker를 자주 찾는데 색을 바로바로 확인하고 싶을 때,
 backgroundColor, textColor 등에 사용할 때 
 해당 페이지에서 확인하고 코드를 복사하여 갖다 쓸 수 있는 페이지.
 
 ***
 
 ## 막힌 부분과 해결 방안
 색상을 골라 클릭하였을 때 클립보드에 저장될 수 있게 하는 부분이 막혔으나
 ₩₩₩
 <script src="https://cdn.jsdelivr.net/npm/vue-clipboard2@0.3.1/dist/vue-clipboard.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/vue-clipboard2@0.3.1/dist/vue-clipboard.min.js"></script>
 ₩₩₩
 
  cdn을 이용하여 $copyText의 not function (typeError)를 해결할 수 있었다.
