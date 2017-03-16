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

                </div>
            </div>
        </div>

        <div class="row bg-body">
            <div class="col-md-12 heading">
                <div>
                    <h1 class="heading">Projects I've Worked On</h1>
                </div>
                <div class="flex-container2">

                    <div class="flex-square">
                        <h5>resume</h5>
                        <a href="rachelmason.me/resume"><img src="../assets/resume.png" alt=""> </a>
                    </div>
                    <div class="flex-square">PROJECT 2</div>
                    <div class="flex-square">PROJECT 3</div>
                    <div class="flex-square">PROJECT 4</div>
                    <div class="flex-square">PROJECT 5</div>
                    <div class="flex-square">PROJECT 6</div>

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
        methods: {
            openModal() {

                $('.modal').modal();
                $('#loginModal').modal('open');
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    #portfolio {
        font-family: 'Josefin Sans', sans-serif;
    }
    
    .modal {
        max-height: 43%;
    }
    
    .resume {
        align-self: flex-end;
        align-items: flex-end;
        color: rgb(237, 226, 215);
        font-family: 'Didot';
    }
    
    .resume:hover {
        align-self: flex-end;
        align-items: flex-end;
        color: rgb(122, 112, 102);
        font-family: 'Didot';
    }
    
    .heading {
        color: rgb(122, 112, 102);
    }
    
    .maintext {
        font-family: 'Josefin Sans', sans-serif;
        color: #4f5161;
    }
    
    .sub-text {
        font-family: 'Josefin Sans', sans-serif;
        color: #4f5161;
    }
    
    a {
        font-family: 'Josefin Sans', sans-serif;
        color: #4f5161;
    }
    
    a:hover {
        font-family: 'Josefin Sans', sans-serif;
        color: rgb(237, 226, 215);
        text-decoration: none;
    }
    
    .bg-pic {
        background-image: url(https://scontent-sea1-1.xx.fbcdn.net/v/t1.0-9/1798609_924146140929829_2755872486769183154_n.jpg?oh=2fd0ddb09a177dd111901aa375eeb317&oe=5912E4CF);
        height: 80vh;
        background-size: cover;
        background-position: center;
        position: relative;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    
    .bg-pic-bottom {
        background-image: url(https://scontent-sea1-1.xx.fbcdn.net/v/t1.0-9/1798609_924146140929829_2755872486769183154_n.jpg?oh=2fd0ddb09a177dd111901aa375eeb317&oe=5912E4CF);
        height: 52vh;
        background-size: cover;
        background-position: center;
        position: relative;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    
    .bg-body {
        height: 88vh;
    }
    
    .big-box {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        width: 100%;
        flex-wrap: wrap;
    }
    
    .flex-container {
        padding: 60px;
        height: 100%;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .flex-container2 {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        width: 100%;
        flex-wrap: wrap;
    }
    
    .flex-item {
        background: rgba(24, 24, 24, .1);
        height: 26vh;
        width: 60vw;
        margin: 10%;
    }
    
    .flex-square {
        height: 34vh;
        width: 24vw;
        margin: 1%;
        background: rgba(24, 24, 24, .1);
    }
    
    img {
        height: 27vh;
        width: 23vw;
        margin: 1%;
    }
    
    .btn-floating {
        background-color: rgb(122, 112, 102);
    }
    
    .btn-floating:hover {
        background-color: rgb(237, 226, 215);
    }
    
    .btn-floating:focus {
        background-color: rgb(237, 226, 215);
    }
    
    .btn {
        background-color: rgb(122, 112, 102);
        color: white;
    }
    
    .btn:hover {
        background-color: rgb(122, 112, 102);
    }
    
    .btn:focus {
        background-color: rgb(122, 112, 102);
    }
    /* label color */
    
    .input-field label {
        color: rgb(122, 112, 102);
    }
    /* label focus color */
    
    .input-field input[type=text]:focus+label {
        color: rgb(122, 112, 102);
    }
    /* label underline focus color */
    
    .input-field input[type=text]:focus {
        border-bottom: 1px solid rgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
    
    .input-field input[type=email]:focus {
        border-bottom: 1px solid rgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
    
    .input-field input[type=textarea]:focus {
        border-bottom: 1px solid rgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
    /* valid color */
    
    .input-field input[type=text].valid {
        border-bottom: 1px solid rgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
    /* invalid color */
    
    .input-field input[type=text].invalid {
        border-bottom: 1px solid rrgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
    /* icon prefix focus color */
    
    .input-field .prefix.active {
        color: rgb(122, 112, 102);
    }
    
    textarea.materialize-textarea:focus:not([readonly]) {
        border-bottom: 1px solid rgb(122, 112, 102);
        box-shadow: 0 1px 0 0 rgb(122, 112, 102);
    }
</style>