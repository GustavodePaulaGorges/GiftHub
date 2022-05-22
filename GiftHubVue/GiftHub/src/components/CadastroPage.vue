<template>
  <div class="wrapper fadeInDown">
    <div id="formContent">
      <!-- Tabs Titles -->
      <h2 class="active">Cadastre-se</h2>

      <!-- Icon -->
      <div class="fadeIn first">
        <img
          src="@/imgs/1946429.png"
          class="userIcon"
        />
      </div>

      <!-- Login Form -->
      <form>
        <input
          type="text"
          id="E-mail"
          class="fadeIn second"
          name="login"
          placeholder="E-mail"
        />
        <input
          type="text"
          id="Senha"
          class="fadeIn third"
          name="E-mail"
          placeholder="Senha"
        />
        <input type="submit" class="fadeIn fourth" value="Criar " />
      </form>

      <!-- Remind Passowrd -->
      <div id="formFooter">
        <a class="underlineHover" href="#">Já tem uma conta?</a>
      </div>
    </div>
  </div>
</template>
