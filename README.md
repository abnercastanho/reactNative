# 💸 Controle de Gastos Diários

Aplicativo mobile desenvolvido com **React Native** para gerenciamento simples de gastos diários.  
Permite adicionar, editar, remover despesas e visualizar o total gasto de forma prática.

---

## 📱 Funcionalidades

✅ Adicionar novos gastos  
✅ Editar gastos existentes  
✅ Remover gastos da lista  
✅ Validação de campos  
✅ Cálculo automático do total gasto  
✅ Interface simples e intuitiva  

---

## 🧠 Regras de Negócio

- A descrição e o valor são obrigatórios
- O valor deve ser numérico
- O valor é formatado com duas casas decimais
- Cada gasto possui um ID único
- Caso um item em edição seja removido, o modo de edição é cancelado

---

## 🛠️ Tecnologias Utilizadas

- React Native
- JavaScript (ES6+)
- Hooks (`useState`)
- Componentes nativos:
  - `View`
  - `Text`
  - `TextInput`
  - `TouchableOpacity`
  - `FlatList`
  - `Alert`

---

## 📸 Interface

### 🏠 Tela Principal
- Campo para descrição
- Campo para valor
- Botão de adicionar/atualizar
- Lista de gastos
- Total acumulado

---

## ⚙️ Como Executar o Projeto

### 🔧 Pré-requisitos

- Node.js instalado
- Expo CLI ou ambiente React Native configurado

---

### 🚀 Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/reactNative.git

# Acesse a pasta do projeto
cd reactNative/controle-gastos

# Instale as dependências
npm install

# Execute o projeto
npm start
