---
TOCTitle: 'MS12-MAY'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, květen 2012'
ms:assetid: 'ms12-may'
ms:contentKeyID: 61224023
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms12-may(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, květen 2012
================================================================

Publikováno: 8. května 2012 | Aktualizováno: 22. května 2012

**Verze:** 2.1

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v květnu 2012.

Spolu s vydáním bulletinů zabezpečení pro květen 2012 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 3. května 2012. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání 9. května 2012 v 11:00 časového pásma Tichomoří (USA a Kanada). [Zaregistrujte se pro webové vysílání týkající se květnových bulletinů zabezpečení](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499667). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://go.microsoft.com/fwlink/?linkid=217214).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení s jakýmikoli aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

### Informace o bulletinech

Shrnutí
-------

 
Následující tabulka shrnuje podle závažnosti bulletiny zabezpečení pro tento měsíc.

Podrobnosti o softwaru obsahujícím tuto chybu naleznete v následující části **Software obsahující tuto chybu a umístění aktualizací ke stažení**.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID bulletinu</th>
<th style="border:1px solid black;" >Název bulletinu a shrnutí</th>
<th style="border:1px solid black;" >Maximální stupeň závažnosti a dopad chyby zabezpečení</th>
<th style="border:1px solid black;" >Požadavek na restartování</th>
<th style="border:1px solid black;" >Postižený software</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v aplikaci Microsoft Word umožňuje vzdálené spuštění kódu (2680352)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v sadě Microsoft Office, kterou oznámila soukromá osoba. Tato chyba umožňuje vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor ve formátu RTF. Útočník, který by tuto chybu zabezpečení úspěšně zneužil, by mohl získat stejná uživatelská práva jako aktuální uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;"><strong>Kombinovaná aktualizace zabezpečení pro systém Microsoft Office, Windows, rozhraní .NET Framework a program Silverlight (2681578)</strong><br />
<br />
Tato aktualizace zabezpečení řeší tři veřejně známé chyby a sedm chyb oznámených soukromými osobami, které se týkají zabezpečení systému Microsoft Office, Microsoft Windows, rozhraní Microsoft .NET Framework a programu Microsoft Silverlight. Nejzávažnější z těchto chyb zabezpečení může způsobit vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený dokument nebo navštíví škodlivou webovou stránku s integrovaným souborem písma TrueType. Útočník nemůže žádným způsobem přinutit uživatele k návštěvě škodlivého webu. Místo toho by útočník musel přesvědčit uživatele, aby navštívili takový web. K tomu se obvykle používá odkaz v e-mailové zprávě nebo zprávě programu pro zasílání rychlých zpráv, na který uživatelé kliknou, a přejdou tak na útočníkův web.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework, Microsoft Silverlight,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v rozhraní .NET Framework umožňují vzdálené spuštění kódu (2693777)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě soukromými osobami oznámené chyby zabezpečení rozhraní .NET Framework. Tyto chyby zabezpečení by mohly umožnit vzdálené spuštění kódu v klientském systému, pokud by uživatel zobrazil speciálně vytvořenou webovou stránku pomocí webového prohlížeče, v němž lze otevírat aplikace prohlížeče XAML (XBAP). Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení systému Microsoft</strong> <strong>Office</strong> <strong>umožňují vzdálené spuštění kódu (2663830)</strong><br />
<br />
Tato aktualizace zabezpečení řeší jednu veřejně známou a pět soukromými osobami oznámených chyb zabezpečení systému Microsoft Office. Chyby umožňují vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor systému Office. Útočník, který by úspěšně zneužil tyto chyby zabezpečení, by mohl získat stejná uživatelská práva, jaká má přihlášený uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v aplikaci Microsoft Visio Viewer 2010 umožňuje vzdálené spuštění kódu (2597981)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v sadě Microsoft Office, kterou oznámila soukromá osoba. Tato chyba umožňuje vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor aplikace Visio. Útočník, který by tuto chybu zabezpečení úspěšně zneužil, by mohl získat stejná uživatelská práva jako aktuální uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v protokolu TCP/IP umožňuje zvýšení úrovně oprávnění (2688338)</strong><br />
<br />
Tato aktualizace zabezpečení řeší jednu soukromou osobou oznámenou a jednu veřejně známou chybu zabezpečení systému Microsoft Windows. Závažnější z těchto chyb zabezpečení by mohla způsobit zvýšení úrovně oprávnění, pokud by se útočník přihlásil k systému a spustil speciálně vytvořenou aplikaci.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení ve správci oddílů systému Windows by mohla způsobit zvýšení úrovně oprávnění (2690533)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v systému Microsoft Windows, kterou oznámila soukromá osoba. Tato chyba zabezpečení by mohla způsobit zvýšení úrovně oprávnění, pokud by se útočník přihlásil k systému a spustil speciálně vytvořenou aplikaci. Tuto chybu může zneužít pouze útočník s platnými pověřeními pro přihlášení, která by mu umožňovala se místně přihlásit.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
<p></p>

  
Index zneužitelnosti  
--------------------
  
 
Následující tabulka uvádí hodnocení zneužitelnosti každé chyby zabezpečení uvedené v tomto měsíci. Chyby zabezpečení jsou řazeny podle čísla jednotlivých bulletinů (ID bulletinu) a chyb (ID CVE). Uvedeny jsou pouze chyby zabezpečení ohodnocené stupněm závažnosti Kritický nebo Vysoký.
  
**Jak pracovat s touto tabulkou**
  
V této tabulce zjistíte, jaká je pravděpodobnost zneužití v podobě spuštění kódu a odmítnutí služby během 30 dní od vydání tohoto bulletinu zabezpečení pro všechny aktualizace zabezpečení, které bude třeba nainstalovat. Všechna níže uvedená hodnocení zvažte na základě vaší specifické konfigurace a podle závěrů hodnocení nastavte priority pro zavádění jednotlivých aktualizací vydaných v tomto měsíci. Další informace o významu těchto hodnocení a způsobu jejich stanovení najdete v indexu zneužitelnosti [Microsoft Exploitability Index](http://technet.microsoft.com/security/cc998259.aspx).
  
Položka nazvaná „Nejnovější vydání softwaru“ odkazuje na příslušný software. Položka nazvaná „Starší vydání softwaru“ odkazuje na všechna starší podporovaná vydání příslušného softwaru, uvedeného v tabulkách bulletinu „Software obsahující tuto chybu“ a „Software neobsahující tuto chybu“.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID bulletinu</th>
<th style="border:1px solid black;" >Název chyby zabezpečení</th>
<th style="border:1px solid black;" >ID CVE</th>
<th style="border:1px solid black;" >Hodnocení zneužitelnosti u nejnovějšího vydání softwaru</th>
<th style="border:1px solid black;" >Hodnocení zneužitelnosti u starších vydání softwaru</th>
<th style="border:1px solid black;" >Hodnocení zneužitelnosti odmítnutí služby</th>
<th style="border:1px solid black;" >Hlavní poznámky</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení při neshodě ve formátu RTF</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0183">CVE-2012-0183</a></td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se poškození paměti ve formátu souboru aplikace Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0141">CVE-2012-0141</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se poškození paměti ve formátu souboru aplikace Excel v záznamu OBJECTLINK</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0142">CVE-2012-0142</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se poškození paměti souboru aplikace Excel použitím různých modifikovaných bajtů</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0143">CVE-2012-0143</a></td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">Týká se pouze systému Microsoft Office 2003.<br />
<br />
Tato chyba zabezpečení je veřejně známá.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se poškození paměti záznamu SXLI aplikace Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0184">CVE-2012-0184</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se přetečení haldy záznamu MergeCells aplikace Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0185">CVE-2012-0185</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Zneužitelný kód nelze jednoduše vytvořit</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Zneužitelný kód nelze jednoduše vytvořit</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se neshody typů při analýze záznamu Series aplikace Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1847">CVE-2012-1847</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se poškození paměti ve formátu VSD</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0018">CVE-2012-0018</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">Týká se aplikací Visio Viewer 2010 a Visio Viewer 2010 Service Pack 1 (jediné podporované verze aplikace Visio Viewer).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení související s obejitím brány firewall systému Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0174">CVE-2012-0174</a></td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">Jedná se o chybu zabezpečení související s obejitím zabezpečení.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se dvojitého uvolnění protokolu TCP/IP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0179">CVE-2012-0179</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">Tato chyba zabezpečení je veřejně známá.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení správce konfigurace Plug and Play (PnP)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0178">CVE-2012-0178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Dočasné</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení při analýze písma TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">Tato chyba zabezpečení je veřejně známá.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení při analýze písma TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení v přidělování vyrovnávací paměti rozhraní .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0162">CVE-2012-0162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení typu záznamu GDI+</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0165">CVE-2012-0165</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Zneužitelný kód nelze jednoduše vytvořit</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se přetečení haldy záznamu GDI+</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0167">CVE-2012-0167</a></td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se dvojitého uvolnění aplikace Silverlight</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0176">CVE-2012-0176</a></td>
<td style="border:1px solid black;">Žádné ohrožení</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se systému Windows a zpráv</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0180">CVE-2012-0180</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se souboru s rozložením klávesnice</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0181">CVE-2012-0181</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Vytvoření zneužitelného kódu není pravděpodobné</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">Tato chyba zabezpečení je veřejně známá.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se výpočtu posuvníku</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1848">CVE-2012-1848</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Trvalé</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se serializace rozhraní .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0160">CVE-2012-0160</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;">Chyba zabezpečení týkající se serializace rozhraní .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0161">CVE-2012-0161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Je pravděpodobné vytvoření zneužitelného kódu</td>
<td style="border:1px solid black;">Netýká se</td>
<td style="border:1px solid black;">(Žádné)</td>
</tr>
</tbody>
</table>
<p></p>

  
Software obsahující tuto chybu a umístění aktualizací ke stažení  
----------------------------------------------------------------
  
 
Následující tabulky řadí bulletiny podle kategorie hlavního softwaru a závažnosti.
  
**Jak pracovat s těmito tabulkami?**
  
V těchto tabulkách zjistíte, které aktualizace zabezpečení bude třeba nainstalovat. Přečtěte si seznam všech programů a komponent a zjistěte, zda se některé aktualizace zabezpečení týkají vaší instalace. Pokud se program nebo komponenta v seznamu nachází, je v něm zároveň uveden odkaz na dostupnou aktualizaci softwaru a také stupeň závažnosti aktualizace softwaru.
  
**Poznámka:** Jedna chyba zabezpečení může vyžadovat instalaci více aktualizací. Přečtěte si celý sloupec u každého identifikátoru bulletinu. Zjistíte v něm, které aktualizace je třeba nainstalovat v závislosti na programech nebo součástech nainstalovaných ve vašem systému.
  
#### Operační systém Windows a jeho komponenty

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th colspan="5" style="border:1px solid black;">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b2ea7a8d-a537-441c-8e80-2ba4ac37e320)  
(KB2660649)  
(Pouze Tablet PC Edition 2005 Service Pack 3)  
(Vysoký)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9a4db1b4-15b2-4fae-83c4-a86331425c9e)  
(KB2659262)  
(Vysoký)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8d341077-8fcd-4666-a27e-2141a04a321e)  
(KB2676562)  
(Kritický)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=954e8ae9-9247-496a-bbde-76981c49e3b3)  
(KB2686509)  
(Vysoký)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b0803633-7fda-4862-a908-3450180cdaaa)  
(KB2604042)  
(Pouze Media Center Edition 2005 Service Pack 3 a Tablet PC Edition 2005 Service Pack 3)  
(Kritický)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6ebaccbc-512b-4f2f-bf2a-8958f012e13f)  
(KB2659262)  
(Vysoký)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0357165-4400-40a6-a7a4-7b762a1793ba)  
(KB2676562)  
(Kritický)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3b1568f-d7ad-4e6e-b45b-53b16b303d9d)  
(KB2686509)  
(Vysoký)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový** **stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc7bfb79-8eaf-4c22-b1c9-e774c55eb06d)  
(KB2659262)  
(Vysoký)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6287b994-041f-45b7-a230-d689bf1901a8)  
(KB2676562)  
(Kritický)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=167e8c49-f9f6-488b-86ad-4056d3d20213)  
(KB2686509)  
(Vysoký)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b0df42a4-7444-4da6-a9b2-35a56bdc64a4)  
(KB2604078)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bf7c9aea-dc18-499f-b456-2c29e9a74a15)  
(KB2659262)  
(Vysoký)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9f49cd0-24db-4438-afde-aa7113ec2035)  
(KB2676562)  
(Kritický)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4614161c-ae05-43ad-8dd3-85975ec2bc4c)  
(KB2686509)  
(Vysoký)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6414b607-6fb1-4527-b218-c3cb5adfd4d1)  
(KB2659262)  
(Vysoký)  
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2563425d-4f6e-4f33-b775-a8d421b0e254)  
(KB2676562)  
(Kritický)  
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=67f659ee-0d28-40f3-ae2f-f8fceeac8bff)  
(KB2686509)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e11d8738-379a-4dfe-b21c-495041d9523a)  
(KB2658846)  
(Vysoký)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8068e95-ac4d-45e8-84b7-b12d633c70b5)  
(KB2659262)  
(Vysoký)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=02c857c6-5dfa-46fb-adef-35eac2bf5f41)  
(KB2660649)  
(Vysoký)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=292d1f3b-a065-4d7d-9046-f35ab7f0591b)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1dc6e10-34eb-45ea-92b3-9983c00f6cb5)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9d5e290-dc57-4587-b31d-706b541924ec)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=838f588b-2a0d-4dae-b54d-782e6985fd83)  
(KB2658846)  
(Vysoký)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3bde7f59-163c-4491-abc9-a822daa8142f)  
(KB2659262)  
(Vysoký)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9f97c5a4-62ee-4e4f-8811-a43545d76327)  
(KB2660649)  
(Vysoký)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8f90c09c-a2cb-4adb-ace7-a8bc38d78ba6)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d65565d4-d865-438a-bfb7-d71af9dd884e)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=827b9f15-b67d-4dd4-a39b-7c148bae5041)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=360adbed-a451-44ed-8675-ca5624ef1cf3)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=278c378b-6ee4-4f80-b9c3-ede885f4bbda)<sup>[3]</sup>
(KB2660649)  
(Vysoký)  
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5a6d617-8ef6-42fa-a325-c15fa7ece7aa)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98c4ac87-eec2-4e02-b0e1-00626bcb0ffd)<sup>[3]</sup>
(KB2660649)  
(Vysoký)  
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(Kritický)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c65df271-8b7d-46d3-81b3-87c0ad05e8d0)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=11da5031-1733-43ea-9204-294eb483c858)  
(KB2676562)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(Kritický)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c5f7ee25-2fc1-44c7-b3e6-e2c969ecf1bc)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c081b058-b95e-4467-a2fc-fb1a68345c8f)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 pro 32bitové systémy
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(Vysoký)  
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(Vysoký)  
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(Vysoký)  
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 pro 32bitové systémy Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(Vysoký)  
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(Vysoký)  
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(Vysoký)  
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 pro systémy s procesorem x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(Vysoký)  
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(Kritický)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Možnosti instalace Server Core
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(Vysoký)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(Vysoký)  
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(Vysoký)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Stupeň závažnosti není určen<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)  
(KB2656405)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(Kritický)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(Vysoký)
</td>
</tr>
</table>
<p></p>

 
**Poznámky** **k bulletinu** **MS12-034**

