# 🚀 빠른 배포 가이드

## 즉시 링크 공유하기

### 1️⃣ **GitHub Pages (추천)**
```bash
# 1. GitHub에 새 저장소 생성
# 2. 로컬에서 파일 업로드
git init
git add .
git commit -m "RAG System Initial Deploy"
git remote add origin https://github.com/[사용자명]/[저장소명].git
git push -u origin main

# 3. GitHub Settings > Pages > Source: GitHub Actions 선택
# 4. 자동 배포 완료! (2-3분 소요)
```

**접속 주소**: `https://[사용자명].github.io/[저장소명]`

### 2️⃣ **Netlify (가장 빠름)**
1. [netlify.com](https://netlify.com) 접속
2. "New site from Git" 클릭  
3. GitHub 저장소 연결
4. Deploy 클릭
5. **즉시 링크 생성!** (30초-1분)

**접속 주소**: `https://[랜덤이름].netlify.app`

### 3️⃣ **Vercel (고성능)**  
1. [vercel.com](https://vercel.com) 접속
2. "New Project" 클릭
3. GitHub 저장소 import
4. Deploy 클릭  
5. **고성능 링크 생성!** (1-2분)

**접속 주소**: `https://[프로젝트명].vercel.app`

---

## ⚡ 초간단 드래그&드롭 배포

### Surge.sh (파일만 있으면 OK!)
```bash
# 1. 터미널에서 프로젝트 폴더로 이동
cd [프로젝트 폴더]

# 2. Surge 설치 및 배포
npm install -g surge
surge

# 3. 도메인 입력 (또는 자동 생성)
# 4. 즉시 링크 생성!
```

**접속 주소**: `https://[선택한도메인].surge.sh`

---

## 📱 모바일에서도 배포하기

### GitHub Mobile App
1. GitHub 모바일 앱 설치
2. 저장소 생성
3. 파일 업로드  
4. Settings에서 Pages 활성화

### Netlify Drop  
1. [netlify.com/drop](https://netlify.com/drop) 접속
2. 프로젝트 폴더를 드래그&드롭
3. 즉시 링크 생성!

---

## 🎯 **건설업계 추천 배포 방법**

| 용도 | 플랫폼 | 배포시간 | 특징 |
|------|--------|----------|------|
| **사내 데모** | Netlify | 30초 | 즉시 공유 |
| **고객 프레젠테이션** | Vercel | 1분 | 빠른 로딩 |
| **장기 운영** | GitHub Pages | 3분 | 무료, 안정적 |
| **임시 테스트** | Surge.sh | 30초 | 명령어 한 줄 |

---

## ✅ 배포 완료 체크리스트

- [ ] 두 시스템 모두 정상 작동 (index.html, simplified-rag-system.html)
- [ ] 시스템 간 전환 버튼 작동  
- [ ] 모바일에서 접속 테스트
- [ ] 링크 공유 및 접속 확인
- [ ] 성능 확인 (로딩 속도 3초 이내)

---

## 🆘 문제 해결

### 배포 실패 시
1. 파일명 확인 (대소문자, 공백)
2. 브라우저 캐시 삭제
3. 다른 플랫폼으로 재시도

### 링크 접속 안될 시  
1. 배포 상태 확인 (GitHub Actions 로그)
2. DNS 전파 대기 (최대 24시간)
3. 직접 파일 경로로 접속 시도

**즉시 지원**: 배포 관련 문제 발생 시 언제든 문의주세요!