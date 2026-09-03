<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffb6c1,100:ff3ebf&height=200&section=header&text=Maria%20Eduarda%20Marques&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Machine%20Learning%20Engineer&descSize=18&descAlignY=58&animation=none" width="100%"/>

Sou desenvolvedora Python com foco em machine learning aplicado e faço o caminho inteiro: coleta
e rotulagem dos dados, feature engineering, treino, validação e o modelo servido por API em
contêiner.

<a href="https://www.linkedin.com/in/maria-eduarda-marquess" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-FF3EBF?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://dudamarqs.netlify.app/" target="_blank">
  <img src="https://img.shields.io/badge/Portf%C3%B3lio-FF2A9E?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>
<a href="mailto:eduardamarquesnoleto@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-FF5CB8?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

## Projetos

**[Tradutor de Libras em tempo real](https://github.com/dudamarqs/libras-translator)** · Visão computacional

Reconhece o alfabeto manual de Libras pela webcam e escreve o texto na tela. Coletei e rotulei 9.271 amostras de 20 letras. Validei com `LeaveOneGroupOut` por sessão de captura, e não por sorteio: cada dobra testa o modelo numa condição de luz e de posição que ele nunca viu. Reporto **88,4%**, e não a média de 95,9%, porque as dobras antigas tinham só 5 letras e inflavam o resultado. O sistema recusa a resposta quando não reconhece o que vê. São 104 testes e 21 decisões de arquitetura escritas.

`Python` `OpenCV` `MediaPipe` `scikit-learn` `PyTorch` `pytest`

**[Assistente de análise de dados com IA](https://github.com/dudamarqs/ai-data-scientist)** · LLM aplicado · [aplicação no ar](https://ai-data-scientist-6gl8.onrender.com)

Você sobe um CSV e pergunta em português. O LLM escolhe a ferramenta, mas quem calcula é o Python: pandas, scikit-learn e SHAP. Cada resposta mostra qual ferramenta foi chamada e qual número voltou — nenhum valor sai do modelo de linguagem. O provedor troca entre Gemini e Claude por uma linha do `.env`. São 51 testes, Docker Compose e CI, porque para mim um sistema só fica pronto quando outra pessoa consegue rodar.

`Python` `FastAPI` `pandas` `scikit-learn` `SHAP` `Docker` `PostgreSQL` `GitHub Actions`

**[Análise SQL de 100 mil pedidos](https://github.com/dudamarqs/olist-ecommerce-analysis)** · SQL e estatística

Dez perguntas de negócio sobre pedidos reais do marketplace Olist, cada uma com a ressalva junto do número. **Dois dos dez achados não sobreviveram a um teste de permutação** — e estão publicados assim mesmo, porque é isso que uma análise honesta parece.

`DuckDB` `SQL` `Python`

**[Analisador de repositórios com IA](https://github.com/dudamarqs/github-analyzer-ia)** · LLM aplicado · [aplicação no ar](https://github-analyzer-ia.onrender.com)

Avalia a saúde de qualquer repositório público do GitHub. A nota de 0 a 100 sai de 7 sinais ponderados por regras determinísticas; o Gemini só explica o resultado, nunca produz o número. Sem chave de API, a aplicação continua respondendo por regras em vez de falhar.

`Python` `FastAPI` `API do GitHub` `Google Gemini`

**[Classificação de gênero musical](https://github.com/dudamarqs/classificacao-de-genero-musical)** · Machine learning supervisionado · trabalho acadêmico em equipe

Classificação de 35 gêneros a partir de características de áudio do Spotify. Naive Bayes com busca em grade chegou a 80,5% de acurácia. Auditei vazamento de alvo na feature `playlist_subgenre`: removê-la derruba o Random Forest de 75,9% para 48,8% — ainda quase 4x o baseline, e o número honesto do problema.

`Python` `scikit-learn` `R`

**[BR CHAIN — plataforma de notícias](https://github.com/dudamarqs/brchain-plataforma-noticias)** · Full stack · parceria com o Porto Digital

Plataforma de recomendação de notícias com perfis de administrador e de leitor. Em um time de sete pessoas, cuidei da integração dos serviços e da automação do ambiente de desenvolvimento.

`FastAPI` `Next.js` `React Native` `MongoDB` `TypeScript`

## Tecnologias

**Linguagens** — Python, SQL, TypeScript, JavaScript, Java, R, C

**Machine learning** — scikit-learn, PyTorch, pandas, NumPy, validação cruzada
(`LeaveOneGroupOut`, `GridSearchCV`), prevenção de data leakage, detecção de novidade,
SHAP para interpretabilidade

**Visão computacional** — OpenCV, MediaPipe, extração e normalização de landmarks, inferência em
tempo real

**IA aplicada** — APIs de LLM (Google Gemini, Claude), Tool Use, saída estruturada, fallback
determinístico

**Back-end e deploy** — FastAPI, Flask, Streamlit, APIs REST, Docker, Docker Compose,
GitHub Actions, PostgreSQL, MySQL, MongoDB, Redis, DuckDB

**Qualidade** — pytest, ruff, ADRs (registros de decisão de arquitetura)

**Front-end e mobile** — React, React Native, Next.js, Expo

**Em aprendizado** — AWS e sistemas de recuperação (RAG) com avaliação medida

## Formação

**Pós-graduação em Machine Learning Engineering** — FIAP, jul/2026 a jul/2027 (em andamento)

**Análise e Desenvolvimento de Sistemas** — Universidade Católica de Brasília, concluído em 2026
