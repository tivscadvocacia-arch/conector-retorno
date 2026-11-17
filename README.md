# conector-retorno

Ponte do retorno OAuth do Google para o Conector Ative (conectar.vscadvocacia.com.br). Repassa apenas `state`, `code` e `error` para `retorno.php`, sem o parâmetro `iss` (bloqueado pelo ModSecurity da hospedagem). Não guarda nem envia dados para nenhum outro lugar.
