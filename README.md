---
marp: true
theme: default
paginate: true
header: "MultiGest"
footer: "Campus Videira · IFC"
style: |
  section { font-family: Helvetica, Arial, sans-serif; font-size: 26px; }
  h1, h2 { color: #5A1BB0; }
  table { font-size: 20px; }
  a { color: #5A1BB0; }
---
 
<!-- _class: lead -->
<!-- _paginate: false -->
 
# MultiGest
 
### Portaria que simplifica, resultados que multiplicam
 
Sistema web para gerenciamento de portarias institucionais
**Campus Videira · IFC**
 
Celia Raizer · Alessandra Corrêa
 
---
 
## O problema
 
A gestão de portarias no Campus Videira é feita de forma **predominantemente manual**.
 
Isso gera dificuldade para:
 
- controlar os documentos;
- acompanhar a vigência;
- rastrear alterações;
- distribuir responsabilidades;
- emitir relatórios administrativos.
---
 
## A solução
 
Um sistema informatizado que **centraliza e automatiza** todo o ciclo da portaria:
 
**solicitação → validação → emissão → assinatura → vigência → relatórios**
 
Também controla membros, carga horária e histórico de alterações.
 
---
 
## Protótipo no Figma
 
Telas obrigatórias do projeto:
 
1. Login (usuário e senha)
2. Recuperação de senha
3. Home com menu de acesso
### [Abrir o protótipo no Figma](https://www.figma.com/design/GH5Himz1qSnZwDsi8zB1Am/Sem-t%C3%ADtulo?node-id=0-1&t=6KrirJ6jNrLeE3u2-1)
 
https://www.figma.com/design/GH5Himz1qSnZwDsi8zB1Am/Sem-t%C3%ADtulo?node-id=0-1&t=6KrirJ6jNrLeE3u2-1
 
---
 
## O que o sistema faz
 
| Área | Funcionalidades |
|---|---|
| Acesso | Login, recuperação de senha, perfis e permissões |
| Portarias | Solicitação, validação, aprovação ou rejeição com justificativa, numeração automática |
| Membros | Servidores, externos, alunos e comunidade, com carga horária |
| Vigência | Monitoramento, alertas de vencimento e notificações por e-mail |
| Documentos | Geração em PDF e assinatura digital |
| Consulta | Busca avançada, histórico e versionamento |
| Gestão | Relatórios exportáveis em PDF e logs de auditoria |
 
---
 
## Ciclo de vida da portaria
 
Solicitada → Em validação → Aprovada → Emitida em PDF → Assinada → **Vigente** → A vencer → Vencida
 
Também pode ser **rejeitada**, **devolvida para ajustes**, **revogada** ou ganhar **nova versão**.
 
---
 
## Perfis de usuário
 
| Perfil | O que faz |
|---|---|
| Solicitante | Pede portarias e acompanha o andamento |
| Validador | Analisa, aprova ou rejeita, emite |
| Signatário | Assina digitalmente |
| Administrador | Gerencia usuários, logs e relatórios |
 
*Perfis propostos, em validação com os setores.*
 
---
 
## Requisitos e regras
 
- **27 requisitos funcionais** e **10 não-funcionais**
- **40 regras de negócio**
- Interface **responsiva**
- **Logs de auditoria** das ações relevantes
- Atendimento à **LGPD**
- **API REST** para integrações futuras
---
 
## Cronograma de marcos
 
| Marco | Data |
|---|---|
| 1. Levantamento de requisitos | 10/08/2026 |
| 2. Definição do nome do projeto | 25/08/2026 |
| 3. Início da criação do protótipo | 03/09/2026 |
| 4. Telas prototipadas no Figma | 11/09/2026 |
| 5. Finalização do projeto | 11/11/2026 |
 
---
 
## Entregáveis
 
| # | Entregável | Situação |
|---|---|---|
| 1 | Plano de Projeto | Ajustado |
| 2 | EAP | Versão 1.0 |
| 3 | Mapeamento de Talentos e Habilidades | Estrutura pronta |
| 4 | Critérios de Aceitação | Versão 1.0 |
| 5 | Requisitos | Versão 1.0 |
| 6 | Regras de Negócio | Versão 1.0 |
| 7 | Interfaces do Sistema | Rascunho |
| 8 | Prototipação | Em andamento (Figma) |
| 9 | Landing Page | A definir |
 
---
 
## O que não está no escopo da primeira versão
 
- Integração com sistemas externos, incluindo o SIPAC
- Substituição dos sistemas institucionais existentes
- Alteração dos procedimentos administrativos oficiais do IFC
- Aplicativo mobile nativo
---
 
<!-- _class: lead -->
<!-- _paginate: false -->
 
## Obrigada!
 
**MultiGest** · Portaria que simplifica, resultados que multiplicam
 
Protótipo: [Figma](https://www.figma.com/design/GH5Himz1qSnZwDsi8zB1Am/Sem-t%C3%ADtulo?node-id=0-1&t=6KrirJ6jNrLeE3u2-1)
 
