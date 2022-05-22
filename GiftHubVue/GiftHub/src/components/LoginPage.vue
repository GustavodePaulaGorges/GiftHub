<template>
  <div class="wrapper fadeInDown">
    <div id="formContent">
      <!-- Tabs Titles -->
      <h2 class="active">Sign In</h2>
      <h2 class="inactive underlineHover">Sign Up</h2>

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
          id="login"
          class="fadeIn second"
          name="login"
          placeholder="login"
        />
        <input
          type="text"
          id="password"
          class="fadeIn third"
          name="login"
          placeholder="Senha"
        />
        <input type="submit" class="fadeIn fourth" value="Logar" />
      </form>

      <!-- Remind Passowrd -->
      <div id="formFooter">
        <a class="underlineHover" href="#">Esqueceu a sua senha?</a>
      </div>
    </div>
  </div>
</template>
