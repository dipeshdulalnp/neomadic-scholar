+++
author = "Anonymous"
title = "Our Team"
date = "2026-03-05"
description = "Our team is a complete package of expert counselling, test preparations, and administrative handling - the team you can trust."
+++


<link href="https://fonts.googleapis.com/css?family=Raleway:400,200,300,800" rel="stylesheet" />
<link href="https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css" rel="stylesheet" />

<style>
.matsusan-profile-container {
  display: flex;
  flex-wrap: wrap;       /* 幅が足りない場合は自動で折り返し */
  justify-content: center; /* 中央寄せ */
  gap: 20px;            /* カード間の隙間 */
  padding: 20px;
  background: #f4f4f4;  /* 背景色はお好みで */
}

/* カードのベーススタイル */
figure.snip0056 {
  font-family: 'Raleway', Arial, sans-serif;
  position: relative;
  overflow: hidden;
  margin: 0;            /* gapで制御するため0に調整 */
  min-width: 350px;
  max-width: 440px;     /* 横並びしやすいよう微調整 */
  width: 100%;
  background: #ffffff;
  color: #000000;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* 浮き出し効果（任意） */
}

figure.snip0056 * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

figure.snip0056 > img {
  width: 50%;
  border-radius: 50%;
  border: 4px solid #ffffff;
  -webkit-transition: all 0.35s ease-in-out;
  transition: all 0.35s ease-in-out;
  -webkit-transform: scale(1.6);
  transform: scale(1.6);
  position: relative;
  float: right;
  right: -15%;
  z-index: 1;
}

figure.snip0056 figcaption {
  padding: 20px 30px 20px 20px;
  position: absolute;
  left: 0;
  width: 50%;
}

figure.snip0056 figcaption h2,
figure.snip0056 figcaption p {
  margin: 0;
  text-align: left;
  padding: 10px 0;
  width: 100%;
}

figure.snip0056 figcaption h2 {
  font-size: 1.3em;
  font-weight: 300;
  text-transform: uppercase;
  border-bottom: 1px solid rgba(0, 0, 0, 0.2);
}

figure.snip0056 figcaption h2 span {
  font-weight: 800;
}

figure.snip0056 figcaption p {
  font-size: 0.9em;
  opacity: 0.8;
}

figure.snip0056 figcaption .icons {
  width: 100%;
  text-align: left;
}

figure.snip0056 figcaption .icons i {
  font-size: 26px;
  padding: 5px;
  color: #000000;
}

figure.snip0056 figcaption a {
  opacity: 0.3;
  -webkit-transition: opacity 0.35s;
  transition: opacity 0.35s;
}

figure.snip0056 figcaption a:hover {
  opacity: 0.8;
}

figure.snip0056 .position {
  width: 100%;
  text-align: left;
  padding: 15px 30px;
  font-size: 0.9em;
  opacity: 1;
  font-style: italic;
  color: #ffffff;
  background: #000000;
  clear: both;
}

/* カラーバリエーション */
figure.snip0056.blue .position { background: #20638f; }
figure.snip0056.red .position { background: #962d22; }
figure.snip0056.yellow .position { background: #bf6516; }

figure.snip0056:hover > img,
figure.snip0056.hover > img {
  right: -12%;
}
</style>

<div class="matsusan-profile-container">


  <figure class="snip0056 yellow">
    <figcaption>
      <h2>Maheshwor <span>Bhattarai</span></h2>
      <p>Managing Director</p>
      <div class="icons">
        <a href="#"><i class="ion-ios-home"></i></a>
        <a href="#"><i class="ion-ios-email"></i></a>
        <a href="#"><i class="ion-ios-telephone"></i></a>
      </div>
    </figcaption>
    <img src="/images/hero-image.png" alt="" />
    <div class="position">Certified IELTS Instructor</div>
  </figure>

  <figure class="snip0056 blue">
    <figcaption>
      <h2>Firstname <span>Lastname</span></h2>
      <p>Certified Counselor</p>
      <div class="icons">
        <a href="#"><i class="ion-ios-home"></i></a>
        <a href="#"><i class="ion-ios-email"></i></a>
        <a href="#"><i class="ion-ios-telephone"></i></a>
      </div>
    </figcaption>
    <img src="/images/hero-image.png" alt="" />
    <div class="position">Germany and Nordic Countries</div>
  </figure>

</div>