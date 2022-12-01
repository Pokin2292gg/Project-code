<template>
    <div>
        <Navbar />

        <section class="about">

            <h1 class="heading"> recom<span>mend</span> </h1>

            <div class="row">

                <div class="info-container">

                    <div class="box-container">
                        <div class="box">
                            <h1>แมคโดนัลด์ สาขาพหลโยธิน รังสิต</h1>
                            <h3> <span>กลางวัน : </span> ราคาประมาณ 100 บาท <span>กลางคืน : </span> ราคาประมาณ 250 บาท</h3>
                            <h3> <span>ที่อยู่ : </span> พหลโยธิน รังสิต (ไดร์ฟทรู ดูอัลเลน) ตำบลคลองหนึ่ง อำเภอคลองหลวง จังหวัดปทุมธานี </h3>
                            <a href="https://goo.gl/maps/Y67HbRSMyt7YUymb6">Location</a>
                            <star-rating :inline="true" :star-size="20" :read-only="true" :show-rating="false" :rating="5"></star-rating>
                        </div>
                        <div class="container">
                           <span id="rateMe2"  class="empty-stars"></span>
                        </div>
                    </div>

                    <div class="box-container">
                        <div class="box">
                            <h1>สมยง ตำซั่ว สาขา 3</h1>
                            <h3> <span>กลางวัน : </span> ราคาประมาณ 250 บาท <span>กลางคืน : </span> ราคาประมาณ 250 บาท</h3>
                            <h3> <span>ที่อยู่ : </span> ซอยรังสิตภิรมย์ ตำบลคลองหนึ่ง อำเภอคลองหลวง ปทุมธานี </h3>
                            <a href="https://goo.gl/maps/zaDahxxvWMt8S2Yf9">Location</a>
                            <star-rating :inline="true" :star-size="20" :read-only="true" :show-rating="false" :rating="5"></star-rating>
                        </div>
                    </div>

                    <div class="box-container">
                        <div class="box">
                            <h1>วัวล้วนๆ ไม่มีควายผสม</h1>
                            <h3> <span>กลางวัน : </span> ราคาประมาณ 100 บาท <span>กลางคืน : </span> ราคาประมาณ 100 บาท</h3>
                            <h3> <span>ที่อยู่ : </span> ซอยรังสิตภิรมย์ ถนนพหลโยธิน ตำบลคลองหนึ่ง อำเภอคลองหลวง ปทุมธานี </h3>
                            <a href="https://goo.gl/maps/uwti35EA5DcgwYjk9">Location</a>
                            <star-rating :inline="true" :star-size="20" :read-only="true" :show-rating="false" :rating="5"></star-rating>
                        </div>
                    </div>

                    <div class="box-container">
                        <div class="box">
                            <h1>ตำยำยั่ว By โบตั๋น ม.กรุงเทพ รังสิต</h1>
                            <h3> <span>กลางวัน : </span> ราคาประมาณ 250 บาท <span>กลางคืน : </span> ราคาประมาณ 250 บาท</h3>
                            <h3> <span>ที่อยู่ : </span> ซอยรังสิตภิรมย์ ถนนพหลโยธิน ตำบลคลองหนึ่ง อำเภอคลองหลวง ปทุมธานี </h3>
                            <a href="https://goo.gl/maps/PjBUchkEC25sq1p88">Location</a>
                            <star-rating :inline="true" :star-size="20" :read-only="true" :show-rating="false" :rating="5"></star-rating>
                        </div>
                    </div>

                    <div class="box-container">
                        <div class="box">
                            <h1>หมูทอดติดฟัน มหาวิทยาลัยกรุงเทพ(รังสิต)</h1>
                            <h3> <span>กลางวัน : </span> ราคาประมาณ 250 บาท <span>กลางคืน : </span> ราคาประมาณ 250 บาท</h3>
                            <h3> <span>ที่อยู่ : </span> ซอยรังสิตภิรมย์ ถนนพหลโยธิน ตำบลคลองหนึ่ง อำเภอคลองหลวง ปทุมธานี </h3>
                            <a href="https://goo.gl/maps/5iQ9yZjW6zkheP4Q6">Location</a>
                            <star-rating :inline="true" :star-size="20" :read-only="true" :show-rating="false" :rating="5"></star-rating>
                        </div>
                    </div>

                </div>

                

                <div class="count-container">

                    <div class="box">
                        <h3>สถานที่</h3>
                        <p>ขับรถยากมาก ที่จอดรถสบาย</p>
                    </div>

                    <div class="box">
                        <h3>อาหาร</h3>
                        <p>เมนูใหม่อร่อย อยากกินเฟรสฟรายต้องมานี่</p>
                    </div>

                    <div class="box">
                        <h3>สถานที่</h3>
                        <p>ร้านนั่งสบาย แต่หาที่จอดรถยาก</p>
                    </div>

                    <div class="box">
                        <h3>อาหาร</h3>
                        <p>อาหารอร่อย แนะนำส้มตำที่นี่เลย</p>
                    </div>

                    <div class="box">
                        <h3>สถานที่</h3>
                        <p>ร้านเล็กๆสบาย</p>
                    </div>

                    <div class="box">
                        <h3>อาหาร</h3>
                        <p>เครื่องดื่มอร่อยทุกเมนู</p>
                    </div>

                    <div class="box">
                        <h3>สถานที่</h3>
                        <p>หาที่จอดรถยาก ต้องมีสกิลขับรถ</p>
                    </div>

                    <div class="box">
                        <h3>อาหาร</h3>
                        <p>อาหารอร่อย รสชาติดี บริการดีค่ะ</p>
                    </div>

                    <div class="box">
                        <h3>สถานที่</h3>
                        <p>ร้านนั่งสบาย หาที่จอดรถยาก</p>
                    </div>

                    <div class="box">
                        <h3>อาหาร</h3>
                        <p>อาหารอร่อย ราคาสมเหตุสมผล</p>
                    </div>

                </div>

            </div>

        </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

        <section class="skills">

            <h1 class="heading"> con<span>tacts</span>  </h1>

            <div class="box-container">
                <div class="box">
                    <img src="images/Lineman.png">
                    <h3>lineman</h3>
                </div>
                <div class="box">
                    <img src="images/index.png">
                    <h3>GrabFood</h3>
                </div>
                <div class="box">
                    <img src="images/Foodpanda.png">
                    <h3>Foodpanda</h3>
                </div>
                <div class="box">
                    <img src="images/shoppeefood.png">
                    <h3>ShoppeeFood</h3>
                </div>
                <div class="box">
                    <img src="images/Logo-Robinhood.png">
                    <h3>Robinhood</h3>
                </div>
                <div class="box">
                    <img src="images/Dot.png">
                    <h3>Other</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

        <!-- education section starts  -->
  
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import StarRating from 'vue-star-rating'
export default {
    components: { Navbar, StarRating}
}
</script>

<style>

</style>