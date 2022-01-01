<template>
  <header class="layout-header">
    <div class="header-top">
      <div>
        <nuxt-link to="">
          <img
            src="../assets/images/jordan.svg"
            alt="jordan-logo"
            class="jordan-logo"
          />
        </nuxt-link>
      </div>
      <ul class="menu">
        <li class="item"><nuxt-link to="" class="link">ヘルプ</nuxt-link></li>
        <li class="item">|</li>
        <li class="item">
          <nuxt-link to="" class="link">ここから始めよう</nuxt-link>
        </li>
        <li class="item">|</li>
        <li class="item">
          <nuxt-link to="" class="link">ログイン</nuxt-link>
        </li>
      </ul>
    </div>
    <div class="header-main">
      <SiteLogo />
      <ul class="menu">
        <li class="item">
          <nuxt-link to="" class="link">NEW RELEASES</nuxt-link>
        </li>
        <li class="item"><nuxt-link to="" class="link">MEN</nuxt-link></li>
        <li class="item"><nuxt-link to="" class="link">WOMEN</nuxt-link></li>
        <li class="item"><nuxt-link to="" class="link">KIDS</nuxt-link></li>
        <li class="item">
          <nuxt-link to="" class="link">CUSTOMIZE</nuxt-link>
        </li>
        <li class="item"><nuxt-link to="" class="link">SALE</nuxt-link></li>
        <li class="item">
          <nuxt-link to="" class="link">COLLECTIONS</nuxt-link>
        </li>
      </ul>
      <div class="operation-area">
        <SearchBar />
        <div class="icon-area">
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
    <div class="header-bottom">
      <p class="message">
        最新のプロダクト、特別なサービス、限定コンテンツが集結。<br />
        <span class="sub-message"
          ><nuxt-link to="" class="link">NIKEアプリをチェック</nuxt-link></span
        >
      </p>
    </div>
  </header>
</template>

<script>
export default {};
</script>
