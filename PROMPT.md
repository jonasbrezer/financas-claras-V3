Prompt para reprodução do app de finanças

Contexto geral
- Aplicativo de finanças pessoais com foco em resumo rápido de saldo, pendências e caixinhas, além de navegação simples para análise, transações e assistente IA.
- Todo o fluxo deve iniciar já autenticado ou em modo convidado, sem exigir login do usuário final.
- Tom de voz amigável e explicativo, dando dicas para configurar fontes de receita, categorias e limites de gastos.

Estrutura de telas e seções
1) Tela "Análise" (painel principal)
   - Cabeçalho: título "Análise".
   - Indicadores em cartões: "Saldo Atual" (R$ 0,00), "Guardado" (R$ 0,00), "Despesas (Mês)" (R$ 0,00) e "Pendentes" (R$ 0,00). Cada cartão mostra rótulo e valor.
   - Sessão "Análise Gráfica": placeholder para gráfico de evolução ou pizza de despesas/receitas.

2) Tela "Transações"
   - Cabeçalho: título "Transações".
   - Resumo: "Saldo" (R$ 0,00), "Pendentes" (R$ 0,00), "Caixinhas" (R$ 0,00).
   - Lista/placeholder para lançamentos e filtros de período.

3) Tela "Assistente"
   - Cabeçalho: "Assistente" com subtítulo "Com o chat IA".
   - Área de conversa/CTA para iniciar interação com IA financeira.

4) Tela "Mais"
   - Cabeçalho: "Mais".
   - Lista de opções em cartões/botões:
     * "Mais Opções" (seção de agrupamento).
     * "Categorias e Caixinhas" — texto de apoio: "Edite suas fontes de receita e despesa.".
     * "Orçamentos" — texto de apoio: "Defina limites de gastos mensais.".
     * "Configurar Assistente IA" — texto de apoio: "Personalize a persona da sua IA.".
     * "Gerenciar Chaves de API" — texto de apoio: "Configure suas chaves do Gemini.".
     * "Testar Notificação" — texto de apoio: "Envie uma notificação de teste para o Kodular.".

Navegação e layout
- Barra inferior com quatro abas: Análise, Transações, Assistente e Mais.
- Cada aba abre a seção correspondente sem exigir login.
- Paleta neutra com ênfase em legibilidade; usar ícones simples para cada aba/botão.

Ações e CTA sugeridos
- Botão global/CTA em "Transações" para adicionar lançamento.
- Botão/CTA em "Assistente" para iniciar chat ou perguntar sobre finanças.
- Botão/CTA em "Análise" para ver detalhes do gráfico ou filtrar por período.
- Botão/CTA em "Mais" para acessar configurações rápidas (categorias, orçamentos, IA, chaves de API, notificação de teste).

Comportamento de dados
- Valores iniciais zerados (R$ 0,00) em saldo, guardado, despesas do mês, pendentes e caixinhas.
- Não exigir autenticação; caso backend não responda, manter modo convidado e continuar navegando.

Tom visual sugerido
- Layout mobile-first, cartões com cantos arredondados e leves sombras.
- Tipografia clara para rótulos e valores, com destaque para números.
- Manter espaçamento confortável entre seções e botões.
