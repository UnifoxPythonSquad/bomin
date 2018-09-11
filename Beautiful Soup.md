Beautiful Soup
==============
묘듈 사용 명령어
---------------
>
## 헤더를 추가하고 html 파일을 읽어줍니다.
## url = "http://www.google.co.kr/"
## req = Request(url)
## req.add_header('User-Agent', 'Mozilla/5.0')
## html = urlopen(req).read()

>
## string이 있는 title태그를 모두 찾습니다.
## soup.title.find_all(string=True)
## soup.title(string=True)

>
## 검색이 가능!!
## soup.body.b # body 태그 아래의 첫번째 b 태그
## soup.a # 첫번째 a 태그

>
## 해당 조건에 맞는 파일을 가져옴 <div>
## with open("example.html") as fp:
##     soup = BeautifulSoup(fp, 'html.parser')
##    all_divs = soup.find_all("div")
## print(all_divs)

>
## 태그해서 가져오기 <p>
## with open("example.html") as fp:
##     soup = BeautifulSoup(fp, 'html.parser')
##     all_ps = soup.find_all("p")
##     print(all_ps)
