<template>
  <div>
    <section class="section">
      <div class="container">
        <div class="content is-medium">
          <div id="privacy-policy">
            <div class="content">
              <h1 class="title">当サイトに掲載されている広告について</h1>
              <p>
                当サイトでは、第三者配信の広告サービス（
                <a href="http://www.google.com/adsense/start/">アドセンス</a>、
                <a href="https://affiliate.amazon.co.jp/">Amazonアソシエイト</a>、を利用しています。
                このような広告配信事業者は、ユーザーの興味に応じた商品やサービスの広告を表示するため、当サイトや他サイトへのアクセスに関する情報
                『Cookie』(氏名、住所、メール アドレス、電話番号は含まれません) を使用することがあります。
                またGoogleアドセンスに関して、このプロセスの詳細やこのような情報が広告配信事業者に使用されないようにする方法については、
                <a href="http://www.google.co.jp/policies/technologies/ads/">こちら</a>をクリックしてください。
              </p>
              <h1 class="title">
                当サイトが使用しているアクセス解析ツールについて
              </h1>
              <p>
                当サイトでは、Googleによるアクセス解析ツール「Googleアナリティクス」を利用しています。
                このGoogleアナリティクスはトラフィックデータの収集のためにCookieを使用しています。
                このトラフィックデータは匿名で収集されており、個人を特定するものではありません。
                この機能はCookieを無効にすることで収集を拒否することが出来ますので、お使いのブラウザの設定をご確認ください。
                この規約に関して、詳しくは
                <a href="http://www.google.com/analytics/terms/jp.html">こちら</a>、または
                <a href="https://www.google.com/intl/ja/policies/privacy/partners/">こちら</a>をクリックしてください。
              </p>
              <h1 class="title">当サイトへのコメントについて</h1>
              <p>
                当サイトでは、スパム・荒らしへの対応として、コメントの際に使用されたIPアドレスを記録しています。
                これはブログの標準機能としてサポートされている機能で、スパム・荒らしへの対応以外にこのIPアドレスを使用することはありません。
                また、メールアドレスとURLの入力に関しては、任意となっております。
                全てのコメントは管理人である、たかふさが事前にその内容を確認し、承認した上での掲載となりますことをあらかじめご了承下さい。
                加えて、次の各号に掲げる内容を含むコメントは管理人の裁量によって承認せず、削除する事があります。
                特定の自然人または法人を誹謗し、中傷するもの。 極度にわいせつな内容を含むもの。
                禁制品の取引に関するものや、他者を害する行為の依頼など、法律によって禁止されている物品、行為の依頼や斡旋などに関するもの。
                その他、公序良俗に反し、または管理人によって承認すべきでないと認められるもの。
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'PrivacyPolicy',
});
</script>

<style lang="stylus" scoped>
.font-awesome-icon {
  margin-right: 8px;
}

a {
  color: #4a4a4a;
}
</style>
