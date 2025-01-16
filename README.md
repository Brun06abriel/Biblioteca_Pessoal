# 📚 **Biblioteca Pessoal - Bruno Oliveira**  
📍 **Endereço:** Rua dos Bobos, n° 0  
🌆 **Localidade:** Cidade, Estado, 12345-678  
📞 **Contato:** (XX) 0000-0000  
🗓️ **Data:** 14 de janeiro de 2025  


## 🧐 **Visão Geral**  
O sistema de cadastramento pessoal de livros tem como objetivo:  
- 📘 Centralizar informações sobre **leituras**.  
- 📚 Gerenciar **pretensões de leitura**.  
- ✨ Proporcionar **recomendações personalizadas**.  
- 🔗 Armazenar **links úteis** relacionados à experiência literária.  

Com uma interface organizada e acesso protegido por sistema de login, o projeto foca em oferecer um ambiente personalizado e eficiente para os amantes de livros.


## 🎯 **Objetivos**  
- 🗂️ **Organização pessoal:** Acompanhar livros lidos e os que deseja ler, além de recomendar e receber sugestões personalizadas.  
- 🏢 **Gestão centralizada:** Centralizar links e anotações relacionados aos livros.  
- 🔒 **Segurança de dados:** Proteger as informações do usuário com um sistema seguro de autenticação.  
- 📱 **Fácil acessibilidade:** Criar uma interface intuitiva e responsiva.  


## 📝 **Necessidades Observadas**  
- 🔍 Sistema eficiente para **organizar leituras**.  
- 🌐 Plataforma integrada para informações pessoais sobre livros.  
- 🤝 Recurso para registrar e compartilhar **recomendações literárias**.  
- 📌 Ferramenta para armazenar **links úteis** relacionados à leitura.


## ⚙️ **Regras de Negócio**  
1. 👤 Cada usuário deve possuir um **perfil único** acessível por login.  
2. 📖 Usuários podem **cadastrar, editar e remover livros** em suas listas pessoais.  
3. 🗂️ Organização em **três categorias principais**:  
   - Lidos  
   - Quero Ler  
   - Recomendações  
4. 🔗 Links associados a livros são opcionais, com suporte a descrições curtas.  
5. 🔒 Dados de usuários devem ser mantidos em sigilo, com senhas seguras.  


## 🛠️ **Requisitos Funcionais**  
### **Cadastro de Usuário**  
- ➕ Permitir o registro de novos usuários.  
- 🔑 Dados necessários: **nome, e-mail e senha**.  

### **Login e Autenticação**  
- 🔐 Implementar autenticação por **e-mail e senha**.  
- 🔄 Oferecer opção de **recuperação de senha**.  

### **Gestão de Livros**  
- 📥 Inserir livros com campos:  
  - Título  
  - Autor  
  - Gênero  
  - Status ("Lido", "Quero Ler", "Recomendação")  
  - Links relacionados  
- ✏️ Atualizar e excluir registros.  

### **Organização e Pesquisa**  
- 📚 Organizar livros por **categorias**.  
- 🔍 Função de busca para localizar livros por **título** ou **autor**.  

### **Histórico e Estatísticas**  
- 📊 Gerar relatórios simples (ex.: total de livros lidos, gêneros mais lidos).


## 🛡️ **Requisitos Não Funcionais**  
- **Segurança**:  
  - 🔒 Armazenar senhas com hashing.  
  - 📶 Implementar boas práticas de segurança no banco de dados.  
- **Performance**:  
  - ⚡ Suporte para até **1000 usuários simultâneos**.  
- **Compatibilidade**:  
  - 🌐 Funcionar em navegadores modernos e dispositivos móveis.


## 🛠️ **Tecnologias Utilizadas**  
- **Backend:** Java (Spring Boot ou similar)  
- **Banco de Dados:** MySQL  
- **Frontend:** HTML, CSS, JavaScript (ou frameworks como React)  
- **Autenticação:** Spring Security ou biblioteca equivalente  


## 🗄️ **Estrutura Inicial do Banco de Dados**  

### **Usuários**  
- ID (chave primária)  
- Nome  
- E-mail  
- Senha  

### **Livros**  
- ID (chave primária)  
- Título  
- Autor  
- Gênero  
- Status  
- Link  
- Usuário ID (chave estrangeira)  


## 🚀 **Próximos Passos**  
1. 🖼️ Criar protótipos de interface.  
2. 🏗️ Implementar a estrutura inicial do backend e banco de dados.  
3. 🔐 Desenvolver módulos de autenticação e gestão de livros.  
4. ✅ Realizar testes de usabilidade e segurança.  


## 🔮 **Possíveis Extensões Futuras**  
- 🌐 Integração com APIs para sugerir livros com base nos gêneros favoritos.  
- ⭐ Sistema de avaliação de livros.  
- 📤 Exportação de dados para PDF ou Excel.  
