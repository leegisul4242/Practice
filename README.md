# Practice

https://github.com/2022Team4/PracticeFork/tree/master

08??(?)
포크, 연동(싱크), 브랜치
원 레파지토리로 풀 리퀘 날리기

충돌 수동머지
머지


0814(일)
깃배쉬, 톨토이스깃
  
  🟦 로컬에서 푸시전 
  - 커밋 메세지 변경
  - 커밋 reset
  
    $ git reset --{option} {내가 헤드를 위치할 멀쩡한 커밋해시id 앞7자리}
      git log --oneline  로 커밋id확인
      git reset --hard b59a011
    여기서 사용 가능한 option은 크게 3가지가 있다. 
    1) hard는 파일을 포함해서 모든 히스토리를 싹 날려버린다. 
    2) soft는 히스토리만 삭제하고 파일은 stage 상태 그대로 남겨둔다. 
    3) mixed는 디폴트 옵션으로, 히스토리를 삭제한 후 파일도 그대로 남겨져있지만 stage 상태는 아니기에 다시 add를 해야 추적이 가능하다.

  🟦 리모트에 push 후
  - 커밋 메시지 변경
  - 커밋 revert
  
  커밋내역삭제
  원노트 보기
