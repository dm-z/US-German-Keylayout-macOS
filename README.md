# US-German-Keylayout-macOS  

A custom keyboard layout based on the **ANSI U.S. layout (macOS)**, designed for users who frequently write in German.  
It adds Umlauts and German quotation marks without requiring a full layout switch.  

The **¨ (Option-U) dead key** has been reassigned to the **quote key** to avoid conflicts with `ü`.  

---

### Key Changes  

- **Opt + s** → ß *(not a change, just FYI)*  
- **Opt + a** → ä  
- **Opt + o** → ö  
- **Opt + u** → ü  
- **Shift + Opt + a** → Ä  
- **Shift + Opt + o** → Ö  
- **Shift + Opt + u** → Ü  
- **Opt + [** → „ (opening German quotes)  
- **Shift + Opt + [** → “ (closing German quotes)  
- **Opt + '** → ¨ (dead key; when followed by `a`, `o`, `u` → produces Umlauts)  

---

Everything else remains identical to the default **U.S. layout on macOS**.  

### Installation  

Copy the `.keylayout` file into:

<pre>
```  
/Library/Keyboard Layouts/  
```  
</pre>

[Optional: remove the default U.S./English layout and keep only this one](https://apple.stackexchange.com/a/60521).