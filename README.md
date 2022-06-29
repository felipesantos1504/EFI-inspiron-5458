
# EFI-Inspiron-5458 - macOS Monterey 12.4

![Inspiron](https://i0.wp.com/quenotebookcomprar.com.br/wp-content/uploads/2017/03/comprar-Dell-i14-5458-B40-core-i5.jpg?resize=720,340)

EFI de funcional de instalação e utilização

#### Para usar siga o tutorial do Dortania e altere os MLB, ROM, SystemSerialNumber e SystemUUID

[PlatformInfo Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/broadwell.html#platforminfo)
  
incluido EFI debug e release

- Opencore 0.8.1

- macOS Monterey 12.4

# Problemas encontrados

Porta usb 3.0 só funciona se estiver com um USB 3.0 e se ele estiver plugado ao iniciar, solução que encontrei foi remover o arquivo ```EFI\OC\ACPI\SSDT-UIAC.aml``` e atualizar o config.plist tirando o mesmo de lá, porém fazendo isso o USB vai funcionar somente no padrão 2.0.

# O que não funciona?

- WiFI
- CardReader
- Bluetooth
- GeForce 920M integrada