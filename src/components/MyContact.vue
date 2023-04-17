<template>
  <h1>CONTACT ME</h1>
  <div>
    <div class="me">
      <div class="card" style="width: 16rem; height: 70%">
        <img src="https://cdn.freebiesupply.com/logos/large/2x/linkedin-icon-logo-png-transparent.png" width="30%" height="35%" class="card-img-top" alt="logolinkedin">
        <div class="card-body">
          <h5 class="card-title">Linkedin</h5>
          <p class="card-text" style="color: black">If you want to know more about me</p>
          <a href="https://www.linkedin.com/in/putrisyakirawirdiani/" class="btn btn-primary">Click Here</a>
        </div>
      </div>
      <div class="card" style="width: 16rem; height: 70%">
        <img src="https://logopng.com.br/logos/instagram-40.png" width="30%" height="35%" class="card-img-top" alt="logoig">
        <div class="card-body">
          <h5 class="card-title">Instagram</h5>
          <p class="card-text" style="color: black">Maybe you want check more my documentation</p>
          <a href="https://www.instagram.com/psyakira_w/" class="btn btn-primary">Check it</a>
        </div>
      </div>
      <div class="card" style="width: 16rem; height: 70%">
        <img src="https://logodownload.org/wp-content/uploads/2015/04/whatsapp-logo-icone.png" width="30%" height="35%" class="card-img-top" alt="logowa">
        <div class="card-body">
          <h5 class="card-title">WhatsApp</h5>
          <p class="card-text" style="color: black">You can contact me personaly</p>
          <a href="http://wa.me/089678878557" class="btn btn-primary">Contact Here</a>
        </div>
      </div>
      <div class="card" style="width: 16rem; height: 70%">
        <img src="https://www.rightclickcomputersolutions.com/wp-content/uploads/2018/05/Gmail_logo.max-2800x2800.png" width="30%" height="35%" class="card-img-top" alt="logogmail">
        <div class="card-body">
          <h5 class="card-title" style="margin-top: 7px">Gmail</h5>
          <p class="card-text" style="color: black">Just tell anything to me in here</p>
          <a href="mailto:psyakira.w@gmail.com" class="btn btn-primary">Text here</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyContact"
}
</script>

<style scoped>
h1{
  font-family: "Cambria Math";
  color: #131829;
  font-size: 50px;
}
h5{
  margin-bottom: 0;
  color: #4A4C57;
  font-family: "Arial Black";
}
a{
  color: black;
  text-decoration: none;
}
.me{
  display: flex;
  justify-content: space-between;
  padding-bottom: 5%;
}
.btn{
  color: #BFBEBC;
  background-color: #131829;
  border-color: #131829;
}
p{
  margin-top: 0;
  margin-bottom: 0;
}
</style>