# Linux_OS20.04_V4_X64_By_Griggorii.iso_ubuntu_focal_fossa-linux-image-kernel-5.9.3
iso , RELEASE , X64 , ubuntu , wayland , fast run , fast perfomance wayland , idlepython 3.8.5 my build , python3.8.5 , anti certification os qanon , anti term , anti conspiracy , trump os

Распространяется с mit лицензией ввиду того что содержит пропирти вещи такие как zfs , nvidia и другое ПО.

# ISO DOWNLOAD: https://yadi.sk/d/8hTcz7FdkDiB3Q

Proview desktop: https://youtu.be/9B-nTJyEZX0

Install new graphics mesa LLVMpipe 11.0 https://github.com/Griggorii/Linux_OS20.04_V4_X64_By_Griggorii.iso_ubuntu_focal_fossa-linux-image-kernel-5.9.3/releases/tag/Wayland

Переключение языка виртуальной клавиатуры при входе в gdm3 win-super+space вообщем теперь можете пароль перебить на любой язык хоть на русский и менять вин + пробел раскладку для набора пароля даже на русском.

Установку делайте пока без efi раздела дело в том что туда за место специалистов забрались те кто не понимает типа торвальдса либо но можно попробовать выделить под efi раздел не как ранее 100 Mb , а целых 500 Mb или 1 Gb то как он устроен там должен быть grub который называется ubuntu по адресу /efi/EFI/ubuntu и в него сложены текстовый груб-grub.cfg и grubx64.efi , а кто то сделал что теперь папка называется не ubuntu со всем содержимым , а grub какая то воина дистрибутивов лишь бы загрузочную часть не назвать ubuntu. Вообщем пробовать выделяя не менее 500 метров благодаря засунувшим нос в эту часть и увеличив ее до такого разжирения ефи.

Monitor убрать авторосположение иконок:https://www.youtube.com/watch?v=J7HbQ246W7s

Сессия wayland работает на ноутбуках nvidia optimus , на стационарных придётся удалять иксовую энвидия что бы nouveau драйвер подхватил wayland.
Если устроиство слабое смените тему на любую которая легче и все залетает даже на планшете. Желательно удалить устаревшее расширение после устанвоки и без него на данный момент все работает sudo rm -rf /usr/share/gnome-shell/extensions/GPaste@gnome-shell-extensions.gnome.org ранее это расширение решало проблему копирования текста в wayland.

NVD7 это GF117M на свободном xorg-nouveau драйвере при этом надо удалить все драйвера от bumblebee , prime так же относится к этому источнику https://github.com/Griggorii/libdrm-2.4.101-source версию как я всё время говорю можно делать выше но это будет оферой типа смотрите 2.5.150.000 по этому я предлагаю драиверо писателям остановиться на этом варианте и  точка -> возможно это ускорение флаг в груб типа HW-true или HW-1 и проверить вдруг это заработает.

Так же есть ядро где nvidia точно опробована из этого видео если она не заработает на ядре 5.9.3 которое я собрал , тут все почти пересобрано. https://github.com/Griggorii/linux-image-oem-5.6.0-1020-kernel-ubuntu-x86_64-deb-package это ядро я забраковал оно тяжелее чем 5.9.3 с моим настроенным конфигом.

В остальном же если кто заметит этот дистрибутив почти пересобран сам на себе в некоторых частях так что я хочу сразу предупредить слишком шибко умных патреонщиков которые любят получать донаты за чужие труды переделывая всё под другие патченные де или кому удалось выбить лицензию на продажу дистрибутивов , что этот дистрибутив уже отдельная ветка и при обновлении будут происходит эпики на данный момент я поработал над llvm-10 очень много уходит времени на пере модифицирование бинарников если не сложением определённых реп папок , то модифицирование сначала компилятора и им уже самого бинарника всё это золотое время и тратить его надо как показано качеством в этом дистрибутиве , а не наращивание армии бездельников ит понятно тем бы с их тдрипперми проводить и проводить эксперементы , но я понял у нех нету некого динамическо логического мышления иначе бы не я видео драивер так у паковал в один пак , а они при чём уже как года два назад , возможно даже из него можно будет вытащить скоро системд не потому что тот плохой , а потому что чем больше сервисов загружается тем меньшая скорость загрузки и мы заходим в тупик из которого не вышли ведь хромиум ос загружается на hdd за мгновение , при чем на hdd. На ssd всё загружается очень быстро.

