# Plataforma SaaS de Recrutamento e Seleção

## 1. Sobre o projeto

Plataforma SaaS para centralizar e otimizar processos de recrutamento e seleção, permitindo que empresas gerenciem vagas, candidaturas, currículos e bancos de talentos em um único ambiente.

O objetivo principal é facilitar a gestão de processos seletivos e permitir que recrutadores encontrem e reutilizem candidatos de processos anteriores, reduzindo o retrabalho e o tempo necessário para preencher vagas.

## 2. Objetivos principais

- Centralizar vagas, candidaturas e currículos.
- Facilitar a busca e a reutilização de candidatos antigos.
- Automatizar tarefas operacionais do RH.
- Centralizar informações e o histórico dos candidatos.
- Permitir que diferentes empresas utilizem a plataforma de forma independente.
- Oferecer o produto por meio de planos de assinatura SaaS.
- Desenvolver novas funcionalidades progressivamente, conforme a validação do produto e as necessidades dos clientes.

---

# 3. Funcionalidades atuais — MVP

As funcionalidades desta seção representam o escopo inicial do produto.

## 3.1. Autenticação e gerenciamento de usuários

- [ ] Cadastro de empresas.
- [ ] Login e logout.
- [ ] Recuperação e redefinição de senha.
- [ ] Cadastro e gerenciamento de usuários da empresa.
- [ ] Controle de permissões por usuário.
- [ ] Configurações básicas da conta.
- [ ] Isolamento dos dados entre empresas (multi-tenant).

## 3.2. Gestão de vagas

- [ ] Criar vagas de emprego.
- [ ] Editar informações das vagas.
- [ ] Arquivar ou encerrar vagas.
- [ ] Definir título, descrição, requisitos, benefícios e localização.
- [ ] Definir o status da vaga:
  - Rascunho.
  - Aberta.
  - Pausada.
  - Encerrada.
  - Cancelada.
- [ ] Listar e visualizar vagas.
- [ ] Consultar o total de candidaturas por vaga.
- [ ] Visualizar candidatos vinculados a uma vaga.

## 3.3. Recebimento de candidaturas

- [ ] Criar formulários de candidatura.
- [ ] Permitir o envio de currículos pelos candidatos.
- [ ] Coletar dados básicos: nome, e-mail e telefone.
- [ ] Permitir perguntas personalizadas definidas pelo RH.
- [ ] Registrar a data e o horário da candidatura.
- [ ] Registrar a origem da candidatura, quando disponível.
- [ ] Identificar possíveis candidatos duplicados.
- [ ] Vincular automaticamente a candidatura à vaga correspondente.

## 3.4. Gestão de candidatos

- [ ] Criar e editar perfis de candidatos.
- [ ] Armazenar informações pessoais e profissionais.
- [ ] Anexar e visualizar currículos.
- [ ] Registrar competências, experiências e formação.
- [ ] Consultar o histórico de candidaturas.
- [ ] Vincular um mesmo candidato a diferentes vagas.
- [ ] Adicionar observações internas.
- [ ] Registrar interações e alterações relevantes.
- [ ] Pesquisar candidatos por nome, e-mail e telefone.
- [ ] Filtrar candidatos por critérios disponíveis.

## 3.5. Gestão das etapas do processo seletivo

- [ ] Definir o status de cada candidatura.
- [ ] Disponibilizar etapas iniciais padronizadas:
  - Recebido.
  - Em triagem.
  - Entrevista.
  - Aprovado.
  - Reprovado.
- [ ] Alterar o status de uma candidatura.
- [ ] Visualizar candidatos agrupados por etapa.
- [ ] Registrar o histórico das mudanças de status.
- [ ] Manter candidaturas independentes para cada vaga, mesmo quando pertencem ao mesmo candidato.

## 3.6. Banco de talentos

- [ ] Manter um banco centralizado de candidatos por empresa.
- [ ] Pesquisar candidatos de processos seletivos anteriores.
- [ ] Buscar por nome, competências, formação, experiência e palavras-chave disponíveis.
- [ ] Filtrar candidatos por informações cadastradas.
- [ ] Visualizar o histórico antes de reutilizar um candidato.
- [ ] Vincular candidatos existentes a novas vagas.
- [ ] Identificar possíveis duplicidades no banco.
- [ ] Permitir atualização dos dados dos candidatos.
- [ ] Controlar solicitações de acesso, correção e exclusão de dados pessoais.
- [ ] Implementar regras de retenção de currículos e informações.

## 3.7. Importação e armazenamento de currículos

- [ ] Cadastrar candidatos manualmente.
- [ ] Importar currículos em PDF.
- [ ] Validar os tipos e tamanhos de arquivos aceitos.
- [ ] Armazenar arquivos de forma privada e segura.
- [ ] Visualizar e baixar currículos conforme as permissões.
- [ ] Associar currículos aos perfis correspondentes.
- [ ] Registrar a origem dos candidatos importados.
- [ ] Evitar a criação de registros duplicados durante a importação.

