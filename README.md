Запуск

gcc -o r reciever.c && ./r

Отправка сигнала SIGUSR1 или SIGUSR2:

gcc -o e emitter.c && ./e <PID> <sig>
