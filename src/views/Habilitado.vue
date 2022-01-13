<template>
  <v-container fluid class="habilitado__container">
    <v-row class="habilitado_row__top">
      <v-col>
        <v-row class="top-title">
          <v-col class="main">
            <span> Pase de movilidad: </span>
            <v-icon :size="$vuetify.breakpoint.xs ? 15 : 25"
              >mdi-thumb-up</v-icon
            >
          </v-col>
        </v-row>
        <v-row class="top-text">
          <v-col class="main">
            <h1>Habilitado</h1>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <div class="box">
      <v-row class="box-info">
        <v-col>
          <div class="data">
            <h2 class="run">run: 17.482.353-7</h2>
            <h2 class="nombre">NOMBRE NOMBRE</h2>
            <h2 class="other">Fuckin OMS</h2>
          </div>
          <div class="escanear">
            <v-btn outlined>
              <v-icon> mdi-apps </v-icon>ESCANEAR NUEVO PASE</v-btn
            >
          </div>
        </v-col>
      </v-row>
      <v-row class="box-alert">
        <v-col>
          <p>
            El <strong>Pase de movilidad HABILITADO</strong> acredita que la
            persona en consulta ya ha cumplido con el período de 14 días luego
            de completar su esquema de vacunación contra el COVID-19 y que,
            además, no se encuentra con indicación de aislamientoobligatorio
            determinado por la autoridad sanitaria según los registros oficiales
            actuales.
          </p>
        </v-col>
      </v-row>
      <v-row class="box-logos">
        <v-col class="gob col-12 col-sm-6">
          <v-img src="https://res.cloudinary.com/dhf2d9he9/image/upload/v1642014081/pase-imbecilidad-v3/logogb_spu2ca" class="imggob" />
        </v-col>
        <v-col class="minsal col-12 col-sm-6">
          <v-img src="https://res.cloudinary.com/dhf2d9he9/image/upload/v1642014081/pase-imbecilidad-v3/logomsl_nsr55g" class="imgminsal" />
        </v-col>
      </v-row>
    </div>
    <v-img src="@/assets/logominsal.png" class="imgminsal" />
  </v-container>
</template>
<script>
export default {
  name: 'Habilitado',
  metaInfo: {
    title: 'Pase Habilitado',
    titleTemplate: '%s - Ministerio de Salud',
    htmlAttrs: {
      lang: 'es',
      amp: true
    }
  }
}
</script>
