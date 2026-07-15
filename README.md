# 자동차부품 ERP — 무설치 버전 (Windows)

자동차부품 제조업용 **통합관리(ERP/MES) 프로그램**입니다.
기준정보 · 생산 · 품질 · 구매 · 재고 · 영업 · 설비 · 원가까지 하나의 화면에서 관리합니다.

**설치가 필요 없습니다.** 압축을 풀고 실행 파일 하나만 더블클릭하면 됩니다. (Docker·Node 등 별도 설치 불필요)

---

## ⬇️ 다운로드

### 👉 [**최신 버전 내려받기 (Windows, 무설치)**](https://github.com/ybRoh/erp-download/releases/latest/download/ERP-Portable-Windows-20260714.zip)

- 파일: `ERP-Portable-Windows-20260714.zip` (약 68 MB)

### 📦 다른 버전

| 버전 | 용도 | 다운로드 |
|------|------|----------|
| **무설치 (Windows)** | 개인·소규모 · 가장 간단 | [내려받기](https://github.com/ybRoh/erp-download/releases/latest/download/ERP-Portable-Windows-20260714.zip) (68 MB) |
| **서버 설치형** | 사내 다중 사용자 (Docker) | [내려받기](https://github.com/ybRoh/erp-download/releases/latest/download/erp-web-deploy-20260714.zip) (1.8 MB) |
| **무설치 (고성능·PostgreSQL)** | 데이터 많은 환경 | [내려받기](https://github.com/ybRoh/erp-download/releases/latest/download/ERP-Portable-PostgreSQL-Windows-20260714.zip) (108 MB) |
| **QMS 품질도구 (단일 HTML)** | APQP/FMEA/ISIR/검사/감사/교육 | [브라우저에서 바로 실행](https://ybroh.github.io/erp-download/QMS-Suite-Portable.html) · [파일 내려받기](https://github.com/ybRoh/erp-download/releases/latest/download/QMS-Suite-Portable.html) (0.7 MB) |

> 🧰 **QMS 품질도구**는 설치·다운로드 없이 브라우저에서 바로 실행됩니다. 서버·인터넷 없이 파일 하나로 동작하며, 데이터는 브라우저에 저장됩니다.

- 🏠 **[소개(랜딩) 페이지](https://ybroh.github.io/erp-download/)** · 🌐 **[버전 선택 다운로드 페이지](https://ybroh.github.io/erp-download/download.html)** · 📋 [모든 릴리스](https://github.com/ybRoh/erp-download/releases)

---

## 🚀 사용법 (아주 간단)

1. 내려받은 **zip 파일의 압축을 풉니다.**
2. 폴더 안의 **`실행.bat` 을 더블클릭**합니다.
3. 잠시 후 **웹 브라우저가 자동으로 열립니다.**
   (안 열리면 주소창에 `http://localhost:3000` 입력)
4. 로그인: 아이디 **`admin`** / 비밀번호 **`admin123`**
5. 프로그램을 끄려면 검은 명령창을 닫으면 됩니다.

> 처음 실행 시 초기 데이터가 자동으로 준비되어 바로 사용해 볼 수 있습니다.

---

## 💡 특징

- **무설치 실행** — Docker·데이터베이스 서버·Node 설치가 전혀 필요 없습니다.
- **데이터는 폴더 안에 보관** — 모든 데이터가 폴더 내 `data\erp.db` 파일 하나에 저장됩니다.
  폴더째 복사하면 데이터도 함께 이동하고, **백업도 이 폴더만 복사**하면 끝입니다.
- **주요 기능** — 대시보드, 기준정보, 생산관리, 품질관리(IQC/PQC/OQC·NCR·SPC·FMEA/ISIR),
  구매·재고·영업·설비(OEE)·원가관리, LOT 추적, 사용설명서 내장.

---

## ⚠️ 참고

- **Windows 전용**입니다.
- 폴더 안의 파일(`node.exe`, `dist`, `client`, `node_modules` 등)은 지우거나 옮기지 마세요. **폴더 통째로만** 이동/복사하세요.
- `3000` 포트를 다른 프로그램이 사용 중이면 실행되지 않을 수 있습니다.
- 사내 여러 사람이 동시에 쓰는 서버형 운영이 필요하면 별도 설치형(PostgreSQL) 구성도 가능합니다. 아래로 문의해 주세요.

---

## ✉️ 문의 / 커스터마이징

이 프로그램은 **바이브코딩**으로 만들었습니다.
회사 실정에 맞게 자유롭게 수정해 쓰셔도 됩니다.
개선점이나 커스터마이징이 필요하시면 연락 주세요.

**📧 ybr1090@gmail.com**
