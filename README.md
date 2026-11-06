# Conversor de moedas
Um conversor de moedas feito com **HTML**, **CSS** e **JavaScript**. Você informa um valor, escolhe as moedas e o site consulta a **ExchangeRate-API** para calcular a conversão.

Desenvolvemos o projeto como trabalho final da disciplina de Web 1. Foi minha primeira experiência integrando uma API a um site e uma oportunidade de colocar em prática o que estava aprendendo sobre desenvolvimento web.

### O que dá para fazer

- Converter valores entre real, dólar americano, euro, libra esterlina, iene, yuan, dólar australiano e rupia nepalesa.
- Atualizar a conversão ao mudar o valor ou selecionar outra moeda.
- Inverter as moedas de origem e destino com um botão.

### Tecnologias

- **HTML:** estrutura da página e dos formulários.
- **CSS:** estilos e organização visual.
- **JavaScript:** interação com a página, consulta à API e cálculo da conversão.
- **ExchangeRate-API:** fornecimento das taxas de câmbio.
- **Font Awesome:** ícones da interface.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/LucasLuidy?tab=repositories&language=html5)
[![CSS3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/LucasLuidy?tab=repositories&language=css3)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/LucasLuidy?tab=repositories&language=javascript)

### Como executar

1. Clone o repositório:
```js
   git clone https://github.com/LucasLuidy/Conversor-de-moedas.git
   cd Conversor-de-moedas
```
2. No arquivo **script.js**, substitua o valor da constante apiKey pela sua chave da ExchangeRate-API:
```js
   const apiKey = 'SUA_CHAVE_DA_API';
```

3. Abra o arquivo **index.html**  no navegador. Se preferir, use a extensão Live Server do VS Code.

### Sobre o desenvolvimento
A parte visual me deu trabalho, principalmente o CSS. Eu ainda estava começando a conhecer UI/UX e busquei referências em outros sites para montar uma interface mais simples. Gostei bastante da estética que conseguimos alcançar nessa etapa.

A integração com a API também foi um dos maiores desafios. Era a primeira vez que eu fazia esse tipo de conexão, então precisei entender como buscar os dados e usar a resposta para mostrar a conversão na página.

### Limitações da versão atual
Os formulários de contato e newsletter fazem parte da interface, mas não possuem integração para envio. As seções que mencionam análises de mercado, alertas e consultoria também são conteúdo demonstrativo da página.

O indicador de última atualização ainda precisa de ajuste: ele usa os minutos do relógio local e não informa quando a taxa foi atualizada pela API.

### Autores
- Lucas Luidy Tolentino Gonçalves
- Estevão Castilho Soares Aquino
- Gabriel Alves Teixeira
