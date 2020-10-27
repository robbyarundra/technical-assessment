<template>
    <div class="home">
        <Header/>
        <div class="container">
        <div class="row">
            <img src="images/sunflower.jpg" class="img-fluid">
        </div>
        <!-- CONTENT TEXT -->
        <div class="textline">
            <p>Keppel Land is the property arm of Keppel Corporation, a multi-business company providing robust solutions for sustainable urbanisation, with key businesses in offshore and marine, property, infrastructure and investments.</p>
            <p>As a multi-faceted property company, Keppel Land provides innovative real estate solutions with its sterling portfolio of award-winning residential developments, investment-grade commercial properties and integrated townships.</p>
        </div>

            <!-- CARD TEXT -->
            <div class="row">
            
            <div  class="col-md-4">
                <div class="card">
                <div class="card-body text-center">
                    <h3 class="my-2">$527.0 Million</h3> <!--margin y untuk atas dan bawah-->
                    <span class="subtitle">NET PROFIT</span>
                    <p class="card-text text-left my-2">Keppel Land's net profit was $527m for FY2019, compared to $944m for FY2018.</p>
                </div>
                </div>
            </div>

            <div class="col-md-4"> 
                <div class="card">
                <div class="card-body text-center">
                    <h3 class="my-2">14.3 %</h3>
                    <span class="subtitle">RETURN ON EQUITY</span>
                    <p class="card-text text-left my-2">Keppel Land achieved average return on equity of 14.3% over the last 10 years</p>
                </div>
                </div>
            </div>


            <div class="col-md-4">
                <div class="card">
                <div class="card-body text-center">
                    <h3 class="my-2">$14.2 Billion</h3>
                    <span class="subtitle">TOTAL ASSETS</span>
                    <p class="card-text text-left my-2">Total assets increased by 1.6% year-on-year to $14.2 billion</p>
                </div>
                </div>
            </div>

            </div>  

            <!-- SUBSCRIBE -->
            <div class="row">
            <div class="col-12 text-center">
                <h3 class="subtitle mt-4">Be the first to know</h3>
                <p>Subscribe to receive the updates on our new lauches, articles, and exclusive previews</p>
                <div class="input-group mb-3 d-inline-flex justify-content-center col-md-4 mb-3">
                <input type="text" class="form-control subscribe text-subscribe" placeholder="Enter your email address" aria-label="Email" aria-describedby="basic-addon2">
                <div class="input-group-append">
                    <button class="input-group-text subscribe-button text-subscribe" id="basic-addon2">Subscribe</button>
                </div>
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
