# Casos de Uso – Sistema de Gestão de Eventos

# UC01 – Realizar Inscrição
## Ator Principal
Participante

## Fluxo Principal
1. Acessa catálogo de eventos.
2. Seleciona evento.
3. Informa dados necessários.
4. Confirma inscrição.
5. Sistema registra inscrição.
6. Sistema gera comprovante.

## Fluxos Alternativos
A1. Evento lotado → incluir em lista de espera.
A2. Evento pago → aguardar confirmação financeira.

# UC02 – Cancelar Inscrição
## Ator Principal
Participante

## Fluxo Principal
1. Acessa área do participante.
2. Seleciona inscrição.
3. Solicita cancelamento.
4. Sistema valida regras.
5. Sistema efetiva cancelamento.

## Exceção
E1. Evento não permite cancelamento.

# UC03 – Confirmar Pagamento
## Ator Principal
Equipe Financeira

## Fluxo Principal
1. Consulta pagamentos pendentes.
2. Valida recebimento.
3. Confirma pagamento.
4. Sistema libera inscrição.
5. Sistema notifica participante.

# UC04 – Emitir Certificado
## Ator Principal
Participante

## Fluxo Principal
1. Acessa área do participante.
2. Seleciona evento realizado.
3. Solicita certificado.
4. Sistema valida elegibilidade.
5. Sistema disponibiliza PDF.
