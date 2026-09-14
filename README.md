# 📦 Production Pulse

> Sistema para gerenciamento e apontamento de produção industrial desenvolvido em AppSheet.

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green)
![Platform](https://img.shields.io/badge/Platform-AppSheet-blue)
![Database](https://img.shields.io/badge/Database-Google%20Sheets-yellow)
![Industry](https://img.shields.io/badge/Industry-Manufacturing-orange)

---

# 📖 Sobre

O **Production Pulse** é um sistema desenvolvido para digitalizar e otimizar o processo de apontamento de produção na indústria.

O projeto surgiu da necessidade de substituir controles manuais em papel por uma solução digital, permitindo acompanhamento da produção em tempo real, rastreabilidade dos pallets e indicadores operacionais.

O sistema foi desenvolvido inicialmente como um MVP (Minimum Viable Product) utilizando **Google AppSheet**, possibilitando rápida validação da solução antes de uma eventual implementação em uma plataforma corporativa.

---

# 🎯 Objetivos

- Eliminar apontamentos em papel;
- Centralizar informações de produção;
- Registrar pallets produzidos em tempo real;
- Facilitar o fechamento de produção dos turnos;
- Melhorar a rastreabilidade dos pallets;
- Disponibilizar indicadores instantâneos para a operação.

---

# 🚀 Funcionalidades

## 📋 Plano de Produção

- Cadastro de planos ativos;
- Definição de SKU;
- Meta de produção;
- Status do plano.

---

## 🏭 Apontamentos

- Registro por turno;
- Operador responsável;
- Lote;
- Validade;
- Data;
- Produção do turno;
- Relacionamento com Plano de Produção.

---

## 📦 Registro de Pallets

Cada pallet possui:

- Número do pallet;
- Responsável pelo registro;
- Quantidade de caixas;
- Últimos 4 dígitos do SSCC;
- Data e hora;
- Status do pallet.

---

## 📊 Dashboard

Indicadores em tempo real:

- 📦 Produção realizada
- 🎯 Meta de produção
- ⏳ Caixas restantes
- 📈 Percentual concluído
- 🟢 Status do plano

---

## 🏷 Status dos Pallets

- 🟢 Liberado
- 🔴 Segregado
- ⚫ Descartado

---

# 🛠 Tecnologias

- Google AppSheet
- Google Sheets
- App Formula
- Virtual Columns

---

# 📂 Estrutura do Projeto

```
Plano de Produção
        │
        ▼
 Apontamentos
        │
        ▼
     Pallets
```

---

# 📈 Fluxo do Processo

```
Criar Plano
      │
      ▼
Novo Apontamento
      │
      ▼
Registrar Pallets
      │
      ▼
Atualização automática dos indicadores
```

---

# 💡 Futuras Melhorias

- Integração com SAP;
- Integração com Power Apps;
- Banco de dados SQL;
- Dashboard em Power BI;
- Login corporativo;
- Registro automático de pallets;
- Indicadores de produtividade;
- Histórico completo de produção.

---

# 📸 Telas

- Dashboard Principal
- Plano de Produção
- Registro de Apontamentos
- Registro de Pallets
- Indicadores de Produção

<img width="567" height="703" alt="image" src="https://github.com/user-attachments/assets/b137294f-105c-4839-a1a0-15382db0d935" />
<img width="574" height="698" alt="image" src="https://github.com/user-attachments/assets/a5490693-d87e-4854-a35e-a45f8ff1890c" />
<img width="577" height="652" alt="image" src="https://github.com/user-attachments/assets/e6ac9037-1052-4056-89ea-1a6793169182" />

---

# 👨‍💻 Autor

**Gabriel Souza**

Projeto desenvolvido como iniciativa de melhoria contínua para otimização do processo de apontamento de produção industrial.

---

# 📄 Licença

Projeto desenvolvido para fins de estudo, inovação e melhoria de processos industriais.
