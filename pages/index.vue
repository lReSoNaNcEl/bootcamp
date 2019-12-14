<template>
  <div>
    <Header/>
    <FeedBack/>
  </div>
</template>

<script>

    import Header from '@/components/Header';
    import FeedBack from '@/components/FeedBack';

export default {

    components: {
        Header,
        FeedBack

    }
}
</script>

<style>

  html {
    font-family: Roboto;
  }

  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  a {
    text-decoration: none;
    color: inherit;
  }
  button, input {
    outline: none;
  }

  button:hover {
    cursor: pointer;
  }
</style>
