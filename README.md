# 🛡️ Governança, Transações e Controle de Acesso no MySQL

Projeto prático desenvolvido na disciplina de **Programação e Desenvolvimento de Banco de Dados** (Curso de Engenharia de Software – Faculdade Anhanguera / Unopar), aplicando recursos avançados do **MySQL 8.0** via **MySQL Workbench**.

## 🎯 Funcionalidades Implementadas

* **Automação de Processos (`CREATE EVENT`):** Agendamento de evento recorrente (`ev_reajuste_salarial_anual`) com início imediato para aplicar reajuste salarial anual automático de 3%.
* **Controle Transacional (`ACID`):** Execução atômica (`START TRANSACTION` / `COMMIT`) para transferência de departamento de funcionários com registro simultâneo em tabela de auditoria (`log_transacoes`).
* **Controle de Acesso (`GRANT` / `REVOKE`):** Aplicação do princípio do menor privilégio, restringindo a atualização da coluna `salario` exclusivamente ao perfil `usuario_senior` e mantendo o `usuario_junior` apenas com permissão de leitura (`SELECT`).

## 🛠️ Tecnologias Utilizadas
* **MySQL Server 8.0**
* **MySQL Workbench**

---

## 👨‍💻 Autor & Contato

Desenvolvido por **Flávio Freitas da Costa** — Estudante de Engenharia de Software (Anhanguera / Unopar).

[![LinkedIn](https://shields.io)](https://linkedin.com)

