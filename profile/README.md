# 👕 **FITLOOP 프로젝트**
<p align="center">
  <img src="https://github.com/user-attachments/assets/b6bb06a6-a87c-4507-8a58-7600ed47b422" alt="FITLOOP Logo">
</p>

**FITLOOP**은 사용자가 옷을 사고팔 수 있는 **패션 거래 플랫폼**입니다.  
룩북을 통해 스타일을 공유하고, 챌린지를 통해 트렌디한 패션을 경험할 수 있습니다.

---

## **프로젝트 개요**
- **프로젝트명:** FITLOOP  
- **목적:** 사용자들이 패션 아이템을 사고팔고, 룩북과 챌린지를 통해 스타일을 공유하는 패션 플랫폼 제공  
- **주요 기능:**  
  - **마켓플레이스**: 사용자가 직접 패션 아이템을 등록하고 판매 가능  
  - **룩북 기능**: 사진 업로드를 통해 스타일 공유 (영상 불가)  
  - **챌린지 기능**: 태그와 영상 기반 챌린지 진행 (사진 업로드 불가)  
  - **즐겨찾기(북마크) 기능**: 원하는 상품 및 룩북 저장  
  - **필터링 기능**: 스타일, 브랜드, 가격대별 상품 검색  

---

## **기술 스택**
### **Frontend**
- **Framework:** Next.js  
- **Styling:** Tailwind CSS  
- **State Management:** React Context API  
- **API 통신:** Axios  

### **Backend**
- **Framework:** Spring Boot  
- **Database:** MariaDB (AWS RDS) 또는 MySQL
- **Security:** Spring Security (JWT 인증)  
- **Batch Processing:** Spring Batch  

### **DevOps**
- **CI/CD:** GitHub Actions  
- **Deployment:** AWS EC2, S3  
- **Monitoring:** Prometheus, Grafana  
---

## **프로젝트 실행 방법**
### **1. 환경 변수 설정**
`.env.local` 파일을 생성하고 필요한 API 키 및 설정 값을 입력합니다.

### **2. 프론트엔드 실행**
```bash
cd frontend
npm install
npm run dev
```

### **3. 백엔드 실행**
```bash
cd backend
./gradlew bootRun
```

---

## **기여 방법**
1. 이슈를 확인하고 작업할 내용을 선택합니다.  
2. `feature/{기능명}` 브랜치를 생성 후 작업합니다.  
3. PR을 생성하고 코드 리뷰 후 병합합니다.

---
