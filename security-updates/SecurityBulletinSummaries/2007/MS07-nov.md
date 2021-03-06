---
TOCTitle: 'MS07-NOV'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, listopad 2007'
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61223967
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms07-nov(v=Security.10)'
---

Souhrnný bulletin zabezpečení společnosti Microsoft, listopad 2007
==================================================================

Publikováno: 13. listopadu 2007

**Verze:** 1.0

**Verze** 1.0

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v listopadu 2007.

Spolu s vydáním bulletinů pro listopad 2007 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 8. listopadu 2007. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání dne 14. listopadu 2007 v 11:00 časového pásma Tichomoří (USA a Kanada). [Registrovat se pro webové vysílání týkající se listopadových bulletinů zabezpečení](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení před jakýmikoli důležitými aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

### Informace o bulletinech

#### Shrnutí

Bulletiny zabezpečení podle závažnosti:

Kritický (1)
------------


| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS07-061                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení při zpracování identifikátorů URI v systému Windows umožňuje vzdálené spuštění kódu (943460)**](http://technet.microsoft.com/security/bulletin/ms07-061)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Shrnutí**                        | Tato aktualizace umožňuje odstranit veřejně oznámenou chybu zabezpečení. Byla zjištěna chyba zabezpečení umožňující vzdálené spuštění kódu ve způsobu, jakým prostředí Windows zpracovává speciálně vytvořené identifikátory URI, které mu jsou předány. Pokud prostředí Windows neověřilo tyto identifikátory URI dostatečným způsobem, mohl by útočník zneužít uvedenou chybu zabezpečení a spustit libovolný kód. Společnost Microsoft zjistila způsoby, kterými lze tuto chybu zabezpečení zneužít v systémech používajících aplikaci Internet Explorer 7. Chyba zabezpečení však byla zjištěna v souboru systému Windows Shell32.dll, který je součástí podporovaných vydání systémů Windows XP a Windows Server 2003. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace bude vyžadovat restartování počítače.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Software obsahující tuto chybu** | **Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

Vysoký (1)
----------


| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS07-062                                                                                                                                                                                                                                                                                                                 |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení serveru DNS umožňuje umístění falešného obsahu (941672)**](http://technet.microsoft.com/security/bulletin/ms07-062)                                                                                                                                                                                                                            |
| **Shrnutí**                        | Tato důležitá aktualizace řeší chybu zabezpečení oznámenou soukromou osobou. V serverech DNS systému Windows existuje chyba zabezpečení umožňující umísťování falešného obsahu, která by mohla útočníkovi umožnit odeslat speciálně vytvořené odpovědi na požadavky DNS a tím vložit falešný obsah nebo přesměrovat internetovou komunikaci z legitimního umístění. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                              |
| **Dopad této chyby zabezpečení**   | Vkládání falešného obsahu                                                                                                                                                                                                                                                                                                                                           |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Kromě určitých situací bude aktualizace vyžadovat restartování počítače.                                                                                                                                                                   |
| **Software obsahující tuto chybu** | **Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                      |

Software obsahující tuto chybu a umístění aktualizací ke stažení
----------------------------------------------------------------


**Jak pracovat s touto tabulkou**

V této tabulce zjistíte, které aktualizace zabezpečení bude třeba nainstalovat. Přečtěte si seznam všech programů a součástí a zjistěte, zda jsou u nich vyžadovány aktualizace zabezpečení. Pokud se program nebo součást v seznamu nachází, je u nich uveden dopad chyby zabezpečení s odkazem na příslušnou aktualizaci.

**Poznámka:** Jedna chyba zabezpečení může vyžadovat instalaci více aktualizací. Přečtěte si celý sloupec u každého identifikátoru bulletinu. Zjistíte v něm, které aktualizace nainstalovat v závislosti na programech nebo součástech nainstalovaných ve vašem systému.

**Software obsahující tuto chybu a umístění aktualizací ke stažení**

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Podrobnosti
</th>
<th style="border:1px solid black;" >
Podrobnosti
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS07-061**](http://technet.microsoft.com/security/bulletin/ms07-061)
</td>
<td style="border:1px solid black;">
[**MS07-062**](http://technet.microsoft.com/security/bulletin/ms07-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Důležité**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Operační systém Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Kritický](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Vysoký](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
</table>
 

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------


**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat klepnutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) a [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Doporučené postupy zjišťování a instalace**

Společnost Microsoft poskytla doporučené postupy zjišťování a instalace aktualizací zabezpečení vydaných tento měsíc. Tyto doporučené postupy by měly pomoci také odborníkům v oblasti IT při používání různých nástrojů při instalaci aktualizace zabezpečení, např. Windows Update, Microsoft Update, Office Update, nástroj MBSA (Microsoft Baseline Security Analyzer), nástroj pro rozpoznávání sady Office, Microsoft Systems Management Server (SMS) a nástroj Extended Security Update Inventory Tool (ESUIT). Další informace získáte v [článku 910723 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Nástroj Microsoft Baseline Security Analyzer**

Pomocí nástroje Microsoft Baseline Security Analyzer (MBSA) mohou správci prohledávat místní i vzdálené systémy a zjistit tak, jestli v nich nechybí některé aktualizace zabezpečení nebo jestli v nastavení zabezpečení systému nedošlo k některým běžným chybám. Další informace o nástroji MBSA získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Poznámka:** Po 9. říjnu 2007 už nebude aktualizován soubor MSSecure.XML používaný nástrojem MBSA 1.2.1. Po tomto datu nebudou do souboru MSSecure.XML používaného nástrojem MBSA 1.2.1 přidávány žádné nové aktualizace zabezpečení a nebudou vydávány nové verze nástroje EST. Toto řešení neovlivní nástroj SUIT (Security Update Inventory Tool) ani nástroj ESUIT (Extended Security Update Inventory Tool) u serveru SMS 2.0 a SMS 2003. Další informace získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Služba Windows Server Update Services**

Pomocí služby Windows Server Update Services (WSUS) mohou správci systémů rychle a spolehlivě instalovat nejnovější důležité aktualizace zabezpečení pro systémy Windows 2000 a novější, sadu Office XP a novější, Exchange Server 2003 a SQL Server 2000 do systémů Windows 2000 a novějších.

Další informace o způsobu instalace této aktualizace zabezpečení pomocí služby Windows Server Update Services získáte na webu služby [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) představuje v rozlehlých sítích řešení pro správu aktualizací s rozsáhlými možnostmi konfigurace. Umožňuje správcům identifikovat počítače se systémem Windows, které vyžadují aktualizace zabezpečení, a provést řízenou instalaci těchto aktualizací v celé rozlehlé síti s minimálním dopadem na koncové uživatele. Další informace o tom, jak mohou správci pomocí serveru SMS 2003 nasazovat aktualizace zabezpečení, získáte na webu [Správa oprav zabezpečení pomocí serveru SMS 2003 (SMS 2003 Security Patch Management)](http://go.microsoft.com/fwlink/?linkid=22939). Uživatelé serveru SMS 2.0 mohou při nasazení aktualizací zabezpečení použít také sadu [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340). Další informace o serveru SMS získáte na webu [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Poznámka:** Server SMS využívá nástroj MBSA (Microsoft Baseline Security Analyzer) a nástroj pro rozpoznávání sady Microsoft Office, a poskytuje tak širokou podporu pro zjišťování a instalaci aktualizací uvedených v bulletinech zabezpečení. Tyto nástroje nemusí některé softwarové aktualizace zjistit. V takovém případě mohou správci použít funkce serveru SMS a nasměrovat aktualizace do určitých systémů. Další informace o tomto postupu najdete na webu [Nasazení aktualizací softwaru pomocí funkce Distribuce softwaru serveru SMS](http://go.microsoft.com/fwlink/?linkid=33341). Některé aktualizace zabezpečení vyžadují po restartování počítače oprávnění správce. Správci mohou k instalaci těchto aktualizací použít nástroj Elevated Rights Deployment Tool (k dispozici v sadě [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) a [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

### Další informace

#### Nástroj pro odstranění škodlivého softwaru systému Microsoft Windows

Společnost Microsoft vydává aktualizovanou verzi Nástroje pro odstranění škodlivého softwaru systému Microsoft Windows na webu Windows Update, Microsoft Update, ve službě Windows Server Update Services a v centru pro stahování Download Center.

#### Důležité aktualizace nesouvisející se zabezpečením na webu Microsoft Update (MU), Windows Update (WU) a ve službě Windows Server Update Services (WSUS)

Tento měsíc:

-   Společnost Microsoft vydala tři důležité aktualizace **nesouvisející se zabezpečením** na webu Microsoft Update (MU) a ve službě Windows Server Update Services (WSUS).
-   Společnost Microsoft nevydala žádnou důležitou aktualizaci systému Windows **nesouvisející se zabezpečením** na webu Windows Update (WU).

Tato informace se týká **pouze** důležitých aktualizací **nesouvisejících se zabezpečením** na webu Microsoft Update, Windows Update a ve službě Windows Server Update Services vydaných ve stejný den jako souhrnný bulletin zabezpečení. Informace **se netýká** aktualizací **nesouvisejících se zabezpečením** vydaných v jiné dny.

#### Strategie zabezpečení a komunita

**Strategie instalace aktualizací**

Web [Doporučené postupy zabezpečení pro správu oprav (Security Guidance for Patch Management)](http://go.microsoft.com/fwlink/?linkid=21168) obsahuje další informace o instalaci aktualizací zabezpečení podle doporučení společnosti Microsoft.

**Získání dalších aktualizací zabezpečení**

Aktualizace odstraňující další problémy se zabezpečením získáte v následujících umístěních:

-   Aktualizace zabezpečení jsou k dispozici na webu služby [Stažení softwaru (Microsoft Download Center)](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.
-   Aktualizace pro klientské platformy jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizace zabezpečení nabízené tento měsíc na webu Windows Update jsou k dispozici na webu služby Stažení softwaru v souborech obrazu ISO disku CD s vydanými aktualizacemi zabezpečení a kritickými aktualizacemi. Další informace získáte v [článku 913086 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Komunita odborníků v oblasti zabezpečení**

Můžete se zde naučit, jak zlepšit zabezpečení a jak optimalizovat infrastrukturu IT. Také můžete s dalšími členy komunity IT Pro diskutovat o bezpečnostních tématech na webu [Komunita odborníků v oblasti zabezpečení (IT Pro Security Community)](http://go.microsoft.com/fwlink/?linkid=21164).

#### Poděkování

Společnost Microsoft tímto [děkuje](http://go.microsoft.com/fwlink/?linkid=21127) za spolupráci při ochraně zákazníků:

-   Jesperu Johanssonovi za spolupráci na řešení chyby popsané v bulletinu MS07-061.
-   Carstenu H. Eiramovi ze společnosti [Secunia](http://corporate.secunia.com/) za spolupráci na řešení chyby popsané v bulletinu MS07-061.
-   Avivu Raffovi ze společnosti [Finjan](http://www.finjan.com/) za spolupráci na řešení chyby popsané v bulletinu MS07-061.
-   Petku Petkovovi ze společnosti [GNUCITIZEN](http://www.gnucitizen.org/) za spolupráci na řešení chyby popsané v bulletinu MS07-061.
-   Allu Berzroutchkovi ze společnosti [Scanit](http://www.scanit.be/) za oznámení chyby popsané v bulletinu MS07-062.
-   Amitu Kleinovi ze společnosti [Trusteer](http://www.trusteer.com/) za oznámení chyby popsané v bulletinu MS07-062.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné.
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (13. listopadu 2007): Souhrnný bulletin byl publikován.

*Built at 2014-04-18T01:50:00Z-07:00*
