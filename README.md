Tarsii Army
===========

Closely related to the [Simian Army](https://github.com/Netflix/SimianArmy) but built around bosh.

#Monkeys

### Afrotarsius (Network Latency)
This monkey runs the `tc` command. It will introduce latency (1 second +- 50%) to all network packets.

### Esosimias (Network Loss)
This monkey runs the `tc` command. It will introduce loss (7% with 25% correlation) to outgoing network packets.

### Bahinia (Burn CPU)
This monkey runs a specified number of 100% cpu scripts.
