# Controle de Estoque de Comidas Nordestinas

Este é um sistema desenvolvido em Python utilizando a biblioteca Tkinter para interface gráfica. O sistema tem como objetivo a gestão de entradas, saídas e cadastro de comidas típicas da região nordestina do Brasil.

## Funcionalidades

- Login de usuários: permite que diferentes usuários acessem o sistema com autenticação.
- Cadastro, consulta, edição e exclusão de comidas típicas da culinária nordestina.
- Registro e histórico detalhado das movimentações no estoque (entradas e saídas).
- Alertas visuais para avisar quando o estoque de um alimento está abaixo do nível mínimo definido.

## Execução

1. Execute o arquivo `db_init.sql` para criar o banco de dados com suas tabelas e dados iniciais, ou deixe o sistema criar automaticamente no primeiro uso.
2. Execute o arquivo `main.py` para iniciar o sistema e acessar a interface gráfica.

## Estrutura de arquivos

- `main.py` : Arquivo principal que inicializa o sistema e gerencia as telas principais.
- `db.py` : Responsável pela conexão e inicialização do banco de dados SQLite.
- `login.py` : Tela e lógica de autenticação dos usuários.
- `comidas.py` : Cadastro, edição, exclusão e exibição das comidas típicas.
- `estoque.py` : Gestão das quantidades no estoque e registro das movimentações.
- `utils.py` : Funções auxiliares diversas, como centralização de janelas e ordenação.
- `db_init.sql` : Script SQL para criação do banco de dados com tabelas e dados iniciais.
- `README.md` : Este arquivo, com orientações e informações gerais sobre o sistema.

**Requisitos:** Python 3.12 ou superior, Tkinter e SQLite.

## Diagrama (DER)

<img width="1168" height="573" alt="image" src="https://github.com/user-attachments/assets/0a318db0-b7a5-424e-870a-0cb7de79a4a9" />


## Tela Inicial

***Login***

<img width="299" height="208" alt="image" src="https://github.com/user-attachments/assets/6c3215c6-e424-4b20-9081-9757422eb826" />

***Login realizado***

<img width="298" height="208" alt="image" src="https://github.com/user-attachments/assets/4a128327-f143-491a-b04b-032f87862296" />

***Usuário Logado***

<img width="746" height="434" alt="image" src="https://github.com/user-attachments/assets/6dd1f85d-14bf-4562-a039-7da0cc934e8d" />

<br>

## Controle de Estoque

<img width="746" height="433" alt="image" src="https://github.com/user-attachments/assets/368cb0e2-7cec-41d9-a18d-7a48372f6f5d" />

***Movimentação***

<img width="748" height="427" alt="image" src="https://github.com/user-attachments/assets/eb4b035b-938d-42ec-8805-44b241113442" />

**Selecionar comida para realizar a movimentação***

<img width="748" height="430" alt="image" src="https://github.com/user-attachments/assets/61602604-daac-405d-82bf-d755d4a981b0" />

***Registrar Movimentação***

<img width="745" height="427" alt="image" src="https://github.com/user-attachments/assets/399fa1dd-59c0-4955-99ae-99e724321e28" />

***Movimentação Concluída***

<img width="746" height="432" alt="image" src="https://github.com/user-attachments/assets/173d93a3-6fae-436a-94f7-9b0ba00cc660" />

<br>

## Histórico

<img width="743" height="428" alt="image" src="https://github.com/user-attachments/assets/b7ea9fe7-ebdb-4801-86d4-ce97917cddc0" />

***Selecionar comida para visualizar o histórico***

<img width="748" height="431" alt="image" src="https://github.com/user-attachments/assets/83351f40-e693-4419-81de-83c819ebf6f5" />

***Visualização do Histórico***

<img width="743" height="425" alt="image" src="https://github.com/user-attachments/assets/8d324402-1d49-462c-a70c-33f09cb27804" />

<br>

***Pesquisa e busca de prato***

<img width="741" height="429" alt="image" src="https://github.com/user-attachments/assets/2f0deb68-11ee-4ab7-b73b-5623cc4a4167" />

***Busca realizada***

<img width="746" height="428" alt="image" src="https://github.com/user-attachments/assets/44e7fb1d-0d1b-4c75-ba5e-02110d464daf" />

<br>

## Edição

<img width="740" height="430" alt="image" src="https://github.com/user-attachments/assets/381125ee-0d2f-40b5-ab65-f73ea421d382" />

***Comida selecionada***

<img width="743" height="431" alt="image" src="https://github.com/user-attachments/assets/89608573-7126-4d97-8abb-271618af93bc" />

***Comida Editada***

<img width="743" height="432" alt="image" src="https://github.com/user-attachments/assets/46155c29-ea0d-4db5-9ef1-c32ac1e5310c" />

<br>

## Nova Comida

***Adição de novo prato***

<img width="750" height="431" alt="image" src="https://github.com/user-attachments/assets/e79ac77a-eef0-4259-a5cd-64335f54966b" />

***Editando Informações***

<img width="744" height="433" alt="image" src="https://github.com/user-attachments/assets/9aee180e-8079-4bfa-8233-a2dee2a61502" />

***Prato Salvo!***

<img width="743" height="434" alt="image" src="https://github.com/user-attachments/assets/bd7a584c-be6d-4aca-8a94-2df5b1f82831" />


