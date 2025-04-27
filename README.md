
# Criando Máquinas Virtuais na Azure 🚀

## 📚 Sobre o Projeto
Este repositório documenta o processo de criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure, como parte do desafio prático proposto pela DIO.

O objetivo é consolidar o conhecimento adquirido durante o curso, criar um material de apoio para futuras implementações e utilizar o GitHub para compartilhar a experiência de forma estruturada.

## 🎯 Objetivo
- Praticar a criação de uma máquina virtual na Azure.
- Registrar de maneira clara e organizada os passos realizados.
- Compartilhar dicas e boas práticas para otimizar o uso da plataforma.

## 🛠️ Tecnologias e Ferramentas Utilizadas
- **Microsoft Azure** (portal de gerenciamento de recursos em nuvem)
- **GitHub** (controle de versão e compartilhamento de documentação)
- **Markdown** (linguagem de formatação para documentação)

## 🧩 Passo a Passo da Criação da Máquina Virtual

### 1. Acesso ao Portal Azure
- Acessado o portal através do link: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação do Grupo de Recursos
- Nome do grupo de recursos: **grupo-vm-dio**
- Região: **Brazil South**

### 3. Criação da Máquina Virtual
- **Nome da máquina virtual:** vm-dio-teste
- **Imagem utilizada:** Ubuntu Server 22.04 LTS
- **Tamanho da máquina:** Standard_B1s (opção econômica para testes)
- **Método de autenticação:** Par de chaves SSH
- **Portas de entrada abertas:** SSH (porta 22)

### 4. Configurações de Disco
- Tipo de disco do sistema operacional: SSD Standard

### 5. Configurações de Rede
- Rede virtual criada automaticamente.
- IP público atribuído automaticamente para acesso remoto.

### 6. Revisão e Criação
- Conferência de todas as configurações realizadas.
- Aguardada a validação e finalização da implantação.

### 7. Acesso à Máquina Virtual
- Acesso realizado via terminal utilizando o comando:
  ```bash
  ssh nomeusuario@ip_publico_da_vm
  ```
- Primeira conexão solicitou confirmação da autenticidade do host.

## 📷 Capturas de Tela
As imagens do processo estão disponíveis na pasta [/images](./images).

| Etapa                  | Imagem                                   |
|-------------------------|-----------------------------------------|
| Grupo de Recursos       | ![Grupo de Recursos](./images/grupo-recursos.png) |
| Configuração da VM      | ![Configuração da VM](./images/configuracao-vm.png) |
| Acesso via SSH          | ![Acesso SSH](./images/acesso-ssh.png) |

## 📝 Anotações e Dicas Extras
- 🔹 **Economia de custos:** Sempre desligue a VM após o uso para evitar cobranças desnecessárias.
- 🔹 **Automação:** A criação de VMs pode ser feita via Azure CLI ou PowerShell para automação em projetos futuros.
- 🔹 **Boas práticas:** Organizar seus recursos em Grupos de Recursos facilita o gerenciamento e a exclusão de ambientes de testes.

## 🔗 Links úteis
- [Documentação oficial Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Azure CLI - Criar máquinas virtuais via terminal](https://learn.microsoft.com/pt-br/cli/azure/vm)

## 🤝 Contribuição
Este repositório é de uso educacional, mas melhorias e sugestões são bem-vindas! 

