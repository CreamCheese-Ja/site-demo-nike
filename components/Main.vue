<template>
  <main class="o-layout-main">
    <section class="sectionArea">
      <a href="" class="link">
        <TopImage
          :image-src="require('../assets/images/nike-top-2-1.jpg')"
          image-alt="Top画像1"
        />
        <div class="content">
          <div class="textArea">
            <h1 class="title">ひとりじゃみれない、夢に向かって。</h1>
            <p class="message">
              駅伝ランナーたちが新年に駆け抜ける、山岳風景からインスピレーションを受けたランニングコレクション「EKIDEN
              PACK」。今作は、<br />
              駅伝レースが始まる早朝の朝日とレースのエネルギーを燃えるようなカラーで表現。さらに、<br />
              東京のスクランブル交差点などの街並みをイメージしたダズルカモ柄を施している。さあ、<br />
              新しい幕を駆け上がろう。<br />
              12月1日より日本先行で順次発売。
            </p>
          </div>
          <div class="buttonArea">
            <BasicButton label="メンズを見る" />
            <BasicButton label="ウィメンズを見る" />
            <BasicButton label="キッズを見る" />
            <BasicLink label="近くの店舗を探す" />
            <BasicLink label="本プロモーション規約" />
          </div>
        </div>
      </a>
    </section>
    <section class="sectionArea">
      <a href="" class="link">
        <TopImage
          :image-src="require('../assets/images/nike-top-2-2.jpg')"
          image-alt="Top画像2"
        />
        <div class="content">
          <div class="textArea">
            <p class="message">
              レオパード柄のアイテムを大胆に着こなして、力強いスタイリングに挑戦
            </p>
          </div>
          <div class="buttonArea">
            <BasicButton label="コレクションを見る" />
          </div>
        </div>
      </a>
    </section>
    <section class="sectionArea">
      <a href="" class="link">
        <TopImage
          :image-src="require('../assets/images/nike-top-2-3.jpg')"
          image-alt="Top画像3"
        />
        <div class="content">
          <div class="textArea">
            <h1 class="title">JORDAN x PARIS SAINT-GERMAIN コレクション</h1>
            <p class="message">
              高級感と伝説の風格を備えるジョーダンブランドとパリ・サンジェルマン。<br />
              一味違うカラーと斬新なシルエットで、コラボレーションを新たな次元へ。
            </p>
          </div>
          <div class="buttonArea">
            <BasicButton label="商品を見る" />
          </div>
        </div>
      </a>
    </section>
    <section class="sectionArea">
      <a href="" class="link -positionRel">
        <TopImage
          :image-src="require('../assets/images/nike-top-2.jpg')"
          image-alt="Top画像4"
        />
        <div class="content -positionAbsLeft">
          <div class="textArea">
            <h1 class="title -white">冬の運動に最適な最新コレクション。</h1>
          </div>
          <div class="buttonArea -positionAbsLeft">
            <BasicButton label="コレクションを見る" anotherClassName="-white" />
          </div>
        </div>
      </a>
    </section>
  </main>
</template>
