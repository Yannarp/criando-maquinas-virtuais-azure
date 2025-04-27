

## 🛠 Plano de Entrega do Desafio: Criando Máquinas Virtuais na Azure

# Criando Máquinas Virtuais na Azure 🚀

## 📚 Sobre o Projeto
Este repositório contém a documentação da criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure, como parte do desafio da DIO.

## 🎯 Objetivo
- Praticar a criação de VMs no Azure.
- Documentar de forma clara os passos realizados.
- Utilizar o GitHub como ferramenta de apoio para estudos futuros.

## 🛠️ Tecnologias e Ferramentas
- **Microsoft Azure**
- **GitHub**
- **Markdown** (para documentação)

## 🧩 Passo a Passo

### 1. Acessar o Portal Azure
- Entrar em: [portal.azure.com](https://portal.azure.com)

### 2. Criar uma Máquina Virtual
- Ir em **Máquinas Virtuais** > **Criar** > **Máquina Virtual**.
- Configurações principais:
  - **Grupo de Recursos**: (nome do grupo criado ou usado)
  - **Nome da VM**: (nome escolhido)
  - **Região**: (ex.: Brazil South)
  - **Imagem**: (ex.: Ubuntu Server 22.04 LTS / Windows Server 2022)
  - **Tamanho**: (ex.: Standard_B1s)
  - **Autenticação**: (usuário e senha ou chave SSH)
  - **Portas de entrada**: Habilitar RDP (para Windows) ou SSH (para Linux).

### 3. Configurar Disco e Rede
- Disco padrão: SSD Premium ou HDD Standard.
- Rede: Aceitar configurações padrão para testes.

### 4. Revisar e Criar
- Revisar todas as informações.
- Clicar em **Criar** e aguardar a implantação.

### 5. Acessar a VM
- Usar SSH ou RDP para conectar à máquina virtual criada.

## 📷 Capturas de Tela
As imagens do processo estão disponíveis na pasta `/images`.

## 📝 Anotações e Dicas Extras
- Sempre parar a VM quando não estiver usando para evitar cobranças.
- Utilizar as "Camadas Gratuitas" da Azure se disponível.
- Anotar IPs públicos e credenciais de acesso.
- Automatizar a criação com Azure CLI é uma opção para projetos futuros!

## 🤝 Contribuição
Sinta-se à vontade para contribuir ou sugerir melhorias!

