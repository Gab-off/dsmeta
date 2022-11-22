# DSMeta by Gab-off
Aplicação Front-end e Back-end criada na semana [DEVSUPERIOR](https://devsuperior.com.br/cursos) do professor Nélio Alves no youtube.
Em 3 aulas construimos do zero utilizando Spring e React essa aplicação simples porém funcional para mostrar os dados de vendas dos vendedores e enviar um sms através
de um botão indicando o ganho do vendendor em um período X.
A aplicação funcional está no [DSMeta by Gab-off.](https://dsmetabygab.netlify.app/)
Utilizamos o Heroku para subir a aplicação do Back-end e o Netlify para a parte visual.
Tivemos um overview rápido a respeito de todas ferramentas utilizadas mas para alguém que já estudou um pouco de Front-end e está estudando JAVA, ter essa experiência
traz o feeling de saber como irá ser em uma aplicação real.

## Tela inicial
Nessa tela podemos ver os arquivos mostrados na tela, retirado do banco de dados onde também podemos pesquisar por datas específicas.
![First Screen](../assets/first_screen.png?raw=true)

## Toast alert adicionado
Adicionamos um alerta toast para indicar quando o botão de envio de sms for enviado.
![Toast image](../assets/toasted_pressed.png?raw=true)

O envio do sms é integrado com a ferramenta [Twilio](https://www.twilio.com/pt-br/) que disponibiliza o número para fazermos o envio.
