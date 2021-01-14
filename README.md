# AULA 01

O que era o projeto Mono criado por Miguel de Icaza em 2001?
Uma reimplementação black box do .NET, criado de forma independente por ele com foco em ser open source e multiplataforma.

O .NET Core é uma implementação open source e multiplataforma do .NET Standard. Qual dos itens abaixo é uma das outras implementações?
.NET Framework

Qual é a ordem correta de atuação de cada componente dentro do .NET?
Código Fonte > Compilador da linguagem > Linguagem Intermediária > CLR > Linguagem de Máquina

Em qual década a Microsoft foi criada?
1970

O que acontece a partir de 2020 com relação ao .NET?
O .NET Framework deixará de ser evoluido, mantendo-se a evolução apenas do .NET Core, que passará se chamar apenas .NET.

Qual linguagem de programação começou a ser criada pela Microsoft em 1999 com ajuda de Anders Hejlsberg?
C#

Qual o foco da Microsoft a partir de 2014?
Cloud.

Em qual ano surgiu a primeira versão do Visual Studio?
1997

Em 1999, Jason Zander ajudou na criação de um CLR. Qual o significado de CLR?
Common Language Runtime

Qual dos fatos a seguir não é verdadeiro?
Em 2014 o empresário Satya Nadella compra a Microsoft e se torna sócio majoritário da empresa.

# AULA 02

Qual dos itens abaixo é necessário ter instalado na máquina para desenvolver aplicações .NET?
.NET SDK

O que faz o comando 'dotnet restore' na CLI do .NET?
Restaura os pacotes e dependências do projeto.

Qual o comando para criar uma aplicação console via CLI do .NET com o nome 'Teste'?
dotnet new console -n Teste

Qual o comando parâmetro para visualizar a documentação de ajuda da CLI do .NET?
--help

O que significa CLI?
Command Line Interface

Qual é o comando da CLI do .NET para compilar o código fonte e gerar as DLL's?
dotnet build

Qual o comando para rodar uma aplicação .NET via CLI?
dotnet run

Qual dos itens abaixo não compõe o pacote de instalação do .NET SDK?
Visual Studio Code

Qual dos itens abaixo é uma opção multiplataforma para edição/criação do meu código fonte em .NET?
Visual Studio Code.

O que é uma aplicação console?
Uma aplicação que é executada em um terminal.

# AULA 03

Qual dos itens a seguir é exemplo de membro?
Campos.

O código e os recursos de Linguagem Intermediária são armazenados no disco em um arquivo executável chamado:
Assembly

Os assemblies gerados na compilação do C# geralmente possuem qual extensão?
.exe ou .dll

Qual o nome da compilação para converter o código de Linguagem Intermediária em instruções de máquina nativas?
JIT (Just in Time)

Qual dos itens a seguir é exemplo de tipo?
Classe.

Qual é a função do Garbage Collector?
Limpar objetos não utilizados da memória.

O que um código C# gera ao ser compilado no comando "dotnet build"?
Código compilado em Linguagem Intermediária.

Qual dos itens a seguir é parte da estrutura de um programa C#?
Todas as alternativas estão corretas.

Quando os programas C# são compilados, eles são fisicamente empacotados em:
Assemblies.

Quem converte os assemblies em Linguagem de Máquina?
CLR

# AULA 04

Quais destes são instruções para tratativa de exceções?
try e catch

Qual das afirmações não é verdadeira sobre Arrays?
Arrays são tipos de valor.

Os índices dos elementos de um array começam a ser contados em:
0

Qual destes não é exemplo de um tipo Valor?
class

O que é correto afirmar sobre variáveis de tipo Valor?
Variáveis de tipos de valor contêm diretamente seus dados.

Quais destes são instruções de repetição?
for e while

Qual das inicializações de array a seguir é inválida?
string[] a = new int[] {1, 2, 3};

O que é correto afirmar sobre variáveis de tipo Referência?
Variáveis de tipos de referência armazenam referências a seus dados.

Quais destes são instruções condicionais?
if e switch

Qual destes não é exemplo de um tipo Referência?
enum

# AULA 05

Uma classe é uma estrutura de dados que combina:
Estado e ações.

Sobre membros é correto afirmar:
Todas as alternativas são corretas.

Quando a classe A herda da classe B, a classe A herda todos os membros da classe B. Sobre esta afirmação é correto afirmar que:
Nem todos os membros são herdados.

Sobre métodos é errado afirmar:
Os métodos não podem ter um tipo de retorno.

Qual dos itens abaixo não representa um tipo de acessibilidade de um membro?
static

O que são objetos?
São instâncias de uma classe.

O que indica o modificar "ref" antes de um parâmetro em um método?
Indica que aquele parâmetro será passado como referência.

Sobre objetos é correto afirmar
Todas as alternativas estão corretas.

Um método internal pode ser acessado por qualquer parte do código. Sobre esta afirmação:
Ela está correta em partes, pois o internal só pode ser acessado por classes do seu próprio assembly.

Sobre métodos estáticos é correto afirmar:
Todas as alternativas estão corretas.

# AULA 06

O que é uma Interface em C#?
Uma interface define um contrato que pode ser implementado por classes e structs.

Qual área da memória que as Classes requerem alocação e as Structs não requerem?
Heap

O que são Structs?
São estruturas de dados que podem conter membros de dados e membros de ação.

Qual área da memória que normalmente as Structs são alocadas?
Stack

Um Enum que não declara explicitamente um tipo subjacente tem um tipo subjacente:
int

O que é um Enum no C#?
É um tipo de valor distinto com um conjunto de constantes nomeadas.

Qual das alternativas abaixo não é verdadeira sobre Structs?
As structs são tipos de valor e requerem alocação de heap.

Sobre Interface é correto afirmar:
Todas as afirmativas estão corretas.

Sobre Enums é correto afirmar:
Eles fornecem significado semântico a valores discretos.

Qual o tipo que as Strucuts se enquadram?
Tipo valor.
