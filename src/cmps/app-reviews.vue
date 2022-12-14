<template>
    <section class="app-reviews flex row">
        <img src="../assets/images/bg-quotes.png" alt="">
        <div class="item flex column">
            <p>{{users[0].review}}</p>
            <div class="user flex row">
                <img src="../assets/images/profile-1.jpg" alt="">
                <div class="text flex column">
                    <h4>{{users[0].name}}</h4>
                    <p>{{users[0].position}}</p>
                </div>
            </div>
        </div>
        <div class="item flex column">
            <p>{{users[1].review}}</p>
            <div class="user flex row">
                <img src="../assets/images/profile-2.jpg" alt="">
                <div class="text flex column">
                    <h4>{{users[1].name}}</h4>
                    <p>{{users[1].position}}</p>
                </div>
            </div>
        </div>
        <div class="item flex column">
            <p>{{users[2].review}}</p>
            <div class="user flex row">
                <img src="../assets/images/profile-3.jpg" alt="">
                <div class="text flex column">
                    <h4>{{users[2].name}}</h4>
                    <p>{{users[2].position}}</p>
                </div>
            </div>
        </div>
     
    </section>
</template>

<script>
export default {
    name: 'app-reviews',
    data(){
        return{
            users:[
                {imgUrl:'../assets/images/profile-1.jpg',name:'Satish Patel',position:'Founder & CEO, Huddle',review:'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.'},
                {imgUrl:'../assets/images/profile-2.jpg',name:'Bruce McKenzie',position:'Founder & CEO, Huddle',review:'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.'},
                {imgUrl:'../assets/images/profile-3.jpg',name:'Iva Boyd',position:'Founder & CEO, Huddle',review:'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.'}
            ]
        }
    }
}
</script>