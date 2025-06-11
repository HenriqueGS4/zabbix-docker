Zabbix com Docker Compose

Este projeto configura um ambiente completo com *Zabbix*, *MySQL* e *Zabbix Agent* utilizando Docker Compose. Ideal para testes, aprendizado ou monitoramento básico.

🔧 Serviços incluídos

- *MySQL 8.0* – Banco de dados para o Zabbix
- *Zabbix Server* – Coleta e armazena os dados de monitoramento
- *Zabbix Web* – Interface web para visualizar e gerenciar os dados
- *Zabbix Agent* – Monitora o próprio servidor Zabbix

🚀 Como subir o ambiente

1. Clone o repositório:
   bash
   git clone https://github.com/seuusuario/zabbix-docker.git
   cd zabbix-docker
   

2. Inicie os containers:
   bash
   docker-compose up -d
   

3. Acesse a interface web:
   - Navegue até: [http://localhost](http://localhost)
   - Login padrão:
     - *Usuário*: Admin
     - *Senha*: zabbix

⚙️ Requisitos

- Docker
- Docker Compose

🧾 Observações

- O volume do MySQL é persistente.
- Zabbix Agent se comunica via rede Docker com o servidor.
- Ajuste as senhas e variáveis conforme seu ambiente.

---

📌 *Projeto criado para fins de aprendizado e prática com Docker e ferramentas de monitoramento.*
