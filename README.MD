## Autohotkey for Maths_and_Arrows

This AHK script lets you easily access commonly used Symbols for the different Number Types (Real, Complex, Rational, and Integer)

Either use \\R with the usual Letter, or use \real with the firest 3-4 letters of the name (normally case sensitive, but in the script there are options for both uncapitalized "real", and capitalized "Real")

```
\\R → ℝ , \real → ℝ, or \Real → ℝ

```
## AHK Installation

  1. Download [Autohotkey](https://www.autohotkey.com/download/) and install it. 
  2. Download the script [Maths_and_Arrows.ahk](https://github.com/PCBaum/ahk_Maths_and_Arrows/blob/main/Maths_and_Arrows.ahk)
   or create a new script with your prefered Name and copy paste the Key Mapping into it.
  3. Put the script into a folder of your choice. 
  4. Start the script Maths_and_Arrows.ahk 
  
  Optional: 
  
  5. Compile your Script with rightclick → compile script (shoud be somewhere around the the second row)
  
  6. Put the executable ("YOUR_SCRIPT_NAME".exe) in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.
  
  
## Whithout installing AHK on Windows

  1. Download the compiled [Maths_and_Arrows.exe](https://github.com/PCBaum/ahk_Maths_and_Arrows/raw/main/Maths_and_Arrows.exe) File
  2. Put the script into a folder of your choice.
  3. Start the script Maths_and_Arrows.exe
  
  Optional:
  
  4.  Put the executable in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.

## Key Mapping 

how this AHK script maps input to output: 
::input::output   output is given as the Unicode code.

```

#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
#Hotstring C * ?
::\forall::{U+2200}
::\emptyset::{U+2205}
::\Element::{U+2208}
::\nElement::{U+2209}
::\nelement::{U+2209}
::\element::{U+220A}
::\Contains::{U+220B}
::\nContains::{U+220C}
::\ncontains::{U+220C}
::\contains::{U+220D}
::\sqrt::{U+221A}
::\3rt::{U+221B}
::\4rt::{U+221C}
::\proportional::{U+221D}
::\infinity::{U+221E}
::=\= ::{U+2260}
::=|= ::{U+2260}
::=/= ::{U+2260}
::=> ::{U+21D2}
::\<= ::{U+21D0}
::<=>::{U+21D4}
::<=\=>::{U+21CE}
::<=/=>::{U+21CE}
::<=|=>::{U+21CE}
::<- ::{U+2190}
::-> ::{U+2192}
::<->::{U+2104}
::<-|::{U+21A4}
::|->::{U+21A6}
::=<::{U+2266}
::\>=::{U+2265}
::-+::{U+2213}
::+-::{U+00B1}
::\AND::{U+2227}
::\OR::{U+2228}
::\XOR::{U+2295}
::\NAND::{U+22BC}
::\NOR::{U+22BD}
::\XNOR::{U+2299}
::\integral::{U+222B}
::\dintegral::{U+222C}
::\tintegral::{U+222D}
::\cintegral::{U+222E}
::\cdintegral::{U+222F}
::\ctintegral::{U+2230}
::\Cintegral::{U+222E}
::\aintegral::{U+222F}
::\Aintegral::{U+222F}
::\vintegral::{U+2230}
::\Vintegral::{U+2230}
::\weil::{U+2235}
::\dann::{U+2234}
::\Sum::{U+2211}
::\Existiert::{U+2203}
::\existiert::{U+2203}
::\nexistiert::{U+2204}
::\nExistiert::{U+2204}
::\because::{U+2235}
::\then::{U+2234}
::\Exists::{U+2203}
::\exists::{U+2203}
::\nexists::{U+2204}
::\nExists::{U+2204}
::\qed::{U+2B1C}
::\QED::{U+2B1C}
#Hotstring *0 ?0 C0$0

```

## Credits

Template for AHK Script: was a some time ago and I don't remember. Also, the beginning seems to be standard, and is the only not heavily changed part.
