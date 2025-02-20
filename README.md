# Ambiente-Virtual
## Introdução
Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como *MySQL, Node.js* e *Python*. A atividade integra conceitos de sistemas operacionais, redes de computadores, levantamento de requisitos e lógica de programação. Com pesquisas sobre os componentes, com a meta de montar um computador com custo máximo de R$ 5.000,00, configurará uma máquina virtual e instalará uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

## Levantamento de Requisitos
### Requisitos para o Computador Físico
- **Processador (CPU):** Bom desempenho para multitarefa, 2 núcleos.
- **Memória RAM:** 16 GB.
- **Armazenamento:** SSD 50 GB.
- **Placa-mãe:** 32 GB de RAM.
- **Fonte de alimentação:** 500W.
- **Orçamento Máximo:** R$ 5.000,00
### Requisitos para a Máquina Virtual
- **Memória:** 4 GB.
- **CPU:** Processador com 2 núcleos.
- **Armazenamento:** 25 GB livre. 
- **Rede:** Configuração via NAT para acesso à internet.

## Pesquisa e Orçamento de Componentes
Foram esses componentes escolhidos, pois possuem um ótimo custo-benefício e são de marcas de qualidade, confiáveis, resultando num total de R$ 3.100,00.
- **Processador:** [Link do Processador](https://www.terabyteshop.com.br/produto/21317/processador-amd-ryzen-5-4600g-37ghz-42ghz-turbo-6-cores-12-threads-cooler-wraith-stealth-am4-100-100000147box?p=139255&utm_source=craftmybox&utm_medium=afiliados&utm_campaign=craftmybox)
- **Memória RAM:** [Link da Memória RAM](https://www.kabum.com.br/produto/110769/memoria-ram-corsair-vengeance-lpx-16gb-2x8gb-2400mhz-ddr4-cl16-black-cmk16gx4m2a2400c16?awc=17729_1740052634_1e9162127b65d932f203be25b6a4b316&utm_source=AWIN&utm_medium=AFILIADOS&utm_campaign=fevereiro24&utm_content=2025-02-20&utm_term=691737)
- **Armazenamento:** [Link do Armazenamento](https://www.amazon.com.br/dp/B0DBR3DZWG?tag=craftmybox-20&linkCode=osi&th=1&psc=1&smid=A38JVMMYJLUN90)
- **Placa-Mãe:** [Link da Placa-Mãe](https://www.pichau.com.br/placa-mae-pichau-b550m-k-ddr4-socket-amd-am4-m-atx-chipset-amd-b550-b550m-k-1p?gad_source=1&gclid=Cj0KCQiAwtu9BhC8ARIsAI9JHalALsVTZ_bWLrstEPlF7sgnrPYG0cXEM4gyNl3FGeJw1Rw-R1TvdnoaAnwHEALw_wcB)
- **Fonte de Alimentação:** [Link da Fonte](https://www.pichau.com.br/fonte-mancer-thunder-500w-bronze-80-plus-mcr-thr500-bl01?utm_source=meupcnet&utm_medium=afiliados&utm_campaign=meupcnet)
- **Teclado:** [Link do Teclado](https://www.amazon.com.br/dp/B07VMV8CJQ?tag=craftmybox-20&linkCode=osi&th=1&psc=1&smid=A2G1PFNJHO5AB3)
- **Mouse:** [Link do Mouse](https://www.mercadolivre.com.br/mouse-para-jogo-trust-rava-gxt-108-preto/p/MLB9927162#polycard_client=mshops-appearance-api&type=product&tracking_id=1602a3e0-9ebc-44ad-922f-276289a7cd7c&source=eshops&wid=MLB1791854872&sid=storefronts)
- **Monitor:** [Link do Monitor](https://www.terabyteshop.com.br/produto/26992/monitor-gamer-3green-195-pol-led-75hz-2ms-hdmivga-m195whd?p=139255&utm_source=craftmybox&utm_medium=afiliados&utm_campaign=craftmybox)
- **Gabinete:** [Link do Gabinete](https://www.pichau.com.br/gabinete-tgt-b110-preto-tgt-b110-pr01?utm_source=meupcnet&utm_medium=afiliados&utm_campaign=meupcnet) 
- **Placa de Vídeo:** [Link da Placa de Vídeo](https://produto.mercadolivre.com.br/MLB-3934669741-placa-de-video-afox-amd-radeon-rx-550-4gb-gddr5-128-bits--_JM#polycard_client=mshops-appearance-api&type=item&tracking_id=5bc93f7a-6ef9-41a8-98c2-8f97792c2a1c&source=eshops)

## Sistema Operacional Linux
Após comparar as versões do Linux, a que mais seria compatível com nosso projeto seria a versão Ubuntu 24.04, pois é bem leve, fácil de usar, possui compatibilidade com ferramentas de desenvolvimento, como Docker, Git e IDEs, possui atualizações regulares, garante estabilidade e segurança, é ideal para criar ambientes isolados e testar aplicações e é uma ótima opção para fins educacionais. 

## Manual de Instalação do Linux no VirtualBox
### Pré-requisitos
- **VirtualBox:** Baixe e instale a versão mais recente do [VirtualBox](https://www.virtualbox.org/).
- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

### Passo a Passo
#### 1. Instalação do VirtualBox
- Acesse o site do VirtualBox e baixe a versão Ubuntu 24.04.
- Siga as instruções de instalação fornecidas.
- Após a instalação, abra o VirtualBox.

#### 2. Criação da Máquina Virtual
1. **Clique em "Novo":**
   - **Nome:** jo-o
   - **Tipo:** Linux
   - **Versão:** Ubuntu 24.04
2. **Configuração de Memória:**
   - 4 GB.
   - 4 núcleos.

3. **Criação do Disco Rígido Virtual:**
   - 
   - 
   - 

#### 3. Configuração de Rede
- Selecione a máquina virtual criada e clique em "Configurações".
- 

#### 4. Configuração do Disco de Instalação


#### 5. Iniciando a Instalação do Ubuntu
1. **Inicie a Máquina Virtual:**
   - Configuramos idioma, personalização da acessibilidade e clicamos para realizar atualização.

2. **Instalação Passo a Passo:**
   - Instalamos na forma interativa.
   - E deixamos os apps na configuração padrão.
   - Instalamos o drivers de terceiros e baixamos suporte para formatos de mídia.
   - Apagamos o disco e instalamos o Ubuntu.
   - Realizamos configuração da conta (nome, senha e nome do computador..)
   - Colocamos localização e fuso horário.
   - Por fim revisou nossas escolhas e instalamos.
   - Se solicitado, conecte à internet para atualizações.

#### 6. Pós-Instalação e Testes
- Após a instalação, a máquina virtual reiniciará.
- Faça login com as credenciais criadas.
- Abra o terminal e verifique a instalação dos softwares executando os seguintes comandos:
  - **Mysql 8.0 version**
  ![mysql](https://github.com/user-attachments/assets/0a49a1d0-92e8-4918-b59b-6ea9a3b2c246)

  - **Node v18.19.1**
  ![node](https://github.com/user-attachments/assets/ae6f344c-98e9-4ce8-ab5c-050de410821b)

  - **Python3 3.12.3 version**
  ![pytohn](https://github.com/user-attachments/assets/75c20758-f61b-4d53-b2e3-cb4bdd3ccb7e)

## Considerações Finais
Nossa equipe aprendeu como é o processo de instalação de uma *Máquina Virtual*, como utilizá-la, como instalar softwares como *Phython*; aprendemos a fazer levantamento de preços, com um preço limite; analisar componentes entre qual é melhor. O que poderiamos melhorar seriam as peças da máquina para termos um melhor desempenho da máquina.
