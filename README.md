markdown

# Desafio Azure - Máquinas Virtuais (DIO)

## Descrição
Desafio prático proposto pela DIO para consolidar conhecimentos sobre máquinas virtuais na plataforma Microsoft Azure.

## Objetivo
- Criar e configurar uma VM no Azure
- Documentar o processo
- Compartilhar no GitHub

## Passos Executados

1. Acesse o portal Azure: https://portal.azure.com/
2. Criação da VM (Windows):
   - Digite máquinas virtuais na pesquisa
   - Nas opções que vão surgir na pesquisa, em Serviços, selecione Máquinas virtuais
   - Na página Máquinas virtuais, clique em Criar e selecione Máquina virtual. A página Criar uma máquina virtual é aberta.
   - Em Detalhes da instância, insira myVM no Nome da máquina virtual e escolha Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 na Imagem. Deixe os outros padrões
   - Em Conta de administrador, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.
   - Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa
   - Deixe os padrões restantes e, em seguida, selecione o botão Examinar + criar na parte inferior da página
   - Após a execução da validação, selecione o botão Criar na parte inferior da página
   - Após a conclusão da implantação, selecione Ir para o recurso
   
3. Capturas de tela: veja pasta `/imagens`

## Tecnologias Utilizadas
- Microsoft Azure
- Git e GitHub
- Bloco de Notas (Markdown)

## Capturas de Tela
Veja a pasta `/imagens` com evidências do processo.

## Autor
Sidinei - [LinkedIn](www.linkedin.com/in/sidinei-cruz-seguranca-cibernetica)