Дистрибутив нацелен на кино производителей и саунд дизайнеров поскольку имеет самые качественные компоненты видеодрайвера что дает не реально хорошее качество изображения и звука , кому надо игры есть стим , литрус и много другого в репозиториях достаточно открыть synaptic и поставить. В /lib64 созданна ссылка на libcuda.so для давинчи редактора.  

Этот дистрибутив делается очень сложно так что больше его распространяйте и чем больше узнает что такое качество и тогда может другие страны отправят инвестиции и вообще зар платы за мой ручной труд и перестроение дистрибутива. На данный момент могу только сказать что если вы будете компилировать компилятор LLVM то делйте свап раздел с памятью на 50 Гигабайт и именно у этого дистрибутива очень хорошее связка с виртуальной и динамической памятью и он справится с компиляцией , другие дистрибутивы могут не поддерживать качественно swap память что и характерезирует наивысшее качество моего дистрибутива. Что бы поддерживать дистрибутив надо хотя бы миллионов 50 что бы нанимать людей рубящих в теме , например есть идея перекомпилировать всю убунту или какие то её части через не через gcc , а через javac и получить дистрибутив у которого все бинарники будут нативными и если даже изменится glib и ldd то такой дистрибутив продолжит работу , но не в этом идея конечно потом на другой глиб менять ничего не надо будет потому что с наличием денег этот дистрибутив поидет отдельно от каноникал и других фирм называться будет типа jubuntu или еще как то далее придумаем сообщаясь со всеми специалистами которых найму на данный момент некоторые мои текста могут быть с ошибками по банальной причине могу либо букву не дожать или совершить ошибку при наборе потому что тороплюсь , а сурдо переводчика исправления ошибок тут не встроено. Конечно кода мидлииарды строк и по этому ни какую распильную астра не имеет смысла строить. Так же есть электронный кошелек для биткоина туда могут кидать как просто благодарные люди и разработчики анонимно , так же могут кидать те кому стыдно что они работая в компаниях типа амазон , каноникал , гугл , яндекс и других компаний имеют дистрибутив созданные ихними сотрудниками получая миллионы нефти на порядки хуже либо с отсутствующими фичами типа быстрой настройки dconf единого профиля браузера с иконкой "gaia_given_name" которую гугл все время пытается удалить из профиля потому что default на кошелек ниже:

Griggorii@gmail.com только настоящие технологии bitcoin support real technology new fix 1Fps612daCcb7vYN2bFDRoDuUnrjJESDmk thanks wayland session perfomance ! , X11 session better hignt perfomance ! calculator-> wayland + perfomance stable mesa gui = X11 hignt perfomance session !

По нашему это означает что если ваиланд сессия работает быстро то здоровье иксовой сессии становится еще выше и скоростнее такой у меня подход к настройке и пере конфигурированию в моей системе расширения находятся в папке /usr/share/gnome-shell/extensions на данный момент не работает GPaste так что можно сделать sudo rm -rf /usr/share/gnome-shell/extensions/GPaste@gnome-shell-extensions.gnome.org в иксовой сессии выполните в терминале plank --preferences и вы можете убрать конфликт панелей переместив plank вниз тогда авто скрытие верха будет только при развертке окна или приложения во весь экран.

Nvidia autoconfig run support notebook optimus , nvidia all laptop desktop support nvidia autoconfig , not recommended generate xorg file nvidia auto onli

Данный дистрибутив использует пакет собранных мной дрйверов https://github.com/Griggorii/mesa-20.1.5_v3_ubuntu-19.04-20.04-20.10_X86_64_graphics в получения именно такого ядра так же поучаствовали своего рода инклюдами для новго ядра благодаря чему ядро собралось именно под эти видео драйвера и не будет конфликтовать если не делать резких движении с хорг конфигами , а точнее вообще их не делать так же перебилдены такие пакеты как glib посколько надо что бы он обернул драйвера для лучшей работо способности https://github.com/Griggorii/glibc-2.31_all.deb_package_version_gcc-10-full_ubuntu_20.04_focal_fossa перебилденный pulseaudio https://github.com/Griggorii/pulseaudio_13.99.1-1ubuntu3.5-ubuntu-focal-20.04 gdm3 https://github.com/Griggorii/gdm3_3.34.1-1ubuntu1-run-keyboard-test-deb-package busybox https://github.com/Griggorii/busybox-1.30.1-deb-package-ubuntu-20.04-ubuntu-20.10 частично добавленны некоторые библиотеки из так же перебилденного llvm-10 на более старой системе 16.04 где на борту был ещё только python3.5 https://github.com/Griggorii/llvm-10-tools где ранее на нём же была опробована сразу же сборка предоставляемых в тарболе драйверов mesa. Все клавиши переназначены допустим снимок экрана shift+f7 , shift+f6 настройки , посмотреть переназначения в терминале: gnome-control-center keyboard , был получен c сверх тяжелого перебилда новый python3.8.5 https://github.com/Griggorii/python3.8.5_ubuntu_20.04_new_rebuild_amd64.deb теперь он идет в поставке.

