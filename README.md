# goMarketplace

<h1>
<img src="src/assets/logo.png">
</h1>
<br />



## 💬 Sobre
Aplicação que simula um market place, baseada no desafio 08 do **Bootcamp GoStack 11**, com o intuito de fixar o conteúdo sobre <u>fundamentos de hooks</u> do React-Native.

## :hammer_and_wrench: Tecnologias principais utilizadas
<ul>
  <li>
  react<br>
  &emsp;&bull; version: 16.11.0
  </li>
  <li>
  react-native<br>
  &emsp;&bull; version: 0.62.2
  </li>
  <li>
  axios<br>
  &emsp;&bull; version: 0.19.2
  </li>
</ul>

## Como reproduzir

<ol>
  <li>Realize o clone desse repositório;</li><br>
  <li>No local em que foi clonado, execute o comanto <i><b>yarn</b></i> para a instalação de todas as dependências do projeto;</li><br>
  <li>Para emular o servidor que retornará a lista de produtos disponíveis:
    &emsp;
    <ul>
      <li>
      Se estiver rodando em um dispositivo virtual:<br>
      <b><i>json-server server.json -p 3333</i></b>
      </li><br>
      <li>
      Agora, caso seja em um dispositivo físico ou em algum outro endereço da rede<br>
      <b><i>json-server server.json -p 3333 -H 192.168.0.15</i></b>
      </li>
    </ul>
  </li><br>
  <li>Execute o comando <b><i>yarn android</i></b> para realizar a instalação da aplicação em seu dispositivo.</li>
</ol>
