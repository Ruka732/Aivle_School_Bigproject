# Aivle_School_Bigproject

에이블스쿨 3기 AI트랙 2반 8조 빅프로젝트 VITA(Video To Answer)</BR>
![썸네일](https://github.com/Ruka732/Aivle_School_Bigproject/assets/101920181/2062de45-9435-4e58-bbd1-43a79ec5e410)
</BR></BR>

VITA 소개
---
사용자가 보유 중인 영상을 기반으로 AI 채팅을 제공하는 서비스</BR>
사용자가 영상을 업로드하면 AI가 내용을 요약하여 사용자에게 보여준 후 영상 내용을 기반으로 대화를 주고 받을 수 있는 챗봇

![소개](https://github.com/Ruka732/Aivle_School_Bigproject/assets/101920181/ec003cb6-b0a0-464e-aa83-6063c1fa1ad9)
</BR></BR>

핵심기능
---
![비타작동](https://github.com/Ruka732/Aivle_School_Bigproject/assets/101920181/05fc6c98-c049-448a-bc31-2025eaec6374)


</BR></BR>

프로젝트에서 역할
---
- DB 설계
- 로그인 기능
- 게시글 기능
- 파싱
</BR></BR>

코드구현
---
- 로그인 기능

<img width="622" alt="로그인" src="https://github.com/Ruka732/Aivle_School_Bigproject/assets/101920181/a58f4286-c211-41f5-9f50-0e7d69d320a0">

1) 프론트엔드에서 요청 한 JSON 로그인 데이터를 DB와 비교
2) 로그인 데이터가 일치 시 사용자명과 ID를 세션으로 저장하여 JSON형태로 리턴
3) 아이디가 맞고 비밀번호가 틀린 경우 '아이디 또는 비밀번호가 올바르지 않습니다' 리턴
4) DB에 저장된 아이디가 아닐 경우 '존재하지 않는 id입니다' 리턴
</BR>

-- 게시글 기능

<img width="816" alt="게시글코드" src="https://github.com/Ruka732/Aivle_School_Bigproject/assets/101920181/4cb9639f-03fd-40dc-9197-18ea23110b1b">

1)
