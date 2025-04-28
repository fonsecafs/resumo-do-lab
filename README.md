# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

Aqui vamos configurar uma VM no Microsoft Azure.
  1. **Acesse o Portal do Azure:**
     1.1. Vá para portal.azure.com e faça login com suas credenciais.
     1.2. Certifique-se de ter uma assinatura ativa do Azure. Acesse o portal do Azure 

  2. **Navegue até o serviço de Máquinas Virtuais:**
     2.1. No menu à esquerda, clique em "Máquinas Virtuais" e, em seguida, em "Criar" ou "Adicionar".
     
  3. **Escolha as configurações básicas:**
     3.1. Nomeie sua máquina virtual.
     3.2. Escolha o sistema operacional (Windows, Linux, etc.) na seção "Imagem".
     3.3. Selecione a região onde a máquina virtual será hospedada.
     3.4. Lembre-se de separar as Zonas de disponibilidade, cada zona corresponde a um datacenter.
     3.5. Escolha o tipo de tamanho para os recursos, como CPU e RAM.
     3.6. Defina o redimensionamento, ontagem de instancias, definindo o percentual de escala horiental a ser atingido para criar 1 ou N novas instancias.
     3.7. Defina tambem o o percentual para reduzir horizontalmente para diminuir as instancias criadas.

  4. **Configure a autenticação:**
     4.1. Configure o método de autenticação (senha ou chave SSH).
     4.2. Insira as credenciais necessárias para acessar a máquina virtual.
     
  5. **Defina as configurações adicionais:**
     5.1. Revise as configurações de rede e conectividade.
     5.2. Escolha o disco de armazenamento (SSD ou HDD) e defina o tamanho.
     5.3. Selecionar as portas de entrada. Lembrando que RDP(não recomendado), deixa seu IP aberto a qualquer tipo de acesso na internet.

  7. **Defina as configurações adicionais:**
     6.1. Revise as configurações de rede e conectividade.
     6.2. Escolha o disco de armazenamento (SSD ou HDD) e defina o tamanho.

  8. **Revise e crie:**
     7.1. Revise todas as configurações escolhidas.
     7.2. Clique em "Criar" para provisionar a máquina virtual. Esse processo pode levar alguns minutos.

  9. **Acesse sua máquina virtual:**
     8.1. Após a criação, vá até o painel de máquinas virtuais e conecte-se usando o método de autenticação configurado.
