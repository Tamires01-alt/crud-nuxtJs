<template>
  <b-container>
    <b-row class="justify-content-md-center">
      <b-col md="6">
        <b-card title="Login">
          <b-form @submit.prevent="login">
            <b-form-group
              label="E-mail"
              label-for="email-input"
              description="Digite o seu endereço de e-mail"
            >
              <b-form-input
                id="email-input"
                v-model="email"
                type="email"
                required
              ></b-form-input>
            </b-form-group>

            <b-form-group
              label="Senha"
              label-for=""
              description="Digite a sua senha"
            >
              <b-form-input
                id=""
                type="password"
                required
              ></b-form-input>
            </b-form-group>

            <b-button type="submit" variant="primary">Entrar</b-button>
          </b-form>
        </b-card>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
</script>
