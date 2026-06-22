# Mini Navegador Web

![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk)
![JavaFX](https://img.shields.io/badge/JavaFX-21-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 📌 Sobre o Projeto

Mini Navegador Web é uma aplicação desktop desenvolvida em Java com JavaFX como parte de estudos em desenvolvimento de interfaces gráficas. O projeto implementa um navegador funcional com campo de URL e visualização de páginas web embutida, explorando os recursos de `WebView` e `WebEngine` da plataforma JavaFX.

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **JavaFX 21** — `WebView`, `WebEngine`, `TextField`, `VBox`, `Scene`
- **Eclipse IDE** — ambiente de desenvolvimento e build

## 📋 Funcionalidades

- Campo de texto para digitação da URL
- Navegação para a URL ao pressionar **Enter**
- Formatação automática de URL: adiciona `http://` caso o endereço não comece com `http://` ou `https://`
- Visualização de páginas web embutida na janela da aplicação

## ▶️ Como Executar

### Pré-requisitos

- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)
- [JavaFX SDK 21](https://gluonhq.com/products/javafx/)
- [Eclipse IDE](https://www.eclipse.org/downloads/) com suporte a JavaFX (e-fx-clipse recomendado)

### Configuração no Eclipse

1. Clone o repositório:
   ```bash
   git clone https://github.com/MarceloJustin/MiniNavegadorWeb.git
   ```

2. Importe o projeto no Eclipse:
   - `File` → `Import` → `Existing Projects into Workspace` → selecione a pasta clonada

3. Configure a User Library do JavaFX:
   - `Window` → `Preferences` → `Java` → `Build Path` → `User Libraries`
   - Crie uma biblioteca chamada `JavaFX` e adicione os `.jar` da pasta `lib` do JavaFX SDK

4. Adicione os VM arguments na configuração de execução:
   - `Run` → `Run Configurations` → `Arguments` → `VM arguments`:
   ```
   --module-path "caminho/para/javafx-sdk/lib" --add-modules javafx.controls,javafx.web
   ```

5. Execute a classe `application.Main` como **Java Application**.

## 🧪 Testes

O projeto não possui testes implementados — trata-se de um projeto de estudo focado na exploração da API JavaFX.

## 👨‍💻 Autor

Feito por **Marcelo Justin**

[![GitHub](https://img.shields.io/badge/GitHub-MarceloJustin-181717?style=flat-square&logo=github)](https://github.com/MarceloJustin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marcelojustin-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/marcelojustin)

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