___________________________________________________________________________________________________________________

Sync test OS https://github.com/CanonicalLtd/subiquity command 

Для разработки не относится к обычным пользователям так что пропустите этот текст который от верхней линии до нижней

Griggorii example zsync server and desktop download iso my reos structure performance beta

$ urlbase=http://cdimage.ubuntu.com/ubuntu-server/daily-live/current

$ isoname=$(distro-info -d)-live-server-$(dpkg --print-architecture).iso

$ zsync ${urlbase}/${hirsute-hirsute-live-server-amd64.iso}.zsync

Griggorii example zsync desktop download

$ urlbase=http://cdimage.ubuntu.com/daily-live/20201215

$ isoname=$(distro-info -d)-live-server-$(dpkg --print-architecture).iso

$ zsync ${urlbase}/${hirsute-hirsute-desktop-amd64.iso}.zsync

_____________________________________________________________________________________________________________________

griggorii@GriggoriiX64:
$ /usr/bin/pstree
systemd─┬─ModemManager───2*[{ModemManager}]
        ├─NetworkManager───2*[{NetworkManager}]
        ├─accounts-daemon───2*[{accounts-daemon}]
        ├─acpid
        ├─atd
        ├─avahi-daemon───avahi-daemon
        ├─bluetoothd
        ├─bumblebeed
        ├─colord───2*[{colord}]
        ├─cron
        ├─cups-browsed───2*[{cups-browsed}]
        ├─cupsd
        ├─dbus-daemon
        ├─f2b/server───4*[{f2b/server}]
        ├─gdm3─┬─gdm-session-wor─┬─gdm-wayland-ses─┬─gnome-session-b───2*[{gnom+
        │      │                 │                 └─2*[{gdm-wayland-ses}]
        │      │                 └─2*[{gdm-session-wor}]
        │      └─2*[{gdm3}]
        ├─gnome-keyring-d───3*[{gnome-keyring-d}]
        ├─irqbalance───{irqbalance}
        ├─networkd-dispat
        ├─polkitd───2*[{polkitd}]
        ├─rsyslogd───3*[{rsyslogd}]
        ├─rtkit-daemon───2*[{rtkit-daemon}]
        ├─switcheroo-cont───2*[{switcheroo-cont}]
        ├─systemd─┬─(sd-pam)
        │         ├─2*[at-spi-bus-laun─┬─dbus-daemon]
        │         │                    └─3*[{at-spi-bus-laun}]]
        │         ├─2*[at-spi2-registr───2*[{at-spi2-registr}]]
        │         ├─2*[dbus-daemon]
        │         ├─dbus-launch
        │         ├─dconf-service───2*[{dconf-service}]
        │         ├─gjs───6*[{gjs}]
        │         ├─gnome-session-b─┬─gsd-disk-utilit───2*[{gsd-disk-utilit}]
        │         │                 ├─indicator-messa───3*[{indicator-messa}]
        │         │                 ├─nemo-desktop─┬─nemo───4*[{nemo}]
        │         │                 │              └─9*[{nemo-desktop}]
        │         │                 └─3*[{gnome-session-b}]
        │         ├─gnome-session-c───{gnome-session-c}
        │         ├─gnome-shell─┬─Xwayland───12*[{Xwayland}]
        │         │             ├─gufw───gufw-pkexec───python3─┬─WebKitNetworkP+
        │         │             │                              ├─WebKitWebProce+
        │         │             │                              └─7*[{python3}]
        │         │             ├─ibus-daemon─┬─ibus-engine-sim───2*[{ibus-engi+
        │         │             │             ├─ibus-extension-───3*[{ibus-exte+
        │         │             │             ├─ibus-memconf───2*[{ibus-memconf+
        │         │             │             └─2*[{ibus-daemon}]
        │         │             └─14*[{gnome-shell}]
        │         ├─gnome-terminal-─┬─bash───pstree
        │         │                 └─4*[{gnome-terminal-}]
        │         ├─goa-daemon───3*[{goa-daemon}]
        │         ├─goa-identity-se───2*[{goa-identity-se}]
        │         ├─gsd-a11y-settin───3*[{gsd-a11y-settin}]
        │         ├─gsd-color───3*[{gsd-color}]
        │         ├─gsd-datetime───3*[{gsd-datetime}]
        │         ├─gsd-housekeepin───3*[{gsd-housekeepin}]
        │         ├─gsd-keyboard───3*[{gsd-keyboard}]
        │         ├─gsd-media-keys───3*[{gsd-media-keys}]
        │         ├─gsd-power───3*[{gsd-power}]
        │         ├─gsd-print-notif───2*[{gsd-print-notif}]
        │         ├─gsd-printer───2*[{gsd-printer}]
        │         ├─gsd-rfkill───2*[{gsd-rfkill}]
        │         ├─gsd-screensaver───2*[{gsd-screensaver}]
        │         ├─gsd-sharing───3*[{gsd-sharing}]
        │         ├─gsd-smartcard───4*[{gsd-smartcard}]
        │         ├─gsd-sound───3*[{gsd-sound}]
        │         ├─gsd-usb-protect───3*[{gsd-usb-protect}]
        │         ├─gsd-wacom───3*[{gsd-wacom}]
        │         ├─gsd-wwan───3*[{gsd-wwan}]
        │         ├─gsd-xsettings───3*[{gsd-xsettings}]
        │         ├─gvfs-afc-volume───3*[{gvfs-afc-volume}]
        │         ├─gvfs-goa-volume───2*[{gvfs-goa-volume}]
        │         ├─gvfs-gphoto2-vo───2*[{gvfs-gphoto2-vo}]
        │         ├─gvfs-mtp-volume───2*[{gvfs-mtp-volume}]
        │         ├─gvfs-udisks2-vo───3*[{gvfs-udisks2-vo}]
        │         ├─gvfsd───2*[{gvfsd}]
        │         ├─gvfsd─┬─gvfsd-dnssd───2*[{gvfsd-dnssd}]
        │         │       ├─gvfsd-network───3*[{gvfsd-network}]
        │         │       ├─gvfsd-recent───2*[{gvfsd-recent}]
        │         │       ├─gvfsd-trash───2*[{gvfsd-trash}]
        │         │       └─2*[{gvfsd}]
        │         ├─2*[gvfsd-fuse───5*[{gvfsd-fuse}]]
        │         ├─gvfsd-metadata───2*[{gvfsd-metadata}]
        │         ├─ibus-portal───2*[{ibus-portal}]
        │         ├─ibus-x11───2*[{ibus-x11}]
        │         ├─obexd
        │         ├─pulseaudio─┬─gsettings-helpe───3*[{gsettings-helpe}]
        │         │            └─4*[{pulseaudio}]
        │         ├─sbscheduler
        │         ├─seahorse───3*[{seahorse}]
        │         ├─xdg-permission-───2*[{xdg-permission-}]
        │         └─xfconfd───2*[{xfconfd}]
        ├─systemd-journal
        ├─systemd-logind
        ├─systemd-resolve
        ├─systemd-timesyn───{systemd-timesyn}
        ├─systemd-udevd
        ├─udisksd───4*[{udisksd}]
        ├─upowerd───2*[{upowerd}]
        └─wpa_supplicant
        
        
############## Configuration file for h264enc ##############
#
# Version: 19 - do not modify or remove this line!
#
# This file is used by the h264enc script and contains the
# paths to the programs needed for its correct operation.
# The user can use it to modify the path to the various programs
# in case one or more of these programs is not in a standard location
# and connot be found by the system. It can also be used in
# case the user has multiple executables of the same program but
# wants to use a specific executable for the job.
# Note that this file cannot be used to store encoding settings
# or other parameters! They will be ignored. Everything after
# a # sign is a comment.
#
# The EDITOR variable is used to set the preferred text editor for
# editing the config file through the terminal. It defaults to the
# nano text editor.
#
# The ALLOW_* variables can be used to enable or disable specific
# audio/video filters and containers. Setting a variable to 'n' will
# skip asking questions about the specific filter/container.
#
# The DEFOUTPUT variable can be used to provide a custom output directory
# for your encodes. If left empty, h264enc defaults to your home
# directory for output. If set, h264enc checks for it and will create
# the directory if it's not present. The DEFOUTPUT variable can be
# overwritten on the command line, meaning that if it's set but the
# user provides a path on the command line, that path will be used
# instead.
#
# The TEMPDIR variable below can be used to change the location
# of the temporary directory used by h264enc. If unset, h264enc
# will default to /home/username/.h264enc/job<PID>
# If used, you must provide the full path to a directory. If the
# directory is missing, h264enc will create it.
#
# The MPLAYEROPTS variable can be used to set other mplayer options.
# Be careful which options you use as they may introduce problems
# when using the script.
#
# The PRIORITY variable is used to set a 'nice' value for the encoding
# process. The values one can use are between -20 and 19 where -20
# will give the highest possible priority and 19 the least favorable
# one. Please note that only root can set/use a negative nice value.
# Regular users can only use/set values 0 to 19. If the variable is
# empty, then the default nice value of 0 is used. If the variable
# contains a negative value but the script is ran with normal user
# privileges, h264enc will print a notice and exit.
#
# The DVD_DEVICE and CDROM_DEVICE variables can be used to specify a
# preferred device to encode from. Note that only block devices are
# supported in these variables. CDROM_DEVICE is used for (S)VCD encoding
#
# h264enc can also send mails if configured to do so. There are four
# variables that need to be set in the mail settings below:
# MAILNOTIFY    # Enable/disable sending mail with y or n
# EMAIL         # The recepient's email address
# MAILSUBJ      # The mail's subject
# MAILMSG       # The actual mail message
#
# There is no need to add date/time to your email message as this is
# being done automatically.
#
# h264enc uses the 'mail' program which reads the mail settings from
# /home/username/.mailrc. If there's no such file present or it is
# configured incorrectly, mail sending will fail. A gmail example
# settings for .mailrc can look like this:
#
# set smtp-use-starttls
# set smtp=smtp://smtp.gmail.com:587
# set smtp-auth=login
# set smtp-auth-user=your-email@gmail.com
# set smtp-auth-password=your-password
#


EDITOR="nano"

# Video filters
ALLOW_VID_DEINTERLACE="y"
ALLOW_VID_INTERLACE="y"
ALLOW_VID_DEBLOCK="y"
ALLOW_VID_DELOGO="y"
ALLOW_VID_DENOISE="y"
ALLOW_VID_NOISE="y"
ALLOW_VID_DEBAND="y"
ALLOW_VID_UNSHARP="y"
ALLOW_VID_BRIGHTNESS="y"
ALLOW_VID_EQUALIZER="y"
ALLOW_VID_AUTOCROP="n"
ALLOW_VID_FPS_CONVERSION="y"
ALLOW_VID_SCALER_TUNING="n"
ALLOW_VID_DSIZE="y"
ALLOW_VID_EXPAND="y"
ALLOW_VID_COLORSPACE="n"
ALLOW_VID_ASPECT="y"

# Audio filters
ALLOW_AUD_CHANNELS="y"
ALLOW_AUD_RESAMPLE="y"
ALLOW_AUD_NORMALIZE="y"
ALLOW_AUD_VOLUME="y"
ALLOW_AUD_EQUALIZER="y"
ALLOW_AUD_PAN="y"

# Containers
ALLOW_MKV_MUXING="y"
ALLOW_MP4_MUXING="y"
ALLOW_TS_MUXING="y"
ALLOW_OGM_MUXING="y"

# Misc
ALLOW_SAMPLE_ENCODING="y"
ALLOW_SCAN_MULTIPLE_VIDSTREAMS="y"
ALLOW_SCAN_MULTIPLE_AUDSTREAMS="y"

# Script/mplayer settings
DEFOUTPUT=""
TEMPDIR=""
PRIORITY="10"
MPLAYEROPTS="-noconfig all -loop 1"
DVD_DEVICE=""
CDROM_DEVICE=""

# Mail settings
MAILNOTIFY="n"
EMAIL=""
MAILSUBJ="[h264enc]: Encoding finished"
MAILMSG="This is a notification mail from the h264enc script to inform you that encoding has finished."

# Paths to executables
MPLAYER="/usr/bin/mplayer"
MENCODER="/usr/bin/mencoder"
X264="/usr/bin/x264"
LSDVD="/usr/bin/lsdvd"
DVDXCHAP="/usr/bin/dvdxchap"

MP4BOX="/usr/bin/MP4Box"
MKVMERGE="/usr/bin/mkvmerge"
OGMMERGE="/usr/bin/ogmmerge"
TSMUXER=""

OGGENC="/usr/bin/oggenc"
FLAC=""
NEROAACENC=""
AACPLUSENC=""
FAAC="/usr/bin/faac"

MAIL="/usr/bin/mail"
BC="/usr/bin/bc"
PV="/usr/bin/pv"
DD="/usr/bin/dd"        
        



