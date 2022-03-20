# Sesshomaru[^1]'s code

Archlinux je super. To je jeden z hlavních důvodů tohoto projektu. Obyčejný dělník který pracuje v nákladní dopravě na dráze a pochopí chod systému archlinux na co nejlepší úrovni! Naučí se psát scripty, modifikovat prostředí linuxu a programovat v Pythonu.

**Cíl je tedy jasný. Nezbývá než k němu směřovat a dotáhnout vše do konce!**

### archlinux:

64bitová **rolling relase**[^2] distribuce, která klade důraz především na jednoduchost a přímočarost uživatelského prostředí.
Pro instalaci balíčků používá program Pacman, který balíčky instaluje z repozitářů, které se dělí na oficialní databázy a AUR (arch user repo.)
1. [core] 
2. [extra]
3. [community]
4. [multilib]
5. [test]
6. [chaotic-aur] 
7. and [other custom]

### init
Program v unixových systémech. Je spuštěn jako první proces a následně spouští další procesy. Běží neustále na pozadí jako démon.

##### Bash sriptS:

## separators:
1. ; - provede první příkaz, následně druhý
      
      ```
      ls -a /home/sesshom4ru/Documents ; cd ~/Documents
      ```
      
2. && - provede první příkaz, druhý příkaz provede pokud projde první příkaz
3. || - funguje naopak než &&, provede druhý příkaz pouze když první příkaz neprojde
4. &  - _u tohoto separátoru si nejsem jistý, ale vypadá to že:_ narozdíl od předchozích třech spustí oba příkazy najednou a vypíše číslo procesu u prvního příkazu 

[^1]: **Sesshomaru** flies on [_Garuda i3WM_](https://garudalinux.org/downloads.html)

[^2]: **Rolling relase** znamená "postupně uvolňovaná". Nevychází najednou v konkretní plánované datum, ale aktualizuje se neustále. (zároveň tato platforma přináší určitá uskalí)


