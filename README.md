# Bat-Sinal App - Interface Mobile em React Native

Bem-vindo ao projeto **Bat-Sinal App**, uma aplicação móvel desenvolvida em **React Native** que permite acionar e visualizar o famoso sinal do Batman de forma **interativa e responsiva**.

---

## 📝 Objetivos de Aprendizagem

Ao concluir este desafio, você será capaz de:

- Reproduzir e/ou melhorar um projeto com base em um código existente;  
- Aplicar os conceitos aprendidos em um cenário real;  
- Documentar seu raciocínio técnico e decisões de forma clara e organizada;  
- Utilizar o GitHub como plataforma para versionamento e exposição do seu trabalho.

---

## 🚀 Tecnologias Utilizadas

- **React Native** – framework para desenvolvimento mobile multiplataforma;  
- **Expo** – ferramenta para simplificar o desenvolvimento e testes em dispositivos reais;  
- **React Hooks** – gerenciamento de estado com `useState` e ciclo de vida com `useEffect`;  
- **Flexbox** – para construção de layouts responsivos;  
- **StyleSheet** – para estilização consistente e modular.

---

## 🎯 Funcionalidades

O aplicativo Bat-Sinal oferece:

1. **Acionamento do Sinal**  
   - Botão interativo para ligar e desligar o sinal do Batman.  
   - Animação suave ou efeito sonoro opcional para aumentar a imersão.  

2. **Visualização Responsiva**  
   - O layout se adapta a diferentes tamanhos de tela (smartphones e tablets).  
   - Utiliza componentes como `View`, `Image`, `TouchableOpacity` e `Text`.

3. **Feedback Interativo**  
   - Alteração visual do botão ao pressionar.  
   - Indicação do estado atual do Bat-Sinal (ativo ou inativo).

---

## 🛠️ Estrutura do Projeto

BatSinalApp/
│
├── assets/ # Imagens, ícones e sons
├── components/ # Componentes reutilizáveis (Botão, Sinal, etc.)
├── screens/ # Telas do aplicativo
├── App.js # Componente principal
├── package.json # Dependências e scripts
├── README.md # Documentação do projeto
└── ...


---

## 💡 Dicas de Desenvolvimento

- Utilize **hooks** (`useState`, `useEffect`) para controlar o estado do Bat-Sinal.  
- Para animações, considere o uso de `Animated` do React Native.  
- Estilize com `StyleSheet.create` e utilize **Flexbox** para responsividade.  
- Teste no **Expo Go** para validar a experiência em dispositivos reais.  
- Documente decisões técnicas e registre seu progresso no **GitHub**.  

---

## 📌 Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/bat-sinal-app.git
cd bat-sinal-app

    Instale as dependências:

npm install
# ou
yarn install

    Inicie o projeto com Expo:

npx expo start

    Abra no dispositivo usando Expo Go ou em um emulador.

📝 Considerações Finais

Este projeto serve como exercício para:

    Praticar desenvolvimento mobile com React Native;

    Construir interfaces interativas e responsivas;

    Documentar o fluxo de desenvolvimento e decisões técnicas;

    Expor seu trabalho em GitHub de maneira organizada.

Divirta-se construindo o Bat-Sinal e explore melhorias como efeitos sonoros, animações avançadas e integração com sensores de luz do dispositivo!
