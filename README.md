# ORBIT — Systems Intelligence Lab

ORBIT é um laboratório interativo de observabilidade e resposta a incidentes simulados, criado como projeto de portfólio em Computação.

## O que faz
- Dashboard com indicadores simulados de saúde, ativos, incidentes e resposta.
- Topologia de rede interativa: selecione componentes e inspecione métricas.
- Simulador local de falhas: latência, CPU, conexão com banco e perda de pacotes.
- Central de incidentes com severidade, recomendações de triagem e resolução manual.
- Inventário de ativos sintéticos com busca e exportação CSV.
- Linha do tempo de eventos e exportação de relatórios.
- Tema claro/escuro e layout responsivo.

## Tecnologias
HTML5 · CSS3 · JavaScript Vanilla · Canvas API · CSV · LocalStorage (preferência de tema)

## Executar
Abra `index.html` em um navegador. Nenhum backend, pacote ou chave de API é necessário.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `orbit-systems-intelligence`.
2. Envie `index.html`, `style.css`, `script.js` e `README.md` para a raiz.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)`.
5. Salve e aguarde o link de publicação.

## Arquitetura e limitações
Este MVP é uma demonstração front-end com dataset sintético. Não faz varreduras, não envia pacotes, não acessa dispositivos, não integra monitoramento real e não usa IA real. A resposta é uma recomendação baseada em regras estáticas. Os dados são reiniciados ao recarregar a página.

## Próximas evoluções possíveis
- API Python/FastAPI para separar regras de negócio e interface.
- Coleta de métricas a partir de fontes autorizadas, com autenticação.
- Testes automatizados para detecção, severidade e resolução de incidentes.
- Regras configuráveis e motor de correlação de eventos.
- Integração opcional com modelos de IA para resumir eventos, com validação e rastreabilidade.
- Acessibilidade aprimorada e testes de compatibilidade entre navegadores.
