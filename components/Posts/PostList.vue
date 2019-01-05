<template>
    <section class="posts-list">

    <posts-preview id="1" title="Post Title 1" previewText="Preview Text 1" thumbnail="https://www.codingdojo.com/blog/wp-content/uploads/tech-literacy-Copy.gif"/>
    
    <posts-preview id="2" title="Post Title 2" previewText="Preview Text 2" thumbnail="https://pro2-bar-s3-cdn-cf.myportfolio.com/ec4657434c011e1a856a01752ef5f2f5/bf15faa73b4e4fa5c0bea7ae4afd56bb40a1d4cf06f2f73c349ebc640c3ceac9441990f6ec55da25_rw_1920.gif?h=29f18d9bcf1a2a651316b564f047596c"/>

    <posts-preview id="3" title="Post Title 3" previewText="Preview Text 3" thumbnail="https://cdn.dribbble.com/users/214929/screenshots/4366947/dribbble-shot_6.gif"/>

    </section>
</template>


<script>
import PostsPreview from '~/components/Posts/PostsPreview'


export default {
    components: {
        PostsPreview
    }
}
</script>


<style scoped>
.posts-page{
    display: flex;
    justify-content: center;
    align-items: center;
}
.posts-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

</style>
