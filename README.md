# 8251-USART-Topsecret
This system will make serial communication with an unknown topsecret interface.
In the first discovery, the unknown interface asks the user for a key after receiving the 'S' character. After this key is entered, the interface sends numbers and encrypted data equal to the number of digits.
Ending the communication with EOT, it resets itself and switches back to 'S' standby mode from the user. In the 'S' standby mode, if the user enters a different character, 'X' is returned, if he enters S, it asks for the key again.
