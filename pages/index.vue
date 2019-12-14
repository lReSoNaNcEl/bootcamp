<template>
  <div>
    <Header/>
    <Service/>
    <Gallery/>
    <FeedBack/>
  </div>
</template>

<script>

    import Header from '@/components/Header';
    import Service from '@/components/Service';
    import Gallery from '@/components/Gallery';
    import FeedBack from '@/components/FeedBack';

export default {

    components: {
        Header,
        Service,
        Gallery,
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
