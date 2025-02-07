# AFLORAR 🌿

O **Aflorar** é um projeto acessível para monitoramento de terrários utilizando um sensor DHT11 conectado a uma Raspberry Pi 4. Ele coleta dados de temperatura e umidade, armazena essas informações em um banco de dados MySQL e permite a visualização por meio de uma interface gráfica desenvolvida em Java (Swing).

## 📌 Funcionalidades
- Leitura de temperatura e umidade com o sensor **DHT11**
- Armazenamento dos dados em um banco **MySQL** via SSH
- Interface gráfica (Swing) para exibição das informações
- Projeto de baixo custo e acessível
- Modularidade e boas práticas de programação orientada a objetos (POO) em Java

## 📋 Requisitos
### Hardware:
- Raspberry Pi 4
- Sensor DHT11
- LED'S
- Resistores
- Fonte de energia (notebook)
- Cabo micro-usb
- Jumpers (cabos macho-femea) e protoboard (opcional)

### Software:
- **Java** (Apache NetBeans/com suporte a Swing)
- **MySQL**
- **Bibliotecas para comunicação com DHT11**
- **Conector JDBC para MySQL**
- **Python**
- **Putty**
- **Mariadb** (mySql)

## ⚙️ Instalação e Configuração
1. **Configurar a Raspberry Pi:**
   - Conectar o sensor DHT11 aos pinos GPIO da Raspberry Pi
   - Instalar as dependências necessárias para leitura do sensor

2. **Configurar o Banco de Dados:**
   - Criar um banco de dados MySQL
   - Configurar as tabelas para armazenar temperatura e umidade

3. **Executar a Aplicação Java:**
   - Compilar e executar a interface gráfica
   - Verificar a comunicação com o banco de dados

## 💡 Melhorias futuras
- Integração com API para alertas
- Suporte para mais sensores
- Gráficos para análise de histórico
- Versão web para acesso remoto

--------------------------------------------------

Criado por **Dev's** (Daniel, Eliza e Victoria)
