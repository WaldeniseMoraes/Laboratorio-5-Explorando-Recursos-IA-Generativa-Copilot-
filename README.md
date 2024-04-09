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

