# 코딩테스트 연습을 위해 푼 문제들 모음

>1. [[프로그래머스 - 위클리 챌린지] 2주차](https://github.com/JIWON0813/Practice-For-Test/blob/master/%5B%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20-%20%EC%9C%84%ED%81%B4%EB%A6%AC%20%EC%B1%8C%EB%A6%B0%EC%A7%80%5D%202%EC%A3%BC%EC%B0%A8)

<h4>느낀점</h4>
1. for문을 사용하려다 Stream을 사용하면 보기 깔끔할 것 같아서 Stream으로 문제 해결<br>
2. 삼항연산자를 여러개 이어쓰면 한줄로 보일수는 있지만 사실상 실무에서는 보기가 너무 어려워 if return으로 메소드 생성<br>
3. C#이랑 문법이 너무 달라서 구글링 검색을 엄청 많이했지만 덕분에 Stream 연습이 많이됐음<br>
4. 이번 문제로 내부 메소드도 많이 읽어보고 배열, 리스트, 스트림 사용법을 좀 더 많이 익혔다
<br><br><br>

>2. [[프로그래머스 - 위클리 챌린지] 4주차](https://github.com/JIWON0813/Practice-For-Test/blob/master/%5B%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20-%20%EC%9C%84%ED%81%B4%EB%A6%AC%20%EC%B1%8C%EB%A6%B0%EC%A7%80%5D%204%EC%A3%BC%EC%B0%A8)

<h4>느낀점</h4>
1. 문제 자체는 쉬운데 split을 사용하지 않고 해결해보려는데 성능 개선에 비해 소스가 너무 더러워 질까봐 패스(그래도 추후 새로 짜보는 걸로)
2. HashMap에서 get할때 null값에 대해 디폴트 값을 넣어주는 메소드를 찾지못해 직접 구현(추후 더 찾아볼 예정)<br>
<br><br><br>

>3. [[프로그래머스 - 위클리 챌린지] 6주차](https://github.com/JIWON0813/Practice-For-Test/blob/master/%5B%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20-%20%EC%9C%84%ED%81%B4%EB%A6%AC%20%EC%B1%8C%EB%A6%B0%EC%A7%80%5D%206%EC%A3%BC%EC%B0%A8)

<h4>느낀점</h4>
1. 정렬 기준이 많아 compareTo를 사용할 생각으로 모델링<br>
2. 사실상 정렬은 DB에서 order by로 가져오기 때문에 모델 객체에 고정으로 선언하는 경우가 거의 없음<br>
3. 다른 사람의 풀이 중 람다식으로 정렬한 로직이 있는데 참고하기 좋아서 추후 정렬이 필요할 때 람다식으로 해 볼 예정<br>
4. 객체 프로퍼티는 은닉화를 해야하지만 lombok 사용 불가능이라 getter,setter 를 직접 선언해주면 너무 쓸데없는 부분에서 길어져서 해당 부분은 그냥 직접 참조
<br><br><br>

>4. [[카카오] 거리두기 확인하기](https://github.com/JIWON0813/Practice-For-Test/blob/master/%5B%EC%B9%B4%EC%B9%B4%EC%98%A4%5D%20%EA%B1%B0%EB%A6%AC%EB%91%90%EA%B8%B0%20%ED%99%95%EC%9D%B8%ED%95%98%EA%B8%B0)

<h4>느낀점</h4>
1. 그냥 dfs나 bfs를 활용하는게 더 깔끔했을 것 같다<br>
2. 기능별로 메소드를 만들어 어느정도 중복 사용을 제거하려고 보니 오류가 생겨 메소드를 늘림<br>
3. checkBlock과 checkSecondBlock을 하나의 메소드로 합쳐야 하는데 문제를 빨리 푸는데 급해 하나를 늘려버림<br>
4. 사실상 범위가 정해져있고(범위5), 거리두기의 거리도 정해져있어(최대2) 해당 문제를 푸는데는 쉬웠지만 주어진 숫자가 바뀐다면 유지보수하기에는 정말 안좋은 소스
5. 추후 유지보수에 용이한 소스로 변경해야함
<br><br><br>
