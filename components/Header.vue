<template>
  <div>
    <b-navbar toggleable="lg" type="dark"  variant="success">
      <b-navbar-brand to="/">Rin's 게시판</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/">자유게시판</b-nav-item>
          <b-nav-item to="/Login">로그인</b-nav-item>
          <b-nav-item to="/gallery">갤러리</b-nav-item>
          <b-nav-item to="/boardlist">VUE리스트</b-nav-item>
          <b-nav-item to="/CalVue">달력보기</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  nama: "Header",
  data() {
    return {

    }
  }
};
</script>


<style>
  .greenC {background:}
</style>
