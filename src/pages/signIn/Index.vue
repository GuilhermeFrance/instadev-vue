<template>
  <q-page class="flex flex-center column q-pa-md">
    <q-img class="logo " src="../../assets/instadev-logo.svg" style="margin-bottom: 30px;"></q-img>
    <div>
    <div style="width: 300px; margin: 20px;">
    <q-btn class="sign-In-button full-width"  icon="fa-brands fa-facebook-f" label="Continue with Facebook" tyle="width: 200px" no-caps/>

    </div>
    <div class="row full-width items-center justify-center" style="margin-bottom: 24px;">
      <q-separator class="separator" inset  />
     <span style="font-weight: 100;">OR</span>
      <q-separator class="separator" inset />
    </div>

    <q-input filled v-model="text" label="E-mail" class="full-width q-mb-md inputBox" />
    <q-input filled v-model="text" label="Senha" type="password" class="full-width" />
    <div class="column q-mt-sm items-end full-width"><a class="link">Forgot password?</a></div>


    <q-btn class="sign-In-button full-width q-mt-lg"  no-caps>
      <span>Log In</span>
    </q-btn>
    </div>
    <div class="signUp q-mt-md">
      <a class="link" href="" style="font-size: 15px"
        ><span class="link-a">Não é cadastrado?</span> <strong>Cadastre-se</strong></a
      >
    </div>
  </q-page>
</template>

<script >
export default {
  name: 'SignIn',
}
</script>

<style lang="scss" scoped>
.logo {
  height: 50px;
  width: 194px;
}
.sign-In-button {
  height: 35px;
  border-radius: 6px;
  background-color: #1877f2;
  color: white;
}
.link {
  text-decoration: none;
  font-size: 15px;
  font-weight: 600;
  color: #1877f2;
}
.link-a {
  color: #aea9a9;
}
.separator {
  width: 30%;
}
</style>

<style scoped>
.q-btn>>>.q-icon {
  font-size: 15px;
}
</style>


