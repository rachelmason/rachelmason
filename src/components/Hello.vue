<template>
  <div id="hello">
    <div class="row big">

      <div class="col m9 s12 ">
        <div class="back">


          <div class="title">
            <h3 class="heading">
              WEB DESIGN &
            </h3>
            <h1 class="heading under">
              MARKETING
            </h1>

          </div>
        </div>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <div>
         <ul id="staggered-list">
            <li>
        <h1 class="heading underport">What I've Worked On:</h1>
            </li>
        </ul>
        <br>
        <br>
        <br>
      <div class="col s12 flexIt">
          <a href="https://rachelmason.github.io/keepr">
        <div class="portfolio"><img src="../assets/keepr.png" alt="" >
        <div class="imgDescription">
        <ul class="imgText">
            <li>based on pinterest</li>
            <li>view all public keeps</li>
            <li>search keeps based off of keywords</li>
            <li>create public or private keeps</li>
            <li>create vaults</li>
            <li>add keeps to personal vaults</li>
            </ul>
        </div>
        </div>
          </a>
          <a href="https://rachelmason.github.io/passafist">
        <div class="portfolio"><img src="../assets/passafist.png" alt="Card Game" >
        <div class="imgDescription">
        <ul class="imgText">
            <li>group project based off of the card game, <a href="pass-a-fist.net"></a>Pass-A-Fist</li>
            <li>project utilized partner programming</li>
            <li>worked mostly on:</li>
            <ul>
            <li>design aspects</li>
            <li>mobile responsiveness</li>
            </ul>
            <li>assisted with:</li>
            <ul>
            <li>game logic</li>
            </ul>
            </ul>
        </div>
        </div>
          </a>
      </div>
        </div>

      </div>
      <div class="col m3 s12 side" style="right:0">
        <div class="row text">
          <h4 class="headingName">RACHEL MASON</h4>
           <h5 class="test">What I Know:</h5>
            <h6 class="text">
                Microsoft Office
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 90%"></div>
            </div>

            <h6 class="text">
                Adobe Creative Suite
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 20%"></div>
            </div>

            <h6 class="text">
                SPSS
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 10%"></div>
            </div>

            <h6 class="text">
                HTML
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 80%"></div>
            </div>

            <h6 class="text">
                CSS
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 80%"></div>
            </div>
            <h6 class="text">
                JavaScript: Vue, Node, MongoDb
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 50%"></div>
            </div>
            <h6 class="text">
                C#
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 10%"></div>
            </div>
            <h6 class="text">
                Source Control: Git, Github
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 30%"></div>
            </div>
          <!--<h5>Things I Do: </h5>
          <p>- Web Design</p>
          <p>- Marketing</p>
          <p>- Social Media Management</p>-->
          <h5>What I've Learned: </h5>
          <p>- Full Stack Web Development
            <p class="underbc">@ Boise CodeWorks</p>
          </p>
          <p>- Marketing BBA
            <p class="underbsu">@ Boise State University</p>
          </p>
          <h5>Let's Talk: </h5>
          <p><a class="underres" href="https://standardresume.co/rachelmason">Resume</a></p>
          <p><a class="underli" href="www.linkedin.com/rachmason">LinkedIn</a></p>
          <p><a class="undergh" href="www.github.com/rachelmason">GitHub</a></p>
          <p><a class="underinsta" href="www.instagram.com/raemase">Instagram</a></p>
          <p data-target="modal1" @click="openModal" class="undercn">ramason@icloud.com</p>
          

        </div>
      </div>
        <div id="modal1" class="modal text">
          <div class="modal-content">
            <form action="https://formspree.io/ramason@icloud.com" method="POST">
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
                <input type="hidden" name="_next" value="www.rachelmason.me" />
              </div>
              <div class="input-field col s1">

                <button type="submit" class="waves-effect waves-light btn">submit</button>

              </div>
            </form>
          </div>
        </div>
    </div>
   
   
    <!--<div class="nav">
        <div class="nav-item"><router-link to="/">home</router-link></div>
        <div class="nav-item"><router-link to="/resume">resume</router-link></div>
        <div class="nav-item"><router-link to="/portfolio">portfolio</router-link></div>
    </div>-->
    <!--<div class="flex-container">
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
                </div>-->
    <!--<div id="modal1" class="modal">
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
        </div>-->
  </div>
</template>
<script>
    export default {
        name: 'hello',
        mounted() {
            var options = [{
                selector: '#staggered-list',
                offset: 200,
                callback: function(el) {
                    Materialize.showStaggeredList($(el));
                }
            }];
            Materialize.scrollFire(options);
        },
        components: {

        },
        methods: {
            openModal() {

                $('.modal').modal();
                $('#loginModal').modal('open');
            }
        }

    }
