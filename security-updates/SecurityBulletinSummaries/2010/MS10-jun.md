---
TOCTitle: 'MS10-JUN'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, červen 2010'
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61224000
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms10-jun(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, červen 2010
================================================================

Publikováno: 8. června 2010 | Aktualizováno: 13. září 2011

**Verze:** 2.0

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v červnu 2010.

Spolu s vydáním bulletinů pro červen 2010 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 3. června 2010. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání 9. června 2010 v 11:00 časového pásma Tichomoří (USA a Kanada). [Zaregistrovat pro webové vysílání týkající se červnových bulletinů zabezpečení](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení před jakýmikoli důležitými aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení při dekompresi médií umožňují vzdálené spuštění kódu (979902)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě soukromými osobami oznámené chyby zabezpečení v systému Microsoft Windows. Tyto chyby zabezpečení mohou umožnit vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený mediální soubor nebo obdrží speciálně vytvořený obsah vysílání datového proudu médií z webové stránky nebo jakékoli aplikace poskytující webový obsah. Útočník, který by úspěšně zneužil tyto chyby zabezpečení, by mohl získat stejná uživatelská práva, jaká má místní uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení dezaktivačních bitů ActiveX (980195)</strong><br />
<br />
Tato aktualizace zabezpečení se týká dvou soukromě oznámených chyb zabezpečení softwaru Microsoft. Tato aktualizace zabezpečení má kritický stupeň závažnosti pro všechny podporované edice systému Microsoft Windows 2000, Windows XP, Windows Vista a Windows 7 a mírný stupeň závažnosti pro všechny podporované edice systému Windows Server 2003, Windows Server 2008 a Windows Server 2008 R2.<br />
<br />
Tyto chyby zabezpečení mohou umožnit vzdálené spuštění kódu, pokud uživatel pomocí aplikace Internet Explorer zobrazí speciálně vytvořenou webovou stránku, jež vytváří instanci konkrétního ovládacího prvku ActiveX. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. Tato aktualizace také obsahuje dezaktivační bity pro čtyři ovládací prvky ActiveX jiných výrobců.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (982381)</strong><br />
<br />
Tato aktualizace zabezpečení řeší pět chyb zabezpečení oznámených soukromými osobami a jednu veřejně známou chybu zabezpečení v aplikaci Internet Explorer. Nejzávažnější chyby zabezpečení mohou umožnit vzdálené spuštění kódu, pokud uživatel pomocí aplikace Internet Explorer zobrazí speciálně vytvořenou webovou stránku. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v ovladačích režimu jádra systému Windows umožňují zvýšení úrovně oprávnění (979559)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě veřejně oznámené chyby zabezpečení a jednu soukromě oznámenou chybu zabezpečení v ovladačích režimu jádra systému Windows. Tyto chyby zabezpečení by mohly umožnit zvýšení úrovně oprávnění, pokud by uživatel zobrazil obsah ve speciálně vytvořeném písmu TrueType.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení při ověřování objektů COM v systému Microsoft Office umožňuje vzdálené spuštění kódu (983235)</strong><br />
<br />
Tato aktualizace zabezpečení řeší soukromě oznámenou chybu zabezpečení při ověřování objektů COM v systému Microsoft Office. Tato chyba umožňuje vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor aplikace Excel, Word, Visio, Publisher nebo PowerPoint pomocí verze systému Microsoft Office obsahující tuto chybu. Tuto chybu nelze automaticky zneužít pomocí e-mailu. Aby byl útok úspěšný, musí uživatel otevřít přílohu, která je odeslána v e-mailové zprávě.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v ovladači písma OpenType formátu CFF (Compact Font Format) umožňuje zvýšení úrovně oprávnění (980218)</strong><br />
<br />
Tato aktualizace zabezpečení řeší soukromě oznámenou chybu zabezpečení v ovladači písma OpenType formátu CFF (Compact Font Format). Tato chyba zabezpečení by mohla umožnit zvýšení úrovně oprávnění, pokud by uživatel zobrazil obsah ve speciálně vytvořeném písmu CFF. Tuto chybu může zneužít pouze útočník s platnými pověřeními pro přihlášení, která by mu umožňovala se místně přihlásit. Tuto chybu zabezpečení nemohou zneužít vzdálení ani anonymní uživatelé.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v aplikaci Microsoft Office Excel umožňují vzdálené spuštění kódu (2027452)</strong><br />
<br />
Tato aktualizace zabezpečení řeší čtrnáct soukromě oznámených chyb zabezpečení v systému Microsoft Office. Závažnější chyby zabezpečení mohou umožnit vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor aplikace Excel. Útočník, který by úspěšně zneužil některou z těchto chyb zabezpečení, by mohl získat stejná uživatelská práva, jaká má místní uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení ve službě Microsoft SharePoint umožňují zvýšení úrovně oprávnění (2028554)</strong><br />
<br />
Tato aktualizace zabezpečení řeší jednu veřejně oznámenou a dvě soukromě oznámené chyby zabezpečení služby Microsoft SharePoint. Nejzávažnější chyba zabezpečení by mohla umožnit zvýšení úrovně oprávnění, pokud by útočník přesvědčil uživatele cílového webu služby SharePoint, aby klikl na speciálně vytvořený odkaz.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení Internetové informační služby umožňuje vzdálené spuštění kódu (982666)</strong><br />
<br />
Tato aktualizace zabezpečení řeší soukromě oznámenou chybu zabezpečení Internetové informační služby (IIS). Tato chyba zabezpečení může umožnit vzdálené spuštění kódu, pokud uživatel přijme speciálně vytvořený požadavek HTTP. Útočník, který by tuto chybu zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v rozhraní Microsoft .NET Framework může umožnit manipulaci (981343)</strong><br />
<br />
Tato aktualizace zabezpečení řeší veřejně oznámenou chybu zabezpečení v rozhraní Microsoft .NET Framework. Tato chyba zabezpečení by mohla umožnit manipulaci s daty v podepsaném obsahu XML, aniž by byla zjištěna. Ve vlastních aplikacích je dopad na zabezpečení závislý na způsobu použití podepsaného obsahu v konkrétní aplikaci. Scénáře, ve kterých jsou podepsané zprávy XML přenášeny zabezpečeným kanálem (například protokolem SSL), nejsou touto chybou zabezpečení ovlivněny.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Vysoký</a><br />
Manipulace</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
<p></p>
  
Index zneužitelnosti  
--------------------
  

Následující tabulka uvádí hodnocení zneužitelnosti každé chyby zabezpečení uvedené v tomto měsíci. Chyby zabezpečení jsou řazeny v pořadí zmenšující se úrovně posouzení zneužitelnosti, jinak než tomu je u řazení podle čísla chyb. Uvedeny jsou pouze chyby zabezpečení ohodnocené stupněm závažnosti Kritický nebo Vysoký.
  
**Jak pracovat s touto tabulkou**
  
V této tabulce zjistíte, jaká je pravděpodobnost vydání funkčního zneužitelného kódu během 30 dní od vydání tohoto bulletinu zabezpečení pro všechny aktualizace zabezpečení, které bude třeba nainstalovat. Všechna níže uvedená hodnocení zvažte na základě vaší specifické konfigurace a podle závěrů hodnocení nastavte priority pro zavádění jednotlivých aktualizací. Další informace o významu těchto hodnocení a způsobu jejich stanovení najdete v indexu zneužitelnosti [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID bulletinu                                              | Název chyby zabezpečení                                                                        | ID CVE                                                                           | Hodnocení indexu zneužitelnosti                                                                                                | Hlavní poznámky                                                                                                                                                         |  
|-----------------------------------------------------------|------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Chyba zabezpečení při vytváření oken subsystému Win32k                                         | [CVE-2010-0485](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Chyba zabezpečení týkající se skriptování mezi servery souboru Help.aspx                       | [CVE-2010-0817](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | Tato chyba zabezpečení byla poprvé oznámena v [informačním zpravodaji zabezpečení společnosti Microsoft 983438](http://technet.microsoft.com/security/advisory/983438). |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se přetečení zásobníku objektů aplikace Excel                       | [CVE-2010-0822](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti záznamů aplikace Excel                          | [CVE-2010-0824](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti záznamů aplikace Excel                          | [CVE-2010-1245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti při zpracování dat RTD v aplikaci Excel         | [CVE-2010-1246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti aplikace Excel                                  | [CVE-2010-1247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti při zpracování záznamu HFPicture aplikace Excel | [CVE-2010-1248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti aplikace Excel                                  | [CVE-2010-1249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti při zpracování záznamu EDG aplikace Excel       | [CVE-2010-1250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se objektu ADO aplikace Excel                                       | [CVE-2010-1253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se oprávnění formátu Open XML systému Mac Office                    | [CVE-2010-1254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Chyba zabezpečení týkající se poškození neinicializované paměti                                | [CVE-2010-1259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Chyba zabezpečení týkající se poškození paměti                                                 | [CVE-2010-1262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-036](http://go.microsoft.com/fwlink/?linkid=190554) | Chyba zabezpečení při ověřování objektu COM                                                    | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Chyba zabezpečení při dekompresi médií                                                         | [CVE-2010-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní zneužití kódu je pravděpodobné               | (Žádné)                                                                                                                                                                 |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Chyba zabezpečení týkající se zpřístupnění informací při přechodu mezi doménami                | [CVE-2010-0255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | Tato chyba zabezpečení byla poprvé oznámena v [informačním zpravodaji zabezpečení společnosti Microsoft 980088](http://technet.microsoft.com/security/advisory/980088). |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Chyba zabezpečení týkající se nesprávného ověřování dat subsystému Win32k                      | [CVE-2010-0484](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-037](http://go.microsoft.com/fwlink/?linkid=190508) | Chyba zabezpečení týkající se poškození paměti ovladače písma OpenType formátu CFF             | [CVE-2010-0819](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti při analýze záznamů aplikace Excel              | [CVE-2010-0821](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození paměti aplikace Excel                                  | [CVE-2010-0823](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se poškození zásobníku záznamů aplikace Excel                       | [CVE-2010-1251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Chyba zabezpečení týkající se proměnné řetězce aplikace Excel                                  | [CVE-2010-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Chyba zabezpečení při analýze písma TrueType subsystému Win32k                                 | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-040](http://go.microsoft.com/fwlink/?linkid=191788) | Chyba zabezpečení týkající se poškození paměti při ověřování služby IIS                        | [CVE-2010-1256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Chyba zabezpečení při dekompresi médií formátu MJPEG                                           | [CVE-2010-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Je pravděpodobné vytvoření kódu nekonsistentního zneužití | (Žádné)                                                                                                                                                                 |  
| [MS10-041](http://go.microsoft.com/fwlink/?linkid=185042) | Chyba zabezpečení související s obejitím ověření oříznutí algoritmu HMAC podpisu XML           | [CVE-2009-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení umožňující vkládání falešného obsahu a manipulaci s daty                                                                                   |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Chyba zabezpečení týkající se zpřístupnění informací metody toStaticHTML                       | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Vytvoření funkčního zneužitelného kódu není pravděpodobné | Tato chyba zabezpečení má rovněž vliv na bulletin [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905)                                                             |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Chyba zabezpečení týkající se zpřístupnění informací metody toStaticHTML                       | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Vytvoření funkčního zneužitelného kódu není pravděpodobné | Tato chyba zabezpečení má rovněž vliv na bulletin [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898)                                                             |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Chyba zabezpečení týkající se odmítnutí služby na stránce s nápovědou služby SharePoint        | [CVE-2010-1264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Vytvoření funkčního zneužitelného kódu není pravděpodobné | (Žádné)                                                                                                                                                                 |
  
Software obsahující tuto chybu a umístění aktualizací ke stažení  
----------------------------------------------------------------
  

Následující tabulky řadí bulletiny podle kategorie hlavního softwaru a závažnosti.
  
**Jak pracovat s těmito tabulkami?**
  
V těchto tabulkách zjistíte, které aktualizace zabezpečení bude třeba nainstalovat. Přečtěte si seznam všech programů a komponent a zjistěte, zda se některé aktualizace zabezpečení týkají vaší instalace. Pokud se program nebo komponenta v seznamu nachází, je v něm zároveň uveden odkaz na dostupnou aktualizaci softwaru a také stupeň závažnosti aktualizace softwaru.
  
**Poznámka:** Jedna chyba zabezpečení může vyžadovat instalaci více aktualizací. Přečtěte si celý sloupec u každého identifikátoru bulletinu. Zjistíte v něm, které aktualizace je třeba nainstalovat v závislosti na programech nebo součástech nainstalovaných ve vašem systému.
  
#### Operační systém Windows a jeho komponenty

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádný
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow) (DirectX 9)](http://www.microsoft.com/downloads/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a)<sup>[1]</sup>
(KB975562)  
(Kritický)  
[Windows Media Format Runtime 9](http://www.microsoft.com/downloads/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2)<sup>[2]</sup>
(KB978695)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Vysoký)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527)  
(Stupeň závažnosti není určen)<sup>[1]</sup>
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádný
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 a Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5)  
(KB975562)  
(Kritický)  
Pouze Windows XP Service Pack 2:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 a Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3)  
(KB978695)  
(Kritický)  
Pouze Windows XP Service Pack 3:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 a Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085)  
(KB978695)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Vysoký)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4)  
(Kritický)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c)  
(Kritický)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Pouze Windows XP Media Center Edition 2005:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(Vysoký)  
Pouze Windows XP Media Center Edition 2005 a Windows XP Tablet PC Edition 2005:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(Vysoký)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
(Kritický)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
(Kritický)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(Kritický)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(Vysoký)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(Vysoký)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
(Kritický)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
(Kritický)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad) (KB979909)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a)  
(KB975562)  
(Kritický)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5)  
(KB978695)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Vysoký)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f)  
(Mírný)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c)  
(Mírný)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c)  
(KB979907)  
(Vysoký)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe)  
(KB975562)  
(Kritický)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163)  
(KB978695)  
(Kritický)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(Vysoký)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(Vysoký)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6)  
(Mírný)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070)  
(Mírný)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
(Mírný)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 a Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Pouze Windows Vista Service Pack 1:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6)  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3)  
(KB979482)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf)  
(KB979332)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4)  
(Kritický)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
Pouze Windows Vista Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Vysoký)  
Pouze Windows Vista Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Vysoký)  
Pouze Windows Vista Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb) (KB979910)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Pouze Windows Vista x64 Edition Service Pack 1:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c)  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06)  
(KB979482)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f)  
(KB979332)  
(Vysoký)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33)  
(KB979332)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5)  
(Kritický)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
Pouze Windows Vista x64 Edition Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Vysoký)  
Pouze Windows Vista x64 Edition Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Vysoký)  
Pouze Windows Vista x64 Edition Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
Pouze Windows Server 2008 pro 32bitové systémy:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9)\*\*  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e)\*  
(KB979482)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171)\*\*  
(KB979332)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e)\*\*  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc)\*\*  
(Mírný)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385)\*\*  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d)\*<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(Vysoký)  
Pouze Windows Server 2008 pro 32bitové systémy:  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(Vysoký)  
Pouze Windows Server 2008 pro 32bitové systémy:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(Vysoký)  
Pouze Windows Server 2008 pro 32bitové systémy Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
Pouze Windows Server 2008 pro systémy s procesorem x64:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731)\*\*  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c)\*  
(KB979482)  
(Kritický)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6)\*\*  
(KB979332)  
(Vysoký)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3)\*\*  
(KB979332)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1)\*\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e)\*\*  
(Mírný)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91)\*\*  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706)\*<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem x64:  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem x64:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem x64 Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Pouze Windows Server 2008 pro systémy s procesorem Itanium:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
(Kritický)  
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913)<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem Itanium:  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem Itanium:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Vysoký)  
Pouze Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 pro 32bitové systémy
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330)\*  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77)\*\*  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0)\*\*  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)\*  
(KB979916)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (součást objektu COM)](http://www.microsoft.com/downloads/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Internetová informační služba 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámky k systémům Windows Server 2008 a Windows Server 2008 R2**

**\*Instalace Server Core obsahující chybu zabezpečení.** Tato aktualizace se stejným hodnocením závažnosti se vztahuje k podporovaným edicím systému Windows Server 2008 nebo Windows Server 2008 R2, jak je uvedeno, s instalací pomocí volby pro instalaci Server Core nebo bez ní. Další informace o této možnosti instalace naleznete v článcích na webu služby MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) a [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008 a Windows Server 2008 R2; další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalace Server Core není touto chybou ovlivněna.** Chyby zabezpečení, které tato aktualizace řeší, nemají vliv na podporované edice systému Windows Server 2008 nebo Windows Server 2008 R2, jak je uvedeno, v případě instalace s využitím možnosti instalace Server Core. Další informace o této možnosti instalace naleznete v článcích na webu služby MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) a [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008 a Windows Server 2008 R2; další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Poznámka k bulletinu MS10-033**

<sup>[1]</sup>Aktualizace knihovny Quartz.dll (Direct Show) (DirectX 9) se týká rovněž rozhraní DirectX 9.0a, DirectX 9.0b a DirectX 9.0c.

<sup>[2]</sup>Tento balíček aktualizace se týká součásti Windows Media Format 9 SDK Runtime v systému Microsoft Windows 2000 obsahující aktualizaci pro přehrávače médií s technologií DRM (KB891122). Další informace získáte v [článku 974316 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/974316).

<sup>[3]</sup>Pokud jste nainstalovali součást Windows Media Format Runtime 9.5 x64 Edition, je nutné nainstalovat bezpečnostní aktualizace součástí Windows Media Format Runtime 9.5 a Windows Media Format Runtime 9.5 x64 Edition, abyste dosáhli plné ochrany před chybou zabezpečení popsanou v bulletinu MS10-033.

**Poznámka k bulletinu MS10-035**

<sup>[1]</sup>U této aktualizace není určen stupeň závažnosti, neboť chyby zabezpečení uvedené v tomto bulletinu se netýkají tohoto softwaru. Tato aktualizace zabezpečení však nabízí opravu problému s regresí vztahujícího se k bulletinu [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979). Podrobnosti naleznete v bulletinu [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898).

**Poznámka k bulletinu MS10-040**

<sup>[1]</sup>Tento operační systém obsahuje danou chybu zabezpečení pouze v případě, že je nainstalována Rozšířená ochrana pro ověřování. Další informace naleznete v [článku 973917 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/973917).

#### Sady Microsoft Office a jejich software

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Sady Microsoft Office, systémy a komponenty
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádný
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3<sup>[1]</sup>
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f)  
(KB982299)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3)  
(KB982311)  
(Vysoký)  
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)<sup>[2]</sup>
(KB982133)  
(Vysoký)  
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc)<sup>[2]</sup>
(KB982157)  
(Vysoký)  
[Microsoft Office Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4)<sup>[2]</sup>
(KB982122)  
(Vysoký)  
[Microsoft Office Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a)<sup>[2]</sup>
(KB982126)  
(Vysoký)  
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245)<sup>[2]</sup>
(KB982134)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)  
(KB982133)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Systém Microsoft Office 2007 Service Pack 1 a systém Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Systém Microsoft Office 2007 Service Pack 1 a systém Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167)  
(KB982312)  
(Vysoký)  
[Microsoft Office Excel 2007 Service Pack 1 a Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[3]</sup>
(KB982308)  
(Vysoký)  
[Microsoft Office PowerPoint 2007 Service Pack 1 a Microsoft Office PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a)<sup>[3]</sup>
(KB982158)  
(Vysoký)  
[Microsoft Office Publisher 2007 Service Pack 1 a Microsoft Office Publisher 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65)<sup>[3]</sup>
(KB982124)  
(Vysoký)  
[Microsoft Office Visio 2007 Service Pack 1 a Microsoft Office Visio 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b)<sup>[3]</sup>
(KB982127)  
(Vysoký)  
[Microsoft Office Word 2007 Service Pack 1 a Microsoft Office Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755)<sup>[3]</sup>
(KB982135)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 a Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[1]</sup>
(KB982308)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádný
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádný
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Otevření nástroje XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Otevření nástroje XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Jiný software systému Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádný
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 1 a Microsoft Office Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 a Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a)  
(KB982333)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1 a sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1 a sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0)  
(KB982331)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336)  
(KB980923)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 Service Pack 1 a Microsoft Office InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 Service Pack 1 a Microsoft Office InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6)  
(KB979441)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 1 a Microsoft Office SharePoint Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(Vysoký)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(Vysoký)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(Vysoký)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64bitové edice)](http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámky k bulletinu MS10-036**

<sup>[1]</sup>Není k dispozici žádná aktualizace. Další informace naleznete v bulletinu.

<sup>[2]</sup>Navíc k této aktualizaci je třeba, aby si zákazníci také nainstalovali aktualizaci pro systém Microsoft Office 2003 Service Pack 3 (KB982311), která zajišťuje ochranu před chybou zabezpečení popisovanou v tomto bulletinu.

<sup>[3]</sup>Navíc k této aktualizaci je třeba, aby si zákazníci také nainstalovali aktualizaci pro systém Microsoft Office 2007 Service Pack 1 a Microsoft Office 2007 Service Pack 2 (KB982312), která zajišťuje ochranu před chybou zabezpečení popisovanou v tomto bulletinu.

**Poznámka k bulletinu MS10-038**

<sup>[1]</sup>Navíc k této aktualizaci je třeba, aby si zákazníci také nainstalovali aktualizaci zabezpečení pro sadu Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 s aktualizací Service Pack 1 a pro sadu Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 s aktualizací Service Pack 2 (KB982308), která zajišťuje ochranu před chybami zabezpečení popisovanými v tomto bulletinu.

**Poznámky k bulletinu MS10-039**

<sup>[1]</sup>Kromě balíčku aktualizací zabezpečení KB979445 je u podporovaných edicí aplikace Microsoft Office SharePoint Server 2007 třeba, aby si zákazníci nainstalovali aktualizaci zabezpečení pro službu Microsoft Windows SharePoint Services 3.0 (KB983444), která zajišťuje ochranu před chybami zabezpečení popisovanými v tomto bulletinu.

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

#### Microsoft Server Software

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Důležitý**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 1 a Microsoft Windows SharePoint Services 3.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 a Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32bitové verze)](http://www.microsoft.com/downloads/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783)  
(KB983444)  
(Vysoký)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 a Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64bitové verze)](http://www.microsoft.com/downloads/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f)  
(KB983444)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámka k bulletinu MS10-039**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------


**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat kliknutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Poznámka:** K 1. srpnu 2009 ukončí společnost Microsoft podporu webu Office Update a nástroje Office Update Inventory Tool. Nejnovější aktualizace produktů Microsoft Office bude přinášet web [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Další informace naleznete v části [O webu Microsoft Office Update: Nejčastější dotazy](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Doporučené postupy zjišťování a instalace**

Společnost Microsoft poskytuje doporučené postupy zjišťování a nasazení aktualizací zabezpečení. Tyto dokumenty obsahují doporučení a informace, které mohou odborníkům v oblasti IT pomoci porozumět, jak se používají různé nástroje pro detekci a nasazení aktualizací zabezpečení. Další informace získáte v [článku 961747 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Nástroj Microsoft Baseline Security Analyzer**

Pomocí nástroje Microsoft Baseline Security Analyzer (MBSA) mohou správci prohledávat místní i vzdálené systémy a zjistit tak, jestli v nich nechybí některé aktualizace zabezpečení nebo jestli v nastavení zabezpečení systému nedošlo k některým běžným chybám. Další informace o nástroji MBSA získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Služba Windows Server Update Services**

Pomocí služby Windows Server Update Services (WSUS) mohou správci systémů rychle a spolehlivě nasadit nejnovější důležité aktualizace zabezpečení pro systémy Microsoft Windows 2000 a novější, systém Office XP a novější, Exchange Server 2003 a SQL Server 2000 do systémů Microsoft Windows 2000 a novějších.

Další informace o způsobu instalace této aktualizace zabezpečení pomocí služby Windows Server Update Services získáte na webu služby [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) představuje v rozlehlých sítích řešení pro správu aktualizací s rozsáhlými možnostmi konfigurace. Umožňuje správcům identifikovat počítače se systémem Windows, které vyžadují aktualizace zabezpečení, a provést řízenou instalaci těchto aktualizací v celé rozlehlé síti s minimálním dopadem na koncové uživatele. K dispozici je nyní nová verze nástroje SMS, System Center Configuration Manager 2007 (viz také webové stránky produktu [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Další informace o tom, jak mohou správci pomocí serveru SMS 2003 nasazovat aktualizace zabezpečení, získáte na webu [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Uživatelé služby SMS 2.0 mohou k nasazení aktualizací zabezpečení použít také nástroj SUIT (Security Update Inventory Tool). Další informace o serveru SMS získáte na webu [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Poznámka:** Služba SMS pomocí modulu Microsoft Baseline Security Analyzer poskytuje rozsáhlou podporu při zjišťování a nasazení aktualizací bulletinu zabezpečení. Tyto nástroje nemusí některé softwarové aktualizace zjistit. V takovém případě mohou správci použít funkce serveru SMS a nasměrovat aktualizace do určitých systémů. Další informace o tomto postupu najdete na webu [Nasazení aktualizací softwaru pomocí funkce Distribuce softwaru serveru SMS](http://go.microsoft.com/fwlink/?linkid=33341). Některé aktualizace zabezpečení vyžadují po restartování počítače oprávnění správce. Správci mohou k instalaci těchto aktualizací použít nástroj Elevated Rights Deployment Tool (k dispozici v sadě [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Nástroj Update Compatibility Evaluator a sada Application Compatibility Toolkit**

Aktualizace často zapisují do stejných souborů a nastavení registru požadovaných pro spouštění aplikací. To může způsobit nekompatibilitu a zvýšit dobu, po kterou trvá nasazení aktualizací zabezpečení. Testování a ověřování aktualizací systému Windows lze usnadnit pomocí součástí nástroje [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), které jsou dodávány se sadou [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sada Application Compatibility Toolkit (ACT) obsahuje nezbytné nástroje a dokumentaci pro posouzení a zmírnění problémů s kompatibilitou aplikací před nasazením systému Microsoft Windows Vista, služby Windows Update, aktualizací zabezpečení společnosti Microsoft nebo nové verze aplikace Windows Internet Explorer ve vašem prostředí.

### Další informace

#### Nástroj pro odstranění škodlivého softwaru systému Microsoft Windows

Společnost Microsoft vydává aktualizovanou verzi Nástroje pro odstranění škodlivého softwaru systému Microsoft Windows na webu Windows Update, Microsoft Update, ve službě Windows Server Update Services a na webu služby Stažení softwaru.

#### Důležité aktualizace nesouvisející se zabezpečením na webu Microsoft Update (MU), Windows Update (WU) a ve službě Windows Server Update Services (WSUS)

Informace o aktualizacích nesouvisejících se zabezpečením na webu Windows Update a Microsoft Update naleznete na webové stránce:

-   [Článek 894199 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Popis služeb Software Update Services a Windows Server Update Services se mění v obsahu. Zahrnuje celý obsah systému Windows.
-   [Aktualizace vydané v uplynulých měsících pro službu Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Obsahuje přehled všech nových, revidovaných a opětovně vydaných aktualizací pro jiné produkty společnosti Microsoft, než je systém Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Pro zlepšení ochrany dat svých zákazníků poskytuje společnost Microsoft informace o chybách v zabezpečení všem hlavním dodavatelům softwaru pro zabezpečení, a to vždy ještě před vydáním nové měsíční zprávy o aktualizaci zabezpečení. Dodavatelé softwaru pro zabezpečení tak mohou tyto informace o chybách v zabezpečení využít a poskytnout svým zákazníkům ochranu včasnou aktualizací svých programů a zařízení pro zabezpečení, jako jsou antivirové programy, síťové systémy pro detekci napadení či hostitelské systémy pro prevenci napadení. Informace o dostupnosti aktuálních prostředků aktivní ochrany od jednotlivých dodavatelů softwaru pro zabezpečení naleznete na stránkách aktivní ochrany jednotlivých partnerů programu MAPP. Seznam těchto partnerů naleznete na stránce [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Strategie zabezpečení a komunita

**Strategie instalace aktualizací**

Web [Doporučené postupy zabezpečení pro správu aktualizací (Security Guidance for Update Management)](http://go.microsoft.com/fwlink/?linkid=21168) obsahuje další informace o instalaci aktualizací zabezpečení podle doporučení společnosti Microsoft.

**Získání dalších aktualizací zabezpečení**

Aktualizace odstraňující další problémy se zabezpečením získáte v následujících umístěních:

-   Aktualizace zabezpečení jsou k dispozici na webu služby [Stažení softwaru (Microsoft Download Center)](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.
-   Aktualizace pro klientské platformy jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizace zabezpečení nabízené tento měsíc na webu Windows Update jsou k dispozici na webu služby Stažení softwaru v souborech obrazu ISO disku CD s vydanými aktualizacemi zabezpečení a kritickými aktualizacemi. Další informace získáte v [článku 913086 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Komunita odborníků v oblasti zabezpečení**

Můžete se zde naučit, jak zlepšit zabezpečení a jak optimalizovat infrastrukturu IT. Také můžete s dalšími členy komunity IT Pro diskutovat o bezpečnostních tématech na webu [Komunita odborníků v oblasti zabezpečení (IT Pro Security Community)](http://go.microsoft.com/fwlink/?linkid=21164).

#### Poděkování

Společnost Microsoft tímto [děkuje](http://go.microsoft.com/fwlink/?linkid=21127) za spolupráci při ochraně zákazníků:

-   Sebastienu Renaudovi ze skupiny [VUPEN Vulnerability Research Team](http://www.vupen.com/) za oznámení chyby popsané v bulletinu MS10-032.
-   Společnosti [Secunia Research](http://secunia.com/) za spolupráci na řešení chyby popsané v bulletinu MS10-032.
-   Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení dvou chyb popsaných v bulletinu MS10-033.
-   Shaunu Colleymu ze společnosti [NGS Software](http://www.ngssoftware.com/) za oznámení chyby popsané v bulletinu MS10-034.
-   Chrisi Riesovi z výpočetních služeb univerzity Carnegie Mellon za oznámení chyby popsané v bulletinu MS10-034.
-   Chrisi Weberovi ze společnosti [Casaba Security](http://www.casabasecurity.com/) za oznámení chyby popsané v bulletinech MS10-035 a MS10-039.
-   Takeshimu Teradovi ze společnosti [Mitsui Bussan Secure Directions, Inc.](http://www.mbsd.jp/) za oznámení chyby popsané v bulletinu MS10-035.
-   Michalu Zalewskému ze společnosti [Google Inc.](http://www.google.com/) za oznámení chyby popsané v bulletinu MS10-035.
-   Chrisu Rohlfovi ze společnosti [Matasano Security](http://www.matasano.com/) za oznámení dvou chyb popsaných v bulletinu MS10-035.
-   Peteru Vreugdenhilovi, spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [TippingPoint](http://www.tippingpoint.com/), za oznámení chyby popsané v bulletinu MS10-035.
-   Davidovi Deweymu ze společnosti [IBM ISS X-Force](http://www.iss.net/) a Ryanu Smithovi ze společnosti [Accuvant](http://www.accuvant.com/), dříve [VeriSign iDefense Labs](http://labs.idefense.com/), za spolupráci na změnách zvyšujících zabezpečení zahrnutých v bulletinu MS10-036.
-   Chrisu Cartonovi ze společnosti Laserforce International, spolupracujícímu se společností [Secunia](http://secunia.com/), za oznámení chyby popsané v bulletinu MS10-037.
-   Anonymnímu výzkumníkovi spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [TippingPoint](http://www.tippingpoint.com/) za oznámení chyby popsané v bulletinu MS10-038.
-   Nicolasi Jolymu ze skupiny [VUPEN Vulnerability Research Team](http://www.vupen.com/) za oznámení osmi chyb popsaných v bulletinu MS10-038.
-   Bingu Liuovi z výzkumného týmu [FortiGuard Labs společnosti Fortinet](http://www.fortiguard.com/) za oznámení chyby popsané v bulletinu MS10-038.
-   Carstenu Eiramovi ze společnosti [Secunia](http://secunia.com/) za oznámení dvou chyb popsaných v bulletinu MS10-038.
-   Anonymnímu výzkumníkovi spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti [TippingPoint](http://www.tippingpoint.com/) za oznámení chyby popsané v bulletinu MS10-038.
-   Rickovi Glaspiemu ze školního obvodu Gilbert Public Schools v Gilbertu v Arizoně za oznámení chyby popsané v bulletinu MS10-038.
-   Riku Jonesovi z instituce Dallas County Community College District za oznámení chyby popsané v bulletinu MS10-039.
-   Arianu Evansovi ze společnosti [WhiteHat Security](http://www.whitehatsec.com) za oznámení chyby související s obejitím funkce ověřování požadavků ASP.NET, která je řešena v bulletinu MS10-041 důkladnou změnu zvyšující zabezpečení.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné. Další informace o dostupných možnostech technické podpory naleznete na webu [Pomoc a podpora společnosti Microsoft](http://support.microsoft.com/).
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   Verze 1.0 (8. června 2010): Souhrnný bulletin byl publikován.
-   V1.1 (9. června 2010): Revidovány poznámky k bulletinu MS10-033 v části **Software obsahující tuto chybu a umístění aktualizací ke stažení**.
-   V2.0 (13. září 2011): Byl znovu vydán bulletin MS10-035, aby znovu nabídl aktualizace pro aplikaci Internet Explorer v systémech Microsoft Windows 2000 a Windows XP, které řeší chybu detekce. Nebyly provedeny žádné změny souborů aktualizace zabezpečení. Zákazníci, kteří svůj systém již úspěšně aktualizovali, nemusejí podnikat žádná opatření.

*Built at 2014-04-18T01:50:00Z-07:00*
