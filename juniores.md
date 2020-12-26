# Respostas

## O que são classes, o que são objetos e qual a relação entre eles?
<p>Classes são unidades de código que encapsulam atributos e métodos, formando o molde (ou especificação) de objetos.</p> 
<p>Exemplo: A classe User contém e-mail e senha, mas pode ser a base de vários objetos, cada qual com seu status (valor para os mesmos atributos)</p>

## O que são interfaces e qual a diferença entre interfaces e classes abstratas?
<p>
Interfaces não possuem implementação, mas sim apenas assinatura. Isto é, a definição dos seus métodos sem o corpo. Funcionam como um "contrato" onde são especificados os atributos e métodos que as classes que implementam essa interface são obrigadas a implementar.</p>
</p>
<p>
Classes abstratas são um tipo especial de classe a partir da qual não há como criar instâncias. É usada apenas para ser herdada (uma espécie de super classe).
</p>

## Explique os modificadores de acesso presentes no .NET.
- protected:torna métodos e atributos acessíveis apenas à em que são assinados e a suas filhas.
- private: torna métodos e atributos acessíveis apenas à classe em que são assinados.
- public: torna métodos e atributos acessíveis a qualquer outra classe.
- internal: O acesso é limitado ao assembly atual.

## Qual a finalidade do virtual?
A palavra-chave virtual é usada para modificar uma declaração de método, propriedade, indexador ou evento e permitir que ela seja substituída em uma classe derivada.

## O que são Sealed Classes?
Quando aplicado a uma classe, o modificador sealed impede que outras classes herdem dela.

## Referências
- [Devmedia](https://www.devmedia.com.br/interfaces-x-classes-abstratas/13337)
- [Documentação da Microsoft](https://docs.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/virtual)
