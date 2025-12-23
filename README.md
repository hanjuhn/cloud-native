# Cloud-Native | 클라우드 네이티브 기반 CRUD 게시판

## 🌟 Project Overview | 프로젝트 개요

Cloud-Native는 로컬 환경에서 클라우드 환경을 모사하여 클라우드 네이티브 웹서비스를 개발하고 운영하는 것을 목표로 합니다. Docker와 Kubernetes를 기반으로 프론트엔드와 백엔드를 분리한 게시판 서비스를 구현하였으며 각 서비스는 서로 다른 컨테이너와 Kubernetes Deployment로 배포됩니다. 게시글 목록 조회, 작성, 수정, 삭제 기능을 제공하고 Git 기반 CI/CD 파이프라인과 ArgoCD를 연동해 자동 빌드 및 배포를 구성하였습니다. 또한 Prometheus와 Grafana를 활용해 서비스 상태와 성능을 모니터링합니다.

---

## 🚀 Features | 주요 기능

### 게시판 구현

게시글 목록 조회, 작성, 수정, 삭제

### CI/CD 구성

main 브랜치 push 시 자동 빌드되는 워크플로 구성, ArgoCD 연동

### 모니터링 구성

Prometheus와 Grafana를 통한 모니터링 기능

---

## 📁 Key Directories and Files | 주요 디렉토리 및 파일

- `.github/workflows/`: GitHub Actions 기반 CI 빌드 및 자동화 워크플로 설정
- `backend/`: 게시판 백엔드 서비스 코드 및 게시글 수정 기능 구현
- `frontend/`: 게시판 프론트엔드 코드 및 게시글 수정 기능 반영
- `k8s/`: Kubernetes Deployment 및 배포 설정 파일

---

## 📽️ Demonstration | 데모 시연

### 동영상 데모 (사진을 클릭해 주세요)

[![데모 시연](https://github.com/user-attachments/assets/eea5bfe1-6064-4947-b7ad-448880d6baa7)](https://www.youtube.com/watch?v=6JJCd_G-xXw)
