# Destop-Customizations
I will keep all of my essential files for customizing my destkop here. Fonts, config files, wallpapers, scripts, etc...

The Readme is as follows
_________

Using these resources

If you mess up a section, you can can find replacement ones that are default bunsenlabs modified in the folder, you must display hidden files to see the .config

/usr/share/bunsen/skel

______________________

Great General List

https://github.com/oswriter/bl-howtos/blob/master/01-how-i-configured-my-bunsenlabs-linux-desktop.md

________________________

If setting up on a raspberry pi
http://www.bristolwatch.com/rpi/index.htm

________________________


Fonts

Changing system wide fonts

you must edit ~/.config/fontconfig/fonts.conf

Changing the Menu fonts

You must edit ~/.config/openbox/rc.xml


Changing Tint2's Fonts

You edit them in ~.config/tint2/tint2rc

It is in the Fonts Clock,toolbar,Battery,Executor  and taskbar sections (around 100 and 130, 163, 182, 195, 267), you can pick the font family, asize and color

Changing Conky's Fonts

You edit them in ~.config/conky/BL-Default.conkyrc

They have a font section

________________________

Modifying Openbox

You must edit ~/.config/openbox/rc.xml

You can change the number of Workspaces here.
You can change the shortcuts (keybinds) here.

If you mess up the Menu and can not access it you can modidy the configuration files and retart Openbox with this command.

openbox --restart



___________________________

Modifying Conky

Add additional Shortcut Notations

Alt + F4 = close active Window
Alt + tab = cycle through woindows on desktop
Alt + Shift + Tab = cycle through windows in a reverse order
Windows + D = Shows Desktop
Ctrl + Alt + right key = Change to the workspace to the right
Win + F1 or F2 or F3 or F4 = Change workspace
Alt + left click = Move a Window
Alt + Right Click = resize a window

Changing what Conky Displays

http://conky.sourceforge.net/variables.html
http://ifxgroup.net/conky.htm (Examples of Conky Variables with arguments))

Changing the clock (time variable)

Different format variables for date command

Check the man page of the  date command

Displaying Cmus Data
https://v3gard.com/2011/01/getting-cmus-to-cooperate-with-conky/
____________

Modifying Tint2




https://gitlab.com/o9000/tint2/blob/master/doc/tint2.md (wiki for tint2)

__________________________


Changing System wide colors

You can change them via the themes editor in the menu or add a theme to /usr/share/themes


Changing Basic Appearances

https://forums.bunsenlabs.org/viewtopic.php?id=4164



Grub Image

I. The default background image used by grub during the boot process is:

/usr/share/images/bunsen/grub/default.png

Changing the blue version to the grey one can be done by simply copying (as root) /usr/share/images/bunsen/wallpapers/default/BL-Beam-plain-grey.png to /usr/share/images/bunsen/grub/ - rename it to default.png while renaming the original default.png to something like default.png.old and if your root system is encrypted, run

sudo update-grub

.or you can edit /etc/default/grub:

GRUB_BACKGROUND="/path/to/some/image.png"


Default Login Background


The default login background is

/usr/share/images/bunsen/login/default.png

Changing the blue version to the grey one is basically the same as above: Copy the appropriate file (as root) e.g. flame-text-1920x1200-right.png (there might be a better one depending on the screen resolution) from /usr/share/images/bunsen/wallpapers/default  to  /usr/share/images/bunsen/login/ and rename it to default.png while renaming the original default.png to something like default.png.old -> done! 


WallPaper

Changing the desktop background (wallpaper) is easy via Menu/Preferences/Choose Wallpaper. If I’m not mistaken the files are in the ~/Pictures/wallpapers directory.

bunsen Labs Exit Bar color

 For changing the bl-exit bar color from blue to grey copy the directory /etc/bl-exit to ~/.config and change the following line in ~/.config/bl-exit/bl-exitrc under the [style] section to:

rcfile = grey.rc


Required Installations

