<template>
    <section class="service">
        <div class="service__section">
            <div class="service__section__image"></div>
            <div class="service__section__description">
                <h2 class="service__section__description__title">Lorem ipsum dolor sit amet, consectetur.</h2>
                    <div class="service__section__description__text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. At beatae commodi dolor dolorum, enim hic impedit itaque minima nostrum officiis quae quaerat quas qui quo quos similique sint tempora tenetur. Aliquam eos facilis illum labore, officiis quidem unde? Beatae, illo.</div>
            </div>
        </div>
        <div class="service__section">
            <div class="service__section__description">
                <h2 class="service__section__description__title">Lorem ipsum dolor sit amet, consectetur.</h2>
                <div class="service__section__description__text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo incidunt, vitae. Cupiditate exercitationem fugit illo, natus nemo quia sapiente sequi velit. Architecto esse illum libero magnam sed? Ad aspernatur expedita ipsum, iure magni minus modi non obcaecati odio ut vitae?</div>
            </div>
            <div class="service__section__image"></div>
        </div>
        <div class="service__section">
            <div class="service__section__image"></div>
            <div class="service__section__description">
                <h2 class="service__section__description__title">Lorem ipsum dolor sit amet, consectetur.</h2>
                <div class="service__section__description__text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A ab adipisci animi assumenda at autem blanditiis commodi, consequuntur delectus deserunt eaque exercitationem explicabo inventore ipsam iste maiores mollitia nam nostrum pariatur quaerat quam rem soluta tempora tempore velit veniam voluptas.</div>
            </div>
        </div>
        <div class="service__section">
            <div class="service__section__description">
                <h2 class="service__section__description__title">Lorem ipsum dolor sit amet, consectetur.</h2>
                <div class="service__section__description__text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi at cum facilis id laborum. Ad aliquid atque culpa dicta dignissimos ex iure molestias mollitia natus nemo nihil, nobis officiis perferendis quis quisquam ratione repellendus voluptatem voluptatum. Autem eaque nobis quaerat.</div>
            </div>
            <div class="service__section__image"></div>
        </div>
    </section>
</template>

<script>

    export default {

    }
</script>

<style scoped>

.service {
    height: 200vh;
    width: 100%;
}

.service__section {
    width: inherit;
    height: 50vh;
    display: flex;
}

.service__section__image {
    width: 50%;
    height: inherit;
}

.service__section:nth-child(1) .service__section__image {background: url('../assets/img/service_1.jpg'); background-size: cover;}
.service__section:nth-child(2) .service__section__image {background: url('../assets/img/service_2.jpg'); background-size: cover;}
.service__section:nth-child(3) .service__section__image {background: url('../assets/img/service_3.jpg'); background-size: cover;}
.service__section:nth-child(4) .service__section__image {background: url('../assets/img/service_4.jpg'); background-size: cover;}

.service__section__description {
    width: 50%;
    height: inherit;
    padding: 0 10% 0 10%;
    line-height: 150%;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    text-align: left;
    opacity: .7;
}

.service__section__description__title {
    font-size: 2.1875vw;
    line-height: 2.1vw;
}

.service__section__description__text {
    line-height: 1.5vw;
    font-size: 1.0415vw;
}
</style>
