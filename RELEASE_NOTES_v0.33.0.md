ES-DE에서 쓰던 이름과 설명을 그대로. gamelist.xml을 읽고, 목록 테마의 표지 배치를 다듬은 베타 판입니다.

**바뀐 것**

- **게임 이름:** gamelist.xml의 `<name>`에 적힌 이름이 괄호까지 그대로 뜹니다. `Dragon Quest VIII (J-K patch).iso` → 「(한) 드래곤 퀘스트 VIII」. 초성 찾기도 이 이름으로 됩니다.
- **게임 설명:** gamelist.xml의 `<desc>`가 목록 스타일의 설명 칸에 뜹니다.
- **ES-DE 폴더 한 번에 읽기:** 메타데이터 폴더로 **ES-DE 폴더 자체**를 고르면 `downloaded_media`의 그림·영상과 `gamelists`의 이름·설명을 함께 가져옵니다. 롬 폴더의 기기 폴더에 둔 gamelist.xml도 읽습니다.
- **목록 테마 표지 배치:** 정방형 표지(게임보이 등)도 왼쪽 표지·오른쪽 로고로 나란히 놓고, 위아래 배치는 슈퍼 패미컴·N64 같은 확실한 가로형에만 씁니다.

<img src="https://raw.githubusercontent.com/nori-launcher/Nori/main/docs/images/06_list.png" alt="목록 스타일" width="100%">

> [!NOTE]
> 메타데이터 폴더로 `downloaded_media`만 골라 두셨다면 그림만 읽습니다. 이름·설명까지 쓰려면 그 위의 ES-DE 폴더로 바꿔 주세요.
> 롬과 gamelist는 `<path>`의 파일 이름으로 짝짓고, 대소문자와 `(J-K patch)` 같은 괄호는 빼고 맞춥니다.

**설치:** 아래 `Nori-0.33.0.apk`를 받아 쓰던 노리 위에 덮어 깔면 됩니다. 처음이시면 [시작 안내](https://github.com/nori-launcher/Nori#시작-안내)를 봐 주세요.
버그는 [이슈](https://github.com/nori-launcher/Nori/issues/new/choose)로 알려 주세요.
