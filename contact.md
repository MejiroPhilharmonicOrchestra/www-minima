---
layout: page
title:  "お問い合わせ"

<style>
* {
  box-sizing: border-box;
}

input[type=text], input[type=email], input[type=tel], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #aaa;
  border-radius: 4px;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
}

input[type=submit] {
  background-color: #163475;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=submit]:hover {
  background-color: #004a98;
}

.container {
  border: 1px solid #aaa;
  border-radius: 5px;
  padding: 20px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
---

### 各種メディア
* [Facebook](https://www.facebook.com/MPOsince2018/)
* [Twitter](https://twitter.com/MPOsince2018)
* [Peing-質問箱-](https://peing.net/mposince2018)
* [YouTube](https://www.youtube.com/channel/UCtf03ktbP1GfXjeept8sdNA)

### お問い合わせフォーム

<p><span style="color:#ba2636">*&nbsp;必須項目</span> </p>
<script type="text/javascript">
    var submitted = false;
    var currentURL = window.location.href;
</script>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {window.location='/thanks';}"></iframe>
  <form action="https://docs.google.com/forms/d/e/1FAIpQLSfjC7mv9Pj6ybPoUfC3zxa5ZNwM9gAgrmjryu3poRggTxMbyA/formResponse" target="hidden_iframe" onsubmit="submitted=true;">
    <label for="userName">氏名<span style="color:#ba2636">&nbsp;*</span></label>
      <input type="text" id="userName" name="entry.1912182567" placeholder="" required>
    <label for="email">メールアドレス<span style="color:#ba2636">&nbsp;*</span></label>
        <input type="email" id="email" name="entry.150345241" placeholder="mail@example.com" required>
        <p>@mejirophil-orch.comからの受信を許可するよう設定してください。</p><br>
    <label for="category">カテゴリ<span style="color:#ba2636">&nbsp;*</span></label>
        <select id="contactType" name="entry.1654052070" required>
            <option value="">選択してください...</option>
            <option value="演奏会">演奏会</option>
            <option value="入団希望・相談">入団希望・相談</option>
            <option value="演奏依頼">演奏依頼</option>
            <option value="チラシ挟込">チラシ挟込</option>
            <option value="その他">その他</option>
      </select>
    <label for="content">メッセージ<span style="color:#ba2636">&nbsp;*</span></label>
      <textarea id="content" name="entry.780349072" style="height:200px" placeholder="メッセージを入力してください。" required></textarea>
    <input type="submit" value="送信">
</form>
