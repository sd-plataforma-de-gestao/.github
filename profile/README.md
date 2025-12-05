# Vitally - Plataforma de Gestão Farmacêutica

![Vitally](https://img.shields.io/badge/Version-1.0-green)
![Status](https://img.shields.io/badge/Status-Concluído-green)
![License](https://img.shields.io/badge/License-MIT-blue)

<img width="1280" height="320" alt="Prioritize your health" src="https://github.com/user-attachments/assets/0fbea1d9-5b99-48bb-8931-8e1868e80759" />

---

## 📋 Sobre o Projeto

**Vitally** é uma plataforma web moderna desenvolvida para gerenciar e otimizar operações farmacêuticas. O sistema centraliza a gestão de pacientes, atendimentos, farmacêuticos, medicamentos e unidades de saúde, oferecendo uma interface intuitiva e relatórios analíticos em tempo real.

A solução foi projetada para farmácias, clínicas e unidades de saúde que precisam de um controle eficiente de suas operações diárias, desde o atendimento farmacêutico até a análise de métricas de desempenho.

---

## 🎯 Objetivos Principais

- ✅ Centralizar a gestão de pacientes e seu histórico de atendimentos
- ✅ Otimizar o processo de atendimento farmacêutico
- ✅ Permitir controle e gestão de medicamentos
- ✅ Facilitar a administração de farmacêuticos e suas credenciais (CRF)
- ✅ Oferecer relatórios e insights sobre desempenho e métricas
- ✅ Gerenciar múltiplas unidades de saúde
- ✅ Melhorar a adesão dos pacientes ao tratamento

---

## 🚀 Funcionalidades Principais

### 1. **Gestão de Pacientes**
- Cadastro completo de pacientes com informações pessoais
- Classificação por tipo (Crônico, Agudo)
- Histórico de atendimentos
- Cálculo e acompanhamento da taxa de adesão
- Visualização de detalhes e histórico médico

### 2. **Atendimento Farmacêutico**
- Registro de novos atendimentos
- Sugestões inteligentes baseadas em histórico
- Categorização por tipo (Primeira Consulta, Acompanhamento, Emergência, etc.)
- Status de atendimento (Agendado, Em Progresso, Concluído, Cancelado)
- Chat integrado com sugestões contextualizadas

### 3. **Gestão de Farmacêuticos**
- Cadastro de profissionais com validação de CRF
- Controle de status (Ativo/Inativo)
- Filtros por nome, CRF e telefone
- Métricas de produtividade por farmacêutico

### 4. **Gestão de Medicamentos**
- Cadastro e categorização de medicamentos
- Controle de disponibilidade
- Informações sobre posologia e contra-indicações
- Relação com atendimentos realizados

### 5. **Gestão de Unidades**
- Cadastro de unidades de saúde/farmácias
- Informações de localização e contato
- Designação de farmacêutico responsável
- Horários de funcionamento
- Status de operação

### 6. **Dashboard e Insights**
- Visualização de métricas em tempo real:
  - Atendimentos realizados hoje
  - Consultas com pacientes crônicos
  - Casos agudos atendidos
  - Taxa média de adesão
- Gráficos analíticos:
  - Evolução de atendimentos por período
  - Distribuição por tipo de atendimento
  - Performance por unidade
  - Produtividade de farmacêuticos
- Relatórios exportáveis em PDF e CSV

### 7. **Relatórios Avançados**
- Relatórios customizáveis por período
- Filtros por tipo, unidade e farmacêutico
- Exportação em múltiplos formatos
- Histórico de atendimentos detalhado

### 8. **Configurações e Perfil**
- Gerenciamento de perfil do usuário
- Preferências da plataforma
- Logout seguro

---

## 💻 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização responsiva com custom properties
- **JavaScript (ES6+)** - Lógica de front-end, manipulação do DOM
- **Bootstrap 5** - Framework CSS para componentes responsivos
- **Font Awesome** - Ícones vetoriais

### Backend
- **PHP 7.4+** - Processamento server-side
- **Orientação a Objetos** - Estrutura modular e reutilizável

### Banco de Dados
- **MySQL 8.0** - SGBD relacional
- **Character Set UTF-8MB4** - Suporte a caracteres especiais

### Ferramentas de Desenvolvimento
- **Git/GitHub** - Controle de versão
- **XAMPP** - Ambiente local (Apache + PHP + MySQL)
- **VS Code** - Editor de código

### Padrões Arquiteturais
- **MVC** (Model-View-Controller) - Separação de responsabilidades
- **AJAX** - Requisições assíncronas para melhor UX
- **REST** - Endpoints para comunicação cliente-servidor

---

## 🎨 Arquitetura da Aplicação

```
gestao-servicos-repo/
├── config/
│   └── database.php          # Configuração de conexão com banco
├── templates/
│   ├── header.php            # Cabeçalho compartilhado
│   ├── sidebar.php           # Barra lateral de navegação
│   ├── main.php              # Dashboard principal
│   ├── atendimento.php       # Página de atendimentos
│   ├── paciente.php          # Gestão de pacientes
│   ├── farmaceutico.php      # Gestão de farmacêuticos
│   ├── medicamento.php       # Gestão de medicamentos
│   ├── unidade.php           # Gestão de unidades
│   ├── insights.php          # Dashboard de análises
│   └── config.php            # Configurações do sistema
├── js/
│   ├── script.js             # Script principal
│   ├── loadTemplates.js      # Carregamento dinâmico de templates
│   ├── atendimento.js        # Lógica de atendimentos
│   ├── paciente.js           # Lógica de pacientes
│   ├── farmaceutico.js       # Lógica de farmacêuticos
│   ├── medicamento.js        # Lógica de medicamentos
│   ├── unidade.js            # Lógica de unidades
│   ├── insights.js           # Lógica de relatórios
│   └── relatorio.js          # Exportação de relatórios
├── styles/
│   ├── global.css            # Estilos globais e design tokens
│   ├── header.css            # Estilos do header
│   ├── sidebar.css           # Estilos da sidebar
│   ├── main.css              # Estilos do conteúdo principal
│   ├── atendimento.css       # Estilos da página de atendimentos
│   ├── paciente.css          # Estilos de pacientes
│   ├── farmaceutico.css      # Estilos de farmacêuticos
│   ├── medicamento.css       # Estilos de medicamentos
│   ├── unidade.css           # Estilos de unidades
│   ├── insights.css          # Estilos de relatórios
│   ├── responsive.css        # Media queries responsivas
│   └── login.css             # Estilos da página de login
├── utils/
│   ├── gerar_pdf_insights.php    # Geração de PDFs
│   ├── gerar_csv_insights.php    # Exportação em CSV
│   └── relatorio_completo.php    # Relatórios customizados
├── assets/
│   ├── logo-header.png       # Logo para header
│   ├── logo-login.png        # Logo para login
│   └── favicon.png           # Favicon
├── back-end/
│   └── farmacia.sql          # Schema do banco de dados
├── index.php                 # Página inicial (dashboard)
├── login.php                 # Página de login
├── logout.php                # Logout seguro
├── dashboard.php             # API de dados do dashboard
└── README.md                 # Documentação de execução
```

---

## 🔐 Segurança

- ✅ Validação de entrada em todos os campos
- ✅ Prepared Statements para prevenir SQL Injection
- ✅ Hash seguro de senhas com `password_hash()` e `password_verify()`
- ✅ Sessões PHP seguras
- ✅ Escape de saída com `htmlspecialchars()`
- ✅ Validação de Email e CRF com regex
- ✅ Proteção CSRF (recomendado em produção)

---

## 📊 Fluxo de Dados

```
┌─────────────┐
│   Usuário   │
└──────┬──────┘
       │ (Login com CRF + Senha)
       ▼
┌──────────────────────┐
│   login.php          │ ◄─── Valida credenciais
└──────┬───────────────┘
       │
       ▼
┌──────────────────────────┐
│  index.php (Dashboard)   │ ◄─── Carrega templates via AJAX
└──────┬───────────────────┘
       │
    ┌──┴────────────────────────────────────┐
    │                                       │
    ▼                                       ▼
┌─────────────────┐             ┌──────────────────┐
│ atendimento.php │             │  paciente.php    │
│ medicamento.php │             │  farmaceutico.php│
│ unidade.php     │             │  insights.php    │
└────────┬────────┘             └────────┬─────────┘
         │                               │
         └───────────────┬───────────────┘
                         │
                         ▼
                   ┌──────────────┐
                   │   MySQL DB   │
                   │   (farmacia) │
                   └──────────────┘
```

---

## 🎓 Padrões e Boas Práticas

- **Separação de Responsabilidades**: Templates, lógica JavaScript e estilos separados
- **Reutilização de Código**: Funções helper compartilhadas
- **Responsividade**: Design mobile-first com media queries
- **Acessibilidade**: Labels semânticas, ARIA attributes
- **Performance**: Lazy loading, compressão de assets
- **Validação**: Client-side e server-side

---

## 📈 Métricas e KPIs

A plataforma rastreia e exibe:

- **Atendimentos Hoje**: Total de consultas realizadas no dia
- **Consultas Crônicas**: Pacientes com doenças crônicas atendidos
- **Casos Agudos**: Pacientes com condições agudas
- **Taxa de Adesão**: Média de acompanhamento de pacientes
- **Produtividade**: Atendimentos por farmacêutico
- **Performance por Unidade**: Comparativa entre filiais

---

## 🛠️ Instalação e Execução

Para instruções completas de como rodar a aplicação localmente, consulte o arquivo **[README.md](.gestao-servicos-repo/README.md)**.

### Resumo Rápido:
1. Instale o XAMPP
2. Clone o repositório
3. Copie arquivos para `htdocs`
4. Importe o banco de dados (`back-end/farmacia.sql`)
5. Configure `config/database.php`
6. Acesse `http://localhost/gestao-servicos-repo`

---

## 🚀 Roadmap Futuro

- [ ] Autenticação com 2FA (Two-Factor Authentication)
- [ ] Integração com APIs de validação de CRF em tempo real
- [ ] Notificações por email para atendimentos
- [ ] App mobile (React Native)
- [ ] Dashboard com gráficos mais avançados (Chart.js)
- [ ] Sistema de permissões granulares (Roles & Permissions)
- [ ] Backup automático do banco de dados
- [ ] Auditoria de ações dos usuários
- [ ] Integração com sistemas de prontuário eletrônico

---

## 👥 Equipe de Desenvolvimento

**Projeto**: Vitally - Plataforma de Gestão Farmacêutica  
**Organização**: SD Plataforma de Gestão  
**Repositório**: https://github.com/sd-plataforma-de-gestao/gestao-servicos-repo

---

## 📞 Suporte

Para dúvidas, sugestões ou relatar problemas:
- Entre em contato com a equipe de desenvolvimento

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo LICENSE para detalhes.

---

**Versão Atual**: 1.0  
**Data de Lançamento**: Dezembro de 2025  
**Status**: Concluído
