<template>
<div>
<Navbar />
  <main class="content margin-auto">
    <!---article-->
        <article class="artical">
            <section class="row-50 left margin-auto">
                <img class="profile-img" src="img/image.png" alt="Profile">
            </section>
            <section class="row-50 right about-me"> 
                <header>
                    <article class="text-align-left">
                        <section class="title">
                            <h1>Hi, I'm Rawinan Kaewpuang</h1>
                        </section>
                        <section class="position">
                            <h3>No pain No gain</h3>
                        </section>
                        <section class="detail">
                            <span>
                                I'm A Sophomore Student In Multimedia Entertainment Engineering, Bangkok University.Along The Way I Have Been Studying In Bangkok Iniversity. I Have Learnt A Lot Hard Skill And Soft Skill To Become Who I Want To Be And Follow My DREAM!!
                            </span>
                        </section>
                        <section class="position">
                            <h3>About</h3>
                        </section>
                        <section class="detail">
                            <span class="font-bold">
                                Deatails
                            </span>
                            <span>Name : Rawinan Kaewpuang</span>
                            <span>Location : Thailand</span>
                        </section>
                        <article class="margin-top-2">
                            <ul class="ul-menu">
                                <li class="menu-list">
                                    <button class="btn btn-radius btn-primary ">About Me <i class="fa fa-user bg-user fa-1x"></i></button>
                                </li>
                                <li class="menu-list">
                                    <button class="btn btn-radius btn-outline-yellow ">Contact <i class="fa fa-phone bg-user fa-1x"></i></button>
                                </li>
                            </ul>
                        </article>
                    </article>
                </header>
                
            </section>
        </article>
    </main>
    
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