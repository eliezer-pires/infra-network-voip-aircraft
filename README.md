# Projeto de Infraestrutura de Redes e Telefonia - Cisco em grande evento de Aviação

## Descrição Geral

Este repositório documenta a implementação de uma infraestrutura de redes e telefonia utilizando equipamentos Cisco em um grande evento de aviação. O projeto visou integrar a comunicação de VoIP e hotlines entre diferentes locais do evento, realizados simultaneamente em cidades distintas. Além disso, foram implementadas soluções para videoconferência ponto a ponto e redundância de links, garantindo alta disponibilidade dos serviços.

Apresentamos aqui a topologia física e lógica projetada, as configurações dos ativos de rede, os desafios enfrentados durante a implementação e as soluções aplicadas. Este material serve como uma referência prática para profissionais de redes e entusiastas interessados em projetos similares.

## Cenário e Contextualização

O evento foi realizado em um aeródromo com infraestrutura composta por:

*Equipamentos existentes:* Firewall Palo Alto, switches Dell e Huawei.
*Rede operacional:* Redes intranet e internet do aeródromo.

A organização exigiu:

- Comunicação eficiente via VoIP entre as salas do evento e outro local simultâneo em outra cidade.
- 3 Videoconferências ponto a ponto com outra cidade em alta disponibilidade.
- Garantia de alta disponibilidade de dados e voz por meio de links redundantes.

Por questões de sigilo, a topologia inicial foi ajustada para incluir apenas os elementos diretamente relacionados ao escopo deste projeto.

![Topologia Física da Rede Inicial](diagrams/topologia_inicial.jpg)

## Serviços Prestados

Os principais serviços realizados durante o projeto incluem:

1. **Planejamento e Design da Rede:**
   - Criação da topologia física e lógica.
   - Seleção de equipamentos e dimensionamento dos recursos necessários.

2. **Implementação da Infraestrutura de Rede:**
   - Configuração de switches e roteadores Cisco.
   - Segmentação de tráfego com VLANs.

3. **Assessoria à equipe de Segurança da Informação:**
   - Definição e aplicação de regras de firewall para os serviços implementados.

4. **Sistema de Telefonia:**
   - Configuração de VoIP utilizando Call Manager.
   - Integração entre as redes locais e remotas.

5. **Redundância de Links:**
   - Configuração de uma bridge para links redundantes.
   - Automação do plano de continuidade com script específico.

6. **Testes e Otimizações:**
   - Verificação de conectividade, qualidade de chamadas e estabilidade de links.
   - Ajustes conforme novas demandas surgiram durante o evento.

## Topologia Física e Lógica

As topologias desenvolvidas estão detalhadas abaixo:

### Topologia Física

![Topologia Física da Rede Inicial](diagrams/topologia_projetada.jpg)

Esta topologia abrange exclusivamente os componentes e redes que fazem parte do escopo do projeto.

### Topologia Lógica

[Adicione aqui o diagrama lógico, caso tenha.]

> **Nota:** Os diagramas estão disponíveis na pasta `diagrams` deste repositório.

## Configurações dos Ativos

    As configurações mais relevantes dos equipamentos utilizados são apresentadas a seguir:

### Roteador CME
```plaintext
# Configuração básica


# Configuração de Roteamento


# Configuração de Telefonia Voip


```
---

### Switches
```plaintext
# Configuração de VLANs


# Configuração de portas


# Configuração de STP


# Configuração de Etherchannel

```
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
