# azureVision
A simple demo from Azure Vision Studio, Face Recognition and Extract Text from Image




Azure Vision Studio Demo
Este repositório contém instruções para utilizar o Azure Vision Studio, uma plataforma visual do Azure que permite testar e usar modelos de visão computacional sem precisar programar. Aqui, vamos explorar como realizar reconhecimento facial e extração de texto a partir de imagens (OCR) diretamente na interface do Vision Studio.

Recursos Utilizados
Reconhecimento Facial: Detecta rostos, emoções e características faciais.
Extração de Texto (OCR): Extrai texto de imagens, útil para conversão de documentos físicos em texto digital.
Pré-requisitos
Conta Azure: Crie uma conta gratuita no Azure para acessar o Azure Vision Studio.
Visão Computacional e Face: Crie um recurso de Cognitive Services no portal do Azure e adicione o serviço de Visão Computacional e Face.
Passo a Passo
1. Configuração do Serviço no Azure
Acesse o portal do Azure.
Crie um recurso do tipo Cognitive Services e habilite os serviços de Visão Computacional e Face.
Configure a localização e o grupo de recursos de acordo com sua preferência.
Vá até Chaves e Endpoint e copie suas credenciais de acesso, que serão necessárias para acessar o Vision Studio.
2. Acessando o Vision Studio
Vá até o Azure Vision Studio.
Faça login com suas credenciais da conta Azure.
Configure o endpoint e a chave de API obtidos no portal do Azure, caso solicitado.
3. Uso do Reconhecimento Facial
O Vision Studio permite que você faça upload de imagens para detectar rostos e analisar características faciais.

Acesse a seção de Face Detection (Detecção Facial) no Vision Studio.
Faça o upload de uma imagem com rostos e ajuste as configurações para incluir atributos como idade, emoções e pontos de referência faciais.
Clique em Analyze (Analisar) para visualizar os resultados. O Vision Studio exibirá as características do rosto, incluindo coordenadas de pontos faciais e estimativas de idade e emoções.
4. Uso da Extração de Texto (OCR)
O Vision Studio também facilita a extração de texto de imagens. Esse recurso é útil para capturar texto impresso em fotos ou digitalizar documentos.

Acesse a seção de OCR no Vision Studio.
Faça upload de uma imagem contendo texto.
Clique em Extract Text (Extrair Texto) para processar a imagem.
O Vision Studio exibirá o texto detectado, incluindo informações de posicionamento (bounding box) para cada linha ou palavra.
Exemplo de Saída
Reconhecimento Facial: O Vision Studio exibirá a imagem com caixas delimitadoras ao redor dos rostos e, ao clicar em cada rosto, mostrará detalhes como idade, emoções e posição de pontos faciais.
Extração de Texto (OCR): O Vision Studio exibirá o texto detectado em uma lista e marcará cada linha na imagem original com as informações de posicionamento.
