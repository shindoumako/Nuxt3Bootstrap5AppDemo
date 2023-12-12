<template>
<div class="form">
<h1>お問い合わせ</h1>
    <FormKit type="text"
             label="ユーザー名"
	     name="username"
	     help="名前を選んでください"
             value="@myusername"
             prefix-icon="avatarMan"
             inner-class="username-inner"
             validation="required|matches:/^@[a-zA-Z]+$/|length:5"
    >
    </FormKit>
    <FormKit type="select"
	     name="typepreference"
             label="タイプを選択してください"
    />
    <FormKit type="textarea"
	     name="comment"
             label="コメント欄"
    />
</div>
</template>

<style scoped>
.form
  h1{
  position: relative;/*相対位置*/
  padding: 0.5em 0.5em 0.5em 1.5em;/*アイコン分のスペース*/
  line-height: 1.4;/*行高*/
  color: #4e8851;/*文字色*/
  border-top: dotted 1px gray;
  border-bottom: dotted 1px gray;
  background: #fafaf3;
  }
</style>