<template>
    <div>
             <div class="question">
                  <div class="container">
                        <h3>GOT A QUESTION OR INQUIRY?</h3>
                  </div>
             </div>
             <div style="width: 100%"><iframe width="100%" height="485" src="https://maps.google.com/maps?width=100%&amp;height=600&amp;hl=en&amp;q=Romanovih%2033+(My%20Business%20Name)&amp;ie=UTF8&amp;t=&amp;z=15&amp;iwloc=B&amp;output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe></div><br />
             <div class="container">
               <div class="container-contact">
                <div class="form">
                    <h3>CONTACT FORM</h3>
                    <p>Proin pharetra volutpat quam, nec malesuada elit lobortis id. Curabitur mauris sem, scelerisque et sem et, auctor lobortis felis.</p>
                    
                            <input type="text" name="tekst" placeholder="Name" class="input-field" >
                             <br>
                            <input type="email" name="email" placeholder="Email Address" class="input-field">
                             <br>
                            <input type="text" name="subject" placeholder="Subject" class="input-field">
                             <br>
                            <textarea class="input-text" rows="10"  ></textarea>
                             <br>
                            <button type="button" name="send" class="btn-contact">SEND MESSAGE</button>
                 </div>
                <div class="contact">
                    <div class="heder-info">
                            <h4>CONTACT INFO</h4>
                            <p>Lorem ipsum dolor sit amet, consectetur elit. Cras <br> tortor neque,ante in,
                                bibendum ornare orci.</p>
                            <b>email:</b><span id="display-info">info@display.com</span><br>
                            <b>phone:</b><span>1.306.222.4545</span><br> <br>
                            <p>
                                222 2nd Ave South
                                <br>
                                Saskabush, SK S7M 1T6
                            </p>
                            <div id="store-house">
                            <h4>STORE HOURS</h4>
                           </div>
                           <br><br>
                                    <p class="store-paragraf">Monday - Thursday</p>
                                    <p class="store-paragraf">Friday
                                    <p class="store-paragraf">Saturday
                                    <p class="store-paragraf">Sunday & Holiday</p>
                            <div id="am-pm"> 
                                    <p>8am - 5pm</p>
                                    <p>8am - 6pm</p>
                                    <p>9am - 5pm</p>
                                    <p>Closed</p>
                            </div>
                    </div>
                </div>
               </div>
             </div> 
         </div>
</template>
<script>
export default {
    
}
</script>
<style>
.container-contact{
  width: 970px;
  height: 600px;
}
.question {
    background-color: #2ecc71;
    width: 100%;
    height: 100px;
  }
  .question h3{
    width: 461px;
    height: 26px;
    color: white;
    padding-top: 30px;
    font-weight: 500;
    font-size: 28px;
  }
  .from{
    width: 550px;
    height: 600px;
  }
  .form h3{
    color: #8a8888;
    width: 190px;
    height: 18px;
    font-size: 19px;
    font-weight: 500;
    margin-bottom: 40px;
  }
  .form p{
    width: 555px;
    height: 35px;
    color: #8a8888;
    font-size: 15px;
  }
  .input-field {
    width: 350px;
    height: 45px;
    border: 2px solid #8a8888;
    box-sizing: border-box;
    margin-bottom: 20px;
  }
  .input-text {
    width: 560px;
    height: 221px;
    border: 2px solid #8a8888;
    margin-bottom: 10px;
  }
  .btn-contact {
    width: 140px;
    height: 40px;
    font-weight: 600;
    border: none;
    background-color: rgb(45,204,114); 
    color: white;
  }
  .contact{
    margin-left: 670px;
    margin-top: -600px;
  }
  .heder-info h4{
    width: 181px;
    height: 18px;
    color: #8a8888;
    padding-top: 21px;
    font-size: 19px;
    font-weight: 500;
    margin-bottom: 57px;
  }
  .heder-info p{
    width: 338px;
    height: 142;
    color: #8a8888;
    font-size: 15px;
  }
  .heder-info b{
    color: #8a8888;
    font-size: 15px;
  }
  .heder-info span{
    color: #8a8888;
    font-size: 15px;
  }
  #display-info {
    color: #2ecc71;
  }
  #store-house {
    width: 170px;
    height: 18px;
    color: #8a8888;
    font-size: 19px;
    font-weight: 500;
    margin-top: -10px;
  }
  #am-pm {
    width: 80px;
    height: 50px;
    margin-top: -150px;
    margin-left: 220px;
    color: #8a8888;
  }
</style>