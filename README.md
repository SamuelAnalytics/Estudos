# Ritmo — seu espaço de estudos

Um planner de estudos em português, feito com HTML, CSS e JavaScript puro.

## Como abrir

1. Abra a pasta `PlanoEstudos` no Zed.
2. No terminal, dentro da pasta, inicie o servidor local com `python -m http.server 8765`.
3. Abra `http://127.0.0.1:8765` no navegador. Para ver alterações enquanto edita, atualize a página.

O site não precisa instalar bibliotecas. O endereço local permite que o navegador habilite os recursos usados no cadastro.

## Publicar na Vercel

Este projeto é estático e já inclui `vercel.json` para servir os arquivos da própria pasta, sem etapa de build.

1. Acesse [vercel.com/drop](https://vercel.com/drop) em uma conta Vercel elegível.
2. Envie `outputs/ritmo-vercel.zip`, ou selecione diretamente a pasta `PlanoEstudos`.
3. Escolha um nome para o projeto e confira se `index.html` está na raiz antes de publicar.

O Vercel Drop cria um projeto novo a cada envio. Para atualizar sempre o mesmo endereço automaticamente, conecte um repositório Git ao projeto depois.

## Acesso

Na primeira visita, use **Criar conta**. Depois, entre com o mesmo email e senha. A sessão continua ativa nesta aba até você sair.

Este é um protótipo sem servidor: contas e planos ficam apenas neste navegador e não são sincronizados. A senha é armazenada como hash local, mas isso não transforma o protótipo em autenticação segura para produção. Use uma senha de teste, diferente das suas outras senhas.

## O que dá para fazer

- Criar uma conta local e escolher uma área: programação e tecnologia, matérias escolares (como Física, Química, Inglês e História), artes, culinária, esportes, finanças, empreendedorismo ou um objetivo próprio.
- Explorar trilhas de lógica, Python, Front-end, JavaScript, Back-end, Java, C#/.NET, C/C++, Go/Rust, PHP, mobile, jogos, SQL, APIs/HTTP, Git/GitHub, testes, DevOps/cloud, dados/IA e cibersegurança.
- Informar o nível, o estilo de aprendizagem, os dias da semana e o tempo por sessão.
- Receber sessões semanais e métodos sugeridos para a área, o nível e a rotina escolhidos.
- Acompanhar um caminho inicial de seis etapas, com explicações e atividades práticas.
- Usar o painel, o checklist semanal, o calendário e o resumo do progresso.
- Marcar etapas concluídas e acompanhar o avanço da trilha.
- Criar sessões com área, tópico, dia, método e duração.
- Editar sessões, marcar o que concluiu e excluir o que não precisa mais.
- Ver o tempo planejado e os minutos de estudo em cada dia da semana.
- Receber revisões sugeridas para 1, 7 e 30 dias depois de concluir uma sessão.
- Usar prática de memória e aprender sobre Feynman, Active Recall, repetição espaçada, Pomodoro e estudo por objetivo.
- Baixar o plano da semana ou modelos CSV para Excel e Google Planilhas.

As sessões, revisões, preferências e trilhas ficam salvas localmente no navegador e separadas por conta. As sessões iniciais são sugestões para você ajustar ou apagar quando quiser. O painel tem visual escuro e permite alternar para o modo claro.
