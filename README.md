# Instação php_printer para PHP 5.1.X

Extensão pecl compilada para realizar impressão com PHP


## Instalação da extensão
Copie a extensão `php_printer.dll` para pasta de extesões do PHP
    
Configure o `php.ini`
    
    extension=php_printer.dll

Reinicie o serviço HTTP para recarregar as configurações



## Instalação da biblioteca no Windows

Pode ser que ao reiniciar o serviço http ou ao executar módulo aconteça um erro por falta de uma depedência

Copie `msvcr71.dll` para as seguintes pastas do servidor Windows

    C:\Windows\System32
    C:\Windows\SysWOW64

No terminal de comandos, registre a DLL no Windows

    regsvr32.exe msvcr71.dll
