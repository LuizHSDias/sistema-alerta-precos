# 📈 Sistema Alerta Preços

Sistema web desenvolvido para gerenciamento de alertas de preços e registro automático de compras, utilizando integração com a API da plataforma **OdinLine**.

---

## 📖 Sobre o Projeto

O **Sistema Alerta Preços ** foi desenvolvido como exercício avaliativo da disciplina **Desenvolvimento de Sistemas** do **Centro Federal de Educação Tecnológica de Minas Gerais (CEFET-MG)**.

A aplicação permite que usuários autenticados na plataforma OdinLine cadastrem alertas para produtos específicos. Quando o preço desejado é atingido, o sistema executa automaticamente uma das ações configuradas pelo usuário:

- 🔔 Notificar o usuário;
- 🛒 Registrar automaticamente a compra do produto.

Os alertas e compras são armazenados localmente, enquanto os dados dos usuários e produtos são obtidos através da API disponibilizada pela plataforma OdinLine.

---

## 🚀 Funcionalidades

- ✅ Autenticação de usuários via API
- ✅ Consulta dos produtos cadastrados pelo usuário
- ✅ Cadastro de alertas de preço
- ✅ Monitoramento automático de preços
- ✅ Notificação quando o preço desejado é atingido
- ✅ Registro automático de compras
- ✅ Histórico de compras
- ✅ Persistência de dados utilizando LocalStorage

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6)
- REST API
- LocalStorage
- Git
- GitHub

---

## 📂 Estrutura do Projeto

```
SISTEMA-ALERTA-PRECOS
│
├── css/
│
├── js/
│
├── alerta.html
├── compra.html
├── index.html
└── menu.html
```

---

## 📡 Integração com API

A aplicação realizava integração com a API da plataforma **OdinLine**, utilizando os seguintes recursos:

- Autenticação de usuários
- Consulta de produtos
- Consulta dos produtos cadastrados pelo usuário

Essa integração permitia validar o login e obter dinamicamente as informações dos produtos.

---

## ⚠️ Aviso Importante

Este projeto foi desenvolvido exclusivamente para fins acadêmicos.

Atualmente **não é possível executar completamente a aplicação**, pois a plataforma **OdinLine** e sua API foram descontinuadas após o encerramento da disciplina.

Como consequência:

- Não é possível autenticar usuários;
- Não é possível consultar produtos da plataforma;
- Algumas funcionalidades dependentes da API não podem ser demonstradas atualmente.

O código permanece disponível neste repositório para fins de estudo e demonstração das técnicas utilizadas durante o desenvolvimento.

---

## 🎯 Objetivos do Projeto

Este projeto teve como objetivo praticar:

- Desenvolvimento de aplicações Web;
- Consumo de APIs REST;
- Manipulação de dados utilizando JavaScript;
- Persistência de dados com LocalStorage;
- Organização de código em múltiplas páginas;
- Versionamento de código utilizando Git e GitHub.

---

## 📚 Aprendizados

Durante o desenvolvimento foram praticados conceitos importantes como:

- Consumo de APIs utilizando JavaScript;
- Manipulação do DOM;
- Armazenamento local com LocalStorage;
- Estruturação de aplicações Web;
- Controle de fluxo da aplicação;
- Organização de arquivos JavaScript e CSS;
- Versionamento com Git.

---

## 👨‍💻 Autor

**Luiz Henrique Santos Dias**

🎓 Engenharia de Computação — CEFET-MG

🔗 LinkedIn: https://www.linkedin.com/in/dev-luizh/

🔗 GitHub: https://github.com/LuizHSDias

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e de aprendizado.