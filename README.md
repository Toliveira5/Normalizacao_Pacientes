# Normalizacao_Pacientes
**DESAFIO: Normalização Pacientes**

Com base na (1) visão geral do sistema, (2) especificação textual do esquema e (3) instância do
modelo abaixo, aplique o procedimento de normalização e produza um novo modelo relacional
normalizado, bem como o desenho atualizado da instância do modelo na forma de tabelas.

Você deverá produzir um documento contendo: 
- (1) Especificação textual do esquema
- (2) Instância do modelo. 

**VISÃO GERAL DO SISTEMA:** Deseja-se fazer um sistema para registrar as consultas de um
paciente. O paciente pode realizar várias consultas e uma consulta é registrada para um único
paciente. Para cada consulta deve-se registrar a data da consulta, o médico que realizou o
atendimento e o diagnóstico do paciente. Um médico pode realizar várias consultas e uma consulta
é realizada por um médico.

**ESPECIFICAÇÃO TEXTUAL DO ESQUEMA** (não normalizado)

Consulta-Paciente (codPaciente, nomePac, dtNasc, sexo, fone, endereco,
codConsulta, data, codMedico, nomeMed, codEsp, nomeEsp, diagnostico)

**INSTÂNCIA DO MODELO (não normalizado)**

<img width="902" height="364" alt="image" src="https://github.com/user-attachments/assets/9a865244-9e33-499e-ab3b-029c402f3375" />