**Observação:** a extração automática de dados dos currículos poderá ser implementada em uma fase posterior. No MVP, o cadastro manual é suficiente para iniciar a operação.

## 3.8. Comunicação com candidatos

- [ ] Exibir os dados de contato dos candidatos.
- [ ] Registrar contatos realizados.
- [ ] Registrar observações sobre as interações.
- [ ] Preparar modelos básicos de mensagens.
- [ ] Enviar e-mails de confirmação de candidatura, caso a infraestrutura de e-mail esteja implementada.

A integração com WhatsApp oficial e as automações avançadas de comunicação ficam para uma fase futura.

## 3.9. Segurança, privacidade e auditoria

- [ ] Garantir o isolamento dos dados entre empresas.
- [ ] Implementar controle de acesso por usuário.
- [ ] Proteger arquivos e informações pessoais.
- [ ] Registrar ações relevantes dos usuários.
- [ ] Implementar rotinas de backup e recuperação.
- [ ] Monitorar erros e falhas da aplicação.
- [ ] Definir regras de retenção e exclusão de dados.
- [ ] Disponibilizar informações sobre a finalidade do tratamento de dados.
- [ ] Implementar medidas de conformidade com a LGPD.
- [ ] Permitir a gestão de solicitações relacionadas aos dados pessoais.

---

# 4. Funcionalidades futuras

As funcionalidades abaixo estão previstas para versões posteriores e não fazem parte do escopo obrigatório do primeiro lançamento.

## 4.1. Inteligência artificial

- [ ] Extrair automaticamente informações dos currículos.
- [ ] Identificar competências, formação e experiências.
- [ ] Gerar resumos de currículos.
- [ ] Implementar busca semântica no banco de talentos.
- [ ] Comparar perfis com requisitos das vagas.
- [ ] Sugerir candidatos para vagas abertas.
- [ ] Auxiliar na elaboração de descrições de vagas.
- [ ] Gerar sugestões de perguntas para entrevistas.
- [ ] Permitir que o RH revise e controle as recomendações da IA.

A IA deverá atuar como ferramenta de apoio, sem realizar decisões autônomas de contratação ou rejeição.

## 4.2. Integração com WhatsApp oficial

- [ ] Integrar com a WhatsApp Business Platform.
- [ ] Enviar mensagens automáticas aos candidatos.
- [ ] Configurar perguntas de triagem por vaga.
- [ ] Permitir edição das perguntas pelo RH.
- [ ] Registrar respostas automaticamente no perfil do candidato.
- [ ] Criar fluxos de conversa baseados nas respostas.
- [ ] Enviar atualizações sobre processos seletivos.
- [ ] Permitir a continuidade manual da conversa pelo recrutador.
- [ ] Monitorar o consumo e os custos de mensagens.

## 4.3. Integrações com fontes externas

- [ ] Receber candidaturas por e-mail.
- [ ] Importar candidatos por planilhas.
- [ ] Integrar com sistemas externos de recrutamento.
- [ ] Integrar com portais de emprego que disponibilizem mecanismos autorizados.
- [ ] Integrar com formulários externos.
- [ ] Centralizar candidaturas de diferentes fontes.
- [ ] Registrar métricas de origem dos candidatos.

## 4.4. Publicação e divulgação de vagas

- [ ] Criar uma página pública de vagas para cada empresa.
- [ ] Disponibilizar páginas de candidatura públicas.
- [ ] Integrar com o site institucional da empresa.
- [ ] Publicar vagas em portais compatíveis.
- [ ] Automatizar publicações quando houver suporte e autorização.
- [ ] Controlar datas de publicação e encerramento.
- [ ] Acompanhar candidaturas por canal de divulgação.

## 4.5. White label e personalização

- [ ] Permitir a configuração do logotipo da empresa.
- [ ] Personalizar cores e identidade visual.
- [ ] Criar páginas de carreira personalizadas.
- [ ] Permitir domínios personalizados.
- [ ] Personalizar formulários e mensagens.
- [ ] Disponibilizar configurações independentes por empresa.

## 4.6. Gestão avançada de processos seletivos

- [ ] Criar etapas personalizadas por vaga.
- [ ] Configurar fluxos de seleção.
- [ ] Agendar entrevistas.
- [ ] Integrar com calendários externos.
- [ ] Criar formulários de avaliação de entrevistas.
- [ ] Compartilhar avaliações entre recrutadores.
- [ ] Enviar lembretes automáticos.
- [ ] Gerar relatórios de desempenho dos processos seletivos.
- [ ] Acompanhar indicadores como tempo de contratação e conversão por etapa.

## 4.7. Gestão de contratação e documentos

