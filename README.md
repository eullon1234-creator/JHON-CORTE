# ✂️ JHON CORTE — Sistema de Agendamento para Barbearia

Sistema completo de agendamento online para barbearias desenvolvido como Single Page Application (SPA), moderno, mobile-first e integrado ao Firebase Cloud Firestore e WhatsApp.

---

## 🔗 Links de Acesso

* 🌐 **Site Público (Agendamento de Clientes):**  
  👉 **[https://eullon1234-creator.github.io/JHON-CORTE/](https://eullon1234-creator.github.io/JHON-CORTE/)**

* ⚙️ **Painel Administrativo do Barbeiro:**  
  👉 **[https://eullon1234-creator.github.io/JHON-CORTE/?admin=true](https://eullon1234-creator.github.io/JHON-CORTE/?admin=true)**  
  🔑 **PIN de Acesso Padrão:** `0192`

---

## 🚀 Funcionalidades

### 👤 Área do Cliente
- **Interface Mobile-First:** Design dark premium e fluido com Tailwind CSS.
- **Fluxo Guiado de Agendamento:**
  1. Identificação (Nome e WhatsApp com máscara automática e persistência de sessão).
  2. Seleção de serviços com preços e durações dinâmicas.
  3. Calendário com bloqueio automático de dias não trabalhados, feriados/folgas cadastradas e datas passadas.
  4. Grade de horários em tempo real (bloqueio de horários ocupados e passados).
- **Google Agenda & Apple Calendar (.ics):** Botões diretos na tela de sucesso e em "Meus Cortes" para salvar o evento no calendário do celular.
- **Notificação Automática no WhatsApp:** Envia os detalhes do agendamento com link exclusivo de aprovação diretamente para o barbeiro.
- **Instagram Integrado:** Botão direto para os clientes visualizarem os cortes nas redes sociais.

### ✂️ Tela de Aprovação Rápida (via WhatsApp)
- Link direto enviado pelo WhatsApp para o barbeiro aprovar ou recusar o agendamento em 1 clique.
- Notificação de retorno automática no WhatsApp do cliente com status confirmado ou cancelado.

### 🛠️ Painel do Barbeiro
- **Dashboard:** Métricas diárias (total, confirmados, pendentes, cancelados e faturamento previsto), próximo cliente e botão de disparo de lembrete WhatsApp.
- **Gestão de Agendamentos:** Listagem completa com filtros por data e status, botões de ação ("✓ Confirmar", "💈 Iniciar Corte", "🔔 Lembrar Cliente", "⏱️ Avisar Vez").
- **Gestão de Serviços:** Cadastro, edição, ordenação e ativação/desativação de cortes e combos.
- **Gestão de Horários & Expediente:**
  - Gerador inteligente por intervalo médio (20, 30, 35, 45 min) com suporte a pausa/almoço.
  - Configuração individual de horários de atendimento para cada dia da semana.
- **Bloqueios & Folgas:** Cadastro de dias inteiros (feriados/folgas) ou horários específicos para evitar agendamentos.
- **Personalização Visual:**
  - Nome, slogan, descrição e logo da barbearia.
  - WhatsApp de atendimento.
  - Perfil e mensagem do Instagram.
  - Paleta de cores principal (Dourado, Âmbar, Vermelho, Azul, Verde, Roxo ou código HEX customizado).
- **Configuração de Mensagens:** Customização de templates de WhatsApp (Confirmação, Cancelamento e Lembrete).

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript Moderno (ES6+)
- **Estilização:** Tailwind CSS (CDN)
- **Database & Backend:** Firebase Cloud Firestore (v10 Modular SDK)
- **Hospedagem:** GitHub Pages

---

## 📄 Licença

Este projeto está sob a licença MIT. Desenvolvido por [Eullon Silva](https://github.com/eullon1234-creator).
