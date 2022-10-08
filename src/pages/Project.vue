<template>
  <div>
    <Navbar />
    <main class="content margin-auto">
        <article class="artical bg-white">
            <section class="margin-auto">
                <h1 class="title" style="color:black;">Project</h1>
            </section>
        </article>
    </main>
    <footer class="content">
        
        <article style="color:aliceblue" class="artical margin-auto" >
            <section class="content margin-auto">
                <img class="img-gallery" src="img/BB.png" alt="gallery">
            </section>
            <section class="text-center">
                <span>"BEATBOX KNOCKOUT BU Creative Sandbox X Workpoint"</span><br><br>
                <span>--- ซูลูปาก้า ตาปาเฮ้ | BU64 ---</span><br><br>
                <span>TV Production By Students From Bangkok University</span>
            </section>
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