- [ ] Marcar candidatos como contratados.
- [ ] Transferir informações necessárias para o cadastro de colaboradores.
- [ ] Gerar documentos com base em modelos.
- [ ] Gerar propostas de contratação.
- [ ] Integrar com serviços de assinatura eletrônica.
- [ ] Controlar documentos pendentes.
- [ ] Integrar com sistemas de RH e departamento pessoal.

## 4.8. Recursos para consultorias de recrutamento

- [ ] Gerenciar múltiplos clientes em uma conta.
- [ ] Separar vagas e candidatos por cliente.
- [ ] Compartilhar perfis com empresas contratantes, respeitando as permissões aplicáveis.
- [ ] Gerar relatórios por cliente.
- [ ] Gerenciar processos seletivos simultâneos.
- [ ] Personalizar a identidade visual da consultoria.
- [ ] Configurar permissões por cliente e equipe.

## 4.9. Assinaturas e monetização SaaS

- [ ] Criar planos de assinatura.
- [ ] Integrar com um provedor de pagamentos.
- [ ] Implementar cobrança recorrente.
- [ ] Disponibilizar período de teste gratuito.
- [ ] Controlar limites de vagas, usuários e candidatos processados.
- [ ] Monitorar consumo de mensagens e recursos de IA.
- [ ] Implementar cobrança adicional por consumo.
- [ ] Permitir upgrade e downgrade de planos.
- [ ] Gerenciar cancelamentos e inadimplência.
- [ ] Criar painel administrativo para gerenciamento de clientes e assinaturas.

---

# 5. Ordem de desenvolvimento sugerida

### Fase 1 — Fundação

- [ ] Estrutura inicial do projeto.
- [ ] Banco de dados.
- [ ] Autenticação.
- [ ] Cadastro de empresas e usuários.
- [ ] Isolamento de dados por empresa.
- [ ] Permissões básicas.

### Fase 2 — Gestão de vagas e candidaturas

- [ ] Cadastro e gerenciamento de vagas.
- [ ] Formulários de candidatura.
- [ ] Cadastro de candidatos.
- [ ] Associação entre vagas, candidatos e candidaturas.
- [ ] Gestão de etapas do processo seletivo.

### Fase 3 — Banco de talentos

- [ ] Importação de currículos.
- [ ] Armazenamento seguro de arquivos.
- [ ] Pesquisa de candidatos.
- [ ] Filtros.
- [ ] Identificação de duplicidades.
- [ ] Reutilização de candidatos em novas vagas.
- [ ] Histórico de candidaturas.

### Fase 4 — Comunicação e estabilidade

- [ ] Modelos de mensagens.
- [ ] Envio de e-mails básicos.
- [ ] Auditoria de ações relevantes.
- [ ] Backup e recuperação.
- [ ] Revisão de permissões e segurança.
- [ ] Testes funcionais e correção de falhas.

### Fase 5 — Validação e lançamento

- [ ] Testes com empresas piloto.
- [ ] Coleta de feedback dos recrutadores.
- [ ] Correção de problemas identificados.
- [ ] Avaliação de usabilidade.
- [ ] Definição dos planos comerciais.
- [ ] Preparação do ambiente de produção.
- [ ] Lançamento da primeira versão.

### Fase 6 — Expansão

- [ ] WhatsApp oficial.
- [ ] Extração automática de dados de currículos.
- [ ] Recursos de IA.
- [ ] Integrações externas.
- [ ] Publicação automatizada de vagas.
- [ ] White label.
- [ ] Recursos para consultorias.
- [ ] Gestão de contratação e documentos.

---

# 6. Prioridades do MVP

O primeiro lançamento deverá priorizar cinco capacidades fundamentais:

1. **Gerenciar vagas:** criar, editar, encerrar e acompanhar vagas.
2. **Receber candidaturas:** permitir que candidatos enviem seus dados e currículos.
3. **Organizar candidatos:** manter perfis centralizados e acompanhar cada candidatura.
4. **Pesquisar talentos:** localizar candidatos antigos por palavras-chave e filtros.
5. **Reutilizar candidatos:** vincular talentos existentes a novas vagas sem perder o histórico.

Funcionalidades avançadas deverão ser priorizadas com base no feedback dos primeiros clientes, na demanda real e no custo de implementação.

---

# 7. Requisitos gerais do produto

- **Modelo:** SaaS multi-tenant.
- **Público inicial:** equipes de RH de empresas de médio porte.
- **Foco inicial:** gestão de vagas, candidaturas e banco de talentos.
- **Monetização:** planos de assinatura com limites de uso.
- **Segurança:** controle de acesso, isolamento de dados e proteção de currículos.
- **Privacidade:** tratamento de dados conforme a LGPD, com regras de finalidade, acesso, retenção e exclusão.
- **Escalabilidade:** arquitetura preparada para adicionar módulos sem exigir a reescrita completa do sistema.
- **Evolução:** desenvolvimento incremental, validando funcionalidades com usuários reais antes de ampliar o escopo.
