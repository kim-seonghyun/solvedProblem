# solvedProblem
프로그래머스 소소한 팁

진법 변환
1. let a = Number.toString(진법)
2. parseInt(a,진법)

2차원 배열 선언
1. let arr = new Array(length).fill().map((el)=>{
    return el = new Array()
});

문자열 채우기 -> String.repeat(count)

배열 다듬기(솎아내기) -> Array.filter(조건)

문자열 다루기 -> 정규식, string.match() 익히기

배열에서 최대,최소값 찾기 -> Math.min(...arrayName) //깔끔!

재귀함수 팁
종료조건 ? 결과 : 재귀함수
