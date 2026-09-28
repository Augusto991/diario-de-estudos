# Diário de Estudos — GitHub Pages + PC + Android

Versão 100% estática, sem Supabase e sem banco de dados externo.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `diario-de-estudos`.
2. Envie **todos os arquivos desta pasta** para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde o endereço do GitHub Pages aparecer.

## Android

Abra o endereço do GitHub Pages no Chrome do Android. Depois use **Instalar app** ou **Adicionar à tela inicial** (o texto pode variar conforme o navegador).

## PC

Abra o endereço do GitHub Pages no navegador. Também é possível instalar como aplicativo pelo menu do navegador quando o PWA estiver disponível.

## Dados e limitações

Os dados são salvos no `localStorage` do navegador: notas, turma, professores, aulas, atividades e progresso permanecem salvos naquele navegador/dispositivo.

Como esta versão não usa banco de dados, uma alteração feita no PC não sincroniza automaticamente com outro celular ou PC. O GitHub Pages hospeda os arquivos do site, mas não armazena os dados dos usuários.

## Segurança

As credenciais de professor/VIP presentes no código do navegador são adequadas apenas para um projeto escolar/local. Elas **não são autenticação de servidor** e não devem ser usadas para proteger dados sensíveis.
