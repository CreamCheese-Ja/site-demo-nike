<template>
  <header class="o-layout-header">
    <div class="headerTop">
      <div>
        <a href="">
          <img
            src="../assets/images/jordan.svg"
            alt="jordan-logo"
            class="c-jordan-logo"
          />
        </a>
      </div>
      <ul class="menu">
        <li class="item"><a href="" class="link">ヘルプ</a></li>
        <li class="item">|</li>
        <li class="item"><a href="" class="link">ここから始めよう</a></li>
        <li class="item">|</li>
        <li class="item"><a href="" class="link">ログイン</a></li>
      </ul>
    </div>
    <div class="headerMain">
      <SiteLogo />
      <ul class="menu">
        <li class="item"><a href="" class="link">NEW RELEASES</a></li>
        <li class="item"><a href="" class="link">MEN</a></li>
        <li class="item"><a href="" class="link">WOMEN</a></li>
        <li class="item"><a href="" class="link">KIDS</a></li>
        <li class="item"><a href="" class="link">CUSTOMIZE</a></li>
        <li class="item"><a href="" class="link">SALE</a></li>
        <li class="item"><a href="" class="link">COLLECTIONS</a></li>
      </ul>
      <div class="operationArea">
        <SearchBar />
        <div class="iconArea">
          <HeaderIcon
            :image-src="require('../assets/images/icons/favorite.svg')"
            image-alt="お気に入り"
          />
          <HeaderIcon
            :image-src="require('../assets/images/icons/cart.svg')"
            image-alt="買い物かご"
          />
        </div>
      </div>
    </div>
    <div class="headerBottom">
      <p class="message">
        最新のプロダクト、特別なサービス、限定コンテンツが集結。<br />
        <span class="subMessage"
          ><a href="" class="link">NIKEアプリをチェック</a></span
        >
      </p>
    </div>
  </header>
</template>

<script>
export default {};
</script>
