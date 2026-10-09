🛒 Lista de Compras App

Um aplicativo simples e intuitivo de lista de compras construído do zero com React Native, Expo e TypeScript. Este projeto foi desenvolvido para organizar compras de forma rápida, permitindo adicionar itens com quantidade e removê-los com facilidade.

✨ Funcionalidades

Adicionar Itens: Insira o nome do produto e a quantidade (com valor padrão de 1 caso a quantidade seja omitida).

Validação de Entrada: O aplicativo alerta o usuário caso tente adicionar um item sem nome.

Remover Itens: Exclua produtos facilmente tocando no botão de remover.

Contador Dinâmico: Um rodapé atualizado em tempo real mostra a quantidade total de itens na sua lista.

Estado Vazio (Empty State): Interface amigável avisando quando não há produtos na lista.

Tipagem Estática: Código seguro e escalável utilizando TypeScript.

🚀 Tecnologias Utilizadas

React Native

Expo

TypeScript

expo-status-bar para gerenciamento da barra de status.

📱 Estrutura do Projeto

A arquitetura do projeto foi dividida em componentes reutilizáveis para facilitar a manutenção:

lista-de-compras/
├── app.json                # Configurações do Expo (nome, versão, cores)
├── package.json            # Dependências e scripts
├── tsconfig.json           # Configurações do TypeScript
├── types.ts                # Definição de tipos compartilhados (Ex: ItemDeCompra)
├── index.tsx               # Ponto de entrada do aplicativo
├── App.tsx                 # Componente raiz e gerenciamento de estado principal
└── components/             # Componentes da interface
    ├── Cabecalho.tsx       # Título e subtítulo do app
    ├── FormularioItem.tsx  # Campos de input e botão de adicionar
    ├── ListaCompras.tsx    # Renderização da FlatList
    └── ItemCompra.tsx      # Cartão individual de cada produto


🛠️ Como Executar Localmente

Siga os passos abaixo para rodar o projeto na sua máquina:

1. Pré-requisitos

Certifique-se de ter o Node.js instalado em sua máquina. Para testar no celular, baixe o aplicativo Expo Go no iOS ou Android.

2. Instalação

Clone este repositório e instale as dependências:

# Clone o repositório
git clone https://github.com/SEU_USUARIO/lista-de-compras.git

# Entre na pasta do projeto
cd lista-de-compras

# Instale as dependências
npm install


3. Rodando o App

Inicie o servidor de desenvolvimento do Expo:

npm start


Isso abrirá o Expo DevTools no seu terminal/navegador. A partir daí, você pode:

Android: Pressionar a para rodar em um emulador Android.

iOS: Pressionar i para rodar no simulador do iOS (necessário macOS).

Dispositivo Físico: Escanear o QR Code fornecido no terminal usando o aplicativo Expo Go.

4. Validação de Tipos

Para verificar se não há erros de tipagem no TypeScript, rode:

npm run typecheck


🧠 Conceitos Aplicados

Durante o desenvolvimento deste aplicativo, foram explorados os seguintes conceitos do React Native e TypeScript:

Gerenciamento de Estado (useState): Controle dos itens da lista e dos inputs do formulário.

Renderização de Listas (FlatList): Renderização performática de arrays com keyExtractor, renderItem, ListEmptyComponent e componentes de cabeçalho/rodapé.

Interfaces (TypeScript): Tipagem de propriedades (Props) entre componentes pais e filhos.

Componentes Essenciais: Uso de SafeAreaView, TextInput, TouchableOpacity e Alert.

Feito com 💜 para organização de compras!
