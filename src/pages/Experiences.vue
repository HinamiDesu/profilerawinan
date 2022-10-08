<template>
  <div>
    <Navbar />
    <footer class="content margin-auto">
        <article style="color:aliceblue" class="text-center">
            <section>
                <span>"Life Is The Art Of Drawing Without And Eraser"</span>
            </section>
            <section>
                <span>--- John W Gardner ---</span>
            </section> 
            <hr>
            <section class="title">
                <span>Scholarship</span>
            </section> 
            
            <article class="skill-menu margin-auto">
                <ul class="ul-navbar">
                    <li class="menu-list">
                        <a href="index.html">ทุนเพชรในชัยพฤกษ์ 100%</a>
                    </li>
                    <li class="menu-list">
                        <a href="Experiences.html">ทุนสหกรณ์ ประจำปี2565</a>
                    </li>
                </ul>
            </article>

            <section class="title">
                <span>Certificate</span>
            </section>
            <article class="skill-menu margin-auto">
                <ul class="ul-navbar">
                    <li class="menu-list">
                        <a href="index.html">BU Creative SandBox X Workpoint 2022</a>
                    </li>
                    <li class="menu-list">
                        <a href="Experiences.html">การเเข่งขันประกวดร้านค้ากาชาดออนไลน์</a>
                    </li>
                </ul>
            </article>
        </article>
    </footer>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
}
</script>

<style>

</style>