# NEON TIDE Mobile V3.3

## 모바일 조작

- 휴대폰을 가로로 회전
- 화면 왼쪽 영역을 드래그: 기체 이동
- 기본탄: 자동 발사
- 오른쪽 파란 버튼: 현재 미사일 발사
- 오른쪽 주황 버튼: 폭탄 사용
- 상단 오른쪽: 일시정지
- 상단 왼쪽: 사운드

미사일 버튼에는 현재 종류와 잔탄이 표시됩니다.

- S: SEARCH MISSILE
- P: PHOTON TORPEDO
- C: CLUSTER MISSILE
- N: NAPALM ROCKET

## GitHub Pages 배포

터미널에서 이 폴더로 이동한 뒤:

```bash
bash deploy_github_pages.sh
```

기본 저장소 이름은 `neon-tide-mobile`입니다.

다른 이름 사용:

```bash
bash deploy_github_pages.sh my-game-name
```

배포 주소:

```text
https://gt10300407.github.io/neon-tide-mobile/
```

## 홈 화면 설치

GitHub Pages 주소를 iPhone Safari에서 연 뒤:

1. 공유 버튼
2. 홈 화면에 추가
3. NEON TIDE 아이콘 실행

서비스 워커가 설치된 뒤에는 이전에 접속한 버전을 오프라인에서도 실행할 수 있습니다.
