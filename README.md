# React Native Test Static

Este repositório foi criado como parte da aula de **Testes Estáticos** no curso da PUC. Ele demonstra o uso de ferramentas para análise estática de código em projetos React Native, com foco em identificar e corrigir problemas de qualidade antes da execução ou compilação.

---

## 📚 **O que são Testes Estáticos?**

Testes Estáticos são verificações realizadas no código-fonte sem que ele precise ser executado. O objetivo é identificar problemas como:
- Erros de sintaxe.
- Violações de boas práticas.
- Tipos incorretos.
- Código morto ou não utilizado.

As ferramentas usadas para testes estáticos analisam o código diretamente, sem interagir com o ambiente de execução.

---

## 🛠 **Ferramentas Utilizadas**

1. **ESLint**: Detecta problemas de qualidade e formatação do código.
2. **Prettier**: Garante a consistência na formatação do código.
3. **TypeScript**: Verifica erros de tipagem no código.
4. **Depcheck**: Identifica dependências não utilizadas ou faltantes no projeto.

---

## 🚀 **Scripts Disponíveis**

No arquivo `package.json`, você encontrará os seguintes scripts:

- **Lint (ESLint):**
  ```bash
  yarn lint
  ```
  Executa a análise estática do código com o ESLint.

- **Format (Prettier):**
  ```bash
  yarn format
  ```
  Formata o código utilizando o Prettier.

- **Transpile (TypeScript):**
  ```bash
  yarn transpile
  ```
  Transpila um arquivo TypeScript específico para JavaScript.

- **Depcheck:**
  ```bash
  yarn depcheck
  ```
  Verifica dependências não utilizadas ou faltantes no projeto.

---

## 📁 **Estrutura do Projeto**

- **`src/utils/sumArray.ts`**:
  Demonstra o uso de uma dependência (`lodash`) para somar os valores de um array.
- **`src/utils/generateId.ts`**:
  Demonstra o uso da biblioteca `uuid` para gerar identificadores únicos.

---

## 🎓 **Objetivos da Aula**

1. Compreender o conceito de testes estáticos e sua importância.
2. Aprender a configurar ferramentas como ESLint, Prettier, TypeScript e Depcheck em um projeto React Native.
3. Identificar problemas no código e corrigi-los antes da execução.

---

## 📝 **Como Usar este Repositório**

1. Clone o repositório:
   ```bash
   git clone https://github.com/jacksonsmith/react_native_test_static.git
   cd react_native_test_static
   ```

2. Instale as dependências:
   ```bash
   yarn
   ```

3. Execute os scripts para análise:
   - **Lint:**
     ```bash
     yarn lint
     ```
   - **Format:**
     ```bash
     yarn format
     ```
   - **Transpile:**
     ```bash
     yarn transpile
     ```
   - **Depcheck:**
     ```bash
     yarn depcheck
     ```

---

## 💡 **Notas Adicionais**

- Este projeto foi desenvolvido com foco educacional.
- Caso encontre problemas ou tenha dúvidas, sinta-se à vontade para abrir uma issue no repositório.

---

## 📧 **Contato**

Se tiver dúvidas, entre em contato comigo:
- **Email**: [jacksonsmith@puc.com](mailto:jacksonsmith@puc.com)
- **LinkedIn**: [linkedin.com/in/3jacksonsmith](https://linkedin.com/in/3jacksonsmith)
