# Laboratorio-5-Projeto:
# Explorando os Recursos de IA Generativa com Copilot e OpenAI.

 Este projeto é um dos laboratório do Bootcamp Microsoft Azure AI Fundamentals, promovido através da parceria entre a Microsoft e a DIO.

# Ler texto no Vision Studio

Neste exercício, você usará o serviço de IA do Azure para explorar os recursos de reconhecimento óptico de caracteres do Azure AI Vision. Você usará o Vision Studio para experimentar extrair texto de imagens, sem precisar escrever nenhum código.

Um desafio comum de visão computacional é detectar e interpretar texto incorporado em uma imagem. Isso é conhecido como reconhecimento óptico de caracteres (OCR). Neste exercício, você usará um recurso de serviços de IA do Azure, que inclui os serviços de Visão de IA do Azure. Em seguida, você usará o Vision Studio para experimentar o OCR com diferentes tipos de imagens.

# Criar um recurso de *serviços de IA do Azure*

Você pode usar os recursos de OCR do Azure AI Vision com um recurso multisserviço dos **serviços de IA do Azure**. Se você ainda não tiver feito isso, crie um recurso de **serviços de IA do Azure** em sua assinatura do Azure.

1. Em outra guia do navegador, abra o **portal do Azure** em [https://portal.azure.com]( https://portal.azure.com), entrando com a conta da Microsoft associada à sua assinatura do Azure.
2. Clique no botão **+Criar um recurso** e procure serviços de IA do Azure. Selecione **criar** um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:

   * **Assinatura**: sua assinatura do Azure.
   * **Grupo de recursos**: selecione ou crie um grupo de recursos com um nome exclusivo.
   * **Região**: Leste dos EUA.
   * **Nome**: insira um nome exclusivo.
   * **Nível de preços**: Standard S0.
   * **Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo**: *Selecionado*.
3. Selecione **Revisar + criar** e, em seguida, **Criar** e aguarde a conclusão da implantação.

# Conectar seu recurso de serviço de IA do Azure ao Vision Studio

Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

1. Em outra guia do navegador, navegue até **o Vision Studio** em [https://portal.vision.cognitive.azure.com]( https://portal.vision.cognitive.azure.com).
2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.
3. Na home page do Vision Studio, selecione **Exibir todos os recursos** no cabeçalho **Introdução ao Vision**.

![vision-resources](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/aac42ef1-a5c8-4e46-9ffb-8f9b051d85fc)

4. Na página **Selecione um recurso para trabalhar**, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione **Selecionar como recurso padrão**.

! **Nota:** Se o recurso não estiver listado, talvez seja necessário **atualizar** a página.

![Captura de Tela (171)](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/e836257d-cee1-4899-afc7-fa0e75e5a820)

5. Feche a página de configurações selecionando o "x" no canto superior direito da tela.

# Extrair texto de imagens no Vision Studio

1. Em um navegador da Web, navegue até **o Vision Studio** em [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com).
2. Na página inicial **Introdução ao Vision**, selecione **Reconhecimento óptico de caracteres** e o bloco **Extrair texto de imagens**.
3. No subtítulo **Experimentar**, reconheça a política de uso de recursos lendo e marcando a caixa.
4. Selecione [https://aka.ms/mslearn-ocr-images](https://aka.ms/mslearn-ocr-images ) para baixar **ocr-images.zip**. Em seguida, abra a pasta.
5. No portal, selecione**Procurar um arquivo** e navegue até a pasta no computador em que você baixou **ocr-images.zip**. Selecione **advert.jpg** e selecione **Abrir**.
6. Agora reveja o que é devolvido:

* Em **Atributos detectados**, qualquer texto encontrado na imagem é organizado em uma estrutura hierárquica de regiões, linhas e palavras.
* Na imagem, a localização do texto é indicada por uma caixa delimitadora, como mostrado aqui:

![advert-bounding-boxes](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/7ba77df3-f311-4e8c-ae51-36b790b382ae)

7. Agora você pode tentar outra imagem. Selecione **Procurar um arquivo** e navegue até a pasta onde você salvou os arquivos do GitHub. Selecione **letter.jpg**.

![letter](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/3df9d4d4-a0b4-47ff-bc73-8ee7b4e0dcaa)

8. Analise os resultados da segunda imagem. Ele deve retornar o texto e as caixas delimitadoras do texto. Se tiver tempo, tente **note.jpg** e **receipt.jpg**.

**Outps das imagens:**

![Captura de Tela (171)](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/82b5b5d7-338f-459c-a067-20120a90d49a)

![Captura de Tela (172)](https://github.com/WaldeniseMoraes/Laboratorio-5-Explorando-Recursos-IA-Generativa-Copilot-/assets/161647255/ee709eea-ce79-4715-b759-e422c665499a)

# Arrumar

Se você não pretende fazer mais exercícios, exclua todos os recursos que não são mais necessários. Isso evita o acúmulo de custos desnecessários.

1. Abra o [portal do Azure](https://portal.azure.com) e selecione o grupo de recursos que contém o recurso que você criou.
2. Selecione o recurso e selecione **Excluir** e, em seguida, **Sim** para confirmar. O recurso é excluído.

## Conclusão

* **OCR com Azure AI**: O laboratório explora a capacidade de reconhecimento óptico de caracteres (OCR) do Azure AI Vision, permitindo extrair texto de imagens sem escrever código.
* **Uso do Vision Studio**: Utiliza-se o Vision Studio para experimentar o OCR com diferentes tipos de imagens, facilitando o entendimento prático da tecnologia.

Para mais informações, pode-se consultar a documentação do Azure AI Vision sobre reconhecimento óptico de caracteres.

[Referências](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html#create-an-azure-ai-services-resource)
