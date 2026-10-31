SMARTGASTRO — DEPLOY NA VERCEL

1. Acesse https://vercel.com e crie um projeto.
2. Importe este diretório/repositório ou envie os arquivos por um repositório Git.
3. Framework Preset: Other.
4. Build Command: deixe vazio.
5. Output Directory: .
6. Deploy.

O site é estático e não precisa de backend, chave de API ou IA.

DADOS:
- Os dados ficam no localStorage do navegador/dispositivo.
- Limpar os dados do navegador pode apagar os dados do app.
- Use Dados > Baixar backup para exportar um JSON.
- Use Dados > Restaurar backup para recuperar o arquivo.
- Para acessar a mesma lista em outro aparelho, exporte e importe o backup manualmente.

GRÁFICOS:
- São desenhados localmente em Canvas, sem Chart.js ou serviço externo.
- A comparação depende dos produtos, mercados e preços informados pelo usuário.
- O histórico de compras é criado ao marcar um item como comprado.
- O histórico de preços é registrado ao cadastrar ou editar um preço.

O app não consulta preços reais de supermercados. A economia potencial é uma estimativa baseada nos valores digitados.
