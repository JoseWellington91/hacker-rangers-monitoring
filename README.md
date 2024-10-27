# Monitoramento Ativo da Plataforma Hacker Rangers

Este projeto tem como objetivo realizar o monitoramento ativo da plataforma Hacker Rangers, consumindo a API do HR, armazenando os dados no Zabbix e visualizando as informações em dashboards no Grafana.

## Sumário

- [Introdução](#introdução)
- [Arquitetura](#arquitetura)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Introdução

O monitoramento ativo é essencial para garantir a disponibilidade e o desempenho da plataforma Hacker Rangers. Este projeto automatiza a coleta de dados através da API do HR, permite o armazenamento eficiente no Zabbix e oferece visualizações ricas em dashboards no Grafana.

## Arquitetura

A arquitetura do sistema é composta por:

1. **API do Hacker Rangers**: Fonte de dados que fornece informações sobre a plataforma.
2. **Zabbix**: Sistema de monitoramento onde os dados são armazenados.
3. **Grafana**: Ferramenta de visualização para criar dashboards interativos a partir dos dados do Zabbix.

## Pré-requisitos

Antes de começar, você precisará de:

- Acesso à API do Hacker Rangers
- Instâncias do Zabbix e Grafana configuradas
- Python 3.x instalado (para scripts de coleta de dados)
- Bibliotecas: `requests`, `pytz`, `zabbix-api`

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/hacker-rangers-monitoring.git
   cd hacker-rangers-monitoring
