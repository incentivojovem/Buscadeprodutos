BUSCA DE PRODUTOS E CLIENTES — STANDALONE

1. Abra index.html no Chrome ou Edge.
2. Faça login com a mesma conta do sistema original.
3. Após a validação do usuário, os dados são carregados do Firestore.
4. A busca mostra sugestões enquanto você digita e mantém a lógica principal do projeto original:
   - Produtos: relevância por texto, palavras, aproximação e código.
   - Clientes: comparação exata, início e conteúdo nas primeiras 6 colunas.
   - Produtos: até as primeiras 5 colunas e suporte a quantidade no início da busca.
   - Enter em código/CNPJ exato de cliente abre a ficha de impressão.
5. A tela exibe apenas os campos estruturados usados pelo sistema original, evitando metadados internos do Firestore.
6. A impressão replica o padrão original em alta resolução (1780x1080), com cabeçalho SUPERFÁCIL ATACADO, código, QR, razão social, bairro, endereço, vendedor, emissão e rodapé.

OBSERVAÇÃO SOBRE FILE://
A página não usa iframe para imprimir. A impressão abre uma nova janela com a imagem gerada em canvas, evitando o erro de origem única causado por iframe com file://.
O Firebase continua sendo o banco de dados remoto; não é necessário hospedar o site para abrir a interface.
