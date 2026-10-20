# Miriam Estudos — Agente Fiscal de Tributos (SJDR/MG · IBGP 2026)

Plataforma de estudo individual, feita para o concurso da Prefeitura de São João del-Rei (Edital nº 02/2026, consolidado até a Retificação nº 01).

## O que está incluído

- 47 sessões programadas entre 20/10/2026 e 12/12/2026, 2 horas por sessão e domingos livres (42 sessões temáticas ou revisões + 5 simulados).
- 42 materiais de aula/revisão com teoria explicativa dividida em 3 blocos, exemplo, pegadinha e fontes; tarefas dirigidas adicionais para legislação local e atualidades.
- 226 questões autorais distintas, de quatro alternativas, gabarito e justificativa didática. Não são questões oficiais da banca IBGP.
- Cinco simulados, cada um com 30 questões exclusivas, cinco por disciplina e pontuação de acordo com o Anexo III de 2026. Os 150 itens de simulados não são liberados no banco antes da realização da respectiva prova.
- 470 exercícios previstos nas sessões não simuladas, com revisão e reaproveitamento intencional de questões, e 150 itens de simulados: **620 resoluções planejadas, NÃO 620 questões diferentes**.
- Flashcards, revisões em 1, 3, 7 e 14 dias, estatísticas, checklist do edital, cronômetro de estudo, exportação/restauração de progresso e tema claro/escuro.
- Seis PDFs do edital e anexos enviados pelo usuário, na pasta `materiais`.

## Usar imediatamente (computador)

1. Descompacte este ZIP em uma pasta, por exemplo `Miriam Estudos`.
2. Dentro da pasta descompactada, abra **index.html** com Chrome, Edge ou outro navegador moderno.
3. Clique em **Continuar meus estudos** e estude a primeira aula; os dados são mantidos no navegador usado, quando o navegador permite armazenamento local de arquivos.
4. Após as sessões, abra **Configurações → Exportar backup** e salve o `.json` em um local seguro.

**ATENÇÃO:** Abrir HTML diretamente como `file://` é útil para uso offline, mas alguns navegadores restringem o salvamento de dados nesta modalidade. Para maior confiabilidade do progresso e instalação como aplicativo, publique a plataforma em HTTPS usando os passos abaixo. Também existe o arquivo separado `Miriam_Estudos_Abrir_Direto.html` (sem os PDFs anexos), que pode ser enviado diretamente à Miriam.

## Publicar como site instalável (PWA)

Uma opção gratuita é o GitHub Pages. Para publicar:

1. Crie uma conta pessoal em github.com e um repositório novo **público** (por exemplo, `miriam-estudos`).
2. Envie o **conteúdo interno** desta pasta para a raiz do repositório (os arquivos `index.html`, `app.js`, `styles.css`, `data.js`, `manifest.webmanifest`, `sw.js` e as pastas `assets` e `materiais`). Não envie somente o ZIP.
3. Acesse as configurações do repositório: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Selecione a branch principal `main` e a pasta `/(root)`. Salve e aguarde a publicação. O endereço normalmente seguirá o padrão `https://usuario.github.io/miriam-estudos/`.
5. Abra o endereço HTTPS no Chrome/Edge. Se desejar, utilize a opção do navegador para instalar o site como aplicativo.

**Privacidade:** GitHub Pages com repositório público deixa os códigos, aulas e PDFs acessíveis a qualquer pessoa com o endereço. O aplicativo **não envia respostas, notas ou histórico de estudos a um servidor**. Os dados de progresso ficam no navegador local (IndexedDB, com fallback de armazenamento local). Para sincronizar entre dispositivos, use manualmente Exportar/Restaurar backup. Se precisar restringir acesso aos arquivos do curso, será necessário alterar a hospedagem e implementar autenticação.

## Segurança, conteúdo e limitações

- Nenhuma dependência remota, conta, senha, coleta de documentos pessoais, analytics ou anúncios é utilizada.
- Conteúdo elaborado para treinamento; **não há relação oficial com IBGP ou Prefeitura**.
- Legislação municipal exige leitura e conferência da versão consolidada e suas alterações. O PDF integral das leis locais não integra o edital enviado; estão incluídos links oficiais na biblioteca, sujeitos a disponibilidade do portal. Não são presumidas alíquotas e prazos municipais específicos.
- Atualidades e dados locais devem ser verificados em fontes oficiais ou noticiosas atualizadas até a prova; o material não se atualiza sozinho.
- As aulas fornecem uma base didática e revisão dirigida, e não pretendem ser reprodução integral de todas as leis.
- O modo simulado **não corrige durante a prova**. O gabarito de cada teste é liberado após entrega. O tempo é registrado, mas não gera envio automático ao chegar ao limite.
- A plataforma foi testada em renderização de navegador automatizado (fluxos de aula, questões, simulados, relatório, biblioteca e backup). A publicação em domínio HTTPS externo ainda precisa ser feita por quem receber o pacote.

## Arquivos principais

- `index.html`: entrada da plataforma.
- `app.js`: lógica interativa, salvamento, revisões e simulados.
- `data.js`: conteúdo completo já incluído para funcionar offline.
- `data.json`: conteúdo estruturado para futuras edições.
- `styles.css`: identidade visual responsiva.
- `sw.js`, `manifest.webmanifest`, `assets/icon.svg`: instalação e uso offline em HTTPS.
- `materiais/`: edital e anexos enviados originalmente.

**Referência de conteúdo:** Anexo III (pesos e prova), Anexo IV (conteúdos), Anexo II (atribuições), edital consolidado e cronograma. Material autoral de apoio, não material oficial.
