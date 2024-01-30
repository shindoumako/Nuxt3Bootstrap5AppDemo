

<template>
<div class="color">
        <h2>「未然に防ぐ、備える、守る：自然災害のための行動ガイド」</h2>
        <div class="img">
        <img src="~/assets/R.jpg" alt="top"></div>
        <div class="article">
            <h3>・自然災害の対策</h3>
            <h6>自然災害は急に起こります。だからこそ常日ごろから対策を取っておくべきなのです。<br>
            今回はいざ対策を取ろうと思っても何から始めたらよいのかわからない人のためにまとめています。</h6>
            <h3>・自然災害時の行動</h3>
            <h6>自然災害時どのような行動をするべきかわかりますか？<br>
            いざ聞かれるとわからない人が多いのではないでしょうか。そんな方に今回いざ災害にあった時の行動の仕方をまとめています。</h6>
            <h3>・改善点</h3>
            <h6>実際経験した方々の体験談や改善してほしいところを自由に記載することのできるページです。<br>
            皆さんの声を書いていただけたら嬉しいです。</h6>
        </div>   
        <p><font color=#c0c0c0;>※本ページは自然災害で事前に対策できること、実際起こってしまった時の行動、<br>
        また、実際被害にあわれた方の体験談や改善してほしい点を自由に書くことのできるサイトです。</font></p>
        
</div> 
</template>

<style scoped>
.article{
    margin: 8px;
}
.color
  h2 {
  position: relative;
  color: #158b2b;
  font-size: 24px;
  padding: 10px 0;
  text-align: center;
  margin: 1.5em 0;}
  h2:before {
  content: "";
  position: absolute;
  top: -20px;
  left: 50%;
  width: 160px;
  height: 86px;
  border-radius: 50%;
  border: 4px solid #51e665;
  border-left-color: transparent;
  border-right-color: transparent;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  }
  h3 {
  color:#ff4500 ;
  text-align: center;
  }
  h6 {
    position: relative;
    padding: 1rem;
    font-size: 16px;
    text-align: center;
}

h6::before,
h6::after {
    position: absolute;
    width: 20px;
    height: 30px;
    content: '';
}

h6::before {
    border-left: dotted 3px;
    border-top: dotted 3px;
    top: 0;
    left: 0;
}

h6::after {
    border-right: dotted 3px;
    border-bottom: dotted 3px;
    right: 0;
}
p{
text-align: center;
}
.img{
   width: auto;
   height: 300px;
   text-align: center;
}
</style>
