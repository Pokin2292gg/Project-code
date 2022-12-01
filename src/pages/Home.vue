<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/Spicy-Salmons-Salad.jpg" alt="">
            </div>
            <div class="content">
                <h3>WONGKHAMLAO</h3>
                <span>  อาหาร/สถานที่/ราคา/รีวิว</span>
                <p>เป็ยเว็บที่เกี่ยวกับแนะนำอาหารรอบๆภายในม.กรุงเทพ 
                    ให้กับนักศึกษาม.เราหรือบุคคลทั่วไปที่สนใจ
                    อาหารและร้านต้องๆรอบๆม.กรุงเทพ 
                    สามารถ inboxเพื่อเพิ่มสถานที่และร้านอาหารที่เราสนใจเข้าไปในเว็บได้ 
                    มีเมนูอาหารแนะนำด้วย ต้องถูกใจทุกคนแน่นอน!!! 
                    แล้วมารีวิวกันเยอะๆนะคะ!!!</p>
                <a href="about.html" class="btn"> recommend <i class="fas fa-user"></i> </a>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";

export default {
    components: { Navbar }
}
</script>

<style>

</style>