# Documentação do Sistema Bancário Simples

Este projeto implementa um sistema bancário simples em Node.js, oferecendo funcionalidades básicas como criação de contas, consulta de saldo, depósitos, saques e encerramento de sessão.

## Funcionalidades

- **Criar conta**: Permite registrar uma nova conta bancária.
- **Consultar saldo**: Facilita a visualização do saldo de uma conta específica.
- **Depositar**: Adiciona um montante ao saldo de uma conta existente.
- **Sacar**: Realiza um saque de uma conta existente.
- **Sair**: Encerra a sessão atual do usuário.

## Pré-requisitos

- Node.js instalado no sistema.
- Pacotes adicionais necessários, como Inquirer e Chalk.

## Instalação

1. Clone o repositório usando o comando:
```bash
https://github.com/ThyagoHSR/Conta-Bancaria-NodeJS.git
```

3. Acesse o diretório do projeto:
```bash
cd conta-bancaria-nodejs
```

5. Instale as dependências necessárias:
```bash
npm install
```

## Como Executar

Para iniciar o sistema, execute:
```bash
npm start
```

## Estrutura do Projeto

- **index.js**: Ponto de entrada do sistema.
- **contas/**: Diretório contendo arquivos JSON representando as contas dos usuários.
- **Funções**: Implementação das funcionalidades principais como `createAccount`, `deposit`, `withdraw`, `checkAccount`, `getAccount`, entre outras.

## Contribuições

Se deseja contribuir com este projeto, siga os passos:

1. Faça um fork deste repositório.
2. Crie uma nova branch para suas funcionalidades (`git checkout -b feature/sua-feature`).
3. Commit suas mudanças (`git commit -am 'Adicione uma nova funcionalidade'`).
4. Push para a branch (`git push origin feature/sua-feature`).
5. Crie um Pull Request.

## Bugs e Feedback

Para reportar bugs ou fornecer feedback, por favor, abra uma issue no [GitHub](https://github.com/ThyagoHSR/Conta-Bancaria-NodeJS.git/issues).

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE). Para mais informações, consulte o arquivo LICENSE.
