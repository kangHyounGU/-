# Mobile-Project
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>강현구의 자기 소개서</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<style>
@charset "UTF-8";
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR&display=swap');

body {
    background-color: #228dff;
    color: #2f2f2f;
    font-family: 'Noto Sans KR', sans-serif;
    font-size: 16px;
}

section {
    background-color: white;
    border-radius: 20px;
    padding: 20px;
    margin-bottom: 30px;
    margin-left: 7%;
    margin-right: 10%;
    width: 80%;
}

.wrapper {
    width: 85%;
    margin: 20px auto;
}

h1 {
    display: none;
}

h2, h3 {
    font-family: sans-serif;
}

h2 {
    margin: 0 0 10px 0;
    text-transform: uppercase;
    font-size: 18px;
}

#my_info h2 {
    display: on;
}

#my_info img {
    width: 100px;
    height: auto;
    border-radius: 50px;
    margin-right: 40px;
} 

table {
    display: inline-block;
    border-collapse: collapse;
    border-spacing: 0;
    vertical-align: top;
}

th {
    text-align: left;
    padding-right: 20px;
}

th, td {
    font-size: 12px;
}

#myname th {
    display: none;
}

#myname td {
    display: block;
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 10px;
}

a {
    color: inherit;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
    color: gold;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin-bottom: 4px;
}

ul li::before {
    display: inline-block;
    width: 20px;
    height: 20px;
    vertical-align: middle;
    margin-right: 10px;
}

ul li:nth-child(1)::before {
    content: url('../images/ico_mobile.png');
}
ul li:nth-child(2)::before {
    content: url('../images/ico_email.png');
}
ul li:nth-child(3)::before {
    content: url('../images/ico_facebook.png');
}
ul li:nth-child(4)::before {
    content: url('../images/ico_blog.png');
}

#skill ol {
    list-style: none;
    padding: 0;
}

#skill li {
    display: inline-block;
    background-color: gold;
    padding: 5px 10px;
    border-radius: 32px;
    margin: 0 8px 8px 0;
}

#skill li::before {
    content: "#";
}

#project ol {
    list-style: none;
    padding: 0;
}

#project li {
    border-bottom: 1px solid #ddd;
    padding-bottom: 20px;
}

#project li:last-child {
    border-bottom: none;
}

#project video {
    width: 70%;
}

#project a {
    color: gold;
    display: inline-block;
    border-radius: 4px;
    padding: 2px 8px 2px 0;
}

#project a:hover {
    background-color: #2f2f2f;
    text-decoration: none;
    padding: 2px 8px;
    transition: padding 0.2s;
}

</style>
<body>
    <div class="wrapper">
        <h1>KangHyeongu's Resume</h1> 
    
        <section id="my_info">
            <h2>My info</h2> 
            <img src="images/profile.jpg" alt="강현구의 얼굴 사진" />
            <table>
                <tbody>
                    <tr id="myname">
                        <th>이름</th>
                        <td>Kang Hyeongu</td>
                        <td>강현구</td>
                    </tr>
                    <tr>
                        <th>직업</th>
                        <td>개발자</td>
                    </tr>
                    <tr>
                        <th>나이</th>
                        <td>23</td>
                    </tr>
                    <tr>
                        <th>거주지</th>
                        <td>부산</td>
                    </tr>
                </tbody>
            </table>
        </section>
            
        <section id=""about>
            <h2>About</h2>
            <p>현재 동의과학대학교 컴퓨터 소프트웨어 학과를 재학하는 2학년 입니다.</p>
            <p>취미 생활로는 재미있는 것을 찾아서 해보는 것으로 마술, 클라이밍등을 보고 재미있어서 하고 있습니다.</p>
        </section>
        
        <section id="contact">
            <h2>Contact</h2>
            <ul>
                <li><a href="tel:01000000000">010-0000-0000</a></li>
                <li><a href="mailto:mail@mail.com" target="_blank">mail@mail.com</a></li>
                <li><a href="https://google.com" target="_blank"></a>google@google.com</li>
                <li><a href="https://naver.com" target="_blank"></a>naver@naver.com</li>
            </ul>  
        </section>
        
        <section id="skill">
            <h2>Skills</h2>
            <ol>
                <li>HTML</li>
                <li>Python</li>
                <li>Java</li>
                <li>Javascript</li>
                <li>PHP</li>
            </ol>
        </section>
        
        <section id="project">
            <h2>Projects</h2>
            <ol>
                <li>
                    <h3>JSP 웹 서버 만들기 - 쇼핑몰 페이지 만들기</h3>
                    <video src="movie.mp4" controls></video>
                    <p>2학년 1학기 웹프로그래밍 수업 중 기말과제로 팀프로젝트를 진행하였습니다. 팀프로젝트의 주제는 인터넷 쇼핑몰이였으며 저는 프론트 엔드, 백엔드
                        를 하였고 페이지 제작으로는 다음과 같은 페이지들을 제작하였습니다. 메인 화면, 상세 페이지, 상품 목록 등의 프론트엔드 및 백엔드 작업
                        제작하면서 힘든점도 많았고 코드를 찾아서 다양한 방식들이 있다는 것을 알게 되었지만 한 편으로는 그대로 사용만 하면 되는 것이 아니라는 것을 프로젝트를 통해서 알게 되었습니다.<br>
                    <a href="https://github.com/kangHyounGU/JspProject" target="_blank">github</a>
                </li>
            </ol>    
        </section>
    </div>
    

</body>
</html>

