<template>
    <div class="contactus">
        <Header/>
        <!-- FORM -->
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-10 col-md-6">
                    <h1 class="contact-us-text mt-5">Contact Us</h1>
                    <hr class="solid mt-0">
                    <form>
                        <div class="form-group">
                            <label>Firstname *</label>
                            <input type="Name" class="form-control" placeholder="Please enter your firstname *">
                        </div>

                        <div class="form-group">
                            <label>Email *</label>
                            <input type="email" class="form-control" placeholder="Please enter your email * ">
                        </div>

                        <div class="form-group">
                            <label>Message *</label>
                            <textarea type="Message" class="form-control" placeholder="Message for me *"></textarea>
                        </div>
                    
                        <div class="form-group ml-4">
                            <input class="form-check-input" type="checkbox" value="" id="personal" checked>
                            <label class="form-check-label ml-n2" for="personal"> * I agree to allow Example Company to store and process my personal data.</label>
                        </div>

                        <div class="form-group ml-4">
                            <input class="form-check-input" type="checkbox" value="" id="marketing">
                            <label class="form-check-label ml-n2" for="marketing"> * I agree to receive marketing communications from Example Company.</label>
                        </div>

                        <button class="btn btn-primary mt-3 mb-1" style="background-color: green;">Send Messages</button>
                        <p class="text-muted mb-5"> <strong>*</strong>These fields are required</p>
                    </form>
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
  name: 'ContactUs',
  components: {
    Header,
    Footer,
  }
}
</script>