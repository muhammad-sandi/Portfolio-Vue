<script setup>
  import WelcomeItem from './WelcomeItem.vue'
  import DocumentationIcon from './icons/IconDocumentation.vue'
  import ToolingIcon from './icons/IconTooling.vue'
  import PhoneIcon from './icons/IconPhone.vue'
  import EmailIcon from './icons/IconEmail.vue'
  import AddressIcon from './icons/IconAddress.vue'
  import EcosystemIcon from './icons/IconEcosystem.vue'
  import CommunityIcon from './icons/IconCommunity.vue'
  import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
    integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <!-- <img alt="Vue logo" class="img" src="src/assets/cv-img.jpg" width="100" height="" /> -->

  <div class="container-personal">
    <WelcomeItem>
      <template #icon>
        <DocumentationIcon />
      </template>
      <template #heading>Nama</template>
      <p>Muhammad Sandi Haikal</p>
    </WelcomeItem>

    <WelcomeItem>
      <template #icon>
        <ToolingIcon />
      </template>
      <template #heading>Role Pekerjaan</template>
      <p>Front End Developer</p>
    </WelcomeItem>

    <WelcomeItem>
      <template #icon>
        <AddressIcon />
      </template>
      <template #heading>Alamat</template>

      <p>Jl. Masjid Al-Ishlah No.47A</p>
    </WelcomeItem>

    <WelcomeItem>
      <template #icon>
        <EmailIcon />
      </template>
      <template #heading>Email</template>
      <p>muhammadsandi5050@gmail.com</p>
    </WelcomeItem>

    <WelcomeItem>
      <template #icon>
        <PhoneIcon />
      </template>
      <template #heading>No. Handphone</template>
      <p>0858-5143-6201</p>
    </WelcomeItem>

    <!-- <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a target="_blank" href="https://vuejs.org/sponsor/">becoming a sponsor</a>.
  </WelcomeItem> -->
  </div>

  <footer class="text-center text-white" style="background-color: #f1f1f1;">
    <!-- Grid container -->
    <div class="container pt-4 d-flex justify-content-center">
      <section class="mb-4">
        <a class="btn btn-link btn-floating btn-lg text-dark m-1"><i class="fa fa-instagram"></i></a>
      </section>
      <section class="mb-4">
        <a class="btn btn-link btn-floating btn-lg text-dark m-1"><i class="fa fa-github"></i></a>
      </section>
      <section class="mb-4">
        <a class="btn btn-link btn-floating btn-lg text-dark m-1"><i class="fa fa-facebook"></i></a>
      </section>
    </div>

    <div class="text-center text-dark p-3" style="background-color: rgba(0, 0, 0, 0.2);">
      © 2022 Copyright:
      <a class="text-dark" href="https://mdbootstrap.com/">Muhammad Sandi</a>
    </div>
  </footer>

</template>

<style>
  .container-personal {
    /* display: flex; */
    flex-wrap: wrap;
    justify-content: center;
    margin-left: 255px;
  }

  .img {
    margin-top: 15px;
    margin-left: 230px;
    border-radius: 10px;
  }
</style>