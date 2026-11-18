# ETF 시세 보고

- 구간: test
- 출처: 한국투자증권 Open API
- 전일 종가는 조회일 이전 최신 유효 영업일 행. 날짜 원천은 stck_bsop_date. 장중 날짜는 조회일과 일별 행 대조값이며 별도 표시.
- 등락 부호는 같은 응답 행의 prdy_vrss_sign 사용. 미확보는 0이 아님.
- 기본 개장 09:00 KST 기준. 특별 개장·휴장 달력 미연동. 조회시각은 체결시각이 아니며 당일 확정 종가를 보장하지 않음.

|code|name|price_krw|change_krw|change_pct|price_date|fetched_at_kst|status|price_type|price_date_source|sign_source|
|---|---|---|---|---|---|---|---|---|---|---|
|0035T0|PLUS 글로벌휴머노이드로봇액티브|15870|+315|+2.03|20261118|2026-11-19T06:51:56+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|442580|PLUS 글로벌HBM반도체|69945|+1080|+1.57|20261118|2026-11-19T06:51:57+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|487230|KODEX 미국AI전력핵심인프라|14255|+245|+1.75|20261118|2026-11-19T06:52:09+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|456600|TIME 글로벌AI인공지능액티브|42450|−580|−1.35|20261118|2026-11-19T06:52:14+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|478150|TIME 글로벌우주테크&방산액티브|16540|−30|−0.18|20261118|2026-11-19T06:52:16+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|357870|TIGER CD금리투자KIS(합성)|58395|+10|+0.02|20261118|2026-11-19T06:52:27+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|381180|TIGER 미국필라델피아반도체나스닥|33965|+560|+1.68|20261118|2026-11-19T06:52:32+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|360750|TIGER 미국S&P500|24305|−250|−1.02|20261118|2026-11-19T06:52:33+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
|379810|KODEX 미국나스닥100|23895|−145|−0.60|20261118|2026-11-19T06:52:35+09:00|observed|전일 종가(직전 거래일 기준)|stck_bsop_date|prdy_vrss_sign|
