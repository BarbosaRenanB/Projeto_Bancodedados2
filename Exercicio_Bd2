create database taxiradio;

use taxiradio;

create table pessoa (
 id_pessoa int (5) auto_increment primary key, 
 nome_pessoa varchar (50),
 endereco varchar (50)
 );

create table veiculos (
 id_veiculos int (5) auto_increment primary key, 
 nome_veiculo varchar (50),
 placa varchar (50), 
 caracteristicas varchar (50) 
 );

create table motoristas (
 id_motorista int (5) auto_increment primary key, 
 idiomas varchar (50),
 historico varchar(50) 
 );

create table ocorrencias (
 id_ocorrencia int (5) auto_increment primary key,
 detalhes varchar (50) 
 );
 
create table registros (
 id_registro int (5) auto_increment primary key,
 dataa date,
 hora varchar(50),
 percurso varchar (50),
 valor varchar(50)
 );

INSERT INTO motoristas (idiomas, historico)
VALUES ("Ingles", "Nao contem incidentes " );

INSERT INTO ocorrencias (detalhes)
VALUES (" Acidente envolvendo 2 ou mais automoveis - Grave");

INSERT INTO veiculos (nome_veiculo, placa, caracteristicas)
VALUES ("Fiat - Siena", "JXQ-4553", "Prata, 2008/2009");

INSERT INTO pessoa (nome_pessoa, endereco)
VALUES ("Renan Barbosa", "Av. Desembargador Joao Machado, 1500");

INSERT INTO registros (dataa, hora, percurso, valor)
VALUES ('2016-09-25', "10:30", "5 Km", "30 $");



