# EEL7801
Disciplina da Faculdade Federal de Santa Catarina - Projeto em Eletrônica I

Veja a proposta [aqui](tex_src/proposta).

# Toolchain
* Crosspiler GCC ARM

No Ubuntu: 
```
sudo apt-get install libc6-armel-cross libc6-dev-armel-cross binutils-arm-linux-gnueabi libncurses5-dev

```
* STM32CubeMX para initialização de código e geração do makefile inicial.
* [openocd](http://openocd.org/repos/)

Uso:
```
$ openocd -f bluepill.cfg -c "program /*.bin || *.elf || *.hex\ verify reset exit"
```

Para inciar uma seção de debbuging, reprima a opção reset e 

```
$ telnet localhost 4444
```

# Hardware
* Todo
