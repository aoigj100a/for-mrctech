<template>
  <body>
    <div class="header">
      <nav>
        <h1>
          <a href="#"><img src="https://fakeimg.pl/138x34/" /></a>
        </h1>
        <ul class="user-icon">
          <li>
            <a href="#"><i class="fa fa-camera">放大鏡</i></a>
          </li>
          <li>
            <a href="#"
              ><i class="fa fa-user-circle" aria-hidden="true">頭像</i></a
            >
          </li>
        </ul>
      </nav>
      <div class="tag-list">
        <a href="#">
          <div class="tag active">All</div>
        </a>
        <a href="#">
          <div class="tag">Music</div>
        </a>
        <a href="#">
          <div class="tag">One Piece</div>
        </a>
        <a href="#">
          <div class="tag">Anime</div>
        </a>
        <a href="#">
          <div class="tag">Love songs</div>
        </a>
      </div>
    </div>
    
    <div class="tool-bar">
      <ul class="tool-bar-list">
        <a href="#">
          <li class="tool">
            <img src="https://fakeimg.pl/25x25/" /><span>Home</span>
          </li>
        </a>
        <a href="#">
          <li class="tool">
            <img src="https://fakeimg.pl/25x25/" /><span>Trending</span>
          </li>
        </a>
        <a href="#">
          <li class="tool">
            <img src="https://fakeimg.pl/25x25/" /><span>Subscriptions</span>
          </li>
        </a>
        <a href="#">
          <li class="tool">
            <img src="https://fakeimg.pl/25x25/" /><span>Library</span>
          </li>
        </a>
      </ul>
    </div>
  </body>
</template>

<style lang="css">
@charset "UTF-8";
/* 載入字型 */
@import url("https://fonts.googleapis.com/css?family=Noto+Sans+TC:400,700&display=swap&subset=chinese-traditional");
*,
*::before,
*::after {
  box-sizing: border-box;
}

html,
body {
  width: 100%;
  height: 100%;
}

body {
  background-color: #f6f7f8;
  font-family: "Noto Sans TC", sans-serif;
  /* 設定字型 */
  font-size: 1rem;
  line-height: 1.4;
  margin: 0;
}

h1,
h2,
h3,
h4,
h5 {
  line-height: 0.9;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}

p {
  margin: 0;
}

ul,
li {
  list-style-type: none;
  /* 拿掉前方圈圈 */
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
  /* 拿掉底線 */
}

img {
  max-width: 100%;
  /*不使用width:100% 是因避免圖片解析度不好，隨父元素被放大時會糊掉*/
  height: auto;
}

.p-1 {
  padding: 0 8px;
}

.p-2 {
  padding: 16px;
}

.header {
  position: fixed;
  width: 100%;
}

nav {
  padding-top: 10px;
  padding-bottom: 10px;
  display: flex;
  justify-content: space-between;
  background-color: #fff;
  border-bottom: 2px solid #777;
}
nav h1 a img {
  margin-left: 8px;
  display: block;
  /* width: 138px;
  height: 34px; */
  /* background: url(../../static/for-mrctech切版/img/icon.jpg); */
  text-indent: 101%;
  white-space: nowrap;
  overflow: hidden;
  background-repeat: no-repeat;
}
nav ul {
  margin-right: 8px;
}
nav .user-icon li {
  display: inline;
  line-height: 34px;
  color: Tomato;
}

.tag-list {
  display: flex;
  padding: 8px;
  border-bottom: 1px solid #ccc;
  background: #fff;
}
.tag-list .tag {
  border: 1px solid #ddd;
  border-radius: 15px;
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 5px;
  padding-bottom: 5px;
  margin-left: 3px;
  margin-right: 3px;
  background: #eee;
  color: black;
}
.tag-list .active {
  background: #555;
  color: #fff;
}

.tool-bar {
  position: fixed;
  bottom: 0;
  width: 100%;
}
.tool-bar .tool-bar-list {
  display: flex;
  justify-content: space-between;
  background: #fff;
}
.tool-bar .tool-bar-list a {
  width: 100%;
  display: block;
  margin: 0 auto;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 10px;
  padding-right: 10px;
}
.tool-bar .tool-bar-list a:hover {
  background: #ccc;
}
.tool-bar .tool-bar-list .tool img {
  display: block;
  margin: 0 auto;
}
.tool-bar .tool-bar-list .tool span {
  display: block;
  margin: 0 auto;
  text-align: center;
  color: black;
}

.video-warp {
  padding-top: 100px;
  padding-bottom: 100px;
}

.card-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.card-list .card {
  padding: 5px;
}
.card-list .card-info {
  display: flex;
  width: 280px;
  justify-content: center;
  align-items: center;
}
.card-list .card-info .icon img {
  display: inline-block;
  width: 100px;
}
.card-list .card-info .title h2 {
  font-size: 16px;
  font-weight: 500;
}
.card-list .card-info .title p {
  font-size: 14px;
  color: #aaa;
}

/*# sourceMappingURL=all.css.map */
</style>

<script>
export default {};
</script>
