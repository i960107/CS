- Q. process를 간단히 설명해 주세요.
- Q. process의 메모리 영역에 대해서 설명해주세요.
- Q. ⭐⭐⭐⭐ Multi process에 대해서 설명해 주세요.
- Q. process의 context는 무엇인가요?
- Q. PCB에 저장되는  것들은 무엇이 있나요?
- Q. context switch에 대해서 설명해주세요.
- Q. process의 state에는 어떤 것들이 있나요?
- Q. ⭐⭐ Multi thread에 대해서 설명해 주세요.
- Q. thread는 왜 독립적인 stack memory 영역이 필요한가요.
- Q. process와 thread를 비교설명 해주세요.
- Q. ⭐⭐ multi process와 multi thread를 비교설명해 주세요.
    
    multi process의 context switching보다 multi thread의 context switching이 더 빠름. 자원을 공유하고 있기 때문. context swtiching시  캐시메모리를 초기화하지 않기 때문
    
    thread에서는 통신시 별도의 자원을 이용하지 않고 process에 할당된 heap영역등을 통해 데이터를 주고 받음.
    
- Q. ⭐⭐ multi process환경에서 process간에 데이터를 어떻게 주고 받을까요?
- IPC의 예시를 들어줄 수 있나요?
    
    IPC는 크게 공유 메모리 모델과 메시지 전달 모델로 나눌 수 있는데, 공유 메모리 모델은 주소 공간의 일부를 공유하여 공유한 메모리 영역에 read/write를 통해 통신하게 되는데 예시로는 공유메모리와, POSIX가 있습니다. 메시지 전송 모델의 경우에는 kernel을 통해 send/write 연산을 통해 데이터를 전송합니다. 예시로는 pipe, socket, message queue가 있습니다.
    
- Q. ⭐ Multi process/thread 환경에서 동기화 문제를 어떻게 해결하나요?
- Q. 멀티 스레드의 장점과 단점에 대해 설명해 주세요
- Q. CPU 스케줄링에 대해서 설명해 주세요.
- Q. 교착상태(Deadlock)에 대해서 간단히 설명해 주세요.
- Q. paging이란 뭔가요?
- Q. paging 기법 사용시 발생할 수 있는 메모리 단편화(memory fragmentation)문제에 대해 설명해주세요.
- Q. page 교체 알고리즘에 대해서 설명해 주세요.
- Q. 요구 페이징이란 무엇인가요.
- Q. page falut를 처리하는 과정에 대해서 설명해주세요.
- Q. segmentation에 대해서 설명해 주세요.
- Q. segmentation의 메모리 단편화(memory fragmentation)문제에 대해 설명해주세요.
- Q. pagin과 segmentation의 차이는 뭔가요?
- Q. paged segmentation 기법에 대해 설명해주세요.
- Q. LRU와 LFU의 차이에 대해서 설명해주세요.
- Q. ⭐ 가상 메모리에 대해서 설명해 주세요.
- Q. 동기와 비동기의 차이에 대해 설명해주세요
- Q. 캐시의 지역성에 대해 설명해주세요
- Q. 운영체제의 역할을 무엇인가요.
- Q. PCB는 무엇인가요?
- Q. 메모리 계층에 대해 설명해보세요.
- Q. C언어로 작성된 프로그램의 실행과정에 대해 설명해보세요.
- Q. 크롬 아이콘을 클릭했을때 일어나는 일에 대해서 설명해보세요.
- Q. 정적 라이브러리와 동적 라이브러리의 차이점에 대해 설명해주세요.
