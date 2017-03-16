<template>
  <div id="portfolio">
   
        <div class="row bg-pic">
         <div class="nav">
        <div class="nav-item"><router-link to="/">home</router-link></div>
        <div class="nav-item"><router-link to="/resume">resume</router-link></div>
        <div class="nav-item"><router-link to="/portfolio">portfolio</router-link></div>
    </div>
            <div class="col-md-12 big-box">
                <div class="flex-container">
                    <div class="flex-item">
                          <h1 class="heading">RACHEL MASON</h1>
                        
                        <h5 class="heading">A self-motivated web developer who thinks like a marketer. </h5>

                        <h5 class="sub-text">
                            <i class="fa fa-linkedin" aria-hidden="true"></i> <a href="https://www.linkedin.com/in/rachmason">rachmason</a>
                            <i class="fa fa-github" aria-hidden="true"></i><a href="https://github.com/rachelmason">rachelmason</a>
                            <i class="fa fa-instagram" aria-hidden="true"></i> <a href="https://www.instagram.com/raemase/">raemase</a>
                           <a data-target="modal1" @click="openModal"> <i class="fa fa-envelope" aria-hidden="true"></i> ramason@icloud.com</a>
                        </h5>
                    </div>
                        
                    <!--<div class="arrow"><h1> ⇟</h1>  </div>-->

                </div>
            </div>
        </div>

        <div class="row bg-body">
                   <div class="slider">
    <ul class="slides">
      <li>
        <img src="../assets/resume.png"> 
        <div class="caption left-align">
          <h3>resume</h3>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/2"> 
        <div class="caption left-align">
          <h3>next portfolio piece</h3>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/3"> 
        <div class="caption left-align">
          <h3>last portfolio piece</h3>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/4"> 
        <div class="caption left-align">
          <h3>hey mom, look i'm on the internet</h3>
        </div>
      </li>
    </ul>
  </div>
        </div>
        
        <div id="modal1" class="modal">
            <div class="modal-content">
                <form  action="https://formspree.io/ramason@icloud.com" method="POST">
                        <div class="row">
                            <div class="input-field col s6">
                                <input type="text" name="name" placeholder="name" required="" aria-required="true">
                            </div>
                            <div class="input-field col s6">
                                <input type="email" name="_replyto" placeholder="email" required="" aria-required="true">
                            </div>
                        </div>
                        <div class="row">
                            <div class="input-field col s8">
                                <input type="text" name="_subject" placeholder="subject" required="" aria-required="true">
                            </div>
                            <div class="input-field col s8">
                                <input type="hidden" name="_subject" placeholder="subject" required="" aria-required="true">
                            </div>
                            <div class="input-field col s12">
                                <textarea name="message" class="materialize-textarea" placeholder="let's talk" cols="30" rows="10" required="" aria-required="true"></textarea>
                            </div>
                            <input type="hidden" name="_next" value="/resume" />
                        </div>
                        <div class="input-field col s1">

                            <button type="submit" class="waves-effect waves-light btn">submit</button>

                        </div>
                    </form>
            </div>
        </div>
</div>
</template>

<script>
    export default {
        name: 'portfolio',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        mounted() {
            $(document).ready(function() {
                $('.slider').slider({
                    height: 900,
                    interval: 12000
                });
            });

        },
        methods: {
            openModal() {

                $('.modal').modal();
                $('#loginModal').modal('open');
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    #portfolio {
        font-family: 'Josefin Sans', sans-serif;
    }
    
    .bg-pic {
        background-image: url(https://scontent-sea1-1.xx.fbcdn.net/v/t1.0-9/1798609_924146140929829_2755872486769183154_n.jpg?oh=2fd0ddb09a177dd111901aa375eeb317&oe=5912E4CF);
        height: 98vh;
        background-size: cover;
        background-position: center;
        position: relative;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    
    .big-box {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        width: 100%;
        flex-wrap: wrap;
    }
    
    .arrow {
        /*position: fixed;*/
        bottom: 0;
        color: rgb(237, 226, 215);
    }
    
    img {
        height: 100%;
    }
    
    .slider .indicators .indicator-item.active {
        background-color: rgb(122, 112, 102);
    }
</style>