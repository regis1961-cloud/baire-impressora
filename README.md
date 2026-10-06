# BAIRE IMPRESSORA

Sistema local de gestão para manutenção de impressoras, toners, peças e serviços.

## Como abrir
Abra `index.html` em um navegador moderno.

## Dados
A aplicação preserva a chave `baireLocalState` no `localStorage`, permitindo migrar os registros já existentes da versão anterior. Use o botão **BACKUP** para exportar um arquivo JSON antes de alterações importantes.

## Recursos desta versão
- Visão geral e indicadores por Americana/Vinhedo
- Clientes com PF/PJ, CPF/CNPJ, CEP e endereço de entrega
- Consulta gratuita por CNPJ via BrasilAPI e CEP via ViaCEP
- Ordens de serviço completas, edição, status e serviço executado
- Peças utilizadas (até 5) e compras
- A receber, recebidos/pagos, caixa e fluxo de caixa
- Contas a pagar e recorrência
- Vendas e fluxo de toner
- Cobranças, recibos e rascunhos de notas fiscais
- Impressão de OS em meia folha A4
- Compartilhamento de OS
- Foto/vídeo de teste com limite local de 5 MB por arquivo
- Pesquisa global
- Calculadora flutuante
- Layout responsivo para computador, notebook, tablet e celular

## Observação importante
Esta versão continua sendo local e não possui banco de dados compartilhado entre dispositivos. Para uso simultâneo no computador e celular com os mesmos dados será necessária uma etapa futura de backend/banco de dados (por exemplo, Supabase ou outro serviço gratuito/baixo custo).
