# K-리그 데이터
[http://www.kleague.com](http://www.kleague.com)에서 제공하는 K-리그 경기 데이터

## 선수 데이터
`player.csv`

	[
		...,
		{"team": "전북", "name": "이동국", "p_id": 19980443},
		...,
	]

## 선수별 경기 기록
`match_records_by_player_id/{선수ID 앞 4자리}/{선수ID}.csv`

	[
		...,
		{ "os": "2", # 오프사이드
		  "goal": "1", # 득점
		  "gk": "0",  # 골킥
		  "comp": "현대오일뱅크 K리그 클래식 2015", # 대회명 
		  "self_goal": "0", # 자살골
		  "sub_sh": "0", # 교체 (후반)
		  "pk_sh": "0", # 페널티킥 (후반)
		  "sub_fh": "0", # 교체 (전반)
		  "pos": "FW", # 포지션
		  "match_num": "175", # 경기번호 
		  "home": true, # 홈/원정
		  "date": "2015-09-12T00:00:00", # 경기 날짜
		  "opponent": "서울", # 상대팀
		  "fc": "1", # 프리킥 (fk)
		  "back_num": "20", # 등번호 
		  "assist": "0", # 도움
		  "team": "전북", # 소속팀
		  "ck": "0", # 코너킥
		  "lose": "0", # 실점
		  "st": "1", # 슈팅
		  "year": "2015", # 년도
		  "yellow": "0", # 경고
		  "p_id": 19980443, # 선수 ID
		  "pk_fh": "0", # 페널티킥 (전반)
		  "red": "0" # 퇴장
		  }
		...,
	]