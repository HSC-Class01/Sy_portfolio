# Vercel 배포 안내

기존 parkn72-cmd/AI 저장소의 최상단에 portfolio 폴더를 만들고, 이 패키지의 portfolio/index.html 및 portfolio/vercel.json을 넣으세요.
기존 src, site, config.json, requirements.txt, .github 파일은 수정하거나 삭제하지 않습니다.

Vercel → Add New → Project → GitHub parkn72-cmd/AI Import
Root Directory: portfolio
Framework Preset: Other
Build Command: 비워두기 (Override가 필요하면 켜고 빈 값)
Output Directory: .
Install Command: Override를 켜고 비워두기 (정적 HTML이므로 설치 불필요)
Environment Variables: 없음 (DART_API_KEY를 프런트엔드에 등록하지 마세요)
Deploy를 누른 뒤 표시되는 Production URL을 이용하세요. 주소는 실제 배포 후 확인합니다.

Root Directory를 portfolio로 설정하면 기존 AI 분석 사이트와 분리하여 배포됩니다.
추후 portfolio/index.html을 수정하고 Production Branch에 반영하면 Vercel에서 자동 재배포합니다.

주의: 수료증과 공개 프로필이 포함되어 있습니다. 공개 전에 개인정보를 확인하세요.
이 패키지는 배포용 파일이며 실제 저장소 업로드나 Vercel 배포는 수행하지 않았습니다.
