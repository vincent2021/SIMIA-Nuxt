<template>
  <div class="home-container">
    <div data-role="Header" class="home-navbar-container">
      <div class="home-navbar">
        <div class="home-logo">
          <img alt="image" src="/logo-200h.png" class="home-image" />
        </div>

      </div>
    </div>
    <div class="home-container2">
      <img
        alt="image"
        src="/cover-1500w.jpg"
        loading="lazy"
        class="home-image2"
      />
    </div>
    <div class="home-container3">
      <h1 class="home-text">
        NOS TÉTINES ONT TIRÉ LEUR RÉVÉRENCE
      </h1>
    </div>
    <div class="home-hero">
      <img alt="image" src="/Byebye-SIMIA.png" class="home-image3" />
      <div class="home-hero-text-container">
        <span class="home-text01">
          <span><span v-html="rawi5lh"></span></span>
          <span class="home-text03">
            Nos jolies tétines naturelles ont été les complices privilégiées des sommeils apaisés et des
            nuits parfois animées de vos tout petits.
          </span>
          <br class="Section-Text" />
          <br class="Section-Text" />
          <span class="home-text06">
            Nous avons eu à cœur de produire en France et de travailler de belles
            matières, parfaitement saines, qui respectent la planète.
          </span>
          <br class="Section-Text" />
          <br class="Section-Text" />
          <span class="home-text09">
            Nous espérons de tout cœur que notre aventure en aura inspiré beaucoup
            d&apos;autres.
          </span>
          <br class="Section-Text" />
          <br class="Section-Text" />
          <span class="home-text09">
            Un immense merci pour vos commandes, les photos si mignonnes de vos
            tout petits, tous vos mots. Cette aventure a été incroyable grâce à
            vous.
          </span>
          <br class="Section-Text" />
        </span>
      </div>

    </div>
    <a
      href="mailto:bonjour@simia.co?subject=Contact"
      class="home-cta-btn1 Anchor button"
    >
      NOUS CONTACTER
    </a>
    <div class="home-section-separator"></div>
    <div class="home-footer">
      <span class="home-text14">© 2023, simia.co avec plein d&apos;amour</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {
      rawi5lh: ' ',
    }
  },
  head: {
    title: 'SIMIA',
    meta: [
      {
        property: 'og:title',
        content: 'SIMIA',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-navbar-container {
  top: 0;
  width: 100%;
  display: flex;
  z-index: 100;
  position: sticky;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-gray-white);
}
.home-navbar {
  width: 100%;
  display: flex;
  position: relative;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  border-color: var(--dl-color-gray-black);
  padding-left: var(--dl-space-space-tripleunit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-logo {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.home-image {
  width: 125px;
  object-fit: cover;
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: var(--dl-space-space-doubleunit);
  position: absolute;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.home-top {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: space-between;
}
.home-image1 {
  width: 50px;
  object-fit: cover;
}
.home-container1 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-icon {
  width: 24px;
  height: 24px;
}
.home-mid {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-links-container {
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: column;
}
.home-link {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.home-link1 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.home-link2 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.home-link3 {
  text-decoration: none;
}
.home-cta-btn {
  color: var(--dl-color-gray-white);
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-fiveunits);
  border-radius: 34px;
  padding-right: var(--dl-space-space-fiveunits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-primary-100);
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.home-bot {
  flex: 0 0 auto;
  width: 200px;
  display: flex;
  margin-top: auto;
  align-items: flex-start;
  flex-direction: column;
}
.home-social-links-container {
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: row;
}
.home-icon2 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-icon4 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-icon6 {
  width: 24px;
  height: 24px;
}
.home-container2 {
  flex: 1;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
}
.home-image2 {
  width: 100%;
  height: 421px;
  align-self: center;
  box-shadow: 0px 5px 10px 0px #d4d4d4;
  object-fit: cover;
}
.home-container3 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-tripleunit);
  align-items: center;
  margin-left: var(--dl-space-space-doubleunit);
  margin-right: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.home-text {
  color: rgb(245, 176, 176);
  width: 893px;
  font-size: 48px;
  font-style: normal;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
  font-family: bimbo-finetip;
}
.home-hero {
  width: 100%;
  display: flex;
  height: fit-content;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-tripleunit);
  margin-bottom: var(--dl-space-space-halfunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: space-evenly;
}
.home-hero-text-container {
  width: 35%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text01 {
  color: var(--dl-color-gray-500);
  align-self: flex-start;
  font-size: 22px;
  text-align: justify;
}
.home-image3 {
  width: 50%;
  object-fit: contain;
}
.home-cta-btn1 {
  color: var(--dl-color-gray-white);
  align-self: center;
  text-align: center;
  padding-top: var(--dl-space-space-doubleunit);
  border-width: 0px;
  border-radius: 34px;
  margin-bottom: var(--dl-space-space-fiveunits);
  padding-bottom: var(--dl-space-space-doubleunit);
  text-decoration: none;
  background-color: #399;
}
.home-section-separator {
  width: 100%;
  height: 0px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-700);
}
.home-footer {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  padding-bottom: var(--dl-space-space-unit);
  justify-content: center;
  background-color: #79b4ad;
}
.home-text14 {
  color: #ffffff;
}

@media(max-width: 991px) {
  .home-cta-btn {
    font-size: 16px;
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
  }
  .home-container3 {
    flex: 1;
    padding-top: var(--dl-space-space-unit);
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    padding-bottom: var(--dl-space-space-unit);
  }
  .home-image2 {
  height: 390px;
  }
  .home-text {
    color: rgb(245, 176, 176);
    height: fit-content;
    font-size: 28px;
    align-self: center;
    font-style: normal;
    text-align: center;

    padding-top: 5px;
    padding-left: 0px;
    padding-right: 0px;
    
  }
  .home-hero {
    flex-direction: column-reverse;
    flex: 1;
  }
  .home-hero-text-container {
    width: 100%;
    height: auto;
    text-align: justify;

  }
  .home-text01 {
    align-self: stretch;
    font-size: 14px;
    text-align: justify;
  }
  .home-image3 {
    flex: 1;
    padding-top: var(--dl-space-space-tripleunit);
    width: 100%;
    height: 675px;
  }
  .home-footer {
    flex: 1;
    padding-top: var(--dl-space-space-unit);
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    padding-bottom: var(--dl-space-space-unit);
  }
}
</style>
