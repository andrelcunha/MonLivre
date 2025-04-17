# MonLivre
[![fr](https://img.shields.io/badge/lang-fr-blue.svg)](README.fr.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

*Um espaço pessoal para organizar, acompanhar e anotar seus livros favoritos.*

## Sobre o projeto
MonLivre é um aplicativo criado para os amantes de livros que desejam:
- Organizar suas coleções de livros e edições específicas.
- Acompanhar seu progresso de leitura e criar listas de desejos para futuras leituras.
- Anotar e documentar seus pensamentos ou citações favoritas.
- Explorar e celebrar sua jornada literária com estatísticas personalizadas e diários.

## Principais funcionalidades
- **Gerenciamento de livros**: Adicione livros com suas edições específicas (editora, ano, tipo de edição).
- **Status pessoal**: Acompanhe os livros que você possui, já leu ou deseja adquirir.
- **Anotações**: Escreva suas reflexões, análises ou citações memoráveis.
- **Estatísticas**: Veja seus hábitos de leitura e monitore o progresso.
- **Design moderno**: Interface responsiva criada com Vue + Quasar.

## Tecnologias utilizadas
- **Frontend**: Vue + Quasar
- **Backend**: Node.js (NestJS) com Prisma para gerenciamento de banco de dados.
- **Banco de dados**: PostgreSQL
- **Implantação**: Hospedado com AWS (Dockerizado).

## Instalação e uso
### Pré-requisitos
- Node.js instalado (versão 16 ou superior).
- PostgreSQL configurado para o backend.

### Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/andrelcunha/MonLivre.git
   ```
2. Instale as dependências:
   ```bash
   cd monlivre-backend
   npm install
   ```
3. Configure o arquivo .env para a conexão com o banco de dados:
   ```env
   DATABASE_URL=postgresql://<usuário>:<senha>@<host>:<porta>/<nome_do_banco>
   ```
4. Inicie o servidor:
   ```bash
   npm run start
   ```
5. Acesse o aplicativo no seu navegador em http://localhost:3000.
## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
   