# Antônio Rodrigues

**Brasília — DF, Brasil** · [`@ToNiauM`](https://github.com/ToNiauM)

**Infraestrutura, Linux e Python aplicados a sistemas, automação e gestão pública.**  
Atuo na interseção entre **infraestrutura, desenvolvimento, dados e processos institucionais**.

---

## Sobre

Minha trajetória em tecnologia começou em **2003**, com atuação prática em infraestrutura e suporte de redes de pequeno e médio porte. Trabalhei com **cabeamento estruturado, patch panels, configuração de equipamentos de rede, estações de trabalho, impressoras, diagnóstico de hardware e recuperação lógica de dados**. Entre 2003 e 2010, também atuei como **empresário do setor de tecnologia**, atendendo ambientes residenciais e corporativos.

Desde **2013 sou empregado de carreira do Conselho Federal de Contabilidade (CFC)**. Fui supervisor do **Setor de Patrimônio (SEPAT)** por oito anos e, desde julho de 2026, atuo como **pregoeiro**. Essa trajetória consolidou experiência em **contratações públicas, gestão patrimonial, fornecedores, fiscalização, processos administrativos e operação institucional**.

Nos últimos anos intensifiquei novamente minha atuação técnica, agora combinando a base de infraestrutura com **Linux, Python, desenvolvimento web, bancos de dados relacionais, containers, deploy, automação e análise de dados**.

Hoje, meu objetivo profissional está direcionado ao aprofundamento em **Infraestrutura de TI, DevOps, redes, cloud e gestão de serviços**, conectando conhecimento técnico à experiência administrativa e institucional construída ao longo da carreira.

---

## Competências Técnicas

### Infraestrutura e operação

**Linux**  
Usuários e grupos · permissões · systemd · journalctl · SSH · filesystem · processos · serviços · networking · troubleshooting

**Containers e deploy**  
Docker · Docker Compose · Nginx · reverse proxy · Gunicorn · volumes persistentes · health checks

**Redes**  
TCP/IP · redes locais · cabeamento estruturado · patch panels · configuração de equipamentos · diagnóstico de conectividade

**Ferramentas**  
Git · GitHub · Bash · SSH · tmux

### Desenvolvimento

Python · Django · Flask · FastAPI · HTMX · APIs REST · automação

### Dados e persistência

PostgreSQL · MySQL · Redis · Pandas · Grafana

---

## Arquitetura que utilizo

Uma arquitetura recorrente nos meus projetos:

```text
Internet / Browser
        │
        ▼
      Nginx
  reverse proxy
        │
        ▼
     Gunicorn
        │
        ▼
      Django
      │    │
      │    └──── Redis
      │
      ▼
  PostgreSQL
      │
      ▼
Volume persistente

Docker Compose
      │
      ▼
     Linux
```

Esse modelo permite separar aplicação, persistência, cache e exposição HTTP, mantendo os componentes isolados e reproduzíveis.

---

## Projetos

| Projeto | Stack | Objetivo |
|---|---|---|
| **PCA — Plano de Contratações Anual** | Django · PostgreSQL · Docker · Nginx | Acompanhamento e gestão do ciclo anual de contratações |
| **Gestão Patrimonial** | Python · PostgreSQL | Automação e controle de processos patrimoniais |
| **Termos de Responsabilidade** | Python · Flask | Geração automatizada de documentos patrimoniais |
| **Dashboard People Analytics** | Flask · PostgreSQL · Docker | Indicadores agregados de recursos humanos |
| **AnaliseDados** | Grafana · Flask · PostgreSQL | Dashboards e análise de dados |
| **Quiz em tempo real** | FastAPI · WebSockets | Aplicação multiusuário em tempo real |

[Ver todos os repositórios →](https://github.com/ToNiauM?tab=repositories)

> Alguns projetos profissionais e institucionais possuem código ou dados de acesso restrito.

---

## Formação

| Formação | Instituição | Status |
|---|---|---|
| **MBA em Data Science & Analytics** | USP/ESALQ | Fase final — TCC |
| **Especialização em Desenvolvimento de Sistemas com Python** | Unicesumar | Concluída |
| **Especialização em Terceirização de Mão de Obra** | Unyleya | Concluída |
| **Bacharelado em Ciências Contábeis** | UDF/Unicesumar | Concluído |

**Formação complementar:** Liderança — Dale Carnegie · cursos técnicos e de desenvolvimento profissional pela Alura.

---

## Certificações e desenvolvimento profissional

Meu roadmap foi estruturado para consolidar quatro pilares: **Linux, redes, cloud e gestão de serviços de TI**.

| Certificação | Área | Status |
|---|---|---|
| **LFCS — Linux Foundation Certified System Administrator** | Linux / infraestrutura | Em preparação |
| **CCNA — Cisco Certified Network Associate** | Redes | Planejada |
| **AWS Solutions Architect — Associate** | Cloud | Planejada |
| **ITIL 4 Foundation** | Gestão de serviços de TI | Planejada |

A prioridade atual é transformar experiência prática em conhecimento formalmente validado, começando pela administração Linux e avançando para redes, cloud e gestão de serviços.

---

## Trajetória

```text
2003
 │
 ├── Infraestrutura e redes
 │
 ├── Suporte técnico
 │
 └── Empreendedorismo em tecnologia
 │
2010
 │
 ▼
2013
 │
 ├── Ingresso no CFC
 ├── Gestão patrimonial
 ├── Contratações e fornecedores
 └── Processos administrativos
 │
 ▼
Desenvolvimento Python
 │
 ├── Sistemas web
 ├── Automação
 ├── Bancos de dados
 └── Análise de dados
 │
 ▼
Infraestrutura moderna
 │
 ├── Linux
 ├── Docker
 ├── Redes
 ├── Cloud
 └── DevOps
```

---

## Foco profissional

Meu interesse está em ambientes nos quais seja necessário combinar:

**infraestrutura técnica + gestão + automação + conhecimento do negócio**

Não busco apenas operar tecnologia, mas compreender o ambiente o suficiente para **diagnosticar problemas, avaliar riscos, melhorar processos, automatizar operações e apoiar decisões técnicas e gerenciais**.

---

## Contato

- E-mail: [toniaum@gmail.com](mailto:toniaum@gmail.com)
- GitHub: [github.com/ToNiauM](https://github.com/ToNiauM)
- Portfólio: [analisedados.online](https://analisedados.online)

---

> `Automatizar. Medir. Documentar. Melhorar.`
