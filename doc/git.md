# Git & GitHub

## Diferença entre Git e GitHub

Git é uma ferramenta de versionamento de código distribuído,
que permite o gerenciamento de projetos por várias pessoas,
a partir de repósitórios locais que se comunicam com um repositório remoto.

GitHub é um serviço de hospedagem de repositórios Git em nuvem,
que oferece também outros serviços que facilitam o gerenciamento de código
e de projetos. 

## Segurança

O Git é sistema distribuído seguro, que em sua natureza, gerencia seus objetos através de referências criptografadas em SHA-1.
Dessa forma, a qualquer mínima alteração na estrutura do projeto, um novo ciclo de versionamento é iniciado. Permitindo também
o registro e acompanhamento de todo o histórico de alteração e dos usuários que as realizaram.

## Objetos básicos do Git

- **Blobs:** referenciam os conteúdos dos arquivos e seus metadados.
- **Trees:** referenciam *blobs* e *trees* e seus metadados.
- **Commits:** referenciam *trees*, o parente (*commit* anterior) e seus metadados.

## Estados dos objetos

- **Untracked:** é o estado em que o objeto encontra-se desconhecido pelo Git.
- **Tracked:** é o estado em que o objeto foi adicionado e encontra-se conhecido pelo Git.
  - **Unmodified:** imediatamente após o *commit*, é o estado em que o objeto se encontra.
  - **Modified:** estado em que se encontram os objetos, quando sofrem qualquer mínima alteração.
  - **Staged:** estado em que ficam os objetos, quando são adicionados e estprontos para o *commit*.
