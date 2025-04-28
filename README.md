# Elysia Frontend

Este repositório contém o frontend da aplicação Elysia, responsável pela interface de envio e visualização das correções de redação com IA.

## Requisitos
- Navegador moderno (Chrome, Firefox, Edge, etc.)
- (Opcional) Servidor HTTP local para testar funcionalidades de upload (ex: Live Server, http-server, ou servir via backend)

## Como rodar o projeto
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Abra a pasta `frontend` no seu editor de código.
3. Crie um arquivo `config.js` na pasta `frontend` com o seguinte conteúdo (ajuste a URL do backend se necessário):
   ```js
   // config.js
   const BACKEND_URL = "http://localhost:8000";
   ```
4. Abra o arquivo `index.html` no navegador ou use uma extensão como Live Server para rodar localmente.

## Estrutura do projeto
- `index.html`: Página principal da aplicação
- `style.css`: Estilos da interface
- `script.js`: Lógica de interação do frontend
- `config.js`: Configuração da URL do backend (crie este arquivo manualmente seguindo o exemplo acima)
- `assets/`: Imagens e ícones utilizados

## Como contribuir
1. Crie uma branch para sua alteração:
   ```bash
   git checkout -b minha-feature
   ```
2. Faça suas modificações e commite:
   ```bash
   git add .
   git commit -m "Descrição da alteração"
   ```
3. Envie sua branch para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
4. Abra um Pull Request no GitHub e aguarde revisão.

---

## Integração com Backend

1. Certifique-se de que o backend está rodando (por exemplo, em http://localhost:8000).
2. No frontend, crie o arquivo `config.js` conforme instrução acima e ajuste a URL se necessário.
3. O frontend irá se comunicar automaticamente com o backend configurado em `config.js`.
4. Para mudar o backend (produção, staging, etc), basta editar `config.js`.
