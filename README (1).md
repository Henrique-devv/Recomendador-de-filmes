# 🎬 Recomendador de Filmes com Flask

Um sistema simples e interativo de recomendação de filmes feito em Python com Flask. O usuário escolhe um filme e recebe sugestões de títulos semelhantes com base em similaridade de conteúdo. O projeto possui histórico de recomendações, modo escuro, tema visual personalizado e exibição de pôsteres dos filmes.

---

## 💡 Funcionalidades

- 🔍 Recomendação de filmes baseada no título selecionado
- 🖼️ Exibição de pôster dos filmes
- 📜 Histórico das últimas recomendações
- 🎨 Modo claro e escuro com fundos diferentes
- 🧠 Recomendação baseada em similaridade de sinopse e gêneros
- ⚡ Feedback visual com rótulo de carregamento
- 💻 Interface amigável com design responsivo

---

## 🚀 Como executar localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/movie-recommender.git
cd movie-recommender
```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
venv\Scripts\activate  # No Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
python app.py
```

5. Acesse no navegador:

```
http://127.0.0.1:5000
```

---

## 🛠️ Tecnologias utilizadas

- Python
- Flask
- Pandas
- scikit-learn
- HTML/CSS
- JavaScript

---

## 📁 Estrutura do projeto

```
movie_recommender/
│
├── app.py
├── data_loader.py
├── recommender.py
├── requirements.txt
│
├── static/
│   ├── style.css
│   └── posters/
│
└── templates/
    ├── base.html
    ├── index.html
    └── recomendacoes.html
```

---

## 🧠 Como funciona a recomendação?

O sistema usa vetorização de texto com TF-IDF para calcular a similaridade entre os filmes com base em seus gêneros e outras características, retornando os mais parecidos com o filme selecionado.

---

## 📸 Prints

(Adicione aqui capturas de tela do sistema rodando — index, recomendações etc.)

---

## 📌 Observações

- As imagens dos pôsteres estão em `/static/posters`
- O projeto não utiliza banco de dados

---

## 🧑‍💻 Autor

Desenvolvido por **Henrique Carvalho Mauricio Junior**  
🔗 [Seu LinkedIn ou GitHub aqui]