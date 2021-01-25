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

정규식
/(\d+)(S|D|T)(\*|#)?/g -> ?는 앞의 표현식이 포함되거나 포함되지 않은경우

// string변수를 정규식에 넣으려면 RegExp 객체를 사용하면 된다
ex) let regExp = new RegExp('변수','플래그');
특정 문자만 남기고 싶으면 replace(정규식, "") 요렇게 하면 된다

max 초기값은 무조건 -Infinity 이다!!!!!!!!

// array.reduce() 사용 주의, initialValue를 사용하지않으면 index는 1부터 탐색한다. 다른 배열과 함께 사용할때는 오류가 일어날수도 있기때문에 initialValue는 0으로 설정해주자
