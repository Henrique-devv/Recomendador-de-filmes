# 🎬 Recomendador de Filmes

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
git clone https://github.com/seu-usuario/Recomendador-de-filmes.git
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
Base html:
![basehtml](https://github.com/user-attachments/assets/d99b74dd-69dd-4157-85b5-757285344c75)
Pastas:
![pastas](https://github.com/user-attachments/assets/c45a8ee8-0e87-4b65-b33a-0b9090b842c9)
Recomendações html:
![recomendacoes](https://github.com/user-attachments/assets/e5a5bd91-f0b1-44d3-bbdb-8193f4b1436b)
App.py:
![app](https://github.com/user-attachments/assets/2d7e9725-81ba-44be-804b-dbc6158a24d5)
Recomender.py:
![recomender](https://github.com/user-attachments/assets/9c8ede3a-9987-415d-bdef-37998a370f9c)
Index html:
![index](https://github.com/user-attachments/assets/30a304aa-e7f7-450c-a4d7-4773ed830267)
dataloader 1: 
![dataloaderpt1](https://github.com/user-attachments/assets/b77fba41-1488-490f-bb09-e3473f7f0ba0)
dataloader 2:
![dataloaderpt2](https://github.com/user-attachments/assets/6e83ec35-5fc8-44a9-a41e-ef547a973778)
Style 1:
![stylept1](https://github.com/user-attachments/assets/e26e01a6-fa13-45c5-8e9b-8ca8126e2b12)
Style 2:
![stylept2](https://github.com/user-attachments/assets/b8acc256-3b92-4aa1-b2d3-3abad4a694f8)
Style 3:
![stylept3](https://github.com/user-attachments/assets/41dbae67-15c8-4598-9318-829710314543)
Style 4:
![stylept4](https://github.com/user-attachments/assets/3094eee3-4ce1-453e-b7f8-23d2eb46ce88)
Style 5:
![stylept5](https://github.com/user-attachments/assets/25dbac05-9a45-424b-a7ec-945a219ebef6)
Pag inicial:
![paginicialbranca](https://github.com/user-attachments/assets/95419a52-82f8-4e0d-a3b7-c630186e24b8)
Pag recomendação:
![pagrecomendacaobranca](https://github.com/user-attachments/assets/50db5765-fbc2-4677-8fcb-080f38f38447)
pag inicial dark theme:
![paginicial](https://github.com/user-attachments/assets/05b406e8-db96-429b-bfb0-bc3c46651436)
pag recomendaçãoo dark theme:
![pagrecomendacao](https://github.com/user-attachments/assets/f97179bc-3f68-4a4c-bdc0-c81c6d498ac1)
Histórico de recomendações:
![historicodeultimasrecomendacoes](https://github.com/user-attachments/assets/ffbb062d-2413-49d0-8f66-1f23448bb274)

---
## Posters

![que_horas_ela_volta](https://github.com/user-attachments/assets/3b393b57-cc1d-4c52-bcd8-77efb67796f6)

![dona_flor](https://github.com/user-attachments/assets/0dd0090c-10e2-4601-a352-2843d521896e)

![cidade_de_deus](https://github.com/user-attachments/assets/6936177c-2a26-40bd-af8c-6776e973f548)

![central_brasil](https://github.com/user-attachments/assets/2ed7db90-c7a0-475e-a3c6-3d302cbd5ab0)

![auto_compadecida](https://github.com/user-attachments/assets/e93584cd-7ec5-4fbb-ae15-205ded1d05f6)

---

## 📌 Observações

- As imagens dos pôsteres estão em `/static/posters`
- O projeto não utiliza banco de dados

---

## 🧑‍💻 Autor

Desenvolvido por **Henrique Carvalho Mauricio Junior**  
🔗 https://github.com/Henrique-devv
