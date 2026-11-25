# Laboratório de Segurança Híbrida com Wazuh

**SIEM \| Monitoramento de Segurança \| Linux \| Windows \| Cloud \|
Blue Team**

## Sobre o projeto

Este projeto tem como objetivo construir um laboratório de monitoramento
de segurança utilizando o **Wazuh** como plataforma centralizada de SIEM
e monitoramento de endpoints.

A proposta é explorar um ambiente híbrido, integrando infraestrutura
local (*on-premises*) e recursos em nuvem, permitindo estudar a coleta,
centralização e análise de eventos de segurança provenientes de
diferentes sistemas operacionais e ambientes.

Além da implementação técnica, este repositório documentará as etapas de
configuração, decisões de arquitetura, dificuldades encontradas,
procedimentos de validação e aprendizados obtidos durante o
desenvolvimento.

## Objetivos

-   Compreender a arquitetura e os principais componentes do Wazuh.
-   Instalar e configurar uma infraestrutura centralizada de
    monitoramento.
-   Integrar endpoints Linux e Windows.
-   Explorar o monitoramento de eventos de segurança.
-   Estudar conectividade e integração entre ambientes locais e cloud.
-   Analisar alertas e eventos apresentados pela plataforma.
-   Desenvolver documentação técnica e procedimentos de troubleshooting.

## Arquitetura proposta

A arquitetura prevê a utilização de um servidor Wazuh hospedado
localmente em uma máquina virtual, com endpoints distribuídos entre
infraestrutura local e ambiente em nuvem.

**Componentes planejados:**

  Componente                Tecnologia        Ambiente
  ------------------------- ----------------- ----------------
  Servidor SIEM             Wazuh             Local / VMware
  Sistema do servidor       Ubuntu Server     Local / VMware
  Endpoint Linux            Ubuntu            Cloud
  Endpoint Windows          Windows           Cloud
  Infraestrutura em nuvem   Microsoft Azure   Cloud

*A disponibilidade dos recursos em nuvem será validada antes da
implementação dessa etapa.*

## Tecnologias e ferramentas

-   Wazuh
-   Ubuntu Server
-   Ubuntu Linux
-   Windows
-   VMware
-   Microsoft Azure
-   GitHub

## Estrutura do repositório

``` text
wazuh-hybrid-security-lab/
│
├── README.md
│
├── docs/
│   ├── arquitetura.md
│   └── planejamento.md
│
├── installation/
│   └── servidor-wazuh.md
│
├── endpoints/
│   ├── agente-linux.md
│   └── agente-windows.md
│
├── network/
│   └── conectividade.md
│
├── analysis/
│   └── analise-de-eventos.md
│
└── evidence/
    └── screenshots/
```

## Etapas do projeto

-   [ ] Planejamento e documentação da arquitetura.
-   [ ] Preparação da máquina virtual Ubuntu Server.
-   [ ] Instalação e configuração do Wazuh.
-   [ ] Integração de um endpoint Linux.
-   [ ] Integração de um endpoint Windows.
-   [ ] Validação da coleta de eventos.
-   [ ] Análise de alertas e eventos de segurança.
-   [ ] Estudo da integração com ambiente em nuvem.
-   [ ] Documentação dos resultados e aprendizados.

## Objetivo de aprendizagem

Este laboratório faz parte de uma jornada de desenvolvimento técnico
voltada para **Security Operations e Blue Team**, com foco nos
fundamentos de monitoramento, análise de eventos, administração de
endpoints e infraestrutura de segurança.

O desenvolvimento será documentado progressivamente, diferenciando
recursos implementados, etapas em andamento e funcionalidades
planejadas.

------------------------------------------------------------------------

**Status:** Em desenvolvimento\
**Área de estudo:** Cybersecurity \| Security Operations \| Blue Team
