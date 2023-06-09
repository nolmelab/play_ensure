# bot 

a load tester. 

여러 봇들을 tokio에서 실행한다. 점진적으로 프로토타이핑을 거치면서 
테스트를 진행한다. 러스트에서 이런 방식은 잘 동작한다. 한번 코딩되면 
완결되는 특성이 있다. 

## 설계 

- Agent 
  - struct 
  - connects to server and waits commands

- Flow 
  - struct

- Act 
  - trait 

- ActComposite : Act
  - trait 

- Bot 
  - struct

