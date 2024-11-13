# 📚 Gerenciador de Links

Bem-vindo ao projeto **Gerenciador de Links**, um aplicativo em React Native feito para organizar e gerenciar links por categorias, como cursos, artigos e muito mais! Esse projeto foi desenvolvido principalmente para fins de aprendizado por meio das aulas da Rocket Seat, explorando as principais funcionalidades do React Native e o uso do Expo.

## 🚀 Funcionalidades

- **Organização de Links**: Adicione, edite e organize seus links favoritos em diferentes categorias, como cursos, artigos, vídeos, etc.
- **Visualização por Categoria**: Visualize links de forma organizada e filtrada.
- **Favoritos**: Marque seus links mais importantes como favoritos para acesso rápido.
- **Compatível com Android e iOS**: Desenvolvido com Expo, o aplicativo pode ser testado e utilizado em ambos os sistemas.

## 🛠️ Tecnologias Utilizadas

- **React Native**: Framework principal para o desenvolvimento de interfaces nativas.
- **Expo**: Plataforma que simplifica o desenvolvimento e deploy de apps em React Native.
- **AsyncStorage**: Para salvar os links e categorias localmente no dispositivo.

## 📸 Demonstração

Tela do aplicativo:

<img src="/readmeAssets/ex.png" alt="Tela Principal do App" width="auto" />


## 📂 Estrutura do Projeto

```bash
├── assets
├── src
    ├── app             # Paginas do Aplicativo
    ├── assets          # Logo do App
    ├── components      # componentes padroes como botões e inputs
    ├── storage         # Por meio do Async, permite armazenar funções que salvam/atualizam/removem os links
    ├── utils           # Funções utilitárias e helpers
    └── styles          # Onde é guardado as cores padrões do app