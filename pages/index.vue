<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news.</h1>
    </section>
    <section class="featured-posts">

      <posts-preview id="1" title="Post Title 1" previewText="Preview Text 1" thumbnail="https://www.codingdojo.com/blog/wp-content/uploads/tech-literacy-Copy.gif"/>
      
      <posts-preview id="2" title="Post Title 2" previewText="Preview Text 2" thumbnail="https://pro2-bar-s3-cdn-cf.myportfolio.com/ec4657434c011e1a856a01752ef5f2f5/bf15faa73b4e4fa5c0bea7ae4afd56bb40a1d4cf06f2f73c349ebc640c3ceac9441990f6ec55da25_rw_1920.gif?h=29f18d9bcf1a2a651316b564f047596c"/>

      <posts-preview id="3" title="Post Title 3" previewText="Preview Text 3" thumbnail="https://cdn.dribbble.com/users/214929/screenshots/4366947/dribbble-shot_6.gif"/>

    </section>
  </div>
</template>

<script>
import PostsPreview from '~/components/PostsPreview'

export default {
  components: {
    PostsPreview
  }
}
</script>

<style >
    .intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-position: center;
  background-size: contain;
  background-image: url('~assets/images/nuxt-fundamentals.png');
  

}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}
</style>
