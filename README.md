## Example problem

- Fazer um programa para ler os dados de uma reserva de hotel (número do quarto, data
de entrada e data de saída) e mostrar os dados da reserva, inclusive sua duração em
dias. Em seguida, ler novas datas de entrada e saída, atualizar a reserva, e mostrar
novamente a reserva com os dados atualizados. O programa não deve aceitar dados
inválidos para a reserva, conforme as seguintes regras:
- Alterações de reserva só podem ocorrer para datas futuras
- A data de saída deve ser maior que a data de entrada.

## Example
- Room number: 8021
Check-in date (dd/MM/yyyy): 23/09/2024
Check-out date (dd/MM/yyyy): 26/09/2024
Reservation: Room 8021, check-in: 23/09/2024, check-out: 26/09/2024, 3 nights
- Update reservation <br>
Enter data to update the reservation:
Check-in date (dd/MM/yyyy): 24/09/2024
Check-out date (dd/MM/yyyy): 29/09/2024
Reservation: Room 8021, check-in: 24/09/2024, check-out: 29/09/2024, 5 nights.

- Room number: 8021
Check-in date (dd/MM/yyyy): 23/09/2024
Check-out date (dd/MM/yyyy): 21/09/2024
Error in reservation: Check-out date must be after check-in date.