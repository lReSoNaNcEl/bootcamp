<template>
    <section class="gallery">
        <div class="gallery__img"></div>
        <div class="gallery__img"></div>
        <div class="gallery__img">
            <div class="gallery__title">gallery</div>
        </div>
        <div class="gallery__img"></div>
        <div class="gallery__img"></div>
    </section>
</template>

<script>

    export default {

    }
</script>

<style scoped>

.gallery {
    height: 100vh;
    width: 100%;
    padding: 100px 5.2vw;
    display: grid;
    grid-template-columns: 35% 1fr 35%;
    grid-template-rows:  30% 1fr 30%;
    grid-template-areas:
        "img-2 img-3 img-4"
        "img-2 img-3 img-5"
        "img-1 img-3 img-5"
    ;
    grid-gap: 1.5vw;
}

.gallery__img:nth-of-type(1) {
    grid-area: img-1;
    width: 75%;
    height: 70%;
    margin: 0 0 0 25%;
    background: url('../assets/img/gallery/img_2.jpg');
}

.gallery__img:nth-of-type(2) {
    grid-area: img-2;
    width: 90%;
    height: 70%;
    margin: 25% 0 0 10%;
    background: url('../assets/img/gallery/img_5.jpg');
   }

.gallery__img:nth-of-type(3) {
    grid-area: img-3;
    background: url('../assets/img/gallery/img_4.jpg');

}

.gallery__img:nth-of-type(4) {
    grid-area: img-4;
    width: 30%;
    height: 70%;
    margin: 10% 0 0 0;
    background: url('../assets/img/gallery/img_1.jpg');
}

.gallery__img:nth-of-type(5) {
    grid-area: img-5;
    width: 65%;
    height: 75%;
    background: url('../assets/img/gallery/img_3.jpg');
}

.gallery__img:nth-of-type(1),
.gallery__img:nth-of-type(2),
.gallery__img:nth-of-type(3),
.gallery__img:nth-of-type(4),
.gallery__img:nth-of-type(5) {
    -webkit-background-size: cover;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.gallery__title {
    color: white;
    font-size: 9vw;
    letter-spacing: 10px;
    position: absolute;
    left: 34vw;
    font-weight: bold;
    text-shadow: 3px 3px #333333;
}

</style>