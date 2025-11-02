# aws-step-functions-lab
Desafio-aws-step-functions-lab


Objetivo
Este laboratório tem como objetivo consolidar workflows automatizados com AWS Step Functions**, integrando serviços como AWS Lambda**, Amazon S3** e S3 Glacier para o arquivamento automático de documentos.

Segue abaixo a idéia,o fluxo criado segue a estrutura:

1. **Amazon S3** recebe um documento.
2. Um evento **S3 Trigger** aciona uma **função AWS Lambda**.
3. A **Lambda** processa o arquivo valida.
4. A função envia o arquivo para o **S3 Glacier**, para armazenamento de longo prazo.
   
