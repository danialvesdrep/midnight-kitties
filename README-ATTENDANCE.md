# Attendance Registry DApp

## Descrição
DApp simples de registo de presença construído com Compact para a blockchain Midnight.

## Funcionalidades
- **markPresent()**: Regista a presença de um participante.
- **getTotalPresent()**: Retorna o total de pessoas presentes.

## Contrato
- Localização: `/packages/contracts/attendance/src/attendance.compact`
- Compilado com: Compact v0.25.0
- Circuitos: 2 (markPresent, getTotalPresent)

## Como compilar
```bash
cd packages/contracts/attendance
export COMPACT_PATH=".:./src:./managed:../node_modules"
compact compile src/attendance.compact managed/attendance
