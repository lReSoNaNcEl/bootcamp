<template>
    <header class="header">
        <div class="flex-wrap">
            <div class="header__logo"></div>
            <nav class="header__navmenu">
                <div class="header__navmenu__item">
                    <a href="#" class="header__navmenu__item__link">Home</a>
                </div>
                <div class="header__navmenu__item">
                    <a href="#" class="header__navmenu__item__link">Service</a>
                </div>
                <div class="header__navmenu__item">
                    <a href="#" class="header__navmenu__item__link">Reviews</a>
                </div>
                <div class="header__navmenu__item">
                    <a href="#" class="header__navmenu__item__link">Feedback</a>
                </div>
                <div class="header__navmenu__item">
                    <a href="#" class="header__navmenu__item__link">Contacts</a>
                </div>
            </nav>
        </div>
        <div class="header__preview">
            <h1 class="header__preview__title">Unforgettable trip</h1>
            <p class="header__preview__text">Our company provides first-class services for traveling to different parts of the world.</p>
            <button class="header__preview__btn">START YOUR ADVENTURE</button>
        </div>
    </header>
</template>
<script>

</script>

<style>

.header {
    width: 100%;
    height: 100vh;
    background: url('../assets/img/bg_header.png');
    background-size: cover;
    padding: 0 18.75vw 0 18.75vw;
    color: white;
}

.flex-wrap {
    display: flex;
    justify-content: space-between;
    padding: 50px 0 150px 0;
    align-items: center;
}

.header__logo {
    background: url('../assets/img/logo.png');
    background-size: cover;
    height: 50px;
    width: 150px;
    border-radius: 50%;
}

.header__navmenu {
    display: flex;
    font-size: 1.25vw;
}

.header__navmenu__item {
    padding: 0 15px;
}

.header__preview {
    border: 5px solid white;
    width: 62.5vw;
    height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
    padding: 0 130px 0 130px;
}

.header__preview__title {
    font-size: 3.75vw;
}

.header__preview__text {
    font-size: 1.875vw;
    text-align: center;
}

.header__preview__btn {
    width: 15.625vw;
    height: 60px;
    font-weight: bold;
    font-size: 1.0415vw;
    background: rgba(149, 79, 29, 0.5);
    color: white;
    border: 1px solid white;
}

</style>