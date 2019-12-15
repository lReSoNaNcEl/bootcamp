<template>
  <div>
    <Header/>
    <Service/>
    <Gallery/>
    <FeedBack/>
    <Contacts/>
  </div>
</template>

<script>

    import Header from '@/components/Header';
    import Service from '@/components/Service';
    import Gallery from '@/components/Gallery';
    import FeedBack from '@/components/FeedBack';
    import Contacts from '@/components/Contacts';

export default {

    components: {
        Header,
        Service,
        Gallery,
        FeedBack,
        Contacts
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

  li {
    list-style-type: none;
  }
</style>
