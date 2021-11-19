#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Linkedin Robson Vaamonde: https://www.linkedin.com/in/robson-vaamonde-0b029028/<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 28/09/2021<br>
#Data de atualização: 19/11/2021<br>
#Versão: 0.3<br>
#Testado e homologado do Clonezilla Alternative Stable - 20210817-hirsute (Ubuntu Based 21.04)

#OBSERVAÇÃO IMPORTANTE:

	_ CUIDADO COM HARD DISK MAIOR OU MENOR NA HORA DE FAZER A CLONAGEM UTILIZANDO O CLONEZILLA, 
	_ as opções de auto-reparticionamento está disponível somente nas opções avançadas, essas 
	_ opções serão mostradas nos próximos vídeos.

Link de Apoio: https://clonezilla.org/clonezilla-live/doc/11_lite_server/advanced/09-advanced-param.php<br>
Link de FAQ/Q&A: https://drbl.org/faq/fine-print.php?path=./2_System/88_mbr_related_options.faq#88_mbr_related_options.faq

#00_ Site Oficial do Clonezilla<br>
	
	_ Site: https://clonezilla.org/
	_ Download: https://clonezilla.org/downloads.php
	_ Releases Note (13/09/2021): https://clonezilla.org/downloads/alternative/release-notes.php

	_ Clonezilla Live: https://clonezilla.org/clonezilla-live.php
	_ Clonezilla Lite Server: https://clonezilla.org/show-live-doc-content.php?topic=clonezilla-live/doc/11_lite_server
	_ Clonezilla Server Edition: https://clonezilla.org/clonezilla-SE/

	_ Alternativas de Software para Clonagem de Hard Disk (Windows, Linux, Mac, etc...)
	_ Comando dd: https://man7.org/linux/man-pages/man1/dd.1.html
	_ Redo Rescue: http://redorescue.com/
	_ Rescuezilla (Fork Clonezilla): https://rescuezilla.com/
	_ Acronis True Image: https://www.acronis.com/en-us/products/true-image/
	_ FOG Project: https://fogproject.org/
	_ Parted Magic: https://partedmagic.com/
	_ OSFClone: https://www.osforensics.com/tools/create-disk-images.html
	_ Mondo Rescue: http://www.mondorescue.org/
	_ Antigo Symantec Ghost: https://en.wikipedia.org/wiki/Ghost_(disk_utility)
	_ AOEMI https://www.aomeitech.com/
	_ Macrium ReflectFree: https://www.macrium.com/reflectfree

#01_ Opções de Gerenciamento de Disco de Otimização do Microsoft Windows

	_ Pesquisa do Windows: Criar e formatar partições do disco rígido
	_ Pesquisa do Windows: Desfragmentar e Otimizar Unidades

#02_ Live-CD do Clonezilla - Boot Inicial<br>
	
	_ Other modes of Clonezilla Live <Enter>
	_ Clonezilla Live (VGA 1024x768) <Enter>

#03_ Configurações iniciais do Clonezilla<br>
	
	_ Choose language: pt_BR.UTF-8 Brazilian Portuguese | Português do Brasil <Enter>
	_ Configuração do teclado: Keep - Manter layout de teclado padrão - layout US <Enter>

#04_ Iniciando a Clonagem com o Clonezilla<br>
	
	_ Start_Clonezilla - Iniciar Clonezilla <Enter>

#05_ Clonando Disco para Imagem (Device to Image) no Clonezilla<br>
	
	_ OBS1: Em Hard Disk Mecânicos utilizando o Microsoft Windows é recomendado desfragmentar
	        a unidade antes de clonar utilizando o: Desfragmentar e Otimizar Unidades
	_ device-image - Trabalhar com disco/partição usando imagens <Enter>
	_ local_dev - Usar dispositivo local (Ex: disco rígido, dispositivo USB - Pen Driver, HD Externo, etc...) <Enter>
	_ OBS2: é recomendado conectar o Hard Disk Externo (USB, eSATA, etc...) antes de iniciar o Clonezilla
	_ Pressione <Enter> para continuar
	_ OBS3: o Clonezilla recomenda utilizar HD Externo, caso não seja utilizado ele irá usar os discos locais
	_ Pressione Ctrl+C para continuar
	_ sdb1 50GB_ntfs_Arquivos (In_VBOX_HARDDISK_)_VBOX_HARDISK_VB <Enter>
	_ no-fsck Skip checking/repairing the file system before mounting <Enter>
	_ CZ_IMG (Diretório pré-criado no Windows para armazenar as imagens) <Enter>
	_ Pressione: TAB para ir para <Done> e pressione: <Enter>
	_ Pressione <Enter> para continuar: <Enter>
	_ Beginner - Modo Iniciante: Aceitar as opções padrões <Enter>
	_ savedisk - Salvar_disco_local_como_imagem <Enter>
	_ Digite um nome para a imagem salva: windows-dev-img <Enter>
	_ [*] sda 53,7GB_VBOX_HARDDISK__VBOX_HARDDISK_VB <Enter>
	_ z1p Usar compressão gzip paralela, para multicore/CPU <Enter>
	_ sfck - Ignorar verificação/correção de sistema de arquivos de origem <Enter>
	_ scs - Não, pular a verificação da imagem salva <Enter>
	_ senc - Não criptografar a imagem <Enter>
	_ p choose - Escolher reiniciar/desligar/etc. quando tudo estiver terminado <Enter>
	_ Pressione <Enter> para continuar: <Enter>
	_ Você tem certeza de que deseja continuar? (y/n) y <Enter>
	_ Pressione <Enter> para continuar: <Enter>
	_ poweroff Desligar <Enter>
	_ Please remove the live-medium, close the tray (if any) and press ENTER to continue: <Enter>