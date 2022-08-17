<template>
  <div class="register">
    <div class="form">
      <div class="input-form">
        <input type="text" placeholder="Propriedade" />
        </div>
        <input type="text" placeholder="Plantação" />
        <br>
            <v-row>
    <v-col cols="12">
      <v-select
        :items="items"
        readonly
        label="Read-only"
      ></v-select>
    </v-col>
  </v-row>
        <v-divider>ou</v-divider>
      <v-row no-gutters>
        <v-row
          class="pa-3"
        >
           <v-btn  class="btn-register"
>salvar</v-btn>
        </v-row>
        <br>
        <v-row
          class="pa-3"
        >
         <v-btn  class="btn-danger"
>Cancelar</v-btn>
        </v-row>
    </v-row>
       </div>
        </div>
</template>
<script>
export default {
  name: 'camposComp',
  data: () => ({
    items: ['Foo', 'Bar', 'Fizz', 'Buzz']
  })
}
</script>
<style scoped>
.space {
  padding-left: 1rem;
  display: flex;
  align-content: center;
}
.register {
  align-items: center;
}
h1 {
  color: black;
  margin-bottom: 1rem;
}
h5 {
  color: rgb(163, 163, 163);
  margin-right: 30px;
  margin-left: 30px;
}
.form {
  text-align: center;
  margin-top: 5rem;
}
.v-btn {
  display: flex;
  /* background-color: rgba(1,149,247,255); */
  background-color: rgb(205, 40, 40);
  color: aliceblue;
  height: 1.5rem;
  margin-left: 10px;
  font-size: 10px;
  width: 14rem;
  margin-top: 1rem;
}
.btn-register {
  background-color: rgba(179, 223, 250, 255);
  color: aliceblue;
  transition: 0.5s;
}
.btn-register:hover {
  background-color: rgba(1, 149, 247, 255);
  color: aliceblue;
}
.v-divider {
  margin: 30px;
}
.v-text-field {
  display: flex;
}
input {
  border: solid rgba(216, 216, 216, 255) 1.3px;
  border-radius: 0.3rem;
  margin: 2px;
  background-color: rgba(250, 250, 250, 255);
  width: 30rem;
  height: 2rem;
  color: rgb(33, 33, 33);
  font-size: 12px;
  padding-left: 0.7rem;
}
.input-form {
  padding-top: 1rem;
  padding-bottom: 1rem;
}
img {
  width: 3rem;
}
</style>