Ibus and Ibus-Anthy(Japanese) for typing in Japanese
Tor Broswer
firefox
chromium
uzbl browser
Gimp
vlc
cmus - C-music (terminal music player
clementine
Audacity
K3b
Audacity
Qjackctl
rosegarden
amsynth
qsynth
sakura terminal
terminator terminal
libre Office
Abiword
gedit
calculator
dmenu
clipit
nitrogen
conky
transmission-gtk (torrents)


List of Japanese Computer Menu Terms

Openbox Menu


terminal - ターミナル
Web /Browswer - Web ブラウザ
File Manager - ファイルマネージャー　
Text Editor - テキストエディター
Media Player - メディア・プレーヤー
Tor Browser -　Tor ブラウザ
________
Multimedia - ムルチメディア
Internet - エンタネット
Office -  事務所 Jimusho
________________
Places - 場所
Recent Files - 最近開けたファイル
________________
Preferences -  設定　せってい　preferences
System - システム
Help - ヘルプ
________________
Screen Lock - 画面ロック　がめん・ロック
Exit - 終了　しゅうりょう　quit



In alphabetical order of English terms
Note: This list has become rather long. Please don’t be daunted by it. The aim is to give you a reference for anything you might run into. Actually a lot of what you encounter won’t be on this list. It will simply be katakana-ized versions of the English terms you know already. You don’t need to know this list! Just bookmark it and use it when you need it.



操作　そうさ　action
追加　ついか    add
適用　てきよう　apply
閉じる　とじる　close
環境設定　かんきょうせってい　configuration (preferences)
作成　さくせい　create
切り取り 　きりとり　cut
削除　さくじょ    delete
編集　へんしゅう　edit
検索　けんさく   find (also the term for “search” in general)
次を検索　つぎをけんさく   find next
強制終了　きょうせいしゅうりょう   force quit
書式　しょしき　format
全画面　ぜんがめん　full screen
履歴　りれき　history
入力　にゅうりょく　input
言語 げんご　language
一覧　いちらん　list
読み込み中　よみこみちゅう　loading
場所　ばしょ　location
管理　かんり　manage
新規　しんき　new
開く　あく　open
上書き　うわがき　overwrite
貼り付け　はりつけ　paste
印刷 　いんさつ　print
再生　さいせい　playback
終了　しゅうりょう　quit
最近　さいきん　recent (as in 最近開けたファイル, recently opened files)
ゴミ箱　ゴミばこ　recycle bin
やり直す　やりなおす　redo
再読み込み　さいよみこみ　reload
再起動　さいきどう   restart
実行　じっこう　run
保存　ほぞん    save
保存先　ほぞんさき    save location (destination)
検索　けんさく   search
設定　せってい　settings
表　ひょう　table
元に戻す　もとにもどす　undo
取り消す　とりけす　undo
無題　むだい　untitled
利用　りよう　use
使用　しよう　use
利用者　りようしゃ　user
表示　ひょうじ　view

入力　にゅうりょく　input
追加 ついか add
作成 さくせい　create
検索 けんさく search
適用　てきよう　apply
利用 りよう　use
使用 しよう　use
実行　じっこう　run
再起動 さいきどう restart
書式 しょしき　format
ゴミ箱 ゴミばこ　recycle bin
利用者　りようしゃ　user
全画面　ぜんがめん　full screen
言語 げんご　language
管理　かんり　manage
印刷 　いんさつ　print
表　ひょう　table
場所　ばしょ　location
操作　そうさ　action
一覧　いちらん　list
上書き　うわがき　overwrite
無題　むだい　untitled
元に戻す　もとにもどす　undo
切り取り 　きりとり　cut
貼り付け　はりつけ　paste
再読み込み さいよみこみ　reload

お気に入り　おきにいり　favorites
戻る　もどる　go back
置き換える　おきかえる　replace
選択　せんたく　select
並べ替え　ならべかえ　sorting
起動　きどう　starting

To type ディ, type "dexi". (This depends on what input engine you're using. Some use x to create small characters, some use l.) Tobberoth July 2009 (http://forum.jisho.org/discussion/324/a-question-about-katakana/p1)
・To type the Nakaguro (Interpunct) dot between katakana simply type the word なかぐろ　orなかてん.  An alternative  spelling is using z/ , the / becomes a middle dot z・. For Anthy.
●　To type the bigger black circle you can type kuromaru くろまる

Typing てん is a last chance measure as it contains a large number of punctuation in it.