<sup>[1]</sup>**Postižena jsou rozhraní .NET Framework 4 a .NET Framework 4 Client Profile.** Distribuční balíčky rozhraní .NET Framework verze 4 jsou k dispozici ve dvou profilech: .NET Framework 4 a .NET Framework 4 Client Profile. Rozhraní .NET Framework 4 Client Profile je verzí rozhraní .NET Framework 4. Chyba zabezpečení řešená v této aktualizaci se týká jak rozhraní .NET Framework 4, tak rozhraní .NET Framework 4 Client Profile. Další informace získáte v článku [Instalace rozhraní .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx) na webu MSDN.

<sup>[2]</sup>U této aktualizace není určen stupeň závažnosti pro konkrétní software, neboť neexistují žádné známé vektory útoků vztahující se k chybě zabezpečení projednávané v tomto bulletinu. Nicméně v rámci zvýšení ochrany doporučuje společnost Microsoft uživatelům tohoto softwaru tuto aktualizaci zabezpečení použít.

<sup>[3]</sup>Tato aktualizace se vztahuje pouze na systémy Windows Server 2008 s nainstalovanou a povolenou volitelnou funkcí Možnosti práce s počítačem. Další informace naleznete v nejčastějších dotazech aktualizace MS12-034.

\[4\]Tato aktualizace se vztahuje pouze na systémy Windows Server 2008 R2 s nainstalovanou a povolenou součástí Podpora rukopisu volitelné funkce Služba podpory rukopisu. Další informace naleznete v nejčastějších dotazech aktualizace MS12-034.

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

