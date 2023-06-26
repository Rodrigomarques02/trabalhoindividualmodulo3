# Banco de dados 
## Modelagem de dados
---
No modulo 3 realizei o trabalho de desenvolver um banco de dados que irá armazenar dados importantes que será 
utilizados pelo sistema da RESILIADATA.

Tabela de Empresas:

Essa tabela foi criada para armazenar informações sobre as empresas parceiras.
Ela possui campos como ID, Nome, Endereço e Contato.
O campo ID é a chave primária, um identificador único para cada empresa.
Os outros campos armazenam informações relevantes sobre cada empresa, como seu nome, endereço e informações de contato.
Tabela de Tecnologias:

Essa tabela foi criada para armazenar informações sobre as tecnologias utilizadas pelas empresas parceiras.
Ela possui campos como ID e Nome, área.
O campo ID é a chave primária, um identificador único para cada tecnologia.
O campo Nome armazena o nome da tecnologia, como Java, Python, MySQL, etc.
Além disso, mencionou-se a opção de selecionar a área da tecnologia. Se desejar, você pode adicionar um campo adicional para representar a área, como "Área" ou "Categoria".
Tabela de Relacionamento Empresa-Tecnologia:

Essa tabela foi criada para estabelecer uma relação entre as empresas e as tecnologias que elas estão utilizando.
Ela possui campos como ID, ID_Empresa e ID_Tecnologia.
O campo ID é a chave primária, um identificador único para cada relacionamento.
Os campos ID_Empresa e ID_Tecnologia são chaves estrangeiras que referenciam os IDs das tabelas de Empresas e Tecnologias, respectivamente.
Esse relacionamento permite registrar quais tecnologias cada empresa está utilizando, associando o ID da empresa ao ID da tecnologia correspondente.
Tabela de Colaboradores:

Essa tabela foi criada para armazenar informações sobre os colaboradores das empresas parceiras.
Ela possui campos como ID, Nome, Cargo e ID_Empresa.
O campo ID é a chave primária, um identificador único para cada colaborador.
Os campos Nome, Cargo e ID_Empresa armazenam informações relevantes sobre cada colaborador, como seu nome, cargo na empresa e o ID da empresa em que trabalha.
O campo ID_Empresa é uma chave estrangeira que referencia o ID da tabela de Empresas, estabelecendo uma relação entre os colaboradores e suas respectivas empresas.
Essa é a estrutura básica do banco de dados proposto, onde as tabelas foram projetadas para armazenar informações sobre empresas parceiras, tecnologias utilizadas por elas e colaboradores associados. É importante lembrar que essa é apenas uma sugestão e você pode personalizar o banco de dados de acordo com as necessidades específicas do sistema RESILIADATA.

---

Sobre mim:

* Linkedin: www.linkedin.com/in/rodrigo-marques021/

* Email: digao020797@gmail.com
