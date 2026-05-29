# GymDesk

> Plataforma de Gestão de Reservas e Horários para Ginásios

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

## Sobre o Projeto

O GymDesk é uma plataforma de gestão interna destinada a ginásios, permitindo centralizar a gestão de reservas, horários, aulas, clientes e funcionários.

O sistema foi concebido para apoiar o trabalho da receção e administração do ginásio, melhorando a organização das atividades e reduzindo conflitos de agendamento.

## Objetivos

- Centralizar a gestão de reservas
- Gerir horários e aulas
- Organizar a disponibilidade dos funcionários
- Facilitar a consulta de calendários
- Melhorar a eficiência operacional do ginásio

## Funcionalidades

### Gestão de Reservas

- Criar reservas
- Editar reservas
- Cancelar reservas
- Consultar histórico

### Gestão de Horários

- Definir horários de funcionamento
- Organizar aulas e treinos
- Visualizar calendário semanal

### Gestão de Clientes

- Registo de clientes
- Consulta de informações
- Atualização de dados

### Gestão de Funcionários

- Registo de funcionários
- Gestão de horários de trabalho
- Consulta de disponibilidade

### Dashboard

- Visão geral do sistema
- Estatísticas operacionais
- Resumo de atividade

## Arquitetura

O projeto segue o padrão arquitetural MVC (Model-View-Controller).

### Camadas

- View
  - JSP
  - HTML
  - CSS
  - Bootstrap

- Controller
  - Servlets Java

- Model
  - Classes de negócio
  - Acesso a dados

- Persistência
  - MySQL

- Servidor
  - Apache Tomcat

## Tecnologias Utilizadas

| Tecnologia | Utilização |
|------------|------------|
| Java EE | Desenvolvimento Backend |
| JSP | Interface Web |
| Servlets | Lógica de Controlo |
| Bootstrap 5 | Interface Responsiva |
| HTML5 | Estrutura |
| CSS3 | Estilização |
| MySQL | Base de Dados |
| Apache Tomcat | Servidor de Aplicações |
| Git | Controlo de Versões |
| GitHub | Repositório |

## Estrutura do Projeto

```text
GymDesk
│
├── docs/
│   ├── Relatorio.pdf
│   ├── Wireframes/
│   └── Diagramas/
│
├── Website_Apresentacao/
│
├── src/
│
├── database/
│
└── README.md
```

## Wireframes

O projeto inclui wireframes para:

- Login
- Dashboard
- Gestão de Reservas
- Calendário
- Gestão de Clientes
- Gestão de Funcionários

## Estado do Projeto

### Concluído

- [x] Levantamento de Requisitos
- [x] Análise do Sistema
- [x] Wireframes
- [x] Arquitetura MVC
- [x] Estrutura de Dados
- [x] Website de Apresentação

### Em Desenvolvimento

- [ ] Implementação Java EE
- [ ] Desenvolvimento da Base de Dados
- [ ] Integração MySQL
- [ ] Testes
- [ ] Documentação Final

## Autor

João Teixeira

Projeto desenvolvido no âmbito da formação de Engenharia de Software do IEFP.

## Licença

Este projeto foi desenvolvido para fins académicos.
