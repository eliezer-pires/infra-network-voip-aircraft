# Projeto de Infraestrutura de Redes e Telefonia - Cisco em grande evento de Aviação

## Descrição Geral

Este projeto documenta a implementação de uma infraestrutura de redes e telefonia utilizando equipamentos Cisco em um grande evento de Aviação. A infraestrutura local era composta apenas por Switches Dell e Huawei, fomos chamados para implementar telefonia voip e hotlines de forma que se comunicassem com outra parte do evento que estaria ocorrendo ao mesmo tempo em outra cidade, além da telefonia também videoconferência e redundância de links para que os serviços sempre estivessem disponíveis. Apresentaremos a topologia física e lógica implementada, as configurações dos ativos de rede, além dos problemas encontrados durante a implementação e suas soluções. 

O objetivo deste repositório é servir como uma referência prática para profissionais de redes e entusiastas interessados em projetos similares.

## Cenário e Contextualização

O projeto foi realizado para uma organização de Aviação. O objetivo era implementar uma solução integrada de rede e telefonia para atender às seguintes necessidades:

- Comunicação interna eficiente por meio de VoIP entre as salas do evento e as salas do evento na outra cidade.
- Garantia de alta disponibilidade e desempenho para tráfego de dados e voz, por meio de implementação de links redundantes.

O ambiente inicial consistia apenas na infraestrutura de rede do Aerodromo com sua rede intranet, internet, seus equipamentos são Firewall PaloAlto, Switches Dell e Huawei e uma Rede Operacional do Aeroporto.

![Topologia Física da Rede Inicial](diagrams/topologia_inicial.jpg)

Foi representado apenas a infraestrutura que envolvesse o projeto, por questão de sigilo foram retiradas informações que não estão no escopo deste projeto.

## Serviços Prestados

Os principais serviços realizados durante o projeto incluem:

1. **Planejamento e Design da Rede:**
   - Definição da topologia física e lógica.
   - Seleção de equipamentos e recursos necessários.

2. **Implementação da Infraestrutura de Rede:**
   - Configuração de switches e roteadores Cisco.
   - Criação de VLANs para segmentação de tráfego.

3. **Assessoria à equipe de Segurança da Informação**
   - Definição das regras de Firewall para os serviços implementados.

4. **Implementação do Sistema de Telefonia:**
   - Configuração de VoIP com Call Manager.
   - Integração com a rede local e remota.

5. **Implementação dos Links Redundantes**
   - Ativação da Bridge para link redundante.
   - Script para Automação do Plano de Continuidade de Negócios.

6. **Testes e Otimizações:**
   - Testes de conectividade e qualidade de chamadas.
   - Ajustes de infraestrutura de acordo com novas demandas.

## Topologia Física e Lógica

A topologia implementada é apresentada abaixo:

### Topologia Física

![Topologia Física da Rede Inicial](diagrams/topologia_projetada.jpg)

Foi representado nesta topologia apenas a infraestrutura que está dentro do escopo deste projeto.

### Topologia Lógica

[Adicione aqui o diagrama lógico, caso tenha.]

> **Nota:** Os diagramas estão disponíveis na pasta `diagrams` deste repositório.

## Configurações dos Ativos

    Será acrescentado as partes relevantes das configurações implementadas nos ativos.

### Roteador CME
```plaintext
# Configuração básica


# Configuração de Roteamento


# Configuração de Telefonia Voip


```
---

### Switches

# Configuração de VLANs


# Configuração de portas


# Configuração de STP


# Configuração de Etherchannel


---

### 7. Problemas Encontrados e Soluções
Será Listado os problemas encontrados durante o projeto e explique como foram resolvidos.

```markdown
## Problemas Encontrados e Soluções

1. **Problema: Configuração incorreta de Roteamento no roteador.**
   - **Causa:** Configuração errada
   - **Solução:** Revisão e correção 

2. **Problema: Loop na rede devido a má configuração de STP.**
   - **Solução:** Configuração e verificação do protocolo Spanning Tree.
