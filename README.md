# 윤태오 AI 캐릭터챗

여성향 오리지널 캐릭터 윤태오의 포트폴리오용 데모입니다.

- 프런트엔드: GitHub Pages (index.html)
- 모델 호출: Cloudflare Worker → Gemini Flash
- Worker URL은 index.html에 포함되어 있으며 Gemini API 키는 포함하지 않습니다.
- 윤태오의 확정된 캐릭터 이미지 **taeo.jpg** 파일은 저장소 루트에 따로 업로드해야 합니다.
- GitHub Pages 설정: Settings → Pages → Deploy from a branch → main / (root) → Save

## 보안
공개 운영 전 Cloudflare Worker에 IP별 요청 제한, 전체 요청/비용 한도, 악용 차단을 설정하세요. 브라우저의 프런트엔드 제한만으로는 API 사용량을 보호할 수 없습니다.
대화 내용은 외부 AI 모델에 전달되므로 비공개 정보는 입력하지 않도록 안내합니다.
