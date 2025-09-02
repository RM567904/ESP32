Setup do ambiente


1. Criar um pasta principal para o seu projeto


\ESP32


2. instalar extensão do Plaformio.IDE e Wokwi Simulator        

3. Criar um arquivo platformio.ini


conteúdo do arquivo platformio.ini
[env:esp32]
platform = espressif32
framework = arduino
board = esp32dev
   4. Criar arquivo wokwi.toml

conteúdo do arquivo wokwi.toml
[wokwi]
version = 1
elf = ".pio/build/esp32/firmware.elf"
firmware = ".pio/build/esp32/firmware.bin"
 
      5. Crie um arquivo chamado diagram.json
      6. Crie um subpasta src (source)
      7. Crie um arquivo na pasta src chamado prog.ino
      8. Obter licença 30 dias WokWi
https://wokwi.com/license?v=2.8.0&r=LicenseMissing&s=v
      9. No VSCode, ativar a licença Wokwi
please copy the key below and press F1 in VS Code, then type Wokwi: Manually Enter License Key, and paste the key.

Ou 

View -> Command Pallet, digite wokwi -> Request new licence e segue o fluxo
      10. Abra um projeto de exemplo
https://wokwi.com/esp32
Starter Templates (ESP32) mais basico
https://wokwi.com/projects/new/esp32
      11.