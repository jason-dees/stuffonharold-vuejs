<template>
    <div class="container">
        <div class="left-area">left</div>
        <!-- this can be the harold stack -->
        <img src="https://stuffonharold-node.vercel.app/api/image" />
        <div class="right-area">right</div>
        how can i do like a psuedo stack of harolds?
        Should I just do a create/destroy thing like usual?
        So once the image gets to the edge of the screen instead of destroying 
        i put it on the back and call get a new harold again.
        I think create/destroy would just be easier

    </div>
</template>
<script>
export default {
  name: 'HaroldContainer',
  props: {
  },
  methods: {

  }
}
</script>
<style scoped>
    .container {
        display: grid;
        background-color:green;
        grid-template-columns: 2fr 3fr 2fr;
        grid-template-rows: 1fr;
    }
    .left-area {
        background-color:orange;
    }
    .right-area {
        background-color:purple;
    }
</style>