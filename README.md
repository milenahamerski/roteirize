# Roteirize - Projeto de Avaliação

## Avaliação

A avaliação da disciplina se dá pela entrega de um projeto de uma aplicação web desenvolvida para a matéria de **Web3** da **UTFPR - Campus Guarapuava**. O projeto utiliza o framework **Angular** e será desenvolvido progressivamente conforme o conteúdo semanal. A aplicação será avaliada com base em uma lista de tópicos a serem implementados e será considerada funcional quando atender ao escopo proposto. A aplicação envolve o desenvolvimento de componentes reutilizáveis, interface responsiva e integração com serviços, aplicando as práticas e tecnologias aprendidas ao longo do curso.


### RA1 - Prototipar e projetar interfaces gráficas de usuário

- [x] **ID1**: Desenvolveu protótipos de interfaces que demonstram compreensão das diretrizes de usabilidade.
- [x] **ID2**: Projetou interfaces responsivas que se adaptam a diferentes tamanhos de tela.

### RA2 - Criar e reutilizar componentes em frameworks frontend

- [x] **ID3**: Desenvolveu componentes reutilizáveis e responsivos.
- [x] **ID4**: Incorporou componentes de frameworks CSS.
- [x] **ID5**: Aplicou diretivas estruturais para exibir/ocultar conteúdo condicionalmente.
- [x] **ID6**: Utilizou diretivas estruturais para criar listas dinâmicas.
- [x] **ID7**: Aplicou Pipes para formatar dados de maneira legível.

### RA3 - Sincronizar dados entre a interface gráfica e o modelo de dados

- [x] **ID8**: Utilizou técnicas de one-way data binding.
- [x] **ID9**: Aplicou event binding para capturar eventos do usuário.
- [x] **ID10**: Implementou two-way data binding.
- [x] **ID11**: Fez uso de variáveis de template para manipulação dinâmica de dados.

### RA4 - Implementar comunicação eficaz entre componentes

- [x] **ID12**: Criou comunicação entre componentes não hierárquicos utilizando serviços.
- [x] **ID13**: Utilizou diretivas @Input e @Output para comunicação entre componentes.

### RA5 - Criar interfaces de navegação intuitivas e responsivas

- [x] **ID14**: Configurou rotas para navegação entre páginas.
- [x] **ID15**: Passou dados entre componentes usando parâmetros de rotas.
- [x] **ID16**: Criou navegação aninhada para representar hierarquias.
- [x] **ID17**: Aplicou guardas de rotas para controle de acesso.

### RA6 - Realizar requisições assíncronas para serviços web

- [x] **ID18**: Fez requisições assíncronas a uma API pública (GET).
- [x] **ID19**: Fez requisições assíncronas a uma API simulada (GET, POST, PUT, PATCH, DELETE).
- [x] **ID20**: Tratou respostas de sucesso e erros de requisições assíncronas.
- [x] **ID21**: Aplicou validações de entrada nos formulários.
- [x] **ID22**: Desabilitou o botão de submit com campos inválidos.
- [x] **ID23**: Utilizou Promises para tratar respostas assíncronas.
- [x] **ID24**: Utilizou Observables para tratar respostas assíncronas.

### RA7 - Gerenciar o código-fonte de maneira eficiente

- [x] **ID25**: Criou o repositório no GitHub com a estrutura do **Gitflow**.
- [x] **ID26**: Colaborou efetivamente com outros membros, resolvendo conflitos de código.
- [x] **ID27**: Planejou, configurou e executou o processo de build e deploy da aplicação.

## 📂 Links importantes

- Protótipos: [https://www.figma.com/design/jOiTP4rxAaJDzGPnDZNpwi/Untitled?node-id=0-1&t=ppaJb3qFjNg7BTCP-1](#)
- Deploy da aplicação: [https://milenahamerski.github.io/roteirize/](#)

## Executando a API com Ambiente Virtual (venv)

Para rodar a API, você precisará configurar um ambiente virtual Python. Siga os passos abaixo para garantir que tudo esteja configurado corretamente:

### Passo 1: Clone o Repositório

Primeiro, clone o repositório para o seu computador:

```sh
git clone https://github.com/seu-usuario/roteirize.git
cd api/teste.py
python -m venv venv

No Windows:
.\venv\Scripts\activate

No macOS ou Linux:
source venv/bin/activate

Passo 4: Instalar as Dependências da API
Agora que o ambiente virtual está ativo, instale as dependências necessárias para rodar a API:
pip install -r requirements.txt

Agora, para rodar a API utilizando o Uvicorn, basta executar o seguinte comando no diretório do projeto:
uvicorn api.teste:app --reload


Agora, para rodar o JSON Server na porta 3001, execute o seguinte comando no diretório onde o arquivo db.json está localizado (no seu caso, parece que é em db.json):

json-server --watch db.json --port 3001