**Poznámka** **k bulletinu** **MS12-035**

<sup>[1]</sup>**Postižena jsou rozhraní .NET Framework 4 a .NET Framework 4 Client Profile.** Distribuční balíčky rozhraní .NET Framework verze 4 jsou k dispozici ve dvou profilech: .NET Framework 4 a .NET Framework 4 Client Profile. Rozhraní .NET Framework 4 Client Profile je verzí rozhraní .NET Framework 4. Chyba zabezpečení řešená v této aktualizaci se týká jak rozhraní .NET Framework 4, tak rozhraní .NET Framework 4 Client Profile. Další informace získáte v článku [Instalace rozhraní .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx) na webu MSDN.

#### Sady Microsoft Office a jejich software

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th colspan="5" style="border:1px solid black;">
Sady Microsoft Office a jejich komponenty
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9819899d-7f7f-4ddd-9fc8-816a57d2979e)  
(KB2598332)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0abbf09c-8828-4524-8b38-e34faefa2ae4)  
(KB2598253)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=162901b1-4c1d-476f-99e9-218780897f92)  
(KB2597086)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(Vysoký)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(Vysoký)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(Vysoký)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(Vysoký)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32bitové edice)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(Vysoký)  
[Microsoft Office 2010 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32bitové edice)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(Vysoký)  
[Microsoft Office 2010 Service Pack 1 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (64bitové edice)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(Vysoký)  
[Microsoft Office 2010 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64bitové edice)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(Vysoký)  
[Microsoft Office 2010 Service Pack 1 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Další software sady Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=9dedfb18-a651-49f7-b1fc-78f7b6cb234a)<sup>[2]</sup>
(KB2596842)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 (32bitová edice)](http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(Vysoký)  
[Microsoft Visio Viewer 2010 Service Pack 1 (32bitová edice)](http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(Vysoký)  
[Microsoft Visio Viewer 2010 (64bitová edice)](http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(Vysoký)  
[Microsoft Visio Viewer 2010 Service Pack 1 (64bitová edice)](http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
</table>
<p></p>

 
**Poznámka k bulletinu MS12-029**

<sup>[1]</sup>Na ochranu před chybami zabezpečení popsanými v tomto bulletinu je u aplikace Microsoft Word 2007 kromě balíčku aktualizací zabezpečení KB2596917 potřeba nainstalovat také aktualizaci zabezpečení pro sadu Microsoft Office Compatibility Pack (KB2596880).

**Poznámky** **k bulletinu** **MS12-030**

<sup>[1]</sup>Na ochranu před chybami zabezpečení popsanými v tomto bulletinu je u aplikace Microsoft Excel 2007 kromě balíčku aktualizací zabezpečení KB2597161 potřeba nainstalovat také aktualizaci zabezpečení pro sadu Microsoft Office Compatibility Pack (KB2597162).

<sup>[2]</sup>Aplikace Microsoft Excel Viewer musí být před instalací této aktualizace aktualizována na podporovanou úroveň servisního balíčku (Excel Viewer 2007 Service Pack 2 nebo Excel Viewer 2007 Service Pack 3). Další informace o podporovaných prohlížečích systému Office naleznete v [článku 979860 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/979860).

**Poznámka** **k bulletinu** **MS12-034**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

#### Vývojářské nástroje a software společnosti Microsoft

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight 4
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) při instalaci v systému Mac  
(KB2690729)  
(Kritický)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) při instalaci ve všech podporovaných vydáních klientů se systémem Microsoft Windows  
(KB2690729)  
(Kritický)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) při instalaci ve všech podporovaných vydáních serverů se systémem Microsoft Windows  
(KB2690729)  
(Kritický)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight 5
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) při instalaci v systému Mac  
(KB2636927)  
(Kritický)  
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) při instalaci ve všech podporovaných vydáních klientů se systémem Microsoft Windows  
(KB2636927)  
(Kritický)  
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) při instalaci ve všech podporovaných vydáních serverů se systémem Microsoft Windows  
(KB2636927)  
(Kritický)
</td>
</tr>
</table>
<p></p>

 
**Poznámka** **k bulletinu** **MS12-034**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------

 
**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat kliknutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Zákazníkům systému Microsoft Office for Mac doporučujeme využít funkci Microsoft AutoUpdate for Mac, která udržuje software společnosti Microsoft v aktuálním stavu. Další informace o funkci Microsoft AutoUpdate for Mac naleznete na webu [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (Automatická kontrola aktualizací softwaru).

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Doporučené postupy zjišťování a instalace**

Společnost Microsoft poskytuje doporučené postupy zjišťování a nasazení aktualizací zabezpečení. Tyto dokumenty obsahují doporučení a informace, které mohou odborníkům v oblasti IT pomoci porozumět, jak se používají různé nástroje pro detekci a nasazení aktualizací zabezpečení. Další informace získáte v [článku 961747 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Nástroj MBSA (Microsoft Baseline Security Analyzer)**

Pomocí nástroje Microsoft Baseline Security Analyzer (MBSA) mohou správci prohledávat místní i vzdálené systémy a zjistit tak, jestli v nich nechybí některé aktualizace zabezpečení nebo jestli v nastavení zabezpečení systému nedošlo k některým běžným chybám. Další informace o nástroji MBSA získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Služba Windows Server Update Services**

Pomocí služby Windows Server Update Services (WSUS) mohou správci systémů rychle a spolehlivě nasadit nejnovější důležité aktualizace zabezpečení pro systémy Microsoft Windows 2000 a novější, systém Office XP a novější, Exchange Server 2003 a SQL Server 2000 do systémů Microsoft Windows 2000 a novějších.

Další informace o způsobu instalace této aktualizace zabezpečení pomocí služby Windows Server Update Services získáte na webu služby [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Služba Software Update Management nástroje Configuration Manager 2007 zjednodušuje složitý proces doručení a správy aktualizací do IT systémů firmy. Pomocí nástroje Configuration Manager 2007 mohou správci informačních technologií doručit aktualizace produktů společnosti Microsoft do řady zařízení, včetně stolních počítačů, notebooků, serverů a mobilních zařízení.

Automatizované hodnocení chyb zabezpečení v nástroji Configuration Manager 2007 odhaluje potřebu aktualizací a hlášení doporučených postupů. Základem služby Software Update Management nástroje Configuration Manager 2007 jsou služby WSUS (Microsoft Windows Software Update Services). Jedná se o časem prověřenou infrastrukturu aktualizací známou správcům informačních technologií po celém světě. Další informace o tom, jak mohou správci používat nástroj Configuration Manager 2007 k nasazení aktualizací, naleznete na webových stránkách [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Další informace o nástroji Configuration Manager naleznete na webových stránkách [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) představuje v rozlehlých sítích řešení pro správu aktualizací s rozsáhlými možnostmi konfigurace. Umožňuje správcům identifikovat počítače se systémem Windows, které vyžadují aktualizace zabezpečení, a provést řízenou instalaci těchto aktualizací v celé rozlehlé síti s minimálním dopadem na koncové uživatele.

**Poznámka:** Systems Management Server 2003 není od 12. ledna 2010 součástí tradiční podpory. Další informace o životním cyklu produktů naleznete na webu [Životní cyklus podpory produktů společnosti Microsoft](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). K dispozici je nyní nová verze nástroje SMS, System Center Configuration Manager 2007 (viz výše uvedená část **System Center Configuration Manager 2007**).

Další informace o tom, jak mohou správci pomocí serveru SMS 2003 nasazovat aktualizace zabezpečení, naleznete na webových stránkách [Scénáře a postupy pro Microsoft Systems Management Server 2003: Distribuce softwaru a správa oprav](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Další informace o serveru SMS naleznete na webových stránkách [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Poznámka:** Služba SMS pomocí modulu Microsoft Baseline Security Analyzer poskytuje rozsáhlou podporu při zjišťování a nasazení aktualizací bulletinu zabezpečení. Tyto nástroje nemusí některé softwarové aktualizace zjistit. V takovém případě mohou správci použít funkce serveru SMS a nasměrovat aktualizace do určitých systémů. Další informace o tomto postupu naleznete na webu [Nasazení aktualizací softwaru pomocí funkce Distribuce softwaru serveru SMS](http://go.microsoft.com/fwlink/?linkid=33341). Některé aktualizace zabezpečení vyžadují po restartování počítače oprávnění správce. Správci mohou k instalaci těchto aktualizací použít nástroj Elevated Rights Deployment Tool (k dispozici v sadě [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Nástroj Update Compatibility Evaluator a sada Application Compatibility Toolkit**

Aktualizace často zapisují do stejných souborů a nastavení registru požadovaných pro spouštění aplikací. To může způsobit nekompatibilitu a zvýšit dobu, po kterou trvá nasazení aktualizací zabezpečení. Testování a ověřování aktualizací systému Windows lze usnadnit pomocí součástí nástroje [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), které jsou dodávány se sadou [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sada Application Compatibility Toolkit (ACT) obsahuje nezbytné nástroje a dokumentaci pro posouzení a zmírnění problémů s kompatibilitou aplikací před nasazením systému Windows Vista, služby Windows Update, aktualizací zabezpečení společnosti Microsoft nebo nové verze aplikace Windows Internet Explorer ve vašem prostředí.

### Další informace

#### Nástroj pro odstranění škodlivého softwaru systému Microsoft Windows

Společnost Microsoft vydává aktualizovanou verzi Nástroje pro odstranění škodlivého softwaru systému Microsoft Windows na webu Windows Update, Microsoft Update, ve službě Windows Server Update Services a na webu služby Stažení softwaru.

#### Aktualizace nesouvisející se zabezpečením na webu Microsoft Update (MU), Windows Update (WU) a ve službě Windows Server Update Services (WSUS)

Informace o aktualizacích nesouvisejících se zabezpečením na webu Windows Update a Microsoft Update naleznete na webové stránce:

-   [Článek 894199 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Popis služeb Software Update Services a Windows Server Update Services se mění v obsahu. Zahrnuje celý obsah systému Windows.
-   [Aktualizace vydané v uplynulých měsících pro službu Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Obsahuje přehled všech nových, revidovaných a opětovně vydaných aktualizací pro jiné produkty společnosti Microsoft, než je systém Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Pro zlepšení ochrany dat svých zákazníků poskytuje společnost Microsoft informace o chybách v zabezpečení všem hlavním dodavatelům softwaru pro zabezpečení, a to vždy ještě před vydáním nové měsíční zprávy o aktualizaci zabezpečení. Dodavatelé softwaru pro zabezpečení tak mohou tyto informace o chybách v zabezpečení využít a poskytnout svým zákazníkům ochranu včasnou aktualizací svých programů a zařízení pro zabezpečení, jako jsou antivirové programy, síťové systémy pro detekci napadení či hostitelské systémy pro prevenci napadení. Informace o dostupnosti aktuálních prostředků aktivní ochrany od jednotlivých dodavatelů softwaru pro zabezpečení naleznete na stránkách aktivní ochrany jednotlivých partnerů programu MAPP. Seznam těchto partnerů naleznete na stránce [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

#### Strategie zabezpečení a komunita

**Strategie instalace aktualizací**

Web [Doporučené postupy zabezpečení pro správu aktualizací (Security Guidance for Update Management)](http://go.microsoft.com/fwlink/?linkid=21168) obsahuje další informace o instalaci aktualizací zabezpečení podle doporučení společnosti Microsoft.

**Získání dalších aktualizací zabezpečení**

Aktualizace odstraňující další problémy se zabezpečením získáte v následujících umístěních:

-   Aktualizace zabezpečení jsou k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.
-   Aktualizace pro klientské platformy jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizace zabezpečení nabízené tento měsíc na webu Windows Update jsou k dispozici na webu služby Stažení softwaru v souborech obrazu ISO disku CD s vydanými aktualizacemi zabezpečení a kritickými aktualizacemi. Další informace získáte v [článku 913086 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Komunita odborníků v oblasti zabezpečení**

Na webu [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) se můžete naučit, jak zlepšit zabezpečení a optimalizovat infrastrukturu IT, a diskutovat s dalšími členy komunity odborníků o bezpečnostních tématech.

#### Poděkování

Společnost Microsoft tímto [děkuje](http://go.microsoft.com/fwlink/?linkid=21127) za spolupráci při ochraně zákazníků:

-   Anonymnímu výzkumníkovi, spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [TippingPoint](http://www.tippingpoint.com/), za oznámení chyby popsané v bulletinu MS12-029.
-   [Omairovi](http://krash.in/) za oznámení dvou chyb popsaných v bulletinu MS12-030.
-   Omairovi, spolupracujícímu se společností [VeriSign iDefense Labs](http://labs.idefense.com/), za oznámení chyby popsané v bulletinu MS12-030.
-   Seanu Larssonovi a Junu Maovi, spolupracujícím se společností [VeriSign iDefense Labs](http://labs.idefense.com/), za oznámení dvou chyb popsaných v bulletinu MS12-030.
-   Anonymnímu výzkumníkovi, spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [TippingPoint](http://www.tippingpoint.com/), za oznámení chyby popsané v bulletinu MS12-030.
-   Luigimu Auriemmovi, spolupracujícímu se společností [VeriSign iDefense Labs](http://labs.idefense.com/), za oznámení chyby popsané v bulletinu MS12-031.
-   Bojanu Zdrnjovi ze společnosti [INFIGO IS](http://www.infigo.hr/) za oznámení chyby popsané v bulletinu MS12-032.
-   Anatoliji Glagolevovi ze společnosti [Genesys Telecommunications](http://www.genesyslab.com/) za spolupráci na řešení chyby popsané v bulletinu MS12-032.
-   Alinu Radu Popovi, spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [Tipping Point](http://www.tippingpoint.com/), za oznámení chyby popsané v bulletinu MS12-034.
-   Vitaliji Toropovovi, spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [Tipping Point](http://www.tippingpoint.com/), za oznámení chyby popsané v bulletinu MS12-034.
-   [Omairovi](http://krash.in/) za oznámení chyby popsané v bulletinu MS12-034.
-   Anonymnímu výzkumníkovi, spolupracujícímu se společností [VeriSign iDefense Labs](http://labs.idefense.com/), za oznámení chyby popsané v bulletinu MS12-034.
-   Anonymnímu výzkumníkovi, spolupracujícímu se společností [VeriSign iDefense Labs](http://labs.idefense.com/), za oznámení chyby popsané v bulletinu MS12-034.
-   Alexi Plaskettovi ze společnosti [MWR InfoSecurity](http://www.mwrinfosecurity.com/) za oznámení chyby popsané v bulletinu MS12-034.
-   Tarjei Mandtovi ze společnosti [Azimuth Security](http://www.azimuthsecurity.com/) za oznámení chyby popsané v bulletinu MS12-034.
-   Nicolasi Economou ze společnosti [Core Security Technologies](http://www.coresecurity.com/) za oznámení chyby popsané v bulletinu MS12-034.
-   Geoffu McDonaldovi ze společnosti Symantec za oznámení chyby popsané v bulletinu MS12-034.
-   Uživateli h4ckmp za oznámení chyby popsané v bulletinu MS12-034.
-   Jamesi Forshawovi ze společnosti [Context Information Security](http://www.contextis.co.uk/) za oznámení dvou chyb popsaných v bulletinu MS12-035.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Řešení zabezpečení pro odborníky v oboru informačních technologií: [Řešení potíží a podpora zabezpečení na webu TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Ochraňte svůj počítač se systémem Windows před hrozbou virů a malwaru: [Centrum pomoci o bezpečnosti a ochraně před viry](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Místní podpora dostupná ve vaší zemi: [Mezinárodní podpora](http://support.microsoft.com/common/international.aspx)

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (8. května 2012): Souhrnný bulletin byl publikován.
-   V1.1 (9. května 2012): V **indexu zneužitelnosti** byl změněn název chyby zabezpečení CVE-2012-1847.
-   V2.0 (11. května 2012): U bulletinu MS12-035 došlo k opravě čísla aktualizace zabezpečení na KB2656353 pro všechny podporované systémy s rozhraním Microsoft .NET Framework 1.1 Service Pack 1 s výjimkou systémů Windows Server 2003 Service Pack 2. Nebyly provedeny žádné změny souborů aktualizace zabezpečení. Zákazníci, kteří již aktualizaci úspěšně nainstalovali, nemusí podnikat žádná opatření.
-   V2.1 (22. května 2012): U bulletinu MS12-034 byly přidány poznámky k aktualizaci zabezpečení KB2660649 pro systém Windows Server 2008 a Windows Server 2008 R2. Nebyly provedeny žádné změny souborů aktualizace zabezpečení. Zákazníci, kteří již aktualizaci úspěšně nainstalovali, nemusí podnikat žádná opatření.

*Built at 2014-04-18T01:50:00Z-07:00*
