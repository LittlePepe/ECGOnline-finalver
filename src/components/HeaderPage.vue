<template>
  <v-app>
    <v-container class="header-container" fill-height align-center>
      <v-row align="center" no-gutters>
        <!-- Coluna do texto de introdução -->
        <v-col cols="12" sm="6" class="text-center intro-column">
          <h1 class="textostyle" style="font-weight: bold; margin-bottom: 10px;">
            VENHA FAZER PARTE
          </h1>
          <h1 class="textostyle mb-10">
            Somos uma central de laudos que atende clínicas e médicos do Brasil inteiro através de um dos melhores sistemas de Telemedicina disponíveis. Quer fazer parte?
          </h1>
          <v-btn outlined height="10vh" color="white" rounded class="custom-button">
            Faça seu orçamento
            <v-icon right style="color:#AE1613">mdi-menu-down</v-icon>
          </v-btn>
        </v-col>

        <!-- Coluna para a logo -->
        <v-col cols="12" sm="6" class="text-center logo-column">
          <!-- <h1 class="textostyle">LOGO</h1> -->
          <v-img max-width="70vh" style="margin-left: 15vh; margin-bottom: 10vh;"  src="../assets/Projeto-Logo.png" alt="logo"></v-img>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  // Sem mudanças no script
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');

.app {
  background-image: url('./src/assets/imageback.png');
  background-size: cover;
  background-repeat: no-repeat;
  /* Outros estilos se necessário */
}

.header-container {
  display: flex;
  padding: 10vh 5vh; /* Ajustar para responsividade */
  min-height: 90vh; /* Proporção do tamanho */
  max-height: 1000vh; /* Evita que a seção seja muito grande */
  max-width: 400%;
  align-items: center; /* Mantém conteúdo centralizado */
  background-image: url('./src/assets/imageback.png');
  background-size: cover;
  background-repeat: no-repeat;
  margin-bottom: 25vh;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(5.8px);
}


.textostyle {
  color: white;
  font-family: "Inter", sans-serif;
  font-size: 3vh;
  font-weight: 300;
}

.custom-button {
  font-size: 20px;
  font-weight: 800;
  color: #AE1613;
}

.logo-column {
  margin-bottom: 5vh; /* Espaçamento para evitar conflitos */
  margin-top: 8vh;
}

.intro-column {
  padding-top: 3vh; /* Espaçamento para centralizar o texto */
}

.vertical-line {
  height: 50px;
  width: 2px;
  background-image: url(imageback.jpg);
  margin: auto;
}
</style>
