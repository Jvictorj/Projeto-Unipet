# Petshop-Unipet
AINDA EM DESENVOLVIMENTO
 https://yurisales11.github.io/projeto-unisuam/
---

# **Unipet**  
*Descrição breve e objetiva do projeto, como: "Sistema para gerenciamento de dados e autenticação com funcionalidades adaptáveis a diferentes perfis de usuários".*

## **Índice**  
1. [Visão Geral](#visão-geral)  
2. [Funcionalidades](#funcionalidades)  
3. [Tecnologias Utilizadas](#tecnologias-utilizadas)  
4. [Requisitos de Sistema](#requisitos-de-sistema)  
5. [Instalação e Configuração](#instalação-e-configuração)  
6. [Contribuição](#contribuição)  
7. [Licença](#licença)  

## **Visão Geral**  
Este projeto foi desenvolvido como parte do módulo de **Desenvolvimento de Software para Internet (Back-end)** no curso de **Análise e Desenvolvimento de Sistemas**. Ele atende às demandas de uma empresa para:  
- Gerenciamento de clientes.  
- Divulgação de produtos.  
- Implementação de login com 2FA.  

## **Funcionalidades**  
- **Autenticação e Perfis de Usuário:**  
  - Login com 2FA.  
  - Diferenciação entre usuários *Master* e *Comum*.  
- **Gerenciamento de Usuários:**  
  - Cadastro, consulta, alteração e exclusão.  
- **Sistema de Log:**  
  - Registro de autenticações.  
- **Gerenciamento de Produtos e Estoque:**  
  - Cadastro e visualização.  
- **Acessibilidade:**  
  - Ajuste de contraste e tamanho de fontes.  
- **Exportação de Dados:**  
  - Download de lista de usuários em PDF.  

## **Tecnologias Utilizadas**  
- **Back-end:** PHP  
- **Banco de Dados:** MySQL  
- **Front-end:** Bootstrap (ou outro framework escolhido)  
- **Autenticação:** Implementação de 2FA  

## **Requisitos de Sistema**  
- **Servidor Web:** Apache/Nginx  
- **Banco de Dados:** MySQL  
- **PHP:** Versão 7.4 ou superior  

## **Instalação e Configuração**  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/seuusuario/seuprojeto.git
   ```  
2. Configure o banco de dados:  
   - Crie o banco usando o script SQL fornecido em `/database/script.sql`.  

3. Configure o arquivo de ambiente:  
   - Renomeie `.env.example` para `.env` e insira suas credenciais.  

4. Inicie o servidor:  
   ```bash
   php -S localhost:8000  
   ```  

5. Acesse no navegador:  
   - `http://localhost:8000`  

## **Contribuição**  
Contribuições são bem-vindas! Para contribuir:  
1. Faça um *fork* do projeto.  
2. Crie um *branch* para sua funcionalidade (`git checkout -b minha-funcionalidade`).  
3. Faça *commit* das alterações (`git commit -m 'Adicionei minha funcionalidade'`).  
4. Envie para o *branch* principal (`git push origin minha-funcionalidade`).  
5. Abra um *Pull Request*.  

## **Licença**  
Este projeto está licenciado sob a [MIT License](LICENSE).  
