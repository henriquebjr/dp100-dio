# 2. Chatbot baseado em conteúdo de PDFs

1. Cria-se o Hub de IA do Azure.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/1_create_ai_foundry_hub.png)

2. Hub de IA do Azure criado.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/2_foundry_criado.png)

3. Cria um projeto dentro do AI Foundry Hub.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/3_criar_projeto.png)

4. Projeto criado.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/4_projeto_criado.png)

5. Depois é necessário selecionar um modelo para implantar.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/5_implantando.png)

6. Implantação do modelo.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/6_implantando_modelo.png)

7. Para implementar um RAG é necessário utilizar algum modelo de embeddings.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/7_embeddings.png)

8. No modelo de embeddings se adiciona então os dados a serem vetorizados.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/8_adiciona_dados.png)

9. A criação do serviço de pesquisa é necessária para possibilitar a pesquisa sobre os dados vetorizados

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/9_search_service.png)

10. Revisão da criação do serviço de pesquisa.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/10_ai_search.png)

11. Os documentos adicionados tomam um tempo para serem adequadamente vetorizados.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/11_ingestao.png)

12. Exemplo do uso do chat com base nos documentos enviados.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources2/12_chat.png)

## Considerações

No playgroud foi possível visualizar o chat com os dados do documento enviado. Porém assim como na demonstração do desafio, não foi possível implantar um "chat pronto". Caso fosse utilizar em um aplicação real, a sugestão é implantar como API para ser consumida por uma interface de chat a ser desenvolvida.