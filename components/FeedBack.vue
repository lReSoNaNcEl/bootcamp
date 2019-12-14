<template>
    <section class="feedback">
        <h2 class="feedback__title">Decided to go on a trip? <br> White to us!</h2>
        <form class="feedback__form" action="#">
            <p class="feedback__form__name">Name:</p>
            <input class="feedback__form__field" type="text" placeholder="John">
            <p class="feedback__form__name">E-mail:</p>
            <input class="feedback__form__field" type="text" placeholder="example@gmail.com">
            <p class="feedback__form__name">Phone:</p>
            <input class="feedback__form__field" type="text" placeholder="+7 (_ _ _) _ _ _   _ _   _ _">
            <button class="feedback__form__btn" type="submit">SEND REQUEST</button>
        </form>
    </section>
</template>

<script>
    export default {

    }
</script>

<style>

.feedback {
    width: 100%;
    height: 100vh;
    background: url('../assets/img/bg_feedback.png');
    background-size: cover;
    padding: 0 36vw 0 36vw;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.feedback__title {
    text-align: center;
    font-size: 2.5vw;
}

.feedback__form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.feedback__form__name {
    font-size: 1.25vw;
    margin: 40px 0 0 0;
}

.feedback__form__field {
    font-size: 1.25vw;
    width: 26.0416vw;
    height: 50px;
    text-indent: .52vw;
}

.feedback__form__field::-webkit-input-placeholder {
    font-size: 1.25vw;
    color: black;
    opacity: .3;
    text-indent: .52vw;
}

.feedback__form__btn {
    width: 15.625vw;
    height: 60px;
    font-weight: bold;
    font-size: 1.0415vw;
    background: rgba(149, 79, 29, 0.5);
    color: white;
    border: 1px solid white;
    margin: 60px 0 0 0;
}

</style>