![image](https://github.com/Alexandre-Konrath/teste-grid/assets/160286787/1eb598a9-afe1-4c40-91ee-9e0e18698611)

Mesmo preferindo o display: flex; aprendi diverças coisas muito interessantes com o display: grid;. Coisas que com o flex seria um pouco mais chatas de se fazer e o grid deixa mais fácil
Ví que criar colunas e linhas nunca foi tão facil usando por exemplo
  display: grid;
  grid-template-columns: auto auto auto;
  grid-template-rows: auto auto auto auto;
Ou fazendo deste modo, colocando classes no objeto que deseja e você literalmente pode por ele em qualquer lugar.
  display: grid;
  grid-template-areas:
    "gato9 gato12 gato10 "
    "gato15 gato14 gato13 "
    "gato16 gato17 gato11 ";
  margin: 10px;
}

.gato9 {
  grid-area: gato9;
}
.gato10 {
  grid-area: gato10;
}
