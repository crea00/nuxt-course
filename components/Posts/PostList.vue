<template>
  <section class="post-list">
      <PostPreview 
        id="1"
        thumbnail="https://blogs.ramco.com/hubfs/Tech%20In%20Logistics%202nd%20Blog.jpg?t=1532905122910"
        title="Hello there!" 
        previewText="This is my first post"/>
      <PostPreview 
        id="2"
        thumbnail="https://blogs.ramco.com/hubfs/Tech%20In%20Logistics%202nd%20Blog.jpg?t=1532905122910"
        title="Hello there! - the second time" 
        previewText="This is my second post"/>
      <PostPreview 
        id="3"
        thumbnail="https://blogs.ramco.com/hubfs/Tech%20In%20Logistics%202nd%20Blog.jpg?t=1532905122910"
        title="Hi!" 
        previewText="This is my third post"/>
    </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";

export default {
  components: {
    PostPreview
  }
};
</script>


<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
