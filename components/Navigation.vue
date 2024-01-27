<template>
<div class="navigation">
    <ul>
        <li>
            <nuxt-link to="/" >ホーム</nuxt-link>
        </li>
        <li>
            <nuxt-link to="onepage">事前対策</nuxt-link>
        </li>
        <li>
            <nuxt-link to="twopage">災害時の行動
             <ul>
                 <li>
                     <nuxt-link to="#zisin">
                     地震
                     </nuxt-link>
                 </li>
                 <li>
                    <nuxt-link to="#kazan">
                     火山噴火
                    </nuxt-link>
                 </li>
                 <li>
                    <nuxt-link to="#huusuigai">
                     風水害
                    </nuxt-link>
                 </li>
                 <li>
                    <nuxt-link to="#syamen">
                     斜面災害
                    </nuxt-link>
                 </li>
                 <li>
                    <nuxt-link to="#snow">
                     雪氷災害
                    </nuxt-link>
                 </li>
             </ul>
            </nuxt-link>
        </li>
        <li>
            <nuxt-link to="threepage">みんなの声</nuxt-link>
        </li>
        <li>
            <nuxt-link to="fourpage">お問い合わせ</nuxt-link>
        </li>   
    </ul> 
</div>
</template>
<style>
h1{
  position: relative;/*相対位置*/
  padding: 0.5em 0.5em 0.5em 1.5em;/*アイコン分のスペース*/
  line-height: 1.4;/*行高*/
  color: #4e8851;/*文字色*/
  border-top: dotted 1px gray;
  border-bottom: dotted 1px gray;
  background: #fafaf3;
}
body{
   margin: 150px;
   padding: 20px;
   background-color:rgb(238, 248, 237);
   }
</style>
