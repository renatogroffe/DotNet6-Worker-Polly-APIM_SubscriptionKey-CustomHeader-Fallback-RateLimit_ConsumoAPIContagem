# DotNet6-Worker-Polly-APIM_SubscriptionKey-CustomHeader-Fallback-RateLimit_ConsumoAPIContagem
Exemplo de consumo em um Worker Service criado com .NET 6 de uma API REST (contagem de acessos), utilizando para isto Headers com uma Subscription Key do Azure API Management + um valor customizado e a biblioteca Polly com o padrão Fallback (retornando um valor default após se atingir um limite de requisições enviadas - Rate Limit).

Aplicação com a API REST consumida por este Worker Service:

**https://github.com/renatogroffe/ASPNETCore6-REST_API-AppInsights-CustomHeader_ContagemAcessos**