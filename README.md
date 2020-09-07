# Learn-Redux

Redux: 자바스크립트에서 지원하는 라이브러리

1. Store: state의 값이 저장된 공간.
2. Reducer: state의 초기값을 지정해주고 dispatch된 state에 따른 objecct의 값을 새롭게 assign해준다.
3. getState(): store에 현재 저장된 state의 값을 불러온다.
4. dispatch: 버튼을 누르는 등의 action이 실행되면 action의 타입과 변형되야하는 상태를 store로 보낸다.
5. subscribe(): 구독하는 기능. store의 값이 바뀔 때마다 store에 저장된 상태를 자동으로 불러와서 새롭게 rendering(재구성)해준다.
