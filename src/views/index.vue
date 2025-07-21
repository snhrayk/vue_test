<template>
  <main>
    <div class="mainVisual"></div>
    <div class="wrapper">
      <div class="about">
        <h2>About</h2>
        <p class="aboutName">Xxxxx Ashley</p>
        <div class="aboutAddress">
          <p>2th Floor xxxxx Building x-x-x Nishiazabu, Minato-ku, Tokyo 106-0031 Japan</p>
          <p>tel: 000-0000-0000</p>
          <p>url: www.xxxxxx.jp</p>
          <p>mail: xxx@xxxxxx.jp</p>
        </div>
        <p class="aboutText">
          プロフィールテキストテキストテキストテキストテキストテキストテキストテキストテキストストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト
        </p>
      </div>
      <div class="works">
        <h2>Works</h2>
        <ul>
          <li><img src="../assets/works1.jpg" alt="" /></li>
          <li><img src="../assets/works2.jpg" alt="" /></li>
          <li><img src="../assets/works3.jpg" alt="" /></li>
          <li><img src="../assets/works4.jpg" alt="" /></li>
          <li><img src="../assets/works5.jpg" alt="" /></li>
          <li><img src="../assets/works6.jpg" alt="" /></li>
        </ul>
      </div>
      <div class="news">
        <h2>News</h2>
        <ul>
          <li>
            <span>2020.XX.XX</span>デザイン雑誌「ＸＸＸＸＸＸ Vol.11』に掲載していただきました。
          </li>
          <li>
            <span>2020.XX.XX</span>ＸＸ月ＸＸ日から写真集「ＸＸＸＸＸＸＸ」の販売を開始します。
          </li>
          <li>
            <span>2019.XX.XX</span
            >【イベント開催のお知らせ】テキストテキストテキストテキストテキストテキストテキスト
          </li>
          <li>
            <span>2019.XX.XX</span>デザイン雑誌「ＸＸＸＸＸＸ Vol.10』に掲載していただきました。
          </li>
          <li>
            <span>2019.XX.XX</span
            >【個展開催のお知らせ】テキストテキストテキストテキストテキストテキストテキスト
          </li>
        </ul>
      </div>
      <div class="contact">
        <h2>Contact</h2>
        <form action="#" method="post">
          <div>
            <label for="">NAME</label>
            <input type="text" />
          </div>
          <div>
            <label for="">E-mail</label>
            <input type="email" />
          </div>
          <div>
            <label for="">MESSAGE</label>
            <textarea name="message"></textarea>
          </div>
          <div>
            <input type="submit" value="送信" />
          </div>
        </form>
      </div>
    </div>
  </main>
</template>
<style scoped>
.mainVisual {
  width: 100%;
  height: 42rem;
  background: url('../assets/mainvisual-pc.jpg');
  background-size: cover;
  background-position: center;
}
.wrapper {
  width: 960px;
  padding: 0 4%;
  margin: 0 auto;
}
.about {
  font-size: 1.4rem;
  padding: 8rem 0 13rem;
}
h2 {
  font-size: 2.4rem;
  margin-bottom: 6.4rem;
  text-align: center;
}
.aboutName,
.aboutAddress,
.aboutText {
  margin-bottom: 3rem;
}
.works {
  padding: 0 0 15rem;
}
.works ul {
  display: flex;
  flex-wrap: wrap;
  column-gap: 3.2rem;
  row-gap: 2.4rem;
}
.works li {
  width: calc((100% - 6.4rem) / 3);
  list-style: none;
}
.works li img {
  width: 100%;
  height: auto;
  display: block;
  object-fit: cover;
}
.news,
.contact {
  padding: 0 0 13rem;
}
.news ul li {
  font-size: 1.4rem;
  padding: 1.6rem;
  border-top: 1px solid #c8c8c8;
}
.news ul li:last-child {
  border-bottom: 1px solid #c8c8c8;
}
.news ul li span {
  margin-right: 8rem;
}
.contact form div {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  margin-bottom: 1rem;
  font-size: 1.4rem;
}
.contact form div label {
  width: 15%;
}
.contact form div input,
.contact form div textarea {
  width: 85%;
  border: 1px solid #c8c8c8;
  padding: 0.4rem 0.4rem;
}
.contact form div textarea {
  height: 15rem;
}
.contact form div input[type='submit'] {
  width: auto;
  padding: 1.6rem 8.8rem;
  margin-top: 2rem;
  background-color: #24292e;
  border: none;
  color: #fff;
  cursor: pointer;
}
</style>
