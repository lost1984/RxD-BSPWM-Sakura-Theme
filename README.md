<h1 align="center">RxD BSPWM Sakura Theme - Git</a></h1>

* A Light & Sweet Theme/Scheme For BSPWM/EWW/GEANY/POLYBAR/ROFI/DUNST/ALACRITTY 
* PKG Including 
   * ROFI-MODULES (powermenu, network-manager-window, screenshotmenu, open-as-root-menu, windows-select-menu) & Find Out More By Trying It Out! 

<p align="center">  
    <img alt="RxD BSPWM Preview" src="/docs/img/preview.png"/>


* Requirements -
   * Need to add rxd-arch-repo in pacman.conf for auto resolving dependencies/installing non-mainline arch (aur) prebuilt packages
         
          [rxd-arch-repo]
          SigLevel = Optional DatabaseOptional
          Server = https://raw.githubusercontent.com/RifsxD/rxd-arch-repo/main/x86_64
         
* Dependencies (if not using rxd-arch-repo)-
   * MAINLINE_ARCH_REPO :
   
            'bspwm' 'alacritty' 'thunar' 'geany' 'gpick'
		    'sxhkd' 'playerctl' 'pavucontrol' 'rofi' 'dunst'
		    'rofi' 'dunst' 'xsel' 'xdotool' 'mpd'
		    'mpd' 'mpc' 'jq' 'lxappearance' 'maim'           
		    'maim' 'xclip' 'viewnior' 'feh' 'xfce4-power-manager' 
		    'xfce4-power-manager' 'xsettingsd' 'xorg-xsetroot' 'wmname'  
	
	
	
debian：
	            apt install -y bspwm alacritty thunar geany gpick  sxhkd playerctl pavucontrol rofi dunst rofi dunst xsel xdotool mpd    mpd mpc jq lxappearance maim  maim xclip viewnior feh xfce4-power-manager xfce4-power-manager xsettingsd xorg-xsetroot wmname
	
                         
	           	          
   * AUR OR RXD_ARCH_REPO :
   
            'ardesia' 'rofimoji' 'eww' 'networkmanager-dmenu-git' 'polybar' 'i3lock-color'
            'betterlockscreen' 'xfce-polkit' 'picom-ibhagwan-git'  'ksuperkey'
                            
                            
* Installation -
   * PACMAN_INSTALL: 
   
              sudo pacman -S rxd-bspwm-sakura && cp -r /usr/share/rxd-sakura/* ~/.config/
   * LOCAL_BUILD: 
   
              git clone https://github.com/RifsxD/RxD-BSPWM-Sakura-Theme.git
              cd $TO_THE_CLONED_REPO
              makepkg -si && cp -r /usr/share/rxd-sakura/* ~/.config/
                  
* Usefull Keybinds -
   * mod = windows / command
   * rofi ( mod / alt + f1 )
   * terminal ( mod + enter )
   * file-manager ( mod + shift + f )
   * powermenu ( mod + x )
   * screenshotmenu ( print / mod + s )
   * windowmenu ( mod + w )
   * open-as-root ( mod + r )
   * draw-over-screen ( mod + shift + p )
   * emoji-selector ( mod + alt + 0 )
   * color picker ( mod + p )
   * reload-all-configs ( alt + shift + r )
   

