# Projeto-Integrador-Barbearia
# 💈 Corte Fino – Sistema de Agendamento para Barbearia

## 🧾 Descrição Geral
O **Corte Fino** é um sistema web para agendamento de horários em barbearia.  
Permite visualizar serviços e preços, conferir horários ocupados e registrar novos agendamentos, evitando conflitos.

---

## ⚙️ Funcionalidades Principais
- Página principal com **serviços e preços**.
- **Formulário de agendamento** (nome, telefone, serviço, data e hora).
- **Validação de conflito** (impede duplicidade de data+hora).
- **Lista de horários ocupados** por data (desafio extra).
- MVP **frontend-only** usando LocalStorage (sem backend).

---

## 💻 Tecnologias Utilizadas
**Frontend:** HTML5, CSS3, JavaScript  
**Backend (futuro):** Node.js + Express (opcional)  
**Banco de Dados (futuro):** MongoDB ou MySQL (opcional)

---

## 🧠 Arquitetura (MVP)
- `index.html` estrutura a interface.
- `style.css` aplica o visual (tema escuro).
- `script.js` implementa regras: serviços, agendamentos, conflitos e listagem de horários.
- Armazenamento local via **LocalStorage**.

---

## 👥 Integrantes do Grupo
| Nome | Função |
|------|--------|
| Felipe Martins | Frontend e Documentação |
| [Integrante 2] | Backend (futuro) |
| [Integrante 3] | Testes e Deploy |

---

## 🚀 Como Executar
1. Baixe/clonar este repositório.
2. Abra o arquivo `frontend/index.html` no navegador.
3. Agende um horário e veja a lista de horários ocupados atualizar.

> Observação: os dados ficam salvos **no navegador** (LocalStorage). Para testes limpos, limpe o cache/localStorage.

---

## 🧩 Estrutura de Pastas (MVP)
