<template>
  <div class="register">
    <div class="form">
      <div class="input-form">
        <div class="select">
      <div class="input-container">
        <select>
          <option value="">Selecione a propriedade</option>
          <option>assadad</option>
        </select>
      </div>
        </div>
        </div>
        <input type="text" placeholder="Plantação" />
        <br>
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
  margin-left: 25px;
  font-size: 10px;
  width: 14rem;
  margin-top: 1rem;
}
.btn-register {
  background-color: rgba(1, 149, 247, 255);
  color: aliceblue;
  transition: 0.5s;
}
.btn-register:hover {
  background-color: transparent;
  color: #222;
}
.btn-danger:hover {
  background-color: transparent;
  color: #222;
}
.v-divider {
  margin: 30px;
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
 select{
  height: 2rem;
  width: 300px;
  display: flex;
  width: 30rem;
  margin: 2px;
  border: solid rgba(216, 216, 216, 255) 1.3px;
  border-radius: 0.3rem;
  background-color: rgba(250, 250, 250, 255);
    font-size: 12px;
    padding-left: 0.7rem;
    margin: 2px;
    color: rgb(123, 123, 123);
}
.input-container{
  padding-left: 2.1rem;
  margin-top: 1rem;
}
</style>
