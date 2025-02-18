# PMSP_SOF
Um código python simples que se propõe a demonstrar como consumir a API do SOF (Sistema de Orçamento e Finanças) da Prefeitura de São Paulo utilizando Python

Necessário acessar a Vitrine de APIs da Prefeitura (https://apilib.prefeitura.sp.gov.br/store/) para (nesta ordem):
1) Fazer seu cadastro definindo seu login e senha
2) Gerar as chaves OAuth "Chave do Consumidor" (client_id no código) e "Segredo do Consumidor" (client_secret no código)
3) Criar Aplicação
4) Increver a API na Aplicação

A documentação no manual parece desatualizada, mas ainda é útil

Para que o código funcione as chaves devem ser coladas no arquivo keysof.py (cuja sintaxe você pode se basear no keysof.py_sample)

Eu rodo os códigos sob proxy no trabalho, mas deixo a opção prontinha pra rodar na tua casa, só reparar no nome do arquivo.