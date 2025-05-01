<h1 align="center">💻 Desafio DIO: Criando uma Máquina Virtual no Azure</h1>

## 📌 Objetivo

Este repositório tem como objetivo documentar o processo de criação e configuração de uma Máquina Virtual (VM) utilizando a plataforma Microsoft Azure, conforme proposto no desafio da DIO.

---

## 🛠️ Passo a Passo

### 1. Acesso ao Portal Azure

- Acesse o [Portal do Azure](https://portal.azure.com).
- Na página inicial, localize a seção **Serviços do Azure** e clique em **Máquinas Virtuais**.

### 2. Criação da Máquina Virtual

- Clique no botão **Criar** e selecione a opção **Máquina virtual do Azure**.
- Preencha os campos obrigatórios, como:
  - Nome da máquina
  - Região
  - Zona de disponibilidade (opcional)
  - Imagem do sistema operacional (ex: Ubuntu, Windows Server)
  - Tamanho da máquina (influencia no custo final)
- Você pode configurar os recursos detalhadamente (disco, rede, etc) ou clicar em **Revisar + Criar** para uma configuração mais rápida.
- Após a validação, o Azure exibirá um resumo com todas as informações da máquina, incluindo o custo por hora.

### 3. Implantação e Acesso

- Confirme e aguarde a conclusão da implantação.
- Após a criação, acesse o recurso para visualizar a tela principal da sua VM.
- As opções disponíveis incluem: **Conectar**, **Parar**, **Reiniciar**, entre outras.
- Para acessar a máquina pelo seu computador:
  - Clique em **Conectar**.
  - Baixe o arquivo RDP (caso tenha escolhido Windows).
  - Insira os dados de login definidos durante a criação.
  - O acesso remoto será iniciado.

> ⚠️ Obs: Algumas telas ou etapas podem diferir das apresentadas no curso, pois o portal Azure passa por atualizações frequentes.

---

## 📚 Aprendizados

- Criação e configuração de uma máquina virtual no Azure
- Acesso remoto utilizando protocolo RDP
- Noções de gerenciamento de recursos na nuvem

---
