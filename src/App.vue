<template>
  <div id="app">
    <AppHeader />
    <LandingPage />
    <BookDescription />
    <AppFooter />
  </div>
</template>
<script>
// @ is an alias to /src
import AppHeader from "@/components/AppHeader.vue";
import LandingPage from "@/components/LandingPage.vue";
import AppFooter from "@/components/AppFooter.vue";
import BookDescription from "./views/BookDescription.vue";

export default {
  components: {
    AppHeader,
    LandingPage,
    AppFooter,
    BookDescription
  }
};
</script>
<style>
/* CSS Reset - Start */

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}
html {
  font-size: 10px;
}
body {
  line-height: 1;
}
ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
/* CSS Reset - End */

#app {
  max-width: 1440px;
  margin: 0 auto;
  font-family: "Roboto";
  font-size: 10px;
  color: #000;
}
.desc {
  font-size: 16px;
  color: #44576e;
  line-height: 1.5;
}
</style>
