#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Linkedin Robson Vaamonde: https://www.linkedin.com/in/robson-vaamonde-0b029028/<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 21/09/2021<br>
#Data de atualização: 19/11/2021<br>
#Versão: 0.2<br>
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

#05_ Clonando Partição para Partição (Partition to Partition) no Clonezilla<br>
	
	_ OBS1: Em Hard Disk Mecânicos utilizando o Microsoft Windows é recomendado desfragmentar
	        a unidade antes de clonar utilizando o: Desfragmentar e Otimizar Unidades
	_ device-device - Trabalhar diretamente de disco para disco ou partição para partição <Enter>
	_ Beginner - Modo Iniciante: Aceitar as opções padrões <Enter>
	_ part_to_local_part - clonagem_de_partição_local_para_partição_local <Enter>
	_ Partição local de origem: sda3 33.1G_ntfs_Arquivos (In_VBOX_HARDISK_)_VBOX_HARDISK_VB <Enter>
	_ Partição local de destino: sdb1 50g_ntfs_Particao (In_VBOX_HARDISK_)_VBOX_HARDISK_VB <Enter>
	_ sfsck - Ignorar verificação/correção de sistema de arquivos de origem <Enter>
	_ p choose - Escolher reiniciar/desligar/etc. quando tudo estiver terminado <Enter>
	_ Pressione "Enter" para Continuar: <Enter>
	_ Você tem certeza de que deseja continuar? (y/n): y <Enter>
	_ Você tem certeza de que deseja continuar? (y/n): y <Enter>
	_ Pressione "Enter" para Continuar: <Enter>
	_ Poweroff - Desligar <Enter>
	_ Please remove the live-medium, close the tray (if any) and press ENTER to continue: <Enter>