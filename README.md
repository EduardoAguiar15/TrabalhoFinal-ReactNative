# TrabalhoFinal-ReactNative

https://github.com/user-attachments/assets/c7dec39e-e5e7-4da1-be23-c62ac80060ad

## 📖 Sobre o projeto:
Projeto desenvolvido durante o curso de **Desenvolvimento de Software** pelo **Parque Tecnológico SERRATEC**, na disciplina de **Desenvolvimento Mobile**. O objetivo foi criar um aplicativo que simula uma **rede de filmes**, consumindo dados de uma API e exibindo informações categorizadas por gênero, descrição e classificação.

## 🚀 Tecnologias utilizadas:
- **React Native**
  
- **TypeScript**
  
- **Bottom Tabs Navigator**
  
- **Async Storage**
  
- **JSON Server**
  
- **DB JSON (simulação de banco de dados)**

## 📂 Funcionalidades
- **Listagem de filmes com informações de gênero, descrição e classificação**

- **Navegação entre telas com Stack Navigation e Bottom Tabs**

- **Consumo de API de filmes**

- **Simulação de backend com JSON Server e db.json**

- **Armazenamento local com Async Storage**

## ⚙️ Como rodar:

- **Instalar o Expo CLI globalmente (necessário para React Native com Expo):**
```bash
npm install -g expo-cli
```

- **Clonar o repositório:**
```bash
git clone https://github.com/EduardoAguiar15/TrabalhoFinal-ReactNative.git
```

- **Instalar JSON Server globalmente:**
```bash
npm install -g json-server
```

- **Instalar dependências (dentro de TrabalhoFinal-ReactNative):**
```bash
npm install
```

- **Descobrir o IP da máquina:**
```bash
ipconfig
```
Procure por algo como: ***Endereço IPv4 . . . . . . . : 192.168.0.15***

- **Alterar a URL da API:**

Na pasta: ***Services/apiUser/api.tsx***, trocar a url a partir do Endereço IPv4 da sua máquina.

EX: ***const url = "http://192.168.0.15:3000/usuarios";***

- **Rodar o JSON Server (dentro de TrabalhoFinal-ReactNative):**
```bash
npx json-server --host 0.0.0.0 db.json
```
- **Abra OUTRO terminal e rode (sem fechar o outro CMD):**
```bash
npx expo start
```
