
## SOLID
	SOLID é um acrônimo dos cinco primeiros princípios da OOP e design de códigos. Seus princípios devem ser aplicados sempre para se obter os benefícios da OOP.

🟢 Fácil de se manter , adaptar e se ajustar às alterações de escopo.<br>
🟢 Código conciso (estável e de fácil entendimento).<br>
🟢 Extensível para alterações com o menor esforço necessário.<br>
🟢 Possibilita o máximo de reaproveitamento.<br>
🟢 Permaneça o máximo de tempo possível em utilização (possibilidade de adicionar novas funcionalidades).<br>

🔴 Dificuldade na testabilidade / criação de unidade.<br>
🔴 Código macarrônico, sem estrutura ou padrão.<br>
🔴 Dificuldade de isolar funcionalidades (muito acoplamento, multiplas finalidades em uma classe).<br>
🔴 Duplicação de código (alterações precisam ser feitas em N pontos).<br>
🔴 Instabilidade (o código quebra facilmente em vários pontos após alguma mudança).<br>

  <img src="https://raw.githubusercontent.com/LeoHLV/Armazenamento/main/Imagens/Sem%20T%C3%ADtulo-1.webp" width="100%">

```SRP ( Single Responsability Principle ) ```<br>
▶ Cada classe possui responsabilidade única e apenas um motivo para ser modificada. <br>
▶ Métodos devem ser voltados apenas a finalidade de sua implementação. <br>

```OCP ( Open Closed ) ```<br>
▶ Entidades de softwere (classes, módulos, funções, etc) devem estar abertas para extensões, mas fechadas para modificação.<br>
▶ Não se deve adicionar funcionalidades a uma classe que funciona perfeitamente, deve-se extender e adicionar funcionalidades por fora.<br>
▶ Deve ser analisado dois fatores: <br>
<img src="https://raw.githubusercontent.com/LeoHLV/Armazenamento/main/Imagens/emoji_empty.webp" height="16px"> 1. Comportamento que já possui : só pode ser alterado na própria classe!<br>
<img src="https://raw.githubusercontent.com/LeoHLV/Armazenamento/main/Imagens/emoji_empty.webp" height="16px"> 2. Comportamento que virá a possuir : pode considerar adaptar apenas para receber extensões.

```LSP ( Liskov Subscription Principle ) ```<br>
▶ Subclasses devem ser substitutíveis por suas Superclasses.<br>
▶ Abrange conceitos de Upcast e Downcast onde subclasses possuem construtores com mesmos tipos e quando instanciados elementos a partir da super classe, ambos executam resultados sem apresentar erros.<br>
	
```ISP ( Interface Segregation Principle ) ```<br>
▶ Abrange conceitos de interfaces.<br>
▶ Clientes ( clientes da interface ou classes ) não devem ser forçados a depender de métodos que não usam.<br>
▶ Muitas interfaces específicas são melhores que uma interface única.<br>

```DIP ( Dependency Inversion Principle ) ```<br>
▶ Abrange conceitos de Abstração.<br>
▶ Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender de abstrações.<br>
▶ Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.<br>
▶ Dependa de uma abstração e não de uma implementação.<br>
