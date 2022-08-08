<template>
    <div class="container">
        
        <h1>The Company</h1>

        <div class="first_div">
            <img class="diamond_picture" src="https://images.pexels.com/photos/5011647/pexels-photo-5011647.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">

            <div class="div_text">
                <div class="div_title">
                    <h1 class="title">Diamonds</h1>
                </div>
                <p class="paragraph">The earliest diamonds were found in India in 4th century BC, although the youngest of these deposits were formed 900 million years ago. A majority of these early stones were transported along the network of trade routes that connected India and China, commonly known as the Silk Road. At the time of their discovery, diamonds were valued because of their strength and brilliance, and for their ability to refract light and engrave metal. Diamonds were worn as adornments, used as cutting tools, served as a talisman to ward off evil, and were believed to provide protection in battle. In the Dark Ages, diamonds were also used as a medical aid and were thought to cure illness and heal wounds when ingested.</p>
            </div>
        </div>
        
        <h1 class="about_the_developer">About the Developer</h1>

        <div class="meet_developer">

            <div class="div_text_developer">
            <div class="div_title_developer">
                <h1 class="title_developer">Gabriel Santillo</h1>
            </div>
            <p class="paragraph_developer">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae reprehenderit corrupti ad, hic deleniti, eaque blanditiis delectus soluta nesciunt placeat rerum reiciendis accusamus, beatae nam quas labore doloribus repellat eius?Lorem ipsum dolor sit amet consectetur adipisicing elit. Et doloremque est repellendus. Eum nesciunt nostrum explicabo delectus nihil, voluptatibus unde corrupti doloremque tenetur reiciendis sequi qui maiores quae totam asperiores. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, nisi dolores. Sed eveniet expedita, iure nesciunt qui itaque voluptatem ea assumenda minus animi totam modi aspernatur at deleniti, accusamus quos!</p>
            </div>

            <img class="developer_picture" src="https://images.pexels.com/photos/5324926/pexels-photo-5324926.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
        </div>

        <div>
            <h1 class="the_team">The Team</h1>
            <div class="div_meet_the_team">
                <div class="team_card">
                    <img class="card_img" src="https://images.pexels.com/photos/806835/pexels-photo-806835.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                    <h2>Alicia Keys</h2>
                    <p class="paragraph_card">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi tempore ad doloribus alias pariatur aspernatur libero debitis, vero nisi officia beatae. Eos est nam eveniet a, quos nostrum impedit autem.</p>
                </div>

                <div class="team_card">
                    <img class="card_img" src="https://images.pexels.com/photos/927451/pexels-photo-927451.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                    <h2>Michael Jackson</h2>
                    <p class="paragraph_card">Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus amet voluptate voluptatem, dignissimos sed obcaecati repellat, voluptas, non sequi suscipit maiores quidem! In ipsa voluptate error dignissimos saepe, tempora vero.</p>
                </div>

                <div class="team_card">
                    <img class="card_img" src="https://images.pexels.com/photos/6592686/pexels-photo-6592686.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                    <h2>Adam Levine</h2>
                    <p class="paragraph_card">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus modi in unde, dicta qui quas, quam minima eos inventore sequi ipsa quae est recusandae ullam aspernatur quis perferendis fugit beatae.</p>
                </div>
            </div>
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

.diamond_picture {
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

.about_the_developer {
    margin-top: 50px;
}

.meet_developer {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin-top: 80px;
}

.div_title_developer {
    background-color: cornflowerblue;
    border-radius: 5px;
    z-index: 2;
    width: 300px;
    color: white;
    display: grid;
    transform: translateX(250px);
}

.div_text_developer {
    margin-top: 50px;
}

.paragraph_developer {
    text-align: end;
    margin-left: 20px;
    margin-right: 20px;
}

.developer_picture {
    width: 100%;
    height: 75%;
    object-fit: cover;
    border-radius: 5px;
}

.div_meet_the_team {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}

.the_team {
    transform: translateY(-50px);
}

.card_img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 5px;
}

.paragraph_card {
    margin: 0 30px;
}

</style>