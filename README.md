# 📖 SQL
## ✅ 특정 월 찾기
- MONTH(컬럼명) = 값
  - 해당 컬럼의 월이 특정 값과 일치하는 데이터만 필터링
  - ex. WHERE MONTH(order_date) = 3 (3월 데이터 조회)
    
## ✅ 특정 문자열 포함 검색(LIKE)
- 컬럼명 LIKE '%문자%'
  - 특정 문자열이 포함된 데이터 검색
  - ex. WHERE address LIKE '%서울%' (주소에 "서울"이 포함된 데이터 조회)
