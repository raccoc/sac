<style scoped>
@font-face {
  font-family: 'Since';
  src: url('../assets/Since-Regular.otf');
}
@font-face {
  font-family: 'Rondo';
  src: url('../assets/Ronde-B_square.otf');
}

@media screen and (max-width:480px) { 
  #main-title {
    position: absolute;
    top: 35%;
    left: 10%;
  }
  h1 {
    font-family: 'Since';
    color:#FFEA00;
    font-size: 5rem;
    line-height: 1;
    margin: 0;
    padding: 0;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
  #main-title span {
    font-family: 'Rondo';
    color:#FFEA00;
    font-size: 1rem;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
  div[id^="group"] {
    padding: 36px;
    font-size: 1rem;
    text-align: left;
  }
  div[id^="group"] b.sub-title {
    font-size: 42px;
  }
  #top-area {
    /** photo from https://www.photo-ac.com/profile/43626" */
    background: url(../assets/main-bg.jpg) no-repeat;
    background-size: cover;
    background-position: 70% 50%;
    min-height: 500px;
    position: relative;
  }
}
@media screen and (min-width:480px) { 
  #top-area {
    /** photo from https://www.photo-ac.com/profile/43626" */
    background: url(../assets/main-bg.jpg) no-repeat;
    background-size: cover;
    background-position: 70% 50%;
    min-height: 500px;
    position: relative;
  }
  #main-title {
    position: absolute;
    top: 20%;
    left: 10%;
  }
  h1 {
    font-family: 'Since';
    color:#FFEA00;
    font-size: 9rem;
    line-height: 1;
    margin: 0;
    padding: 0;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
  #main-title span {
    font-family: 'Rondo';
    color:#FFEA00;
    font-size: 1.5rem;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
}
@media screen and (min-width:1200px) { 
  #top-area {
    /** photo from https://www.photo-ac.com/profile/43626" */
    background: url(../assets/main-bg.jpg) no-repeat;
    background-size: cover;
    background-position: 70% 22%;
    min-height: 700px;
    position: relative;
  }
  div[id^="group"] {
    max-width: 1000px;  
  }

}
div[id^="group"] {
  padding: 36px 36px 24px 36px;
  font-size: 1rem;
  text-align: left;
  display: inline-block;
  width: 100%;
}
div[id^="group"] p {
  margin: 0;
  font-size: 0.8rem;
}
div[id^="group"] b.sub-title {
  font-size: 1.8rem;
  color:#EF5350
}
div[id^="group"] table {
  font-size: 0.7rem;
}
#wrapper {
  text-align: center;
  max-width: 600px;
  margin: 0 auto;
  padding: 0;
}
</style>

<template>
    <div id="main">
        <div id="top-area">
            <div id="main-title">
                <h1>SAC</h1>
                <span>千葉スノーボードクラブ</span>
            </div>
        </div>
        <div id="wrapper">
          <div id="group-1">
              <h2 id="about"><b class="sub-title">SAC</b>  <span style="font-size: 0.8rem">とは</span></h2>
              <p>
                スノーボードが大好き！うまくなりたい！という気持ちの強い人たちの集まりです。<br/>
                スノボ の社会人サークルもたくさんありますが、それらサークルとちょっと違うところは<br/>
                <br/>
                <b>・千葉県スキー連盟スノーボード委員会と連携し、技術レベルアップ講習会やバッジテストに参加できること<br/>
                ・公認指導員・準指導員が多数在籍していること<br/>
                ・指導者養成講習、準指導員検定会、指導員検定会の参加をサポートできること<br/></b>
                <br/>
                など  、より技術力を高めたい人向けのサポートが充実してるところです！<br/>
                <br/>
                シーズン中はがっつり滑って夜は楽しいお酒を飲み、シーズンオフは各々スケボーしたり飲んだり野球観戦したり飲んだり、、と年齢層もバラバラの中みな仲良く楽しく活動しています。参加もすべて自由、強制はありません。<br/>
                もっとスノボ が上手くなりたい人、上手い人と一緒に滑りたい人、とにかくお酒が飲みたい人、など興味を持った方はぜひご連絡ください！（ちなみに千葉在住じゃない人もいっぱいいます笑）
            </p>
            <img src="../assets/takatue.jpg" width="100%" class="pt-4" />
          </div>
          <div id="group-2">
              <h2 id="schedule" style="margin-bottom: 12px"><b class="sub-title">活動スケジュール</b></h2>
              <p class="pb-3">
                参考までに２０２０年の講習会などのスケジュールを一部抜粋して載せます。<br/>
                これ以外にも遊びでほぼ毎週誰かしら滑りに行ってますし、そもそも検定や講習に出ないメンバーもたくさんいますので安心してくださいね！
                さらに詳細を知りたい方は<a href="http://sac-office.jp/event/kyoiku-snowboard/">こちら</a>へどうぞ。
              </p>              
              <table class="table table-bordered">
                <thead class="thead-light">
                  <th>事業名</th>
                  <th>会期</th>
                  <th>会場</th>
                </thead>
                <tr>
                  <td>指導者研修会</td>
                  <td>2020/1/11</td>
                  <td>さかえ倶楽部</td>
                </tr>
                <tr>
                  <td>準指導員検定会(理論/実技)</td>
                  <td>2020/3/21</td>
                  <td>湯の丸高原</td>
                </tr>
                <tr>
                  <td>レベルアップ講習会・第１会場</td>
                  <td>2020/1/12~13</td>
                  <td>さかえ倶楽部</td>
                </tr>
                <tr>
                  <td>レベルアップ講習会・第２会場</td>
                  <td>2020/2/15~16</td>
                  <td>会津たかつえ</td>
                </tr>
                <tr>
                  <td>レベルアップ講習会・第３会場</td>
                  <td>2020/3/20~21</td>
                  <td>湯の丸高原</td>
                </tr>
              </table>
          </div>
          <div id="group-3">
            <div style="margin-bottom: 12px">
              <h2 id="contact"><b class="sub-title">Contact US!</b></h2>
              <p>千葉スノーボードクラブはいつでも一緒に楽しく滑れるメンバーを募集しています！<br />
              興味がある方はFacebookにお気軽にメッセージ送ってください！</p>
            </div>
            <div class="fb-page" data-href="https://www.facebook.com/CHIBASNOWBORD/" data-tabs="timeline,messages" data-width="500px" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="false">
              <blockquote cite="https://www.facebook.com/CHIBASNOWBORD/" class="fb-xfbml-parse-ignore">
                <a href="https://www.facebook.com/CHIBASNOWBORD/">千葉スノーボードクラブ</a>
              </blockquote>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "main-component"
}
</script>