</script>
<style>
    .side {
        position: fixed;
    }
    
    .imgText {
        margin: 16px;
    }
    
    .imgText>a {
        color: white;
    }
    
    .imgText>ul>li {
        margin-left: 20px;
    }
    
    h5 {
        line-height: 77%;
    }
    
    .flexIt {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
    }
    
    .move {
        position: fixed;
        bottom: 0;
        left: 0
    }
    
    .portfolio {
        position: relative;
        margin: 2%;
    }
    
    .imgDescription {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background: #fcdcc2;
        color: #fff;
        visibility: hidden;
        opacity: 0;
    }
    
    .portfolio:hover .imgDescription {
        visibility: visible;
        opacity: 1;
    }
    /*.portfolio:after {
        position: absolute;
        content: "";
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        opacity: 0;
        background-color: #ffb375;
    }*/
    
    .big {
        height: 86vh;
    }
    
    .port {
        height: 86vh
    }
    
    .side {
        border-left: darkgray solid 1px;
        /*position: fixed;*/
    }
    
    .heading {
        font-family: 'Poppins', sans-serif;
        height: 39px;
    }
    
    .headingName {
        font-family: 'Poppins', sans-serif;
        border-bottom: 12px solid #fcdcc2;
        width: 266px;
    }
    
    .title {
        margin-top: 21vh;
        border-top: black solid 12px;
        width: 27%;
        z-index: 1;
    }
    
    .underport {
        text-decoration: none;
        display: inline-block;
        border-bottom: 41px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .underport:hover {
        border-bottom: 41px solid #fcdcc2;
        width: 646px;
    }
    
    .under {
        text-decoration: none;
        display: inline-block;
        border-bottom: 41px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .under:hover {
        border-bottom: 41px solid #fcdcc2;
        width: 352px;
    }
    
    .underbc {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .underbc:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 141px;
    }
    
    .underbsu {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .underbsu:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 202px;
    }
    
    .underinsta {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .underinsta:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 77px;
    }
    
    .undergh {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .undergh:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 51px;
    }
    
    .underli {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .underli:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 69px;
    }
    
    .underres {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
        color: #ffb375;
    }
    
    .underres:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 51px;
    }
    
    .undercn {
        text-decoration: none;
        display: inline-block;
        border-bottom: 12px solid transparent;
        width: 0px;
        transition: 0.5s ease;
        white-space: nowrap;
        height: 25px;
    }
    
    .undercn:hover {
        border-bottom: 12px solid #fcdcc2;
        width: 104px;
    }
    
    .back {
        background-color: lightgray;
        z-index: 0;
        width: 84%;
        height: 40%;
        margin-left: 90px;
        margin-top: 12vh;
        padding: 23px;
    }
    
    .text {
        font-family: 'Source Code Pro', monospace;
    }
    
    li {
        font-family: 'Source Code Pro', monospace;
        color: black;
    }
    
    a {
        font-family: 'Source Code Pro', monospace;
        color: black;
    }
    
    a:hover {
        color: #ffb375;
        text-decoration: none;
    }
    
    .modal {
        max-height: 49%;
    }
    
    .modal-content {
        height: 100%;
    }
    
    .btn {
        background-color: #ffb375;
        color: gray;
    }
    
    .btn:hover {
        background-color: #ffb375;
    }
    
    .btn:focus {
        background-color: #ffb375;
    }
    
    img {
        width: 100%;
    }
    
    .progress .determinate {
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        background-color: #fcdcc2;
        transition: width .3s linear;
    }
    
    .progress {
        background-color: gray;
    }
    /* label color */
    
    .input-field label {
        color: #fcdcc2;
    }
    /* label focus color */
    
    .input-field input[type=text]:focus+label {
        color: #fcdcc2;
    }
    /* label underline focus color */
    
    .input-field input[type=text]:focus {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
    
    .input-field input[type=email]:focus {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
    
    .input-field input[type=textarea]:focus {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
    /* valid color */
    
    .input-field input[type=text].valid {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
    /* invalid color */
    
    .input-field input[type=text].invalid {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
    /* icon prefix focus color */
    
    .input-field .prefix.active {
        color: #fcdcc2;
    }
    
    textarea.materialize-textarea:focus:not([readonly]) {
        border-bottom: 1px solid #fcdcc2;
        box-shadow: 0 1px 0 0 #fcdcc2;
    }
</style>