<template>
<div id="resume">

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
                        
                    <!-- <div class="arrow"><h1> ⇟</h1>  </div>-->

                </div>
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
        <div class="row bg-yel">
        <div class="col s3 offset-s2">
            <h4 class="title">Skills</h4>
            <h6 class="main-text-left">
                Microsoft Office
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 90%"></div>
            </div>

            <h6 class="main-text-left">
                Adobe Creative Suite
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 20%"></div>
            </div>

            <h6 class="main-text-left">
                SPSS
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 10%"></div>
            </div>

            <h6 class="main-text-left">
                HTML
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 80%"></div>
            </div>

            <h6 class="main-text-left">
                CSS
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 80%"></div>
            </div>
            <h6 class="main-text-left">
                JavaScript: Vue, Node, MongoDb
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 50%"></div>
            </div>
            <h6 class="main-text-left">
                C#
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 10%"></div>
            </div>
            <h6 class="main-text-left">
                Source Control: Git, Github
            </h6>
            <div class="progress">
                <div class="determinate" style="width: 30%"></div>
            </div>

            <h4 class="title">Education</h4>

            <h5 class="main-text-left">
                Immersive Full-Stack Developer Bootcamp
            </h5>
            <h7 class="main-text-left">
                Boise CodeWorks
            </h7>
            <br>
            <h8 class="main-text-left">January - March 2017</h8>
            <br>
            <br>
            <h5 class="main-text-left">
                Marketing BBA
            </h5>
            <h7 class="main-text-left">
                Boise State University
            </h7>
            <br>
            <h8 class="main-text-left">2012 - 2016</h8>
        </div>
        <div class="col s5">

            <h4 class="title">Experience</h4>

            <div class="row b-border">
                <div class="col s6">
                    <h5 class="main-text-left">Retail Expert + Events Crew</h5>
                    <h6 class="main-text-left">Proof Eyewear</h6>
                    <h7 class="main-text-left">August 2016 - December 2016</h7>
                    <br>
                    <br>
                </div>
                <div class="col s6">
                    <ul class="main-text-left">
                        <li>Bolster brand awareness</li>
                        <li>Sell high quality, eco-friendly glasses</li>
                    </ul>
                </div>
            </div>

            <div class="row b-border">
                <div class="col s6">
                    <h5 class="main-text-left">Marketing Intern</h5>
                    <h6 class="main-text-left">Treefort Music Fest</h6>
                    <h7 class="main-text-left">November 2015 - April 2016</h7>
                </div>
                <div class="col s6">
                    <ul class="main-text-left">
                        <li>Assist in the execution of marketing campaigns</li>
                        <li>Populate social media channels with relevant posts</li>
                        <li>Plan and attend promotional events</li>
                    </ul>
                </div>
            </div>

            <div class="row b-border">
                <div class="col s6">
                    <h5 class="main-text-left">Customer Service Representitive</h5>
                    <h6 class="main-text-left">Hertz</h6>
                    <h7 class="main-text-left">June 2014 - August 2016</h7>
                    <br>
                    <br>
                </div>
                <div class="col s6">
                    <ul class="main-text-left">
                        <li>Rent quality vehicles while selling insurance and upgrade options</li>
                        <li>Successfully and frequently solve problems</li>
                    </ul>
                </div>
            </div>

            <div class="row b-border">
                <div class="col s6">
                    <h5 class="main-text-left">Sales Intern</h5>
                    <h6 class="main-text-left">Proof Eyewear</h6>
                    <h7 class="main-text-left">September 2015 - December 2015</h7>
                    <br>
                    <br>
                </div>
                <div class="col s6">
                    <ul class="main-text-left">
                        <li>Make calls to potential retailers</li>
                        <li>Scout out new territories to enter</li>
                    </ul>
                </div>
            </div>

            <div class="row b-border">
                <div class="col s6">
                    <h5 class="main-text-left">Marketing Intern</h5>
                    <h6 class="main-text-left">Lee Pesky Learning Center</h6>
                    <h7 class="main-text-left">May 2015 - August 2015</h7>
                    <br>
                    <br>
                </div>
                <div class="col s6">
                    <ul class="main-text-left">
                        <li>Plan and execute an online auction</li>
                        <li>Organize and help run a scavenger hunt through downtown Boise</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

</div>
</template>
<script>
    export default {
        name: 'resume',
        methods: {
            openModal() {

                $('.modal').modal();
                $('#loginModal').modal('open');
            }
        }
    }
</script>
<style scoped>
    #resume {
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
        position: fixed;
        bottom: 0;
        color: rgb(237, 226, 215);
    }
    
    .progress .determinate {
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        background-color: rgb(237, 226, 215);
        transition: width .3s linear;
    }
    
    .progress {
        background-color: rgb(122, 112, 102);
    }
    
    .b-border {
        border-bottom: 1px solid rgb(122, 112, 102);
    }
    
    .main-text-left {
        font-family: 'Didot', sans-serif;
        color: rgb(81, 79, 73);
        text-align: left;
    }
    
    .title {
        font-family: 'Josefin Sans', sans-serif;
        color: rgb(122, 112, 102);
    }
</style>