<template>
    <div class="first_div">
        <img src="https://images.pexels.com/photos/5011647/pexels-photo-5011647.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">

        <div class="div_text">
            <div class="div_title">
                <h1 class="title">Diamonds</h1>
            </div>
            <p class="paragraph">The earliest diamonds were found in India in 4th century BC, although the youngest of these deposits were formed 900 million years ago. A majority of these early stones were transported along the network of trade routes that connected India and China, commonly known as the Silk Road. At the time of their discovery, diamonds were valued because of their strength and brilliance, and for their ability to refract light and engrave metal. Diamonds were worn as adornments, used as cutting tools, served as a talisman to ward off evil, and were believed to provide protection in battle. In the Dark Ages, diamonds were also used as a medical aid and were thought to cure illness and heal wounds when ingested.</p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.first_div {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin-top: 50px;
}

img {
    width: 100%;
    object-fit: cover;
    border-radius: 5px;
}

.div_title {
    background-color: cornflowerblue;
    border-radius: 5px;
    z-index: 2;
    transform: translateX(-80px) translateY(20px);
    width: 200px;
    color: white;
    display: grid;
    text-align: center;
}

.div_text {
    display: grid;
    row-gap: 20px;
}

.paragraph {
    margin-left: 20px;
    margin-right: 20px;
    text-align: start;
}

</style>