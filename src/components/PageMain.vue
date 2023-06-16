<script>


export default {
    name: "PageMain",

}
</script>

<template>
    <main>
        <section id="excellence">
            <img src="../assets/img/university_logo.png" alt="">
            <h2>Inspired By Excellence & Innovation</h2>
            <p>We offer a wide range of high quality of teaching an extra-curricular activies</p>
        </section>
        <section>
            <div id="why">
                <div id="offer">
                    <h2>WHY CHOOSE AVADA UNIVERSITY?</h2>
                    <p>We offer a range of training packages in a range of subject areas and can offer blended learning opportunities o best meet your needs. If sitting in a room with a trainer and having the opportunity for discussion with other learners sounds good you then we can offer this. If you prefer to study in your own time and at your own speed then one of our e-learning packages may be right up your street.Ther is a third option,which is you like the sound of both but perhaps can't attend all training sessions,thi is when blended learning come into its own.  </p>
                </div>
                <div>
                    <img src="../assets/img/fss-demo-main-400x300.jpg" alt="">
                </div>
            </div>
        </section>
    </main>

  
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

#excellence{
    text-align: center;
    margin-top: 50px;
}
#why{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin: 100px;
    margin-left: 250px;
    line-height: 30px;
    height: 400px;
}
#offer{
    width: 50%;
}
 

</style>