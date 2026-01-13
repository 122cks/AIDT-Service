# Chatbot Assets (씨마스온)

이 폴더는 카카오톡 채널/챗봇에 사용할 브랜딩 에셋을 보관합니다.

## 파일
- `cmass-chatbot-avatar.svg` : 기본 프로필 아바타(SVG)
- `cmasson-chatbot-avatar.svg` : 기본 프로필 아바타(씨마스온/SVG)
- `cmasson-chatbot-avatar-flat.svg` : 플랫 버전 아바타(씨마스온/SVG)
- `brand-kit.md` : 이름/소개/톤앤매너/템플릿 문구

## 카카오 프로필용 권장사항(일반 가이드)
- 정사각형(1:1) 기준으로 제작
- 실제 노출은 **원형 크롭**이 될 수 있으므로 가장자리/모서리에 중요한 텍스트 배치 금지
- 배경과 전경 대비(가독성) 확보

## PNG로 내보내기
- SVG 업로드가 불가한 경우 PNG로 변환해 업로드하세요.
- 방법 1) 디자인 툴(권장): Figma/Illustrator/Inkscape에서 1024×1024 PNG로 Export
- 방법 2) ImageMagick 사용(설치되어 있을 때):
  - `magick -background none assets/chatbot/cmass-chatbot-avatar.svg -resize 1024x1024 assets/chatbot/cmass-chatbot-avatar.png`

## 수정 포인트
- 배경색/문구(예: “씨마스 AIDT”)를 원하시면 `cmass-chatbot-avatar.svg`의 하단 텍스트만 바꿔도 됩니다.
