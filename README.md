# excel-gpt-parser

# 📊 Excel GPT Parser

GPT를 활용하여 비정형 Excel 및 PDF 문서로부터 핵심 데이터를 자동 추출하고, 사전 정의된 Excel 템플릿에 정형화된 형태로 삽입하는 자동화 파이프라인입니다.

## 🚀 주요 기능

- 다양한 형태의 Excel / PDF 문서 업로드 처리
- OpenAI GPT-4o를 활용한 데이터 정규화 및 필드 추출
- 기존 템플릿(`수익률표`)에 자동 삽입
- 숫자 필드 자동 포맷 (예: 대출잔액, 이자금액 등)
- `batch_size` 기반 GPT 처리 및 누락 방지
- FastAPI 기반 API 서버 구성

## 🧱 기술 스택

- Python 3.10+
- FastAPI
- OpenAI GPT-4o API
- pdfplumber
- pandas
- openpyxl
- uvicorn
- nest_asyncio

## 📁 프로젝트 구조

