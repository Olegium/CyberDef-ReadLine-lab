# CyberDef-ReadLine-lab

проводим 1ый анализ

<img width="1016" height="645" alt="image" src="https://github.com/user-attachments/assets/acd9bb4a-0537-4999-becf-f49b7b1f5090" />

смотрим все фафлы запущенные по дереву

<img width="991" height="245" alt="image" src="https://github.com/user-attachments/assets/cc3fb31a-b0e3-43dd-a7a4-c11b85c04ef5" />

используем windows.malfind поиск вредоносного кода

<img width="1129" height="1379" alt="image" src="https://github.com/user-attachments/assets/449f56d0-18b1-440b-bbfb-ef14f9e1645c" />

результаты 
    
    RuntimeBroker.exe (PID 5704) Просто выделили много пустой памяти 
    
    oneetx.exe (PID 5896) Есть в блоке памяти MZ это значит файл.exe и protection: PAGE_EXECUTE_READWRITE (Память можно и читать, и писать, и выполнять странно).
    
    smartscreen.exe (PID 7540) protection: PAGE_EXECUTE_READWRITE (Память можно и читать, и писать, и выполнять странно).
