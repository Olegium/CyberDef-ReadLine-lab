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

Вирус oneetx.exe порадил rundll32.exe

<img width="254" height="39" alt="image" src="https://github.com/user-attachments/assets/61e87de4-33dc-4582-b593-2ae9e968883b" />

Вот и ip

<img width="1361" height="1176" alt="image" src="https://github.com/user-attachments/assets/e311eb0d-accf-411a-b867-a957405438a1" />

странно стоит tun2socks.exe + это exe для сетевого подключения

<img width="1356" height="63" alt="image" src="https://github.com/user-attachments/assets/4140da77-396d-4933-8b96-ad4dfbf01bf9" />

тут файл который был запущен сtun2socks

<img width="2295" height="94" alt="image" src="https://github.com/user-attachments/assets/69ef47ae-6d0a-4c9a-b23a-234a72b5662f" />

вот путь 

<img width="1753" height="209" alt="image" src="https://github.com/user-attachments/assets/00d39d21-d9d4-40a1-87df-6d3dcebc4613" />

путь нашли через сточки где ip указан был

<img width="957" height="317" alt="image" src="https://github.com/user-attachments/assets/3b64defb-573e-48f5-b094-1b8129520d13" />


