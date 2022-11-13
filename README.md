# Rasomware as a Masquerade (RaaM)
This repository aims to collect reports on malware that was masqueraded as ransomware. For example, a malware that drops a ransom note even though it does not encrypt data, but destroys it.

----------

| **Masqueraded Malware** | **Malware Name/Description** | **Scheme** | **Date of reported activity** | **Source** |
|---|---|---|---|---|
| Wiper | KillDisk | Wiper with ransomware capabilities. Missing way for decryption. | 2016 | [WeLiveSecurity](https://www.welivesecurity.com/2017/01/05/killdisk-now-targeting-linux-demands-250k-ransom-cant-decrypt/) |
| Wiper | KillDisk | Wipe files but leaves ransom note | 2016-2018 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/killdisk-fake-ransomware-hits-financial-firms-in-latin-america/) |
| Wiper | NotPetya (worm), related to Petya ransomware | Wiper with ransomware capabilities Missing way for decryption. | 2016-2017 | [CSOOnline](https://www.csoonline.com/article/3233210/petya-ransomware-and-notpetya-malware-what-you-need-to-know-now.html)|
| Wiper | ONI, other version is MBR-ONI which is based on DiskCryptor (legitimate tool also seen in Bad Rabbit ransomware) | Ransomware used as wiper Email used in ransom note: hyakunoonigayoru@yahoo[.]co.jp | 2017 | [CyberReason](https://www.cybereason.com/blog/night-of-the-devil-ransomware-or-wiper-a-look-into-targeted-attacks-in-japan), [BleepingComputer](https://www.bleepingcomputer.com/news/security/oni-ransomware-used-in-month-long-attacks-against-japanese-companies/) |
| Ransomware  | Hermes Ransomware | Ransomware deployed but no note or ransom demand. Cover up believed but not sure what (probably bank heist) | 2017 | [McAfee](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/taiwan-bank-heist-role-pseudo-ransomware/) |
| Wiper | Strain from Ordinypt | Wiper masquerading as ransomware | 2019 | [EmsiSoft](https://blog.emsisoft.com/en/34134/why-are-cybercriminals-disguising-wipers-as-ransomware/) |
| Wiper | GermanWiper (seems to be the same as Ordinypt, see [133]) Similarities with Sodinokibi ransomware campaign | Ransomware but overwrites with gibberish instead of encrypting | 2019  | [BleepingComputer](https://www.bleepingcomputer.com/news/security/germanwiper-ransomware-erases-data-still-asks-for-ransom/), [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/details/win.ordinypt) |
| Ransomware | Destructive version of Thanos ransomware | Shows ransom note but overwrites Master Boot Record (MBR) making the system unusable | 2020 (not seen in action at that time) | 135 |
| Wiper | Named Chaos but related to Ryuk | Wiper looking like ransomware | Start development June 2021, last update August 2021 | 136 |
| Wiper | Deadwood (aka Detbosit), and Apostle wiper which was turned into ransomware. Apostle allegedly written by same developer as IPsec Helper | Wiper masquerading as ransomware | Beginning 2020, still active late 2021 | 137, 138 |
| Ransomware (Most likely) | TTP matches Hello ransomware campaigns. Modus operandi similarity to APT27 | Attack stopped before ransomware was deployed. Indicators that ransomware was not primary goal | July 2021  | 139 |
| RAT | STRRAT The resemblance to ransomware is that it appends .crimson to files, but the files are not encrypted | RAT masquerades as ransomware. Capable of stealing data. Gives full control of victim. | Spotted in June 2020 Newer version spread May 2021 | 140 |
| Ransomware | Apparently borrows code from AutoIT-based ransomware families | Ransomware that uses an email address (pusheken91@bk[.]ru) as file ending for encrypted files. Does not drop ransom note. | MAy 2020 | 102 |
| Wiper | MBRLocker plus data wiper | Malware leaving ransom note and address but no way to get decryption key, in combination with malware that overwrites data with fixed number of bytes. | January 2022 | 65, 66, 67 |
| Wiper | Trojan.Killdisk (HermeticWiper) | Wiper that leaves ransom note. Similarities to so-called ’WhisperGate’ attack (see above) | February 2022 | 68 |
| Ranomware | Onyx (Chaos variant, see above) | Ransomware that destroys data (even with leak page). | April 2022 (reported version) | 141 |
| Wiper | Malware equipped to delete all system drives. (This functionality was not working properly in the investigated binary) | Malware renames all files, drops ransom note and deletes drives, but no way to recover files. | October 2022 | 142 |
|  | Azof|  |  |  |
|  |  |  |  |  |

