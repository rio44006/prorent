# ProRent - Sistema de Gestao de Locacao de Veiculos

## Funcionalidades Principais

### 1. Extrator de Dados (OCR)
- Upload de faturas/recibos em multiplos formatos (PDF, PNG, JPG, Excel)
- Extracao automatica de dados usando Tesseract.js
- Preenchimento automatico de formularios
- Validacao de integridade de dados

### 2. Gestao de Lancamentos Financeiros
- CRUD completo (Criar, Ler, Atualizar, Deletar)
- Modal de edicao com confirmacao de exclusao
- Campos de auditoria (criado em, atualizado em, usuario)
- Soft delete para manter historico

### 3. Dashboard Avancado
- Filtros de periodo: Semana, Mes, Trimestre, Semestre, Ano
- Calculos dinamicos de datas
- Graficos e KPIs em tempo real
- Sincronizacao automatica com Firebase

### 4. Backup e Restore
- Exportacao de dados em JSON
- Download automatico de backups
- Restauracao com validacao de integridade
- Confirmacao dupla de seguranca

### 5. Sincronizacao na Nuvem
- Backup automatico a cada 24h
- Integracao com Firebase Realtime Database
- Limpeza segura de dados com confirmacao dupla

## Tecnologias Utilizadas

- React 18+ - Interface do usuario
- TypeScript - Type safety
- Firebase - Backend e sincronizacao
- Tesseract.js - OCR para extracao de dados
- Tailwind CSS - Estilizacao responsiva
- React Hooks - Gerenciamento de estado
- Material Design Icons - Icones da interface

## Instalacao

```bash
git clone https://github.com/rio44006/prorent.git
cd prorent
npm install
cp .env.example .env.local
npm run dev
```

## Arquitetura do Projeto

components/ - Componentes React
hooks/ - Custom hooks
contexts/ - Context API
data/ - Mock data

## Documentacao Completa

Veja a documentacao em: https://docs.google.com/document/d/1O5FTGcNibDCFeeERxW9l-HwBSZ1ozOSyuPGVScXHmdk

## Demo

Acesse em: https://aistudio.google.com/app/apps/drive/1qpPik7X2MJ05WIUw_GZf-NSoud7_ZDIc

## Melhorias de UI/UX (Nov 2025)

### Responsividade e Design
- Menu hamburguer adaptável para dispositivos móveis
- Layout responsivo otimizado para todos os tamanhos de tela
- Melhor espaçamento e hierarquia visual
- Efeitos hover dinâmicos em componentes interativos

### Funcionalidades Adicionadas
- **Busca Rápida**: Campo de busca no dashboard para filtrar veículos por placa ou modelo
- **Filtros Avançados**: Filtros inteligentes nas seções de registro
- **Paginação**: Suporte a paginação para tabelas grandes
- **Notificações**: Sistema de notificações não-intrusivo para ações do usuário

### Performance
- Componentes memoizados para prevenir re-renders desnecessários
- Lazy loading para melhorar tempo de carregamento inicial
- Otimização de renderização com React.memo

### Tema e Acessibilidade
- Dark mode automático baseado em preferências do sistema
- Melhor contraste e legibilidade
- Ícones informativos em todas as seções principais



## Licenca

MIT License

## Contato

Criado por @rio44006
LinkedIn: jorge-almeida

---

Estrela se foi util!
