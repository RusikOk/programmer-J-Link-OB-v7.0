последовательность прошивки:

01) зашить загрузчик 1_stm32boot.bin начиная с адреса 0x08000000
02) установить флажок "Skip Flash Erase" и снять флаг "Reset after programming" в диалоге "Program verifi." STM32 ST-LINK Utility
03) зашить прошивку 2_J-Link ARM-OB STM32.bin начиная с адреса 0x08004000
04) подключить по USB к ПК
05) запустить утилиту JLink.exe из старой версии драйверов c:\Program Files (x86)\SEGGER\JLink_V500\
06) установить новый серийный номер коммандой "exec SetSN=20231225"
07) добавить лицензию коммандой "exec AddFeature RDI"
08) добавить лицензию коммандой "exec AddFeature FlashDL"
09) добавить лицензию коммандой "exec AddFeature FlashBP"
10) добавить лицензию коммандой "exec AddFeature JFlash"
11) добавить лицензию коммандой "exec AddFeature GDB"

(с) RusikOk 2023-12-25

проверить прошивку одним файлом

01) зашить прошивку 3_2023-12-25 OB v7.hex
02) подключить по USB к ПК
03) запустить утилиту JLink.exe из старой версии драйверов c:\Program Files (x86)\SEGGER\JLink_V500\
04) установить новый серийный номер коммандой "exec SetSN=20231225"
05) добавить лицензию коммандой "exec AddFeature RDI"
06) добавить лицензию коммандой "exec AddFeature FlashDL"
07) добавить лицензию коммандой "exec AddFeature FlashBP"
08) добавить лицензию коммандой "exec AddFeature JFlash"
09) добавить лицензию коммандой "exec AddFeature GDB"

(с) RusikOk 2023-12-25