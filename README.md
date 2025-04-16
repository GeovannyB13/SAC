# S.A.C.
Sistema de Aprobación Crediticia
El modelo debe recibir los siguientes datos como entrada:

 ```piton
 "ID",                             # Número identificador del cliente
  "CHECKING_BALANCE",               # Saldo que posee el cliente en su cuenta corriente
  "PAYMENT_TERM",                   # Cantidad de días que el cvliente posee para pagar el préstamo
  "CREDIT_HISTORY",                 # Situación crediticia pasada del cliente
  "LOAN_PURPOSE",                   # Motivo del préstamo
  "LOAN_AMOUNT",                    # Monto del préstamo
  "EXISTING_SAVINGS",               # Saldo de cuenta de ahorros
  "EMPLOYMENT_DURATION",            # Cuántos años ha permanecido el cliente en su empleo
  "INSTALLMENT_PERCENT",            # Cantidad de cuotas en las que el préstamo debe ser pagado
  "SEX",                            # Sexo del cliente
  "OTHERS_ON_LOAN",                 # Denota la existencia de un garante u otro solicitante del préstamo
  "CURRENT_RESIDENCE_DURATION",     # Años que el cliente ha permanecido en su última residencia
  "PROPERTY",                       # Indica si el cliente posee alguna propiedad a su nombre
  "AGE",                            # Edad del cliente
  "INSTALLMENT_PLANS",              # Plan de financiamiento, que puede ser del banco, externo o ninguno
  "HOUSING",                        # Indica si el cliente posee una casa propia
  "EXISTING_CREDITS_COUNT",         # Número de préstamos que le han sido concedidos al cliente en el pasado
  "JOB_TYPE",                       # Tipo de empleo: 0 - desempleado, 1 - no calificado, 2 - autónomo, 3 - calificado
  "DEPENDENTS",                     # Número de personas con acceso a la cuenta
  "TELEPHONE",                      # Denota si el cliente tiene un número de teléfono registrado
  "FOREIGN_WORKER"                  # Denota si el cliente trabaja en un país fuera del banco
]
```

Y como salida un valor binario que representa si se debe permitir o no el préstamo (0 para no, 1 para sí).

**Atención**: los datos proporcionados en este desafío son ficticios, cualquier correlación con la realidad es mera coincidencia.

Para comenz
