<script lang="ts">
import FooterShow from '../components/footer/FooterShow.vue';
import NavbarShow from '../components/navbar/NavbarShow.vue'

export default {
  name: 'ContactUser',
  components: {
    NavbarShow,
    FooterShow
  }
}
</script>
<template>
  <div class="container-xxl bg-white p-0">
    <NavbarShow :currentAdmin="{}"/>
    <!-- Contact Start -->
    <div class="container-xxl py-5">
      <div class="container">
        <h1 class="text-center mb-5 wow fadeInUp" data-wow-delay="0.1s">Contact us</h1><hr>
        <div class="row g-4">
          <div class="col-12">
            <div class="row gy-4">

                <div class="col-md-4 wow fadeIn" data-wow-delay="0.3s">
                                <div class="d-flex align-items-center bg-light rounded p-4">
                                    <div class="bg-white border rounded d-flex flex-shrink-0 align-items-center justify-content-center me-3" style="width: 45px; height: 45px;">
                                        <i class="fa fa-envelope-open text-primary"></i>
                                    </div>
                                    <span>neoledge@neoledge.com</span>
                                </div>
                            </div>
                            <div class="col-md-4 wow fadeIn" data-wow-delay="0.5s">
                                <div class="d-flex align-items-center bg-light rounded p-4">
                                    <div class="bg-white border rounded d-flex flex-shrink-0 align-items-center justify-content-center me-3" style="width: 45px; height: 45px;">
                                        <i class="fa fa-phone text-primary"></i>
                                    </div>
                                    <span>+012 345 6789</span>
                                </div>
                            </div>
            </div>
          </div>
          <div class="col-md-6 wow fadeInUp" data-wow-delay="0.1s">
            <div class="wow fadeInUp" data-wow-delay="0.5s">
          
             <form>
               <div class="row g-3">
                 <div class="col-md-6">
                   <div class="form-floating">
                     <input type="text" class="form-control" id="name" placeholder="Your Name" />
                     <label for="name">Your Name</label>
                   </div>
                 </div>
                 <div class="col-md-6">
                   <div class="form-floating">
                     <input
                       type="email"
                       class="form-control"
                       id="email"
                       placeholder="Your Email"
                     />
                     <label for="email">Your Email</label>
                   </div>
                 </div>
                 <div class="col-12">
                   <div class="form-floating">
                     <input type="text" class="form-control" id="subject" placeholder="Subject" />
                     <label for="subject">Subject</label>
                   </div>
                 </div>
                 <div class="col-12">
                   <div class="form-floating">
                     <textarea
                       class="form-control"
                       placeholder="Leave a message here"
                       id="message"
                       style="height: 150px"
                     ></textarea>
                     <label for="message">Message</label>
                   </div>
                 </div>
                 <div class="col-12">
                   <button class="btn btn-primary w-100 py-3" type="submit">Send Message</button>
                 </div>
               </div>
             </form>
           </div>
          </div>
          <div class="col-md-6">
           <img src="/src/assets/img/contact.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
    <!-- Contact End -->
    <FooterShow/>
  </div>
</template>
<style></style>
