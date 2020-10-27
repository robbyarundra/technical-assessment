<template>
    <div class="login">
        <Header/>
        <!-- SECTION -->
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-10 col-md-6">
                <div class="shadow px-5 pt-5 pb-5 mb-5 bg-white mt-4">
                    <form>
                    <h3 class="text-center text-muted">Login</h3>
                    <div class="social-media text-center mt-5">
                        <a class="btn btn-block" href="">
                        <img src="images/google.png" height="25px">Log in with Google
                        </a>
                    </div>  
                    <div class="social-media text-center">
                        <a class="btn btn-block" href="">
                        <img src="images/facebook.png" height="25px">Log in with Facebook
                        </a>
                    </div>  
                    <div class="social-media text-center">
                    <a class="btn btn-block" href="">
                        <img src="images/line.png" height="25px">Log in with Line
                    </a>
                    </div>  
                    <div class="or-separator text-muted"><i>OR</i></div>
                    <div class="form-group">
                        <input type="email" class="form-control" placeholder="Email">
                        </div>
                    <div class="form-group">
                        <input type="password" class="form-control" placeholder="Password">
                    </div>
                    <button type="button" class="btn btn-block btn-primary" style="height: 50px;">Login</button>
                    <p href="#" class="text-muted mt-3 text-center"> Forgot Password ?</p>
                    </form>
                </div>
                </div>
            </div>
        </div>
        <Footer/>
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Footer,
  }
}
</script>