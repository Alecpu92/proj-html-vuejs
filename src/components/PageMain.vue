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
            <div class="why">
                <div class="offer">
                    <h2>WHY CHOOSE AVADA UNIVERSITY?</h2>
                    <p>We offer a range of training packages in a range of subject areas and can offer blended learning opportunities o best meet your needs. If sitting in a room with a trainer and having the opportunity for discussion with other learners sounds good you then we can offer this. If you prefer to study in your own time and at your own speed then one of our e-learning packages may be right up your street.Ther is a third option,which is you like the sound of both but perhaps can't attend all training sessions,thi is when blended learning come into its own.  </p>
                </div>
                <div>
                    <img src="../assets/img/fss-demo-main-400x300.jpg" alt="">
                </div>
            </div>
        </section>
        <section>
            <div class="why">
                <div class="offer">
                  <h2>WORLD CLASS FACILITIES</h2>
                  <p>Avada Univesrity is devoted to excellence in teaching, learning and research, and developing leaders in many disciplines who make a difference globally. </p>
                  <p><strong>International focus</strong>- our students come from acrossthe globe</p>
                  <p><strong>Residential courses</strong>- we encourage learning and growth</p>
                  <p><strong>People no profits</strong>- education is right not a privilege</p>
                  <p>if you prefer to study own and your than speed our learning packages</p>
                </div>
                <div>
                  <h2>OUR VALUES</h2>
                  <ul id="orange">
                    <li>+ OUR MISSION</li>
                    <li>+ OUR PHILOSOPHY</li>
                    <li>+ OUR COMMITMENT</li>
                    <li>+ OUR PROMISE</li>
                    <li>+ OUR VALUES</li>
                  </ul>
                </div>
            </div>
        </section>
        <section>
            <div id="container-viewmore">
                <div id="view-1">
                    <h2>COURSES</h2>
                   <h4>view more</h4>
                </div>
                <div id="view-2">
                   <h2>EVENTS</h2>
                   <h4>view more</h4>
                </div>
                <div id="view-3">
                    <h2>LATEST NEWS</h2>
                    <h4>view more</h4>
                </div>   
            </div>
        </section>
        <section id="excellence">
            <img src="../assets/img/university_logo.png" alt="">
            <h2>Today University News</h2>
            <p>Covering topics from classes to politics and student organization events</p>
        </section>
    </main>

  
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

#excellence{
    text-align: center;
    margin-top: 50px;
}
.why{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin: 100px;
    margin-left: 250px;
    line-height: 30px;
    height: 400px;
}
.offer{
    width: 50%;
}
#container-viewmore{
    
    height: 400px;
    width: 100%;
    background-color: white;
    color: white;
    display: flex;
    flex-direction: row;
    text-align: center;
    
}
#view-1{
    border-color: black;
    background-image: url(../assets/img/home_courses_section_bg.jpg);
    width: 33%;
}
#view-2{
    border-color: black;
    background-image: url(../assets/img/home_events_section_bg.jpg);
    width: 33%;
    
}
#view-3{
    border-color: black;
    background-image: url(../assets/img/home_latest_news_section_bg.jpg);
    width: 33%;
}

 

</style>