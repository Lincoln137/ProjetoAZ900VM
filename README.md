# ProjetoAZ900VM

### Demonstração de criação de uma máquina virtual no portal Azure.

<p> Este repositório visa demonstrar a criação de uma máquina virtual no Portal Azure, através de prints de tela. A conta no Portal Azure, foi criada com confirmação de identidade via cartão de crédito temporário.</p>
<p> Foram necessárias duas tentativas, visto que a primeira retornou falha de implatação, "zona selecionada não suporta tamanho selecionado".</p>
<p> Ao deparar com esse erro na criação do recurso VM ProjetoAZ900, tentei duas formas de solução, a primeira realizar backup e reimplantar a VM conforme configurações básicas e de acordo com a documentação, a reimplantação por backup retornou falha com o código de erro relacionado a zona de implatação 1. Posteriormente excluí o recurso e o criei novamente, porém retornou o mesmo erro de zona não comporta a configuração selecionada. Com a ajuda do Copilot, introduzi a recomendação atualizada pela IA e houve sucesso na implatação.</p>
<p>Em análise às diferenças de configurações realizadas por mim, as quais estavam de acordo com a documentação para estudos e para testes e a sugerida pelo Copilot, reside no preço do plano que altera o custo da VM, de aproximadamene $10,00 mês para aproximadamente $36,00  mês. Conclui que os planos básicos são aceitos somente na zona 1, visto que tentei a mudança de zona para continuar no plano básico, etretanto retornava erro antes mesmo da implatação.</p>

### Dados da VM ProjetoAZ900
<p>Nome da máquina virtual: ProjetoAZ900</p>
<p>Grupo de recursos: MyVMDio</p>
<p>Image: Windows Server 2022 Datacenter: Azure Edition -x64 Gen2</p>
<p>VM Architecture x64</p> 





