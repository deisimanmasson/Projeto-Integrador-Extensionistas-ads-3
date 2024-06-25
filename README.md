# Projeto-Integrador-Extensionistas-ads-3
Sistema de cadastrar produtos
Requisitos
Ter o XAMPP instalado.
Instalação
É necessário ter um banco de dados com o nome cadastroProdutos, e dentro dele deve ter a tabela produtos, para cria-lá use:
CREATE TABLE produtos (
    id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    quantidade INT NOT NULL,
    valor DECIMAL(10,2) NOT NULL
