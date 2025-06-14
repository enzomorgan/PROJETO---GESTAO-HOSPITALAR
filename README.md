# PROJETO - GESTÃO HOSPITALAR

Este é um projeto de sistema de gestão hospitalar desenvolvido em C.

## Sobre o Projeto

Este sistema foi desenvolvido para a disciplina de ALGORITMOS E ESTRUTURAS DE DADOS II. Ele oferece funcionalidades para cadastro, busca, edição e exclusão de pacientes, além de permitir a consulta de vagas de leitos e o quantitativo de pacientes no hospital.

## Funcionalidades

- **Cadastro de Pacientes:** Permite adicionar novos pacientes ao sistema com suas informações relevantes.
- **Paciente Prioritário:** Gerencia a prioridade de atendimento dos pacientes.
- **Exclusão de Pacientes:** Remove pacientes do sistema.
- **Listagem de Pacientes:** Exibe todos os pacientes cadastrados.
- **Busca de Pacientes:** Permite encontrar pacientes específicos por critérios de busca.
- **Edição de Cadastro:** Atualiza as informações de pacientes existentes.
- **Consulta de Vagas de Leitos:** Verifica a disponibilidade de leitos no hospital.
- **Consulta de Quantitativo de Pacientes:** Informa o número total de pacientes no hospital.
- **Dados do Hospital:** Exibe informações gerais sobre o hospital.

## Como Rodar o Código

Este projeto foi desenvolvido em C e utiliza algumas bibliotecas específicas do Windows (`windows.h`). Portanto, a compilação e execução são recomendadas em um ambiente Windows.

### Pré-requisitos

- Um compilador C (como o GCC, MinGW no Windows).

### Compilação e Execução (Windows)

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/enzomorgan/PROJETO---GESTAO-HOSPITALAR.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd PROJETO---GESTAO-HOSPITALAR
   ```

3. **Compile o código usando um compilador C (ex: MinGW):**
   ```bash
   gcc PROJETO.c paciente.c -o PROJETO.exe
   ```

4. **Execute o programa:**
   ```bash
   ./PROJETO.exe
   ```

## Estrutura do Projeto

- `PROJETO.c`: Contém a lógica principal do programa e o menu de interação.
- `paciente.c`: Implementa as funções relacionadas à manipulação de dados de pacientes.
- `paciente.h`: Define as estruturas de dados e protótipos das funções relacionadas a pacientes.

## Contribuição

Contribuições são bem-vindas! Se você deseja melhorar este projeto, sinta-se à vontade para abrir um *pull request*.



