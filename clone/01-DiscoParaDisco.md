#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Linkedin Robson Vaamonde: https://www.linkedin.com/in/robson-vaamonde-0b029028/<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 13/09/2021<br>
#Data de atualização: 13/09/2021<br>
#Versão: 0.1<br>
#Testado e homologado do Clonezilla Alternative Stable - 20210817-hirsute (Ubuntu Based 19.10)

#00_ Site Oficial do Clonezilla<br>
	
	_ Site: https://clonezilla.org/
	_ Download: https://clonezilla.org/downloads.php
	_ Releases Note (13/09/2021): https://clonezilla.org/downloads/alternative/release-notes.php

#01_ Live-CD do Clonezilla - Boot Inicial<br>
	
	_ Other modes of Clonezilla Live <Enter>
	_ Clonezilla Live (VGA 1024x768)<Enter>

#02_ Configurações iniciais do Clonezilla<br>
	
	_ Choose language: pt_BR.UTF-8 Brazilian Portuguese | Português do Brasil <OK>
	_ Configuração do teclado: Keep - Manter layout de teclado padrão - layout US <OK>

#03_ Iniciando a Clonagem com o Clonezilla<br>
	
	_ Start_Clonezilla - Iniciar Clonezilla <OK>

#04_ Clonando Disco para Disco (Device to Device | Hard Disk to Hard Disk) no Clonezilla<br>
	
	_ device-device - Trabalhar diretamente de disco para disco ou partição para partição <OK>
	_ Beginner - Modo Iniciante: Aceitar as opções padrões <OK>
	_ disk_to_local_disk - Clonagem de disco local para disco local <OK>
	_ Disco de origem: sda 53,7GB_VBOX_HARDDISK__VBOX_HARDDISK_VB <OK>
	_ Disco de destino: sda 64,4GB_VBOX_HARDDISK__VBOX_HARDDISK_VB <OK>
	_ sfsck - Ignorar verificação/correção de sistema de arquivos de origem <OK>
	_ p choose - Escolher reiniciar/desligar/etc. quando tudo estiver terminado <OK>
	_ Pressione "Enter" para Continuar: <Enter>
	_ Você tem certeza de que deseja continuar? (y/n): y <Enter>
	_ Você tem certeza de que deseja continuar? (y/n): y <Enter>
	_ Pressione "Enter" para Continuar: <Enter>
	_ Poweroff - Desligar <OK>
	_ Please remove the live-medium, close the tray (if any) and press ENTER to continue: <Enter>