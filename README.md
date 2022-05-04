# Banco-de-Dados-Tabelas
CREATE TABLE `aluno` (
  `Matricula` int NOT NULL AUTO_INCREMENT,
  `Nome` varchar(30) NOT NULL,
  `CPF` float NOT NULL,
  `Endereco` varchar(30) NOT NULL,
  `CursoPreferido` int DEFAULT NULL,
  PRIMARY KEY (`Matricula`)
) ENGINE=InnoDB AUTO_INCREMENT=6 DEFAULT CHARSET=utf8mb3

CREATE TABLE `curso` (
  `ID_curso` tinyint NOT NULL AUTO_INCREMENT,
  `Nome` varchar(30) NOT NULL,
  PRIMARY KEY (`ID_curso`)
) ENGINE=InnoDB AUTO_INCREMENT=6 DEFAULT CHARSET=utf8mb3

CREATE TABLE `professor` (
  `ID_Prof` tinyint NOT NULL AUTO_INCREMENT,
  `Nome` varchar(30) NOT NULL,
  `CPF` float NOT NULL,
  `Salario` float DEFAULT NULL,
  `CargaH` float DEFAULT NULL,
  PRIMARY KEY (`ID_Prof`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb3
