## '경우의 수 배우 프로필 - Flex&Filter'

<br>

### • 배포 주소: [https://hover-effect-01.netlify.app/](https://hover-effect-01.netlify.app/)

<br>

#### - 작업 기간: 2021.05

#### - 리팩토링: 2024.01

<br>

### 기술 스택

Development

<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
</p>

Config

<p>
<img src="https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white"/></a>
</p>

Environment

<p>
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
</p>
<br>

### 전체 페이지

<img src="https://github.com/azure0929/hover-effect-01/assets/128226527/2f30ccc2-e9fa-4dd7-bbef-553362563a10" />

<br><br>

### 💻 주요 기능

---

- flex, filter:grayscale

```html
<li>
  <h2>경우연</h2>
  <div class="content">
    <p>
      <strong>“너는 나한테 왕자님일까, 마녀일까?”</strong><br />
      내가 너를 완전히 잊었다는 걸. 절대, 두 번 다시 너 같은 놈을 사랑하는 일은
      없을 거다. 절대.
    </p>
    <div class="sns">
      <a href="#none"><i class="fa fa-facebook"></i></a>
      <a href="#none"><i class="fa fa-instagram"></i></a>
      <a href="#none"><i class="fa fa-television"></i></a>
    </div>
  </div>
</li>
```

```css
.gallery li:hover {
  flex: 3;
  filter: grayscale(0);
}
.content {
  position: absolute;
  bottom: -250px;
  left: 0;
  width: 100%;
  height: 200px;
  background-color: #000;
}
.content:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 50px;
  transform-origin: bottom left;
  transform: rotate(-3deg) scale(1.1);
  background-color: #000;
}
.gallery li:hover .content {
  bottom: 0;
  transition: 0.5s;
  transition-delay: 0.35s;
}
```
