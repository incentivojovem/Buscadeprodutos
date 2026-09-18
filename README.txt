VERSÃO STANDALONE

Abra index.html no navegador. Inclui login, criação de usuário, busca inteligente, impressão e cadastro manual de produtos/clientes.

Usuários comuns criados pela opção Cadastrar recebem status bloqueado, seguindo o fluxo original de aprovação administrativa.
O Firestore/Firebase e suas regras continuam sendo o banco e o controle de acesso do sistema.

Ícone: o projeto agora inclui favicon.ico, ícones PNG e site.webmanifest para identificação no navegador e atalhos.


NOVA FUNÇÃO — EDIÇÃO DE CADASTROS
No botão "Novo Cadastro", a tela de cadastro agora possui "Localizar cadastro existente para editar".
Digite código, CNPJ, código de barras ou nome/descrição. Se houver um cadastro existente, o sistema
exibe os resultados encontrados e o botão "Editar dados". Ao editar, os dados existentes são carregados
no formulário e as alterações são gravadas no mesmo documento do Firestore, preservando os campos extras.
O sistema também verifica duplicidade de código/documento antes de salvar.
