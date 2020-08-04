# **Demodoco's dwm**

---

### Key bindings

--- 

- Alt-z: start dmenu, ha la funzione di ricerca e avvio dei programmi installati
  
  (per utilizzarlo andrà installato, nel caso di arch "sudo pacman -S dmenu")
- Alt-Shift-j: ruotare lo stack verso sinistra
- Alt-Shift-k: ruotare lo stack verso destra
  

### **Patch**

---

- vanitygaps: gaps tra i bordi delle finestre
- rotatestack: la possibilità di ruotare lo stack

### Useful programs

----

Per automatizzare l'avvio dopo il login di certi programmi si inserisce il loro comando all'interno del file .xprofile

- xwallpaper: lo utilizzo per aggiungere lo sfondo all'avvio, in particolare nel file .xprofile ho il comando:
  
  " xwallpaper --center ~/Immagini/Wall/wall.png" 
  
  - l'opzione --center serve a centrare lo sfondo, per conoscenre le altre opzioni inseribili si può usare il comando " man xwallpaper"

- compton: è un composite manager, lo uso per la trasparenza del terminale (alacritty)  inserendo dentro .xprofile il comando "compton &"
  
  - la "&" commerciale si usa alla fine di un comando per eseguirlo in background
    
    anche in questo caso è possibile trovare più informazioni in  "man bash" 




