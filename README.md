# Multithreaded Client-Server Application
Ne kemi ndërtuar një aplikacion të thjeshtë duke përdorur programimin socket në gjuhën e programimit C. Do të jenë aplikacione me shumë klientë, që do të thotë se shumë klientë mund të lidhen me serverin në të njëjtën kohë. Serveri do të jetë një server i njëkohshëm, që do të thotë se ka aftësinë për të trajtuar klientë të shumtë duke përdorur threads. Çdo klient trajtohet nga një thread i veçantë, i cili ndihmon serverin të trajtojë klientë të shumtë.
Aplikacioni është i ndërtuar në sistemin operativ: Linux dhe në gjuhën C.
Disa nga libraritë që kemi përdorur janë:stdio.h, stdlib.h, string.h, signal.h, unistd.h, sys/types.h, sys/socket.h, netinet/in.h, arpa/inet.h, pthread.h.
