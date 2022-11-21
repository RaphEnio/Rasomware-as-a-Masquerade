# 'Rasomware as a Masquerade (RaaM)'
This repository aims to collect reports on malware that was masqueraded as ransomware. For example, a malware that drops a ransom note even though it does not encrypt data, but destroys it. 

Let me know if you have any suggestions on changes or/and additions!

----------

| **Masqueraded Malware** | **Malware Name/Description** | **Scheme** | **Date of reported activity** | **Source** |
|---|---|---|---|---|
| Wiper | KillDisk | Wiper with ransomware capabilities. Missing way for decryption. | 2016 | [WeLiveSecurity](https://www.welivesecurity.com/2017/01/05/killdisk-now-targeting-linux-demands-250k-ransom-cant-decrypt/) |
| Wiper | KillDisk | Wipe files but leaves ransom note | 2016-2018 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/killdisk-fake-ransomware-hits-financial-firms-in-latin-america/) |
| Wiper | NotPetya (worm), related to Petya ransomware | Wiper with ransomware capabilities. Missing way for decryption. | 2016-2017 | [CSOOnline](https://www.csoonline.com/article/3233210/petya-ransomware-and-notpetya-malware-what-you-need-to-know-now.html)|
| Wiper | ONI, other version is MBR-ONI which is based on DiskCryptor (legitimate tool also seen in Bad Rabbit ransomware) | Ransomware used as wiper. Email used in ransom note: hyakunoonigayoru@yahoo[.]co.jp | 2017 | [CyberReason](https://www.cybereason.com/blog/night-of-the-devil-ransomware-or-wiper-a-look-into-targeted-attacks-in-japan), [BleepingComputer](https://www.bleepingcomputer.com/news/security/oni-ransomware-used-in-month-long-attacks-against-japanese-companies/) |
| Ransomware  | Hermes Ransomware | Ransomware deployed but no note or ransom demand. Cover up believed but not sure what (probably bank heist) | 2017 | [McAfee](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/taiwan-bank-heist-role-pseudo-ransomware/) |
| Wiper | Strain from Ordinypt | Wiper masquerading as ransomware | 2019 | [EmsiSoft](https://blog.emsisoft.com/en/34134/why-are-cybercriminals-disguising-wipers-as-ransomware/) |
| Wiper | GermanWiper (seems to be the same as Ordinypt, see **Malpedia**) Similarities with Sodinokibi ransomware campaign | Ransomware, but overwrites with gibberish instead of encrypting | 2019  | [BleepingComputer](https://www.bleepingcomputer.com/news/security/germanwiper-ransomware-erases-data-still-asks-for-ransom/), [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/details/win.ordinypt) |
| Ransomware | Destructive version of Thanos ransomware | Shows ransom note but overwrites Master Boot Record (MBR) making the system unusable | 2020 (not seen in action at that time) | [ClearskySec](https://www.clearskysec.com/operation-quicksand/) |
| Wiper | Named Chaos but related to Ryuk | Wiper looking like ransomware | Start development June 2021, last update August 2021 | [TrendMicro](https://www.trendmicro.com/en_us/research/21/h/chaos-ransomware-a-dangerous-proof-of-concept.html) |
| Wiper | Deadwood (aka Detbosit), and Apostle wiper which was turned into ransomware. Apostle allegedly written by same developer as IPsec Helper | Wiper masquerading as ransomware | Beginning 2020, still active late 2021 | [SentinelOne](https://www.sentinelone.com/labs/from-wiper-to-ransomware-the-evolution-of-agrius/), [SentinelOne](https://www.sentinelone.com/labs/new-version-of-apostle-ransomware-reemerges-in-targeted-attack-on-higher-education/) |
| Ransomware (Most likely) | TTP matches Hello ransomware campaigns. Modus operandi similarity to APT27 | Attack stopped before ransomware was deployed. Indicators that ransomware was not primary goal | July 2021  | [eSentire](https://www.esentire.com/security-advisories/ransomware-hackers-attack-a-top-safety-testing-org-using-tactics-and-techniques-borrowed-from-chinese-espionage-groups) |
| RAT | STRRAT The resemblance to ransomware is that it appends .crimson to files, but the files are not encrypted | RAT masquerades as ransomware. Capable of stealing data. Gives full control of victim. | Spotted in June 2020 Newer version spread May 2021 | [TheRecord](https://therecord.media/microsoft-warns-of-malware-campaign-spreading-a-rat-masquerading-as-ransomware/) |
| Ransomware | Apparently borrows code from AutoIT-based ransomware families | Ransomware that uses an email address (pusheken91@bk[.]ru) as file ending for encrypted files. Does not drop ransom note. | May 2020 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/hackers-used-billing-software-zero-day-to-deploy-ransomware/) |
| Wiper | MBRLocker plus data wiper | Malware leaving ransom note and address but no way to get decryption key, in combination with malware that overwrites data with fixed number of bytes. | January 2022 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/microsoft-fake-ransomware-targets-ukraine-in-data-wiping-attacks/), [Zetter](https://zetter.substack.com/p/what-we-know-and-dont-know-about), [Microsoft](https://www.microsoft.com/security/blog/2022/01/15/destructive-malware-targeting-ukrainian-organizations/) |
| Wiper | Trojan.Killdisk (HermeticWiper) | Wiper that leaves ransom note. Similarities to so-called ’WhisperGate’ attack (see above) | February 2022 | [Symantec](http://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/ukraine-wiper-malware-russia) |
| Ransomware | Onyx (Chaos variant, see above) | Ransomware that destroys data (even with leak page). | April 2022 (reported version) | [BleepingComputer](https://www.bleepingcomputer.com/news/security/beware-onyx-ransomware-destroys-files-instead-of-encrypting-them/) |
| Wiper | Malware equipped to delete all system drives. (This functionality was not working properly in the investigated binary) | Malware renames all files, drops ransom note and deletes drives, but no way to recover files. | October 2022 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/fake-adult-sites-push-data-wipers-disguised-as-ransomware/) |
| Wiper | Azov|  | November 2022 | [BleepingComputer](https://www.bleepingcomputer.com/news/security/azov-ransomware-is-a-wiper-destroying-data-666-bytes-at-a-time/) |
|  |  |  |  |  |

This table is based on my research published [here](http://essay.utwente.nl/93500/).


