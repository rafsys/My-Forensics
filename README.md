<!DOCTYPE html>
<html lang='en'>

<head>

  <meta charset='UTF-8'>

<body>

<div id="header">

<h1>DIGITAL FORENSICS AND INCIDENT RESPONSE (DFIR)</h1>

<blockquote><h3>"These programs were never about terrorism: they're about economic spying, social control and diplomatic manipulation. They're about power." (Edward Snowden)</h3></blockquote>

<p align="center"><img src="https://github.com/RENANZG/My-Forensics/assets/53377291/a4ef4137-7b20-4df0-8678-1f48be665386" title="The Treachery of Images (1929) - René Magritte"/></p>

<!-- ################################## -->

<hr>

<h3>BASIC STRATEGY</h3>

<table style="width: 100%" cellspacing="0" cellpadding="0">
<thead>
  <tr>
  </tr>
</thead>
<tbody> 
<tr>
  <td align="center" valign="top"><b>Crime Triangle</b></td>
  <td align="center" valign="top"><b>Basic Investigative Metodology</b></td>
</tr>
<tr>
  <td align="center" valign="top">
    <img src=".data/crime_triangle.png" title="Crime Triangle">
  </td>
  <td align="left" valign="top">
    <p>
    <b>• 5W:</b> Who, What, When, Where and Why<br> 
    <b>• PDCA Cycle:</b> Plan, Do, Check and Act<br>
    <b>• Root Cause Analysis (RCA):</b><br>
    &emsp; — Identify and describe the problem clearly<br>
    &emsp; — Establish a timeline from the normal situation<br>
    &emsp;   until the problem occurs<br> 
    &emsp; — Distinguish between the root cause and other<br>
    &emsp;   causal factors (e.g., using event correlation)<br>
    &emsp; — Establish a causal graph between the root<br>
    &emsp;   cause and the problem<br>
    </p>
  </td>
</tr>
</tbody>
</table>

<!-- ################################## -->
<br>
<hr>

<h3>FORENSIC SUITES</h3>

<table style="width: 100%" cellspacing="0" cellpadding="0">
<thead>
  <tr>
  </tr>
</thead>
<tbody> 
<tr>
<td align="center" valign="top" style="width: 50%"><b>FLOSS</b><br>Free/Libre and Open Source Software</td>
<td align="center" valign="top" style="width: 50%"><b>PROPRIETARY</b><br>Cyber-surveillance Industry</td>
</tr>
<tr>
<td align="left" valign="top" style="width: 50%">
• Kali Linux<br><a href="https://www.kali.org">https://www.kali.org</a><br>
• Parrot Security<br><a href="https://www.parrotsec.org">https://www.parrotsec.org</a><br>
• SIFT Workstation<br><a href="https://www.sans.org/tools/sift-workstation" target="_blank" rel="noopener noreferrer">https://www.sans.org/tools/sift-workstation</a><br>
• CAINE<br><a href="https://www.caine-live.net">https://www.caine-live.net</a><br>
• CSI Linux<br><a href="https://csilinux.com">https://csilinux.com</a><br>
• Avilla Forensics<br><a href="https://github.com/AvillaDaniel/AvillaForensics">https://github.com/AvillaDaniel/AvillaForensics</a><br>
• IPED<br><a href="https://github.com/sepinf-inc/IPED">https://github.com/sepinf-inc/IPED</a><br>
• Debian Forensics Package<br><a href="https://packages.debian.org/unstable/forensics-all">https://packages.debian.org/unstable/forensics-all</a><br>
• Mobile Verification Toolkit (MVT)<br><a href="https://docs.mvt.re/en/latest">https://docs.mvt.re/en/latest</a><br>
• Drive Badger<br><a href="https://drivebadger.com">https://drivebadger.com</a><br>
• Tsurugi Linux<a href="https://tsurugi-linux.org/"><br>https://tsurugi-linux.org/</a><br>
• REMnux<a href="https://remnux.org/"><br>https://remnux.org</a><br>
• Bitscout<a href="https://github.com/vitaly-kamluk/bitscout"><br>https://github.com/vitaly-kamluk/bitscout</a><br>
• Eric Zimmerman's tools (Freeware)<br><a href="https://ericzimmerman.github.io/#!index.md">https://ericzimmerman.github.io/#!index.md</a><br>
• Paladin® (Freeware)<br><a href="https://sumuri.com/product/paladin-lts/">https://sumuri.com/software/paladin/</a><br>
• Forensic Toolkit (FTK)® - Lite (Freeware) <br><a href="https://www.exterro.com/ftk-product-downloads/how-to-run-ftk-imager-from-a-flash-drive-imager-lite" target="_blank" rel="noopener noreferrer">https://www.exterro.com/forensic-toolkit</a><br>
• Magnet Forensic® - Mobile Extractor (Freeware)<br><a href="https://www.magnetforensics.com/" target="_blank" rel="noopener noreferrer">https://www.magnetforensics.com</a><br>
• Windows Forensic Environment WinFE (Freeware)<br><a href="https://www.winfe.net/home" target="_blank" rel="noopener noreferrer">https://www.winfe.net</a><br>
• NirSoft® (Freeware)<br><a href="https://www.nirsoft.net/computer_forensic_software.html">https://www.nirsoft.net</a><br>
• MiTeC® (Freeware)<br><a href="https://www.mitec.cz">https://www.mitec.cz</a><br>
• Medusa Box® (Easy J-TAG)<br> <a href="https://medusabox.com/">https://medusabox.com</a><br> ╰┈➤<a href="https://medusabox.com/eng/features/features">Models Features</a><br> ╰┈➤<a href="https://aliexpress.com/w/wholesale-medusa-box.html">Aliexpress</a><br>
• Octoplus Box® (Easy J-TAG)<br><a href="https://octoplusbox.com">https://octoplusbox.com</a><br> ╰┈➤<a href="https://octoplusbox.com/en/features/models/">Models Features</a><br> ╰┈➤<a href="https://www.aliexpress.com/w/wholesale-octoplus-box.html">Aliexpress</a><br>
</td>
<td align="left" valign="top" style="width: 50%;">
• Cellebrite®<br><a href="https://cellebrite.com/" target="_blank" rel="noopener noreferrer">https://cellebrite.com</a><br>
• NSO Group®<br><a href="https://www.nsogroup.com/" target="_blank" rel="noopener noreferrer">https://www.nsogroup.com</a><br>
• Cognyte®<br><a href="https://www.cognyte.com/" target="_blank" rel="noopener noreferrer">https://www.cognyte.com</a><br>
• BriefCam®<br><a href="https://www.briefcam.com/" target="_blank" rel="noopener noreferrer">https://www.briefcam.com/</a><br>
• Forensic Toolkit (FTK)® <br><a href="https://www.exterro.com/forensic-toolkit" target="_blank" rel="noopener noreferrer">https://www.exterro.com/forensic-toolkit</a><br>
• Magnet Forensic®<br><a href="https://www.magnetforensics.com/" target="_blank" rel="noopener noreferrer">https://www.magnetforensics.com</a><br>
• Harpia Tech®<br><a href="https://harpia.tech/english.html" target="_blank" rel="noopener noreferrer">https://harpia.tech</a><br>
• Visual Cortex®<br><a href="https://visualcortex.com/" target="_blank" rel="noopener noreferrer">https://visualcortex.com</a><br>
• Oxygen Forensic®<br><a href="https://oxygen-forensic.wedatasolution.com/" target="_blank" rel="noopener noreferrer">https://oxygen-forensic.wedatasolution.com</a><br>
• MSAB®<br><a href="https://www.msab.com/" target="_blank" rel="noopener noreferrer">https://www.msab.com</a><br>
• GMDSOFT®<br><a href="https://www.gmdsoft.com/" target="_blank" rel="noopener noreferrer">https://www.gmdsoft.com</a><br>
• Verint Systems®<br><a href="https://www.verint.com/" target="_blank" rel="noopener noreferrer">https://www.verint.com</a><br>
• Cyber Arm®<br><a href="https://cyber-arm.com/services" target="_blank" rel="noopener noreferrer">https://cyber-arm.com/services</a><br>
• Cobalt Strike®<br><a href="https://www.cobaltstrike.com" target="_blank" rel="noopener noreferrer">https://www.cobaltstrike.com</a><br>
• Lumi Networks®<br><a href="https://www.lumi.network" target="_blank" rel="noopener noreferrer">https://www.lumi.network</a><br>
• Clear View AI®<br><a href="https://www.clearview.ai" target="_blank" rel="noopener noreferrer">https://www.clearview.ai</a><br>
• Lockheed Martin®<br><a href="https://www.lockheedmartin.com" target="_blank" rel="noopener noreferrer">https://www.lockheedmartin.com/</a><br>
• MOBILedit®<br><a href="https://www.mobiledit.com/mobiledit-forensic" target="_blank" rel="noopener noreferrer">https://www.mobiledit.com</a><br>
• Crowd Strike®<br><a href="https://www.crowdstrike.com" target="_blank" rel="noopener noreferrer">https://www.crowdstrike.com</a><br>
• Binalyze®<br><a href="https://www.binalyze.com" target="_blank" rel="noopener noreferrer">https://www.binalyze.com</a><br>
• LexisNexis®<br><a href="https://risk.lexisnexis.com" target="_blank" rel="noopener noreferrer">https://risk.lexisnexis.com</a><br>
• Thorn's Safer®<br><a href="https://www.thorn.org/" target="_blank" rel="noopener noreferrer">https://www.thorn.org</a><br>
</td>
</tr>
</tbody>
</table>


<!-- ################################## -->
<br>
<hr>

<h3>FORENSIC TOOLS</h3>

<h4>• Evidence ProjectForensics Tools Catalogue - <a href="https://www.dftoolscatalogue.eu/dftc.home.php">https://www.dftoolscatalogue.eu</a></h4>

<h4>• NIST - Forensics Tools Catalogue - <a href="https://toolcatalog.nist.gov/search/">https://toolcatalog.nist.gov</a></h4>

<h4>• S&T partners and NIST - Computer Forensic Tool Testing (CFTT) - <a href="https://www.dhs.gov/science-and-technology/nist-cftt-reports">https://www.dhs.gov/science-and-technology/nist-cftt-reports</a>

<!-- ################################## -->
<br>
<hr>

<sub>
<p><b>Interesting information</b></p>

<a href="https://socradar.io/beyond-the-veil-of-surveillance-private-sector-offensive-actors-psoas">• Beyond the Veil of Surveillance: Private Sector Offensive Actors (PSOAs)</a>

<a href="https://www.zdnet.com/article/burn-drown-or-smash-your-phone-forensics-can-extract-data-anyway">• Burn, drown, or smash your phone: Forensics can extract data anyway</a>

<a href="https://arstechnica.com/information-technology/2021/01/how-law-enforcement-gets-around-your-smartphones-encryption">• How law enforcement gets around your smartphone’s encryption</a>

<a href="https://www.youtube.com/watch?v=EmWsW_p_ta4">• Cellphone data used to solve murder case from 2 years ago, police say</a>

<a href="https://www.youtube.com/watch?v=wzSgLpNrr2E">• The Stingray: How Law Enforcement Can Track Your Every Move</a>

<a href="https://www.youtube.com/watch?v=DH7edXaZS0A">• Police are tracking you and your license plates</a>

<a href="https://www.youtube.com/watch?v=ASYm-3NJ-GA&t=40s">• SCOTUS: Police Need Search Warrant to Ping cell Phones</a>

<a href="https://www.eff.org/deeplinks/2023/09/eff-michigan-court-governments-shouldnt-be-allowed-use-drone-spy-you-without">• EFF to Michigan Court: Governments Shouldn’t Be Allowed to Use a Drone to Spy on You Without a Warrant</a>

<a href="https://theintercept.com/document/motion-to-suppress-aerial-surveillance-evidence-in-u-s-vs-muhammed-momtaz-alazhari">• Motion to Suppress Aerial Surveillance Evidence in U.S. vs Muhammed Momtaz Alazhari</a>

<a href="https://www.nytimes.com/2008/02/22/technology/22chip.html">• Researchers Find Way to Steal Encrypted Data - NYT (2008)</a>

<a href="https://www.nakedcapitalism.com/2019/02/reverse-location-search-warrant-a-new-personal-data-hoovering-exercise-brought-to-you-by-google.html">• “Reverse Location Search Warrant”: A New Personal Data Hoovering Exercise Brought to You by Google (2019)</a>

<a href="https://www.nakedcapitalism.com/2021/07/as-un-human-rights-chief-urges-stricter-rules-snowden-calls-for-end-to-spyware-trade.html">• As UN Human Rights Chief Urges Stricter Rules, Snowden Calls for End to Spyware Trade (2021)</a>

<a href="https://www.forensicscijournal.com/articles/jfsr-aid1039.pdf">• Forensics Journal Comparative analysis of mobile forensic proprietary tools: an application in forensic investigation (2022)</a>

<a href="https://ppee.unb.br/wp-content/uploads/2020/12/Artigo_Claudinei-Morim.pdf">• Methodology for Forensics Data Reconstruction on Mobile Devices with Android<br> Operating System Applying In-System Programming and Combination Firmware (2020)</a>

</sub>

<!-- ################################## -->
<br>
<hr>

<h3>INTERCEPTION PLATFORMS</h3>

<p>Comparison between Drive Badger with other lawful interception platforms. Visit: <a href="https://docs.google.com/spreadsheets/d/1Ux0WeL-K4NOZTEQgJXuRzHPcG_ewKmcMNADuFhamytg/edit#gid=1460165261" target="_blank" rel="noopener noreferrer">Official online sheet complete and updated</a> or <a href="3.GUIDES_&_PAPERS/Drive_Bagder_-_Comparison_of_lawful_interception_platforms.pdf" target="_blank" rel="noopener noreferrer">PDF in our repo</a>.</p>

<p>News: https://thehackernews.com/2023/12/multi-million-dollar-predator-spyware.html</p>
<p>News: https://thehackernews.com/2023/12/urgent-new-chrome-zero-day.html</p>

<table style="width:830px" cellspacing="0" cellpadding="0">
<tbody valign="top">
<tr>
 <td style="width:7%"><b>PRODUCT KNOWN AS</b></td>
 <td style="width:31%">• Devils Tongue<br>• Sourgum<br></td>
 <td style="width:31%">• Pegasus Spyware</td>
 <td style="width:31%">• Drive Badger<br>• Funkcjonariusz<br></td>
</tr>
<tr>
 <td style="width:7%">DETAILS LAST UPDATED</td>
 <td style="width:31%">2022-06-19</td>
 <td style="width:31%">2021-12-15</td>
 <td style="width:31%">2022-06-18</td>
</tr>
<tr>
 <td style="width:7%">AVAILABILITY</td>
 <td style="width:31%">COMMERCIAL</td>
 <td style="width:31%">COMMERCIAL</td>
 <td style="width:31%">OPEN SOURCE</td>
</tr>
<tr>
 <td style="width:7%">YEARS OF ACTIVITY</td>
 <td style="width:31%">2014-current</td>
 <td style="width:31%">2010-current</td>
 <td style="width:31%">2017-current</td>
</tr>
<tr>
 <td style="width:7%">COMPANY</td>
 <td style="width:31%"><a href="https://citizenlab.ca/2021/07/hooking-candiru-another-mercenary-spyware-vendor-comes-into-focus">Candori</a></td>
 <td style="width:31%">NSO Group</td>
 <td style="width:31%"> — </td>
</tr>
<tr>
 <td style="width:7%">COUNTRY</td>
 <td style="width:31%">Israel</td>
 <td style="width:31%">Israel</td>
 <td style="width:31%">Poland</td>
</tr>
<tr>
 <td style="width:7%">HOW IT WORKS</td>
 <td style="width:31%">— remote installation<br>
 — remote data interception<br></td>
 <td style="width:31%">— remote installation<br>
 — remote data interception<br></td>
 <td style="width:31%">— local one-time usage via USB device<br>
 — local data interception<br>
 — integration with 3rd party remote solutions<br></td>
</tr>
<tr>
 <td style="width:7%">SUPPORTED PLATFORMS<br>(SUMMARY)</td>
 <td style="width:31%">— Windows<br>
 — Android<br>
 — iOS<br>
 — possibly Mac OS<br></td>
 <td style="width:31%">— Android<br>
 — iOS<br>
 — Symbian<br>
 — Blackberry<br></td>
 <td style="width:31%">— Windows<br>
 — Mac OS<br>
 — Linux<br>
 — Windows Embedded<br>
 — Android<br>
 — iOS, iPadOS<br>
 — Windows Mobile/Phone<br>
 — Symbian<br>
 — Canon/Nikon/HP photo cameras<br>
 — VMware ESXi<br>
 — Hyper-V<br></td>
</tr>
<tr>
 <td style="width:7%">HOW OPERATORS USE<br>
 THE SYSTEM</td>
 <td style="width:31%">— web panel for operators<br>
 — all actions are logged<br>
 — operators are fully responsible for any abuse attempts<br></td>
 <td style="width:31%">— web panel for operators<br>
 — all actions are logged<br>
 — operators are fully responsible for any abuse attempts<br></td>
 <td style="width:31%">— all exfiltrated data are stored locally on the USB device (on encrypted partition)<br>
 — no panel — operator has full access to raw data and can analyze it in preferred way, eg. import into Magnet AXIOM, Paraben E3, FTK Forensic Toolkit, Autopsy, or SANS SIFT for forensic analysis using these tools<br>
 — basic Linux knowledge is required<br>
 — both USB device and collected data are in the sole possession of the operator<br>
 — no operator abuse control<br></td>
</tr>
<tr>
 <td style="width:7%">SOME FUNCTIONALITIES AND TRACKING METHODS</td>
 <td style="width:31%"><b>WINDOWS (PC)</b><br>
 • Supported versions<br>
 — 7<br>
 — 10 (documentation states that only 64-bit)<br>
 — not sure about Windows 8 / 8.1<br>
 — not sure about Windows Server<br>
 • Software-only installation method(s)<br>
 ∙ Remote installation using<br>
 — CVE-2021-31979 and CVE-2021-33771 (attack on Windows)<br>
 — RCE for Chrome, Firefox or Internet Explorer<br>
 — RCE on Microsoft Office 2013-2019<br>
 • Post-install remote functionalities<br>
 ∙ Standard package — access to:<br>
 — Skype<br>
 — Outlook<br>
 — Telegram<br>
 — Facebook<br>
 — Gmail<br>
 — device ID<br>
 — browsing history<br>
 — geolocation<br>
 — raw files<br>
 — passwords<br>
 — keylogger<br>
 — webcam<br>
 — microphone recording<br>
 — screenshots<br>
 — Paid separately:<br>
 — remote shell (Windows-only, 1.5M EUR)<br>
 — Twitter<br>
 — Viber<br>
 — Signal<br>
 — WeChat<br>
 — Odnoklassniki<br>
 — Vkontakte<br>
 — Mail.ru<br>
 
 <b>LINUX</b><br>
 • Post-install remote functionalities<br>
 — n/a <br>

 <b>ANDROID</b><br>
 • Installation and tracking method(s)<br>
 — supported, there is a closed list of supported Android versions (4-9 as for 2020); documentation suggests that <br>
 — they may have problems with Android forks eg. Xiaomi MIUI, they support Samsung Galaxy S phones (and probably tablets), and agreed list of models/vendors for additional fee<br>
 
 • What information is available after installation<br>
 ∙ Standard package — access to:<br>
 — photos & screenshots<br>
 — emails, sms<br>
 — browsing history<br>
 — contact details<br>
 — calendar records<br>
 — GPS location tracking<br>
 — basic/advanced device info<br>
 — call history<br>
 — list directories<br>
 — Google Drive<br>
 — Dropbox<br>
 — WhatsApp<br>
 — FB Messenger<br>
 — Skype<br>
 — Telegram<br>
 — network details<br>
 — network change notifications<br>
 — recording microphone and phone calls<br>
 
 ∙ Paid separately:<br>
 — Twitter<br>
 — Viber<br>
 — Signal<br>
 — WeChat<br>
 — Odnoklassniki<br>
 — Vkontakte<br>
 — Mail.ru<br>

<b>MAC OS</b><br>
 • Post-install remote functionalities<br>
 ∙ Standard package — access to:<br>
 • Installation and tracking method(s)<br>
 — not sure — depending on each source, supported or not<br>

<b>APPLE IOs</b><br>
 • Installation and tracking method(s)<br>
 — remote installation using either attack on Safari, or whole iOS (details not revealed)<br>
 • What information is available after installation<br>
 ∙ Standard package — access to:<br>
 — photos & screenshots<br>
 — emails, sms<br>
 — browsing history<br>
 — contact details<br>
 — calendar records<br>
 — GPS location tracking<br>
 — basic/advanced device info<br>
 — call history<br>
 — list directories<br>
 — Google Drive<br>
 — Dropbox<br>
 — WhatsApp<br>
 — FB Messenger<br>
 — Skype<br>
 — Telegram<br>
 — network details<br>
 — network change notifications<br>
 — recording microphone and phone calls<br>
 — Paid separately:<br>
 — Twitter<br>
 — Viber<br>
 — Signal<br>
 — WeChat<br>
 — Odnoklassniki<br>
 — Vkontakte<br>
 — Mail.ru<br>
 </td>
 <td style="width:31%">
 <b>WINDOWS (PC)</b><br>
 • Supported versions<br>
 — n/a <br>
 • Software-only installation method(s)<br>
 ∙ Remote installation using<br>
 — n/a <br>
 • Post-install remote functionalities<br>
 — n/a <br>
    
<b>LINUX</b><br>
 • Post-install remote functionalities<br>
— n/a <br>
<b>ANDROID</b><br>
• Installation and tracking method(s)<br>
∙ Remote:<br>
— magic sms/push, non-persistent infection, requiring re-infecting after each reboot<br>
— in non-root mode it can ask the user for permissions to access eg. photos, just like normal app<br>
*supported Android versions: from 2.1, mainly Samsung Galaxy and Sony Xperia devices<br>
• What information is available after installation<br>
— photos & screenshots<br>
— emails, sms<br>
— browsing history<br>
— contact details<br>
— calendar records<br>
— converations from Skype, WhatsApp, Twitter, Facebook, Viber, KakaoTalk<br>
— GPS location tracking<br>
— device settings<br>
— network details<br>
— raw file retrieval<br>
— recording microphone and phone calls (Android-only)<br>
  
<b>MAC OS</b><br>
• Post-install remote functionalities<br>
∙ Standard package — access to:<br>
• Installation and tracking method(s)<br>
— n/a<br>
<b>Apple IOS</b><br>
• Installation and tracking method(s)<br>
∙ Remote, using:<br>
— magic sms/push<br>
— Trident exploit (CVE-2016-4655, CVE-2016-4656, CVE-2016-4657)<br>
— Kismet exploit (2020)<br>
— ForcedDentry (2021) previously known as Megalodon (2019)<br>
— existing jailbreak<br>
— emulation of clicking on important apps (eg. iMessage) non-persistent infection, requiring re-infecting after each reboot; supported iOS versions: from 4.x (iPhone 4)<br>
• What information is available after installation<br>
— photos & screenshots<br>
— emails, sms<br>
— browsing history<br>
— contact details<br>
— calendar records<br>
— converations from Skype, WhatsApp, Twitter, Facebook, Viber, KakaoTalk<br>
— GPS location tracking<br>
— device settings<br>
— network details<br>
— raw file retrieval<br>
</td>
<td style="width:31%">
<b>WINDOWS (PC)</b><br>
• Supported versions<br>
— from XP SP2 to 11 (including "S")<br>
— Server 2003-2022<br>
— Embedded Standard 7 and 2009<br>
• Software-only installation method(s)<br>
1.local data exfiltration, via plugged-in USB device, support for Bitlocker / LUKS / VeraCrypt drive encryption<br>
2.local injection of 3rd party exploits (possibly remotely exploitable), straight from USB device, without disconnecting the hard drive<br>
• Post-install remote functionalities<br>
— Only exploitation of locally injected 3rd party exploit(s).<br>
<b>LINUX</b><br>
• Software-only installation method(s)<br>
∙ Remote installation using<br>
— n/a<br>
• Post-install remote functionalities<br>
1.local data exfiltration, via USB, support for Bitlocker / LUKS / VeraCrypt drive encryption<br>
2.local injection of 3rd party exploits (possibly remotely exploitable), straight from USB, without disconnecting the hard drive<br>
<b>ANDROID</b><br>
• Installation and tracking method(s)<br>
— local data exfiltration only, through MTP, PTP or Mass Storage (depending onAndroid version and security settings), requires already unlocked device<br>
• What information is available after installation<br>
— photos & screenshots<br>
— in MTP/MSC mode, everything that is remotely visible (access to raw files)<br>
<b>MAC OS</b><br>
• Software-only installation method(s)<br>
∙ Remote installation <br>
• Post-install remote functionalities<br>
— local data exfiltration only, via USB, support for APFS FileVault encryption, on T2-based models requires the device to already unlocked<br>

• Installation and tracking method(s)<br>
— local data exfiltration only, via USB, support for APFS FileVault encryption, on T2-based models requires the device to already unlocked<br>
<b>Apple IOS</b><br>
 
• Installation and tracking method(s)<br>
∙ Remote, using:<br>
— magic sms/push<br>
— Cydia Substrate's hooking functionality (iOS11 and below, only jailbroken devices)<br>

• What information is available after installation<br>
— everything that is remotely visible according to phone/tablet security settings (access to raw files)<br>
</td>  
</tr>
<tr>
 <td style="width:7%">Annual cost per tracked user license (for first 10 users)</td>
 <td>0</td>
 <td>$65 000</td>
 <td>free</td>
</tr>
<tr>
 <td style="width:7%">Annual cost per tracked user license (above first 10 users, up to next limit)</td>
 <td>$ 100.000</td>
 <td>$ 10.000</td>
 <td>free</td>
</tr>
<tr>
 <td style="width:7%">Annual cost per operator</td>
 <td>3 included + € 20 000 for each another</td>
 <td>?</td>
 <td>free</td>
</tr>
<tr>
 <td style="width:7%">One time entry cost — excluding trainings</td>
 <td>€ 16.850.000</td>
 <td>€ 3.500.000</td>
 <td>only hardware cost</td>
</tr>
<tr>
 <td style="width:7%">Trainings</td>
 <td>?</td>
 <td>€ 750.000</td>
 <td>depends on training company, all documentation freely available</td>
</tr>
<tr>
 <td style="width:7%">Source code status</td>
 <td>closed source</td>
 <td>decompiled samples only, mainly from Android agents</td>
 <td>open source</td>
</tr>
<tr>
 <td style="width:7%">Source code link</td>
 <td>-</td>
 <td>https://github.com/jonathandata1/pegasus_spyware</td>
 <td></td>
</tr>
<tr>
 <td style="width:7%">C &amp; C infrastructure</td>
 <td> ? </td>
 <td>Pegasus Anonymizing Transmission Network, up to 500 domains, DNS servers and others, to hide easy detection of traffic; on most platforms ability to self-destruct after 60 days of no connection, or after detecting non-target SIM card</td>
 <td>No remote infrastructure is required, unless Drive Badger is weaponized using 3rd party exploit(s). As for local infrastructure:<br>
 https://drivebadger.com/recommended-hardware.html<br>
 https://drivebadger.com/mobile-recommended-hardware.html<br></td>
</tr>
<tr>
 <td style="width:7%">Indicators of Compromise</td>
 <td>https://citizenlab.ca/2021/07/hooking-candiru-another-mercenary-spyware-vendor-comes-into-focus/<br></td>
 <td>https://github.com/AmnestyTech/investigations/tree/master/2021-07-18_nso<br>
 https://arkadiyt.com/2021/07/25/scanning-your-iphone-for-nso-group-pegasus-malware<br>
 https://sekurak.pl/czym-jest-oprogramowanie-szpiegowskie-pegasus-analiza-zagrozenia-oraz-metody-jego-wykrywania/<br></td>
 <td>regarding 2018+ FinSpy mobile:<br>
 https://securelist.com/new-finspy-ios-and-android-implants-revealed-itw/91685<br></td>
</tr>
<tr>
 <td style="width:7%">More photos</td>
 <td>https://sekurak.pl/devilstongue-czyli-lepszy-pegasus-od-izraelskiej-firmy-candiru/#comment-96837</td>
 <td>https://niebezpiecznik.pl/post/jak-wyglada-rzadowy-trojan-pegasus-od-srodka</td>
 <td>https://drivebadger.com/history.html</td>
</tr>
<tr>
 <td style="width:7%">Other materials</td>
 <td>
 <a href="https://wiadomosci.radiozet.pl/Polska/Polityka/Pegasus-w-Polsce.-CBA-kupilo-potezne-oprogramowanie-szpiegowskie" target="_blank" rel="noopener noreferrer">https://wiadomosci.radiozet.pl/Polska/Polityka/Pegasus-w-Polsce.-CBA-kupilo-potezne-oprogramowanie-szpiegowskie</a><br>
 <a href="https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf" target="_blank" rel="noopener noreferrer">https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf</a><br>
 <a href="https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf" target="_blank" rel="noopener noreferrer">https://googleprojectzero.blogspot.com/2021/12/a-deep-dive-into-nso-zero-click.html</a><br>
 </td>
 <td>
 <a href="https://wiadomosci.radiozet.pl/Polska/Polityka/Pegasus-w-Polsce.-CBA-kupilo-potezne-oprogramowanie-szpiegowskie" target="_blank" rel="noopener noreferrer">https://wiadomosci.radiozet.pl/Polska/Polityka/Pegasus-w-Polsce.-CBA-kupilo-potezne-oprogramowanie-szpiegowskie</a><br>
 <a href="https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf" target="_blank" rel="noopener noreferrer">https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf</a><br>
 <a href="https://s3.documentcloud.org/documents/4599753/NSO-Pegasus.pdf" target="_blank" rel="noopener noreferrer">https://googleprojectzero.blogspot.com/2021/12/a-deep-dive-into-nso-zero-click.html</a><br>
 </td>
 <td>
 https://drivebadger.com<br>
 https://funkcjonariusz.com<br>
 </td>
</tr>
</tbody>
</table>

<!-- ################################## -->

<br>
<hr>

<h3>NATIONAL CYBER SECURITY AGENCIES</h3>

<table style="width:830px" cellspacing="0" cellpadding="0">
<thead>
  <tr>
  </tr>
</thead>
<tbody> 
<tr>
<td valign="top" style="width:25%">
<a href="https://www.cisa.gov/">US — CISA</a><br>
<a href="https://www.cyber.gc.ca/en">CA — Cyber</a><br>
<a href="https://csirtamericas.org/en">Americas — CSIRT</a><br>
</td>
<td valign="top" style="width:25%">
<a href="https://www.enisa.europa.eu">EU — ENISA</a><br>
<a href="https://www.ncsc.gov.uk">UK — NCSC</a><br>
<a href="https://english.ncsc.nl">NL — NCSC</a><br>
<a href="https://www.bsi.bund.de/EN">DE — BSI</a><br>
<a href="https://www.ccn-cert.cni.es/es/">ES —CCN-CERT</a><br>
<a href="https://www.acn.gov.it/en">IT —ACN</a><br>
<a href="https://www.nki.gov.hu/en">HU — NKI</a><br>
<a href="https://www.nukib.cz/en">CZ — NUKIB</a><br>
<a href="https://nsm.no/areas-of-expertise/cyber-securitynorwegian-national-cyber-security-centre-ncsc">NO — NCSC</a><br>
</td>
<td valign="top" style="width:25%">
<a href="https://www.gov.il/en/departments/israel_national_cyber_directorate/govil-landing-page">IS — INCD</a><br>
<a href="https://www.cyber.gov.au">AU — Cyber</a><br>
<a href="https://www.cert.govt.nz">NZ — CERT</a><br>
<a href="https://www.ncsc.govt.nz">NZ — NCSC</a><br>
</td>
<td valign="top" style="width:25%">
<a href="https://www.kisa.or.kr/EN">KR — KISA</a><br>
<a href="https://www.jpcert.or.jp/english">JP — Cert</a><br>
<a href="https://www.nisc.go.jp/eng/index.html">JP — NISC</a><br>
<a href="https://www.csa.gov.sg">SG — CSA</a><br>
</td>
</tr>
</tbody>
</table>

<!-- ############################## -->

<br>
<hr>

${\color{Blue}\textbf{1.PASSIVE FORENSICS}}$

👷🛠️UNDER CONSTRUCTION🚧🏗<br>

<details>
<summary>1.01 Forensic standards</summary>
<br>

<p>Visit our repo tree: <a href="https://github.com/RENANZG/My-Forensics/tree/main/2.FORENSIC_STANDARDS">2.FORENSIC_STANDARDS</a></p>

<br>
</details>

<!-- ########## -->

<details>
<summary>1.02 Forensic certs & training</summary>
<br>

<ul>
<li>
<p><a href="https://aboutdfir.com/education/certifications-training/">About DFIR - Certifications Training</a></p>
</li>
<li>
<p><a href="https://github.com/mikeroyal/Digital-Forensics-Guide">Mikeroyal - Digital Forensics Guide (Github)</a></p>
</li>
<li>
<p><a href="https://www.enisa.europa.eu/topics/training-and-exercises/trainings-for-cybersecurity-specialists/online-training-material">Enisa EU - Online Training Material</a></p>
</li>
<li>
<p><a href=""></a></p>
</li>
<li>
<p><a href=""></a></p>
</li>
</ul>

<!-- ########## -->


<br>
</details>
<details>
<summary>1.03 Forensic tools</summary>
<br>

<h4>Evidence ProjectForensics Tools Catalogue - <a href="https://www.dftoolscatalogue.eu/dftc.home.php">https://www.dftoolscatalogue.eu</a></h4>

<h4>NIST - Forensics Tools Catalogue - <a href="https://toolcatalog.nist.gov/search/">https://toolcatalog.nist.gov</a></h4>

<h4>S&T partners and NIST - Computer Forensic Tool Testing (CFTT) - <a href="https://www.dhs.gov/science-and-technology/nist-cftt-reports">https://www.dhs.gov/science-and-technology/nist-cftt-reports</a>

<h4>Some tools</h4>

<ul>
<li><a href="https://www.sleuthkit.org/sleuthkit/">The Sleuth Kit (TSK)</a><a href="https://github.com/sleuthkit/sleuthkit">(GitHub)</a></li>
<li><a href="https://www.autopsy.com">Autopsy</a></li>
<li><a href="https://github.com/WerWolv/ImHex">ImHex</a></li>
<li><a href="https://hashcat.net">Hashcat</a></li>
<li><a href="https://www.openwall.com/john/">John the Ripper</a></li>
<li><a href="https://github.com/drivebadger/drivebadger">Drive Badger — Covert Data Exfiltration Operations</a></li>
<li><a href="https://github.com/northloopforensics/Fetch">Making Maps for Investigators</a></li>
<li><a href="https://github.com/mxrch/GHunt">Offensive Google framework</a></li>
<li><a href="https://github.com/northloopforensics/Bitlocker_Key_Finder">Bitlocker Key Finder</a></li>
<li><a href="https://github.com/teamdfir/sift">SIFT</a></li>
<li><a href="https://github.com/keydet89/RegRipper3.0">RegRipper</a></li>
<li><a href="https://www.nomoreransom.org/en/index.html">No More Ransom</a></li>
<li><a href="https://docs.microsoft.com/en-us/sysinternals/downloads">MS Sysinternals</a></li>
<li><a href="https://www.winfe.net/download">WinFE</a></li>
</ul>

Image and video upscaling programs<br>

• <a href="https://github.com/imagej/ImageJ">ImageJ</a><br>
• Upscalers - https://github.com/hollowaykeanho/Upscaler<br>

<h4>Extraction Methods</h4>

<table>
<tbody>
<tr>
<td>Encryption:</td>
<td><p>Seize the encrypted files and decrypt them using a password or key and the appropriate decryption software. <br> OR<br> Seize the data while it is in an unencrypted state.</p></td>
</tr>
<tr>
<td>Virtualization:</td>
<td>Seize the virtual image file and open it with the correct password.<br>
 OR<br>
 Log into the virtual machine and seize the data while the virtual machine is turned on and in an unencrypted state.</td>
</tr>
<tr>
<td>Relational Database:</td>
<td>Seize all the files containing records. Obtain a copy of the database software and rebuild the database.<br>
OR<br>
Log into the database while it is live and employ the application used to create and manage the database as a search tool. Download the data using the method allowed by the application, either in the form of printouts or data files.</td>
</tr>
</tbody>
</table>

<br>
</details>

<!-- ########## -->

<details>
<summary>1.04 Forensic online tools</summary>
<br>

• Virus Total — https://www.virustotal.com<br>
• Binvis — https://binvis.io<br>
• Hybrid — https://hybrid-analysis.com<br>
• Verexif - https://www.verexif.com/en/<br>
• Any Run — https://app.any.run<br>
• IP Logger — https://iplogger.org<br>
• The ZMap Project — https://zmap.io<br>
• Grabify IP Logger — https://grabify.link/<br>
• IP Tracker — https://iplogger.org/ip-tracker<br>
• Location Tracker — https://iplogger.org/location-tracker<br>
• URL checker —  https://iplogger.org/url_checker<br>
• MAC address lookup — https://iplogger.org/mac-checker<br>
• IP API<br>
&emsp; — ip-api — https://ip-api.com<br>
&emsp; — ipify — https://www.ipify.org<br>
&emsp; — ipapi — https://ipapi.co<br>
&emsp; — vpnapi — https://vpnapi.io<br>
&emsp; — ipapi — https://ipapi.com<br>
• Name OSINT — https://namechk.com<br>
• Message Header Analyzer — https://mha.azurewebsites.net/  |  https://github.com/microsoft/MHA<br>
• Reverse Shell Generator — https://www.revshells.com<br>
• Rainbow Tables (Hashes) — https://hashes.com/en/decrypt/hash<br>
• Breach Directory - https://breachdirectory.org<br>
• MD5 Decrypt - https://md5decrypt.net/en/Sha1<br>
• Magic Numbers — https://en.wikipedia.org/wiki/Magic_number_(programming)<br>
• Web Cache - https://archive.org<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>1.05 Cryptography</summary>
<br>

<h4>Cryptanalysis</h4>

<p>Visit our repo tree: 3.PAPERS_&_GUIDES/Cryptanalysis</p>

<h4>Bruteforce</h4>

<p>Read the "Brute Force" thread below.</p>

<h4>Workrounds</h4>

<p>Visit our repo tree: 3.PAPERS_&_GUIDES/Encryption</p>

<h4>Steganography</h4>


<br>
</details>

<!-- ########## -->

<details>
<summary>1.06 Memory analysis</summary>
<br>

<h4>Volatile memory analysis</h4>

• Volatility<br>
https://www.volatilityfoundation.org/releases<br>
• Linux Memory Extractor (LiME)<br>
https://github.com/504ensicsLabs/LiME<br>
• Cobalt Strike in memory<br>
https://andreafortuna.org/2020/11/22/how-to-detect-cobalt-strike-activity-in-memory-forensics/<br>

<h3>JTag, Chip-off and ISP forensics</h3>
https://www.teeltech.com/ufaqs/what-is-jtag-chip-off-and-isp<br>
https://www.cellebritelearningcenter.com/mod/page/view.php?id=11903<br>
https://www.fletc.gov/jtag-chipoff-smartphones-training-program<br>
https://www.gillware.com/phone-data-recovery-services/jtag-chip-off-forensics<br>
https://www.gillware.com/phone-data-recovery-services/chip-off-forensics-services<br>

<h4>Researching support for phones in JTAG software</h4>
https://octoplusbox.com<br>
https://medusabox.com<br>
https://www.riffbox.org<br>
https://easy-jtag.com<br>
https://z3x-team.com<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>1.07 Cryptocurrencies analysis</summary>
<br>

<h4>Cryptocurrencies analysis</h4>

https://github.com/OffcierCia/On-Chain-Investigations-Tools-List<br>
https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff<br>
https://blocksherlock.com/home/blockchain-explorers<br>
https://tronscan.org<br>
https://etherscan.io<br>
https://algoexplorer.io<br>
https://explorer.solana.com<br>
https://stellar.expert<br>
https://snowtrace.io<br>
https://flowscan.org<br>
https://polygonscan.com<br>

<h4>Some tools</h4>

https://github.com/demining/CryptoDeepTools<br>
https://github.com/demining/bitcoindigger<br>
https://github.com/demining/Dao-Exploit<br>
https://github.com/immunefi-team/Web3-Security-Library/blob/main/Tools/README.md#blockchain-analysis<br>

<h4>Private sector</h4>

https://chainalysis.com<br>
https://elliptic.co<br>
https://ciphertrace.com<br>
https://coinmetrics.io<br>
https://www.whitestream.io<br>
https://ciphertrace.com<br>
https://elementus.io<br>
https://trmlabs.com<br>
https://bitok.org/investigations<br>

</details>

<!-- ################################## -->

<hr>

${\color{Red}\textbf{2.ACTIVE FORENSICS}}$

👷🛠️UNDER CONSTRUCTION🚧🏗<br>

<details>
<summary>2.01 Police hacking</summary>
<br>

<p>Visit our repo tree: <a href="https://github.com/RENANZG/My-Forensics/tree/main/4.POLICE_HACKING">4.POLICE_HACKING</a></p>

<p>https://archive.epic.org/privacy/carnivore</p>
<p>https://www.aclu.org/press-releases/fbi-renames-carnivore-internet-wiretap</p>

<h4>The Cyber Kill Chain</h4>

<img src="https://github.com/RENANZG/My-Forensics/blob/main/.data/the_cyber_kill_chain.png" title="The Cyber Kill Chain" style="width:100%">

• MITRE ATT&CK — ICS Techniques<br>
https://attack.mitre.org/techniques/ics<br>

• MITRE ATT&CK — Mobile Techniques<br>
https://attack.mitre.org/techniques/mobile/<br>

• MITRE ATT&CK — Enterprise Techniques<br>
https://attack.mitre.org/techniques/enterprise/<br>

<h4>• Training</h4>

∙ Rootme — https://www.root-me.org<br>
∙ Vulnhub — https://www.vulnhub.com<br>
∙ Hacker101 — https://www.hacker101.com<br>
∙ Crackmes — https://crackmes.one<br>
∙ Attack Defense — https://attackdefense.com<br>

<h4>• Some Cases</h4>

<img src="https://github.com/RENANZG/My-Forensics/blob/main/.data/phones.png" title="Police Hack"/><br>

∙ Omerta Digital (FBI Honey Pot?)<br>
https://www.omertadigital.com/<br>
∙ Case: ANON (also stylized as AN0M or ΛNØM)<br>
https://en.wikipedia.org/wiki/ANOM<br>
https://www.vice.com/en/article/n7b4gg/anom-phone-arcaneos-fbi-backdoor<br>
∙ Case: EncroChat<br>
https://en.wikipedia.org/wiki/EncroChat<br>
https://eucrim.eu/news/germany-federal-court-of-justice-confirms-use-of-evidence-in-encrochat-cases<br>
https://xperylab.medium.com/the-dark-phones-encrochat-criminals-are-building-their-own-communication-system-474f3aeef759<br>
∙ Case: Pegasus Spyware (NSO Group)<br>
https://theintercept.com/2021/07/27/pegasus-nso-spyware-security<br>
∙ Case: Verint<br>
https://wikileaks.org/spyfiles/docs/VERINT_2012_AvneTurn_en.html<br>
https://www.reddit.com/r/InfoSecNews/comments/sxxzju/leaktheanalyst_group_leak_critical_data_from/<br>
∙ Case: Phantom Secure<br>
https://en.wikipedia.org/wiki/Phantom_Secure<br>
https://www.vice.com/en/article/v7m4pj/the-network-vincent-ramos-phantom-secure<br>
∙ Case: Sky Global<br>
https://en.wikipedia.org/wiki/Shutdown_of_Sky_Global<br>
∙ Case: Bundestrojaner  <br>
https://en.wikipedia.org/wiki/Bundestrojaner<br>
∙ Case: Magic Lantern<br>
https://en.wikipedia.org/wiki/Magic_Lantern_(software)<br>
https://github.com/bibanon/bibanon/blob/0b84bb23794c91c238a5601403898b61b5d193fc/Encyclopedia/History/Events/Pifts.md?<br>plain=1#L125
∙ Case: Cryptophon<br>
https://en.wikipedia.org/wiki/Tron_(hacker)#Cryptophon<br>
∙ Planting Tiny Spy Chips in Hardware Can Cost as Little as $200<br>
https://www.wired.com/story/plant-spy-chips-hardware-supermicro-cheap-proof-of-concept<br>
∙ Installation of beacon implants<br>
https://arstechnica.com/tech-policy/2014/05/photos-of-an-nsa-upgrade-factory-show-cisco-router-getting-implant  <br>
∙ The tricky issue of spyware with a badge: meet ‘policeware’<br>
https://arstechnica.com/information-technology/2007/07/will-security-firms-avoid-detecting-government-spyware<br>
∙ Analisi della normativa e della giurisprudenza sul captatore informatico e la spiegazione del Caso Exodus<br>
https://www.dirittoconsenso.it/2021/11/11/captatore-informatico-trojan-di-stato<br>
∙ LightEater Demo: Stealing GPG keys/emails in Tails via remote firmware infection<br>
https://www.youtube.com/watch?v=sNYsfUNegEA<br>
∙ KeyGrabber Forensic Keylogger<br>
https://www.youtube.com/watch?v=6JJo8qCYE8M<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.02 Law Enforcement Agency (LEA)</summary>

<h4>• Rule of Law Benchmarks</h4>

<img src="https://github.com/RENANZG/My-Forensics/blob/main/.data/law_in_books_22.png" title="Always remember that the law in books is different from the law in action." style="width:100%">

<p>*First of all, consult court cases to see how laws are (mis)applied.</p>

<h4>• International Law</h4>
∙ UN — Library of Resources — https://www.unodc.org/e4j/en/resdb/index.html<br>
∙ UN — https://www.unodc.org/elearning/en/courses/course-catalogue.html
∙ Budapest Convention — Cybercrime — https://www.coe.int/en/web/cybercrime/the-budapest-convention<br>
∙ Octopus Project — https://coe.int/en/web/cybercrime/octopus-project<br>
∙ Five Eyes — https://en.wikipedia.org/wiki/Five_Eyes<br>

<h4>• Council of Europe — Cybercrime</h4>
∙ Cybercrime — https://www.coe.int/cybercrime<br>
∙ GLACY+ — https://coe.int/en/web/cybercrime/glacyplus<br>
∙ iPROCEEDS-2 — https://coe.int/en/web/cybercrime/iproceeds-2<br>
∙ Octopus Project — https://coe.int/en/web/cybercrime/octopus-project<br>
∙ CyberSouth — https://coe.int/en/web/cybercrime/cybersouth<br>
∙ CyberEast — https://coe.int/en/web/cybercrime/cybereast<br>

<h4>• Publications</h4>

<ul>
<li><a href="https://www.coe.int/en/web/cybercrime/cyber-digests-and-updates" target="_blank" rel="noopener">Council of Europe – Cybercrime Digest and </a><a href="https://www.coe.int/en/web/cybercrime/cyber-digests-and-updates" target="_blank" rel="noopener">Cybercrime@CoE Update</a>: a bi-weekly selection of news relevant to the current areas of interest to the Cybercrime Programme Office of CoE (C-PROC) and&nbsp;a quarterly review of the work carried out by the Cybercrime Convention Committee (T-CY).</li>
<li><a href="https://b96de5da.sibforms.com/serve/MUIEACLiNKgT7-T6ofXDkIGbYxDLmxvtQd9xqKxFPG247oA-YVJ9-zDJ8qkYykiBK8nVIqzbvEglSSAjqBq9QJXVV7OP586AqR8-Q7kR8OYULBlmUfx6Qx5PpLyqDiVdydk9Kjgb4HDoP9qUr0VzwZOxKsi7oOG2tspyXc6wqOaMH7vd-OgQo8rNXLrLMEgtyn0-tg1DNs7jLuEG" target="_blank" rel="noopener">Council of Europe – Cybercrime Newsletter</a>: subscribe to receive the latest updates on the topic.</li>
<li><a href="https://cert.europa.eu/publications/threat-intelligence/2023" target="_blank" rel="noopener">CERT-EU</a>: access quarterly Threat Landscape Reports and monthly Cyber Security Briefs from the Computer Emergency Response Team for the EU institutions, bodies and agencies.</li>
<li><a href="https://www.cepol.europa.eu/publications" target="_blank" rel="noopener">CEPOL – Publications</a>: find the latest documents on trainings for law enforcement officials including the <a href="https://www.cepol.europa.eu/scientific-knowledge-and-research/european-law-enforcement-research-bulletin" target="_blank" rel="noopener">European Law Enforcement Research Bulletin.</a></li>
<li><a href="https://www.enisa.europa.eu/news/newsletter-subscription" target="_blank" rel="noopener">ENISA Newsroom</a>: follow the most recent news on cybersecurity.</li>
<li><a href="https://www.enisa.europa.eu/news/newsletter-subscription" target="_blank" rel="noopener">ENISA Publications</a>: sort the latest publications on cybersecurity by topic (and download copies).</li>
<li><a href="https://ec.europa.eu/newsroom/eurojust/user-subscriptions/2146/create" target="_blank" rel="noopener">EUROJUST Newsletter</a>: news from the European Union Agency for Criminal Justice Cooperation.</li>
<li><a href="https://ec.europa.eu/newsroom/home/user-subscriptions/2668/create" target="_blank" rel="noopener">European Commission’s DG HOME Newsletter</a>: spotlight on Schengen and borders, internal security and relevant European funds.</li>
<li><a href="https://www.europol.europa.eu/newsletter/subscriptions" target="_blank" rel="noopener">Europol – Email alerts</a>: ranging from news to upcoming publications and vacancies, choose what alerts to receive.</li>
<li><a href="https://www.osce.org/subscriptions/signup" target="_blank" rel="noopener">Organisation for Security and Co-operation in Europe (OSCE) Newsletter</a>: hand-picked updates and in-depth information bundles on OSCE activities, with possibility to choose countries of interest.</li>
<li><a href="https://www.europol.europa.eu/publications-events/publications?q=sirius" target="_blank" rel="noopener">SIRIUS project publications</a>: co-implemented by Europol and&nbsp;<a href="https://www.eurojust.europa.eu/">Eurojust</a>, in close partnership with the&nbsp;<a href="https://www.ejn-crimjust.europa.eu/ejn2021/Home/EN">European Judicial Network</a>, the SIRIUS project is a central reference point in the EU for knowledge sharing on cross-border access to electronic evidence and allows to download, among other publications, the yearly EU Digital Evidence Situation Report.</li>
</ul>

<h4>• Investigatory Powers — Criminal Law</h4>

<h6>Americas</h6> 
∙ US — Federal Rules — Criminal Procedure — Overview — <a href="https://www.law.cornell.edu/wex/criminal_procedure" target="_blank">Link</a><br>
∙ US — Federal Rules — Criminal Procedure — Rule 41 — Search and Seizure — <a href="https://www.law.cornell.edu/rules/frcrmp/rule_41" target="_blank">Link</a><br>

<table>
<tbody>
<tr>
<td>On a Network<br>in a Single<br>District</td>
<td>On a Network in Multiple Districts</td>
<td>On a Network with Data Stored Internationally</td>
<td >Unknown Where the Data is Stored (Cloud)</td>
</tr>
<tr>
<td >Search under Rule 41; consider noting in affidavit the possibility of other locations</td>
<td>Multiple search warrants for each district with data or §2703 Warrant served on service provider</td>
<td >Use legal process required in country hosting the data, or consider accessing data remotely with a search warrant under Rule 41</td>
<td >Search under Rule 41 for subject computers, and concurrently search under §2703 served on service provider</td>
</tr>
</tbody>
</table>

<h6>Union European</h6>
∙ UE — Criminal procedural laws across the European Union – A comparative analysis — <a href="https://www.europarl.europa.eu/RegData/etudes/STUD/2018/604977/IPOL_STU(2018)604977(ANN01)_EN.pdf" target="_blank">Link</a><br>
∙ UK — Crime, justice and law — Law and practice — <a href="https://www.gov.uk/guidance/rules-and-practice-directions-2020" target="_blank">Link</a><br>
∙ UK — Public General Acts — Investigatory Powers Act 2016 — <a href="https://www.legislation.gov.uk/ukpga/2016/25/contents" target="_blank">Link</a><br>
∙ GE — German Criminal Code (Strafgesetzbuch — StGB) — <a href="https://www.gesetze-im-internet.de/englisch_stgb" target="_blank">Link</a><br>
∙ GE — German Code of Criminal Procedure (Strafprozeßordnung — StPO) — <a href="https://www.gesetze-im-internet.de/englisch_stpo/index.html" target="_blank">Link</a><br>

![architecture](https://github.com/RENANZG/My-Forensics/assets/53377291/f92b0055-29fe-40de-9a45-da845d0f3f4b)

<h4>Court Cases</h4>
∙ US Federal Cases — https://pacer.uscourts.gov/find-case<br>
∙ EUR-Lex https://eur-lex.europa.eu/homepage.html<br>
∙ EU Common Portal of Case Law — https://network-presidents.eu/cpcl<br>
∙ UNODC — Case Law Database — https://sherloc.unodc.org/cld/v3/sherloc/cldb/index.html?lng=en<br>
∙ UNODC — Cyber Organized Crime — https://www.unodc.org/e4j/en/cybercrime/module-13/additional-teaching-tools.html<br>
∙ Council of Europe - COE Cybercrime - https://www.coe.int/en/web/cybercrime<br>
∙ Council of Europe - Octopus Cybercrime Community - Materials - https://www.coe.int/en/web/octopus/training<br>
∙ US Dod - Computer Crime and Intellectual Property Section (CCIPS) - https://www.justice.gov/criminal/criminal-ccips<br>
∙ US FBI - Internet Crime Complaint Center (IC3) - https://www.ic3.gov<br>
∙ Computer Crime Research Center - https://www.crime-research.org<br>
∙ The IT Law Wiki - https://itlaw.fandom.com<br>

<!-- ########## -->

<h2>The Five, Nine, & Fourteen Eyes surveillance alliance includes the following countries:</h2>

<table style="width: 100%;" cellspacing="0" cellpadding="0">
<thead>
  <tr>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
<tr>
<td align="left"><b>Countries</b></td>
<td align="center"><b>Five Eyes</b></td>
<td align="center"><b>Nine Eyes</b></td>
<td align="center"><b>Fourteen Eyes</b></td>
<td align="center"><b>Other</b></td>
</tr>
<tr>
<td align="left">United Kingdom</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">United States</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Australia</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Canada</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">New Zealand</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Denmark</td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Netherlands</td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">France</td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Norway</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Germany</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Belgium</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Spain</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Sweden</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Italy</td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
<td align="center"></td>
</tr>
<tr>
<td align="left">Israel</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
</tr>
<tr>
<td align="left">Japan</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
</tr>
<tr>
<td align="left">Singapore</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
</tr>
<tr>
<td align="left">South Korea</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">✔️</td>
</tr>
</tbody>
</table>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.03 Liability for Contents</summary>
<br>

<ul>
<li><a href="https://startyourownisp.com/">How to start your own ISP</a></li>
<li><a href="https://i.imgur.com/3fHyG2S.png">Where are torrents permitted?</a></li>
<li><a href="https://www.ukispcourtorders.co.uk/">UK ISP Court Orders</a></li>
<li><a href="https://en.wikipedia.org/wiki/Web_Sheriff">Web Sheriff</a></li>
<li><a href="https://www.theverge.com/2020/1/31/21116788/earn-it-act-section-230-lindsey-graham-draft-bill-encryption">A new bill could punish web platforms for using end-to-end encryption</a></li>
<li><a href="https://www.polygon.com/2019/9/19/20874384/french-court-steam-valve-used-games-eu-law">French court rules that Steam’s ban on reselling used games is contrary to European law</a></li>
<li><a href="https://www.theguardian.com/media/2019/mar/26/meps-approve-sweeping-changes-to-copyright-law-european-copyright-directive">MEPs approve sweeping changes to copyright law</a></li>
<li><a href="https://www.lifewire.com/legalities-of-linking-3468972">The Legalities of Linking</a></li>
<li><a href="https://klarislaw.com/wp-content/uploads/klarislaw-copyright-liability-for-linking-and-embedding.pdf">COPYRIGHT LIABILITY FOR LINKING AND EMBEDDING — Klaris Law (.PDF)</a></li>
<li><a href="https://www.engadget.com/2016/04/08/eu-court-linking-copyrighted-content-is-legal/">EU court says linking to copyrighted material isn&#39;t illegal</a></li>
<li><a href="https://torrentfreak.com/ip-address-is-not-enough-to-identify-pirate-us-court-of-appeals-rules-180828/">IP Address is Not Enough to Identify Pirate, US Court of Appeals Rules</a> — (<a href="https://cdn.ca9.uscourts.gov/datastore/opinions/2018/08/27/17-35041.pdf">.PDF</a>)</li>
<li><a href="https://torrentfreak.com/new-eu-piracy-watchlist-targets-key-pirate-sites-and-cloudflare-181210/">New EU Piracy Watchlist Targets Key Pirate Sites and Cloudflare</a> — (<a href="https://torrentfreak.com/images/tradoc_157564.pdf">.PDF</a>)</li>
<li><a href="https://torrentfreak.com/domain-registrar-can-be-held-liable-for-pirate-site-court-rules-181224/">Domain Registrar Can be Held Liable for Pirate Site, Court Rules</a></li>
<li><a href="https://torrentfreak.com/reporting-when-pirate-releases-hit-the-internet-is-apparently-illegal-now-190101/">Reporting When Pirate Releases Hit The Internet is Apparently Illegal Now</a></li>
<li><a href="https://torrentfreak.com/swiss-copyright-law-downloading-stays-legal-no-site-blocking/">Swiss Copyright Law: Downloading Stays Legal, No Site Blocking</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_websites_blocked_in_the_United_Kingdom">List of websites blocked in the United Kingdom</a></li>
<li><a href="https://torrentfreak.com/major-us-isps-refuse-to-discuss-repeat-infringer-policies-190912/">Major US ISPs Refuse to Discuss Repeat Infringer Policies</a></li>
<li><a href="https://arxiv.org/abs/1902.05796">Who Watches the Watchmen: Exploring Complaints on the Web</a></li>
<li><a href="https://www.theregister.co.uk/2019/07/20/creative_content_piracy/">British ISPs throw in the towel, give up sending out toothless copyright infringement warnings</a></li>
</ul>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.04 Tor Fingerprint</summary>
<br>

<h4>Tor Fingerprint</h4>

∙ TOR Fingerprinting — https://blog.torproject.org/browser-fingerprinting-introduction-and-challenges-ahead<br>
∙ Attacks on Tor — https://github.com/Attacks-on-Tor/Attacks-on-Tor<br>
∙ EFF Test — https://coveryourtracks.eff.org/learn<br>

<h4>Hacker Cases</h4>

<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.05 Forensics Footprints</summary>
<br>

<h4>Forensics Footprints</h4>

• https://github.com/PaulNorman01/Forensia<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.06 Supply Chain Attack</summary>
<br>

<h4>Supply Chain Attack</h4>
• https://reproducible-builds.org<br>
• https://github.com/SAP/risk-explorer-for-software-supply-chains<br>
• https://github.com/ossillate-inc/packj<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.07 APT & Cybercriminal Campagin Collections</summary>
<br>

<h4>APT & Cybercriminal Campagin Collections</h4>
• https://github.com/CyberMonitor/APT_CyberCriminal_Campagin_Collections<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.08 Man In The Middle (MitM)</summary>
<br>

<h4>Man In The Middle (MitM)</h4>
• https://github.com/frostbits-security/MITM-cheatsheet<br>
• https://github.com/andreafortuna/MITMInjector<br>
• https://github.com/KoreLogicSecurity/wmkick<br>
• https://github.com/jakev/mitm-helper-wifi<br>
• https://github.com/jakev/mitm-helper-vpn<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.09 Network Analysis</summary>
<br>

<h4>Network Analysis</h4>

• Snort — https://github.com/snort3<br>
• Wireshark — https://www.wireshark.org<br>
• NMAP — https://nmap.org<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.10 Metadata</summary>
<br>

<h4>Metadata</h4>

∙ ExifTool — https://github.com/exiftool/exiftool<br>
∙ PhotoDNA — https://anishathalye.com/inverting-photodna<br>
∙ Geo-tags — https://tool.geoimgr.com<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.11 Reverse Engineering</summary>
<br>

<h4>Reverse Engineering</h4>

https://github.com/alphaSeclab/awesome-reverse-engineering<br>

<h4>Ghidra</h4>

https://ghidra-sre.org<br>

<br>
</details>

<!-- ########## -->

<details>
<summary>2.12 Social Engineeringg</summary>
<br>

<h4>Social Engineering</h4>

<ul>
<li><a href="https://www.symantec.com/connect/articles/social-engineering-fundamentals-part-i-hacker-tactics"> Social Engineering Fundamentals, Part I: Hacker Tactics, SecurityFocus</a></li>
<li><a href="https://www.symantec.com/connect/articles/social-engineering-fundamentals-part-ii-combat-strategies">Social Engineering Fundamentals, Part II: Combat Strategies, SecurityFocus</a></li>
<li><a href="https://github.com/giuliacassara/awesome-social-engineering">Awesome Social Engineering — GitHub</a></li>
<li><a href="https://github.com/trustedsec/social-engineer-toolkit">Social Engineer Toolkit — GitHub</a></li>
<li><a href=""> </a></li>
</ul>

<br>
</details>

<!-- ############################################################################### -->
<hr>

<details>
<summary>${\color{Yellow}\textbf{PHONE SNIFFING}}$</summary>
<br>

<a href="https://youtu.be/VonHAsY4-VA">
  <img src="https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fyoutu.be%2FVonHAsY4-VA" alt="Phone Surveillance Exposed" title="Phone Surveillance Exposed"/>
</a>

<table>
<thead>
  <tr>
    <th></th>
    <th></th>
   </tr>
</thead>
<tbody>
<tr>
<td>NAME</td>
<td>MEANING</td>
</tr>
<tr>
<td>IMEI</td>
<td><a href="https://en.wikipedia.org/wiki/International_Mobile_Equipment_Identity">International Mobile Equipment Identity</a></td>
</tr>
<tr>
<td>IMSI</td>
<td><a href="https://en.wikipedia.org/wiki/International_mobile_subscriber_identity">International Mobile Subscriber Identity</a></td>
</tr>
<tr>
<td>MCC</td>
<td><a href="https://en.wikipedia.org/wiki/Mobile_country_code">Mobile Country Code</a></td>
</tr>
<tr>
<td>MNC</td>
<td><a href="https://en.wikipedia.org/wiki/Mobile_country_code">Mobile Network Code</a></td>
</tr>
<tr>
<td>MSIN</td>
<td><a href="https://en.wikipedia.org/wiki/Mobile_identification_number">Mobile Subscription Identification Number</a></td>
</tr>
<tr>
<td>ICCID</td>
<td><a href="https://en.wikipedia.org/wiki/SIM_card#ICCID">Integrated Circuit Card Identifier</a></td>
</tr>
<tr>
<td>MSID</td>
<td><a href="https://www.pcmag.com/encyclopedia/term/mobile-station">Mobile Station ID</a></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
<tr>
<td>GSM</td>
<td><a href="https://en.wikipedia.org/wiki/GSM">Global System for Mobile Communications</a></td>
</tr>
<tr>
<td>SIM Card</td>
<td><a href="https://en.wikipedia.org/wiki/SIM_card">Subscriber Identity Module Card</a></td>
</tr>
<tr>
<td>SMS</td>
<td><a href="https://en.wikipedia.org/wiki/SMS">Short Message/Messaging Service</a></td>
</tr>
<tr>
<td>SDR</td>
<td><a href="https://en.wikipedia.org/wiki/Software-defined_radio">Software-Defined Radio</a></td>
</tr>
</tbody>
</table>

<img src="https://user-images.githubusercontent.com/53458032/209445888-a0b016ee-0b05-49d6-a4ab-d14d72f632f7.png" title="IMSI">

<h3>Useful Websites</h3>

— OpenCellID — [Link](https://opencellid.org/)<br>
— Cell Tower Locator (Cell2GPS) — [Link](https://www.cell2gps.com/)<br>
— Cell Phone Trackers — [Link](https://cellphonetrackers.org/)<br>
— International Numbering Plans — [Link](https://www.numberingplans.com/)<br>
— GSM World Coverage Map and GSM Country List — [Link](https://www.worldtimezone.com/gsm.html)<br>
— Imei Info — https://www.imei.info<br>
— Phones — https://www.gsmarena.com<br>
— Cell Towers — https://opencellid.org<br>

<h3>Information & Explanations</h3>

— IMSI-catcher — [Link](https://en.wikipedia.org/wiki/IMSI-catcher)<br>
— GSM frequency bands — [Link](https://en.wikipedia.org/wiki/GSM_frequency_bands)<br>
— List of software-defined radios — [Link](https://en.wikipedia.org/wiki/List_of_software-defined_radios)<br>

<h3>Useful Apps</h3>

— Mobile Software<br>
  — AIMSICD — [Link](https://github.com/CellularPrivacy/Android-IMSI-Catcher-Detector)<br>
  — SnoopSnitch — [Link](https://f-droid.org/en/packages/de.srlabs.snoopsnitch/)<br>
— Desktop Software<br>
  — GsmEvil 2 — [Link](https://github.com/ninjhacks/gsmevil2)<br>
  — IMSI-catcher — [Link](https://github.com/Oros42/IMSI-catcher)<br>

<h3>Equipment</h3>

<pre>
GSM 900 / GSM 1800 MHz are used in most parts of the world: Europe, Asia, Australia, Middle East, Africa.
GSM 850 / GSM 1900 MHz are used in the United States, Canada, Mexico and most countries of S. America.
</pre>

— SDR<br>
  — RTL-SDR (65MHz-2.3GHz) — [Link](https://www.amazon.com/dp/B06Y1HKLHY)<br>
— Antenna<br>
  — Antenna — [Link](https://www.amazon.com/dp/B07HQJKMBD)<br>

<h3>Equipment</h3>

— Catching IMSI Catchers — [Link](https://youtu.be/eivHO1OzF5E)<br>

<h3>GSM Sniffing Install/Setup Guide</h3>

<h4>Install</h4>

<pre>
$ sudo apt install python3-numpy python3-scipy python3-scapy gr-gsm
$ git clone https://github.com/Oros42/IMSI-catcher && cd IMSI-catcher
$ sudo grgsm_livemon && python3 simple_IMSI-catcher.py --sniff
</pre>

<h4>GSM Install Error? Try this!</h4>

<pre>
$ sudo apt-get install -y \
cmake \
autoconf \
libtool \
pkg-config \
build-essential \
docutils \
libcppunit-dev \
swig \
doxygen \
liblog4cpp5-dev \
gnuradio-dev \
gr-osmosdr \
libosmocore-dev \
liborc-0.4-dev \
swig

$ gnuradio-config-info -v
</pre>

<h4>Tips</h4>

<pre>
$ sudo grgsm_scanner -l  # List your SDR connected.
$ sudo grgsm_scanner     # Scan for cell towers near you.
$ sudo grgsm_livemon     # Live radio scanning.
</pre>

<br>
</details>

<!-- ############################################################################### -->
<hr>

<details>
<summary>${\color{Green}\textbf{BRUTE FORCE ATTACKS}}$</summary>
<br>

<p>The speed at which your password is cracked depends on the entropy of your password and the power of the computer.
</p>

<p>Computer programs used for brute force attacks can check anywhere from 10,000 to 1 billion passwords per second. A Pentium 100 can try 10.000 passwords a second. A supercomputer can try 1.000.000.000 per second.</p>


<p>Complex sheet:</p>

<img src="https://github.com/RENANZG/My-Forensics/blob/main/.data/Password_Brute_Force_Strenght_Table.png" title="Password Brute Force Strenght" style="width:100%">

<p>Simplified sheet:</p>

<img src="https://github.com/RENANZG/My-Forensics/blob/main/.data/Password_Brute_Force_Strenght_Table_2023.png" title="Password Brute Force Strenght" style="width:100%">

<h4>Types of brute force attacks</h4>

<h5>Simple Brute Force Attack</h5>

<p>The attacker relies on trying out commonly used, weak passwords such as 123456, qwerty, admin, changeme, qazwsxedc etc.</p>

<h5>Dictionary attack</h5>

<p>Software that can make thousands of guesses every second using dictionary databases, hence the name of the attack.</p>

<h5>Hybrid Brute Force Attack</h5>

<p>A hybrid attack is utilized once the attacker already knows the username of its prey.</p>

<h5>Reverse Brute Force Attack</h5>

<p>A reverse brute force attack requires the attacker to know the password beforehand and then attempt to guess the username.</p>

<h5>Credential stuffing</h5>

<p>Hackers can get entire databases of stolen login credentials and then try to apply them to the account they’re trying to access. This kind of attack can be especially devastating if the attacked user reuses passwords across multiple accounts.</p>

<h5>Rainbow Table Attack</h5>

<p>A rainbow table attack is a method of password cracking that employs rainbow tables to break the password hashes in a database. Websites or apps don’t store passwords in plain text; instead, they encrypt passwords with hashes. Once the password is used for logging in, it is immediately converted to a hash. The next time the user logs in using their passwords, the server checks whether the password matches the previously created hash. If the two hashes match, the user is then authenticated. The tables used to store password hashes are known as rainbow tables.</p>

<h4>Multi Factor Authenticator (MFA) or Two-factor Authenticator (2FA)</h4>

<p>Set up MFA whenever possible, It's an extra layer of security that requires additional steps to verify the user's identity.</p>

<br>
</details>

<!-- ################################## -->

<hr>

<details>
<summary><b>Standards</b></summary>
<br>

<p><b>NIST — National Institute of Standards and Technology</b></p>

<h6>Visit: https://www.nist.gov/standards</h6>

<p><b>ISO/IEC — International Electrotechnical Commission</b></p>

<h6>Visit: https://www.iso27001security.com</h6>

Information security, cybersecurity and privacy protection — https://www.iso.org/standard/27001 <br>

<ul>
<li><A HREF="https://www.iso27001security.com/html/27000.html">ISO/IEC 27000 — ISO27k overview &amp; glossary</a></li>
<li><A HREF="https://www.iso27001security.com/html/27001.html">ISO/IEC 27001 — formal ISMS specification</a></li>
<li><A HREF="https://www.iso27001security.com/html/27002.html">ISO/IEC 27002 — infosec controls catalogue</a></li>
<li><A HREF="https://www.iso27001security.com/html/27003.html">ISO/IEC 27003 — ISMS implementation guide</a></li>
<li><A HREF="https://www.iso27001security.com/html/27004.html">ISO/IEC 27004 — infosec measurement [metrics]</a></li>
<li><A HREF="https://www.iso27001security.com/html/27005.html">ISO/IEC 27005 — info[sec] risk management</a></li>
<li><A HREF="https://www.iso27001security.com/html/27006.html">ISO/IEC 27006-n — ISMS &amp; PIMS certification </a></li>
<li><A HREF="https://www.iso27001security.com/html/27007.html">ISO/IEC 27007 — <I>management system</I> auditing</a></li>
<li><A HREF="https://www.iso27001security.com/html/27008.html">ISO/IEC TS 27008 — <I>security controls</I> auditing</a></li>
<li><A HREF="https://www.iso27001security.com/html/27009.html">ISO/IEC 27009 — sector variants of ISO27k</a></li>
<li><A HREF="https://www.iso27001security.com/html/27010.html">ISO/IEC 27010 — for inter-org comms</a></li>
<li><A HREF="https://www.iso27001security.com/html/27011.html">ISO/IEC 27011 — ISMS for telecoms</a></li>
<li><A HREF="https://www.iso27001security.com/html/27013.html">ISO/IEC 27013 — ISMS &amp; ITIL/service mgmt</a></li>
<li><A HREF="https://www.iso27001security.com/html/27014.html">ISO/IEC 27014 — infosec governance</a></li>
<li><A HREF="https://www.iso27001security.com/html/27016.html">ISO/IEC TR 27016 — infosec economics</a></li>
<li><A HREF="https://www.iso27001security.com/html/27017.html">ISO/IEC 27017 — cloud security controls</a></li>
<li><A HREF="https://www.iso27001security.com/html/27018.html">ISO/IEC 27018 — cloud privacy</a></li>
<li><A HREF="https://www.iso27001security.com/html/27019.html">ISO/IEC 27019 — process control in energy industry</a></li>
<li><A HREF="https://www.iso27001security.com/html/27021.html">ISO/IEC 27021 — competences for ISMS pro&#8217;s</a></li>
<li><A HREF="https://www.iso27001security.com/html/27022.html">ISO/IEC TS 27022 — ISMS processes</a></li>
<li><A HREF="https://www.iso27001security.com/html/27031.html">ISO/IEC 27031 — ICT element of business continuity</a></li>
<li><A HREF="https://www.iso27001security.com/html/27032.html">ISO/IEC 27032 — Internet security</a></li>
<li><A HREF="https://www.iso27001security.com/html/27033.html">ISO/IEC 27033-n — network security</a></li>
<li><A HREF="https://www.iso27001security.com/html/27034.html">ISO/IEC 27034-n — application security</a></li>
<li><A HREF="https://www.iso27001security.com/html/27035.html">ISO/IEC 27035-n — incident management</a></li>
<li><A HREF="https://www.iso27001security.com/html/27036.html">ISO/IEC 27036-n — ICT supply chain &amp; cloud</a></li>
<li><A HREF="https://www.iso27001security.com/html/27037.html">ISO/IEC 27037 — digital evidence [eForensics]</a></li>
<li><A HREF="https://www.iso27001security.com/html/27038.html">ISO/IEC 27038 — document redaction</a></li>
<li><A HREF="https://www.iso27001security.com/html/27039.html">ISO/IEC 27039 — intrusion prevention</a></li>
<li><A HREF="https://www.iso27001security.com/html/27040.html">ISO/IEC 27040 — storage security</a></li>
<li><A HREF="https://www.iso27001security.com/html/27041.html">ISO/IEC 27041 — incident investigation assurance</a></li>
<li><A HREF="https://www.iso27001security.com/html/27042.html">ISO/IEC 27042 — analysing digital evidence</a></li>
<li><A HREF="https://www.iso27001security.com/html/27043.html">ISO/IEC 27043 — incident investigation</a></li>
<li><A HREF="https://www.iso27001security.com/html/27050.html">ISO/IEC 27050-n — digital forensics</a></li>
<li><A HREF="https://www.iso27001security.com/html/27070.html">ISO/IEC 27070 — virtual roots of trust</a></li>
<li><A HREF="https://www.iso27001security.com/html/27071.html">ISO/IEC 27071 — trusted connections</a></li>
<li><A HREF="https://www.iso27001security.com/html/27099.html">ISO/IEC 27099 — ISMS for PKI</a></li>
<li><A HREF="https://www.iso27001security.com/html/27100.html">ISO/IEC TS 27100 — cybersecurity overview/concepts</a></li>
<li><A HREF="https://www.iso27001security.com/html/27102.html">ISO/IEC 27102 — cyber-insurance</a></li>
<li><A HREF="https://www.iso27001security.com/html/27103.html">ISO/IEC 27103 —  ISMS for cybersecurity</a></li>
<li><A HREF="https://www.iso27001security.com/html/27110.html">ISO/IEC TS 27110 — cybersecurity frameworks</a></li>
<li><A HREF="https://www.iso27001security.com/html/27400.html">ISO/IEC 27400 — IoT security and privacy</a></li>
<li><A HREF="https://www.iso27001security.com/html/27550.html">ISO/IEC TR 27550 — privacy engineering</a></li>
<li><A HREF="https://www.iso27001security.com/html/27553.html">ISO/IEC 27553-n — mobile device biometrics</a></li>
<li><A HREF="https://www.iso27001security.com/html/27555.html">ISO/IEC 27555 — deleting PII/personal data</a></li>
<li><A HREF="https://www.iso27001security.com/html/27556.html">ISO/IEC 27556 — privacy preferences</a></li>
<li><A HREF="https://www.iso27001security.com/html/27557.html">ISO/IEC 27557 — privacy risk management</a></li>
<li><A HREF="https://www.iso27001security.com/html/27559.html">ISO/IEC 27559 — de-identification of personal data</a></li>
<li><A HREF="https://www.iso27001security.com/html/27560.html">ISO/IEC TS 27560 — privacy consent record structure</a></li>
<li><A HREF="https://www.iso27001security.com/html/27563.html">ISO/IEC TR 27563 — AI use case security &amp; privacy</a></li>
<li><A HREF="https://www.iso27001security.com/html/27570.html">ISO/IEC TS 27570 — smart city privacy</a></li>
<li><A HREF="https://www.iso27001security.com/html/27701.html">ISO/IEC 27701 — managing privacy with an ISMS</li>
<li><A HREF="https://www.iso27001security.com/html/27799.html">ISO 27799 — information security in healthcare</a></li>
</ul>

<p><b>RFC</b></p>

<p><b>Best Current Practices (BCP)</b></p>

<ul>
 <li><a href="https://www.ietf.org/rfc/rfc1918.txt"> RFC 1918 / BCP 5: Address Allocation for Private Internets</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2350.txt"> RFC 2350 / BCP 21: Expectations for Computer Security Incident Response</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2505.txt"> RFC 2505 / BCP 30: Anti-Spam Recommendations for SMTP MTAs</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2644.txt"> RFC 2644 / BCP 34: Changing the Default for Directed Broadcasts in Routers</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2827.txt"> RFC 2827 / BCP 38: Network Ingress Filtering: Defeating Denial of Service Attacks which employ IP Source Address Spoofing</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3013.txt"> RFC 3013 / BCP 46: Recommended Internet Service Provider Security Services and Procedures</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3227.txt"> RFC 3227 / BCP 55: Guidelines for Evidence Collection and Archiving</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3360.txt"> RFC 3360 / BCP 60: Inappropriate TCP Resets Considered Harmful</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3365.txt"> RFC 3365 / BCP 61: Strong Security Requirements for Internet Engineering Task Force Standard Protocols</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc4086.txt"> RFC 4086 / BCP 106: Randomness Requirements for Security</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc4107.txt"> RFC 4107 / BCP 107: Guidelines for Cryptographic Key Management</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc5068.txt"> RFC 5068 / BCP 134: Email Submission Operations: Access and
Accountability Requirements</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5358.txt">RFC 5358 / BCP 140: Preventing Use of Recursive Nameservers in Reflector Attacks</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5406.txt">RFC 5406 / BCP 146: Guidelines for Specifying the Use of IPsec Version 2</a></li>
</ul>

<p><b>Standards</b></p>

<ul>
<li><a href="https://www.ietf.org/rfc/rfc2142.txt"> RFC 2142: Mailbox Names for Common Services, Roles and Functions</a></li>
<li><a href="https://www.ietf.org/rfc/rfc2246.txt"> RFC 2246: The TLS Protocol  Version 1.0</a></li>
<li><a href="https://www.ietf.org/rfc/rfc2554.txt"> RFC 2554: SMTP Service Extension for Authentication</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3168.txt"> RFC 3168: The Addition of Explicit Congestion Notification (ECN) to IP</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3207.txt"> RFC 3207: SMTP Service Extension for Secure SMTP over Transport Layer Security</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3369.txt"> RFC 3369: Cryptographic Message Syntax (CMS)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3370.txt"> RFC 3370: Cryptographic Message Syntax (CMS) Algorithms</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3834.txt"> RFC 3834: Recommendations for Automatic Responses to Electronic Mail</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4033.txt"> RFC 4033: DNS Security Introduction and Requirements</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4034.txt"> RFC 4034: Resource Records for the DNS Security Extensions</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4035.txt"> RFC 4035: Protocol Modifications for the DNS Security Extensions</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4051.txt"> RFC 4051: Additional XML Security Uniform Resource Identifiers (URIs)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4055.txt">RFC 4055: Additional Algorithms and Identifiers for RSA Cryptography for use in the Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4056.txt">RFC 4056: Use of the RSASSA-PSS Signature Algorithm in Cryptographic Message Syntax (CMS)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4109.txt">RFC 4109: Algorithms for Internet Key Exchange version 1 (IKEv1)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4217.txt">RFC 4217: Securing FTP with TLS</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4250.txt">RFC 4250: The Secure Shell (SSH) Protocol Assigned Numbers</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4251.txt">RFC 4251: The Secure Shell (SSH) Protocol Architecture</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4252.txt">RFC 4252: The Secure Shell (SSH) Authentication Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4253.txt">RFC 4253: The Secure Shell (SSH) Transport Layer Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4254.txt">RFC 4254: The Secure Shell (SSH) Connection Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4255.txt">RFC 4255: Using DNS to Securely Publish Secure Shell (SSH) Key Fingerprints</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4256.txt">RFC 4256: Generic Message Exchange Authentication for the Secure Shell Protocol (SSH)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4301.txt">RFC 4301: Security Architecture for the Internet Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4302.txt">RFC 4302: IP Authentication Header</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4303.txt">RFC 4303: IP Encapsulating Security Payload (ESP)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4308.txt">RFC 4308: Cryptographic Suites for IPsec</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4344.txt">RFC 4344: The Secure Shell (SSH) Transport Layer Encryption Modes</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4346.txt">RFC 4346: The Transport Layer Security (TLS) Protocol Version 1.1</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4359.txt">RFC 4359: The Use of RSA/SHA-1 Signatures within Encapsulating
Security Payload (ESP) and Authentication Header (AH)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4366.txt">RFC 4366: Transport Layer Security (TLS) Extensions</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4513.txt">RFC 4513: Lightweight Directory Access Protocol (LDAP): Authentication Methods and Security Mechanisms</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4871.txt">RFC 4871: DomainKeys Identified Mail (DKIM) Signatures</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4959.txt">RFC 4959: IMAP Extension for Simple Authentication and Security Layer (SASL) Initial Client Response</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4985.txt">RFC 4985: Internet X.509 Public Key Infrastructure Subject Alternative Name for Expression of Service Name</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5070.txt">RFC 5070: The Incident Object Description Exchange Format</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5321.txt">RFC 5321: Simple Mail Transfer Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5322.txt">RFC 5322: Internet Message Format</a></li>
<li><a href="https://www.ietf.org/rfc/rfc5901.txt">RFC 5901: Extensions to the IODEF-Document Class for Reporting Phishing</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6045.txt">RFC 6045: Real-time Inter-network Defense (RID)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6409.txt">RFC 6409: Message Submission for Mail</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6528.txt">RFC 6528: Defending against Sequence Number Attacks</a></li>
</ul>

<p><b>Informational</b></p>

<ul>
 <li><a href="https://www.ietf.org/rfc/rfc1281.txt"> RFC 1281: Guidelines for the Secure Operation of the Internet</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc1321.txt"> RFC 1321: The MD5 Message-Digest Algorithm</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc1470.txt"> RFC 1470: Tools for Monitoring and Debugging TCP/IP Internets and Interconnected Devices</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc1750.txt"> RFC 1750: Randomness Recommendations for Security</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2076.txt"> RFC 2076: Common Internet Message Headers</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2196.txt"> RFC 2196: Site Security Handbook</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2411.txt"> RFC 2411: IP Security Document Roadmap</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2504.txt"> RFC 2504: Users Security Handbook</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2577.txt"> RFC 2577: FTP Security Considerations</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc2979.txt"> RFC 2979: Behavior of and Requirements for Internet Firewalls</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3067.txt"> RFC 3067: TERENA's Incident Object Description and Exchange Format Requirements</a></li>
 <li><a href="https://www.ietf.org/rfc/rfc3098.txt"> RFC 3098: How to Advertise Responsibly Using E-Mail and Newsgroups or — how NOT to $$$$$  MAKE ENEMIES FAST!  $$$$$</a></li>

<li><a href="https://www.ietf.org/rfc/rfc3164.txt">RFC 3164: The BSD syslog Protocol</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3174.txt">RFC 3174: US Secure Hash Algorithm 1 (SHA1)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3330.txt">RFC 3330: Special-Use IPv4 Addresses</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3511.txt">RFC 3511: Benchmarking Methodology for Firewall Performance</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3631.txt">RFC 3631: Security Mechanisms for the Internet</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3833.txt">RFC 3833: Threat Analysis of the Domain Name System (DNS)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3871.txt">RFC 3871: Operational Security Requirements for Large Internet Service Provider (ISP) IP Network Infrastructure</a></li>
<li><a href="https://www.ietf.org/rfc/rfc3964.txt">RFC 3964: Security Considerations for 6to4</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4096.txt">RFC 4096: Policy-Mandated Labels Such as "Adv:" in Email Subject Headers Considered Ineffective At Best</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4270.txt">RFC 4270: Attacks on Cryptographic Hashes in Internet Protocols</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4272.txt">RFC 4272: BGP Security Vulnerabilities Analysis</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4381.txt">RFC 4381: Analysis of the Security of BGP/MPLS IP Virtual Private Networks (VPNs)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4641.txt">RFC 4641: DNSSEC Operational Practices</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4686.txt">RFC 4686: Analysis of Threats Motivating DomainKeys Identified Mail (DKIM)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4766.txt">RFC 4766: Intrusion Detection Message Exchange Requirements</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4772.txt">RFC 4772: Security Implications of Using the Data Encryption Standard (DES)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4778.txt">RFC 4778: Current Operational Security Practices in Internet Service Provider Environments</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4890.txt">RFC 4890: Recommendations for Filtering ICMPv6 Messages in Firewalls</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4891.txt">RFC 4891: Using IPsec to Secure IPv6-in-IPv4 Tunnels</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4942.txt">RFC 4942: IPv6 Transition/Coexistence Security Considerations</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4986.txt">RFC 4986: Requirements Related to DNS Security (DNSSEC) Trust Anchor Rollover</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4949.txt">RFC 4949: Internet Security Glossary, Version 2</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6092.txt">RFC 6092: Recommended Simple Security Capabilities in Customer Premises Equipment (CPE) for Providing Residential IPv6 Internet Service</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6274.txt">RFC 6274: Security Assessment of the Internet Protocol Version 4</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6305.txt">RFC 6305: I'm Being Attacked by PRISONER.IANA.ORG!</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6471.txt">RFC 6471: Overview of Best Email DNS-Based List (DNSBL) Operational Practices</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6480.txt">RFC 6480: An Infrastructure to Support Secure Internet Routing</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6561.txt">RFC 6561: Recommendations for the Remediation of Bots in ISP Networks</a></li>
<li><a href="https://www.ietf.org/rfc/rfc7123.txt">RFC 7123: Security Implications of IPv6 on IPv4 Networks</a></li>
</ul>

<p><b>Experimental / Historic</b></p>

<ul>
<li><a href="https://www.ietf.org/rfc/rfc4406.txt"> RFC 4406: Sender ID: Authenticating E-Mail</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4408.txt"> RFC 4408: Sender Policy Framework (SPF) for Authorizing Use of Domains in E-Mail, Version 1</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4765.txt"> RFC 4765: The Intrusion Detection Message Exchange Format (IDMEF)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc4767.txt"> RFC 4767: The Intrusion Detection Exchange Protocol (IDXP)</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6541.txt"> RFC 6541: DomainKeys Identified Mail (DKIM) Authorized Third-Party Signatures</a></li>
<li><a href="https://www.ietf.org/rfc/rfc6587.txt"> RFC 6587: Transmission of Syslog Messages over TCP </a></li>
</ul>

<br>
</details>

<!-- ################################# -->

<details>
<summary><b>Sites of Interest</b></summary>
<br>

<ul>
<li><a href="https://www.cve.org">https://www.cve.org</a></li>
<li><a href="https://www.cvedetails.com">https://www.cvedetails.com</a></li>
<li><a href="https://www.openwall.com">https://www.openwall.com</a></li>
<li><a href="https://www.lkrg.org">https://www.lkrg.org</a></li>
<li><a href="https://www.attack.mitre.org">https://www.attack.mitre.org</a></li>
<li><a href="https://www.exterro.com">https://www.exterro.com</a></li>
<li><a href="https://www.forensicfocus.com">https://www.forensicfocus.com</a></li>
<li><a href="https://www.forensicscijournal.com">https://www.forensicscijournal.com</a></li>
<li><a href="https://www.hackthebox.com">https://www.hackthebox.com</a></li>
<li><a href="https://www.hackerone">https://www.hackerone</a></li>
<li><a href="https://www.hackread.com">https://www.hackread.com</a></li>
<li><a href="https://www.htcia.org">https://www.htcia.org</a></li>
<li><a href="https://www.osforensics.com">https://www.osforensics.com</a></li>
<li><a href="https://www.magnetforensics.com">https://www.magnetforensics.com</a></li>
<li><a href="https://www.exterro.com/ftk-product-downloads/how-to-run-ftk-imager-from-a-flash-drive-imager-lite">FTK Lite</a><br>
<li><a href="https://www.icann.org/en/ssac/publications">SSAC Publications</a></li>
<li><a href="https://www.cert.org/archive/pdf/Botnets.pdf">Botnets as a Vehicle for Online Crime</a> — CERT </li>
<li><a href="https://www.security-audit.com/">Security Audit</a></li>
<li><a href="https://www.sans.org/">SANS Institute</a></li>
<li><a href="https://isc.sans.org/">Internet Storm Center</a> — SANS Institute</li>
<li><a href="https://www.cerias.purdue.edu">COAST Hotlist: Computer Security, Law and Privacy</a> — CERIAS, Purdue University</li>
</ul>
</ul>

<br>
</details>

<!-- ################################# -->

<details>
<summary><b>General Publications</b></summary>
<br>

• CVE Alerting Platform<br>
https://github.com/opencve/opencve<br>
• The Hacker News — Newsletter<br>
https://thehackernews.com/#email-outer<br>
• Forensic Focus — Newsletter<br>
https://www.forensicfocus.com<br>
SANS Institute — Newsletter<br>
https://www.sans.org> <br>
• Google Scholar — Alerts<br>
https://scholar.google.com/scholar_alerts?view_op=list_alerts&hl=en-US<br>
• Wired News<br>
https://www.wired.com<br>
• Cert Coordination Center<br>
https://www.cert.org<br>
• DoD Instructions Cybersecurity<br>
https://www.esd.whs.mil/dd/<br>
• Computer World<br>
https://computerworld.com<br>
• InfoWorld<br>
https://www.infoworld.com<br>
• InformationWeek<br>
https://www.informationweek.com<br>
• Sophos<br>
https://sophos.com<br>
• TechWorld<br>
https://www.techworld.com<br>
• Government Executive Magazine<br>
https://govexec.com<br>
• E Security Planet<br>
https://www.esecurityplanet.com<br>
• Help Net Security<br>
https://www.helpnetsecurity.com<br>
• Information Security Magazine<br>
https://searchsecurity.techtarget.com<br>
• Network World Fusion<br>
https://www.nwfusion.com<br>
• Federal Computer Week Security News<br>
https://fcw.com/Home.aspx<br>
• Government Computer News IT Security<br>
https://gcn.com/Home.aspx<br>
• IA Technology Analysis Center<br>
https://iac.dtic.mil/csiac<br>
• Overseas Security Advisory Council<br>
https://www.osac.gov<br>
• SANS Internet Storm Center<br>
https://isc.sans.edu<br>
• Search Security<br>
https://searchsecurity.techtarget.com<br>
• News Factor<br>
https://www.newsfactor.com<br>
• Security Focus<br>
https://www.securityfocus.com/news<br>
• New Scientist<br>
https://www.newscientist.com/section/news<br>
• Silicon Valley<br>
https://www.siliconvalley.com<br>
• USA Today<br>
https://www.usatoday.com/tech<br>
• Reuters<br>
https://www.reuters.com/news/technology<br>
• TechWeb<br>
https://www.techweb.com<br>

<br>
</details>

<!-- ################################# -->

<details>
<summary><b>Forensic Publications</b></summary>
<br>
<p>• Make a Google Scholar search from an interesting subject that you want to follow up on.</p>

<p>• Search paramters example:</p>

<pre>police hacking intext:ilegal intext:abusive intext:law</pre>

<p>• You could set keywords alerts: https://scholar.google.com/scholar_alerts?view_op=list_alerts</p>

<hr>

• Science Direct — Forensic Science International: Digital Investigation<br>
https://www.sciencedirect.com/journal/forensic-science-international-digital-investigation<br>
• Science Direct — Computer Law & Security Review<br>
https://www.sciencedirect.com/journal/computer-law-and-security-review<br>
• Forensic Science — Application of science to criminal and civil laws<br>
https://www.forensicscijournal.com<br>
• University of London - SAS Open Journals - Digital Evidence and Electronic Signature Law Review<br>
https://journals.sas.ac.uk/deeslr/<br>
• International Journal of Intelligence and CounterIntelligence<br>
https://www.tandfonline.com/journals/ujic20<br>
• Information Security Journal: A Global Perspective<br>
https://www.tandfonline.com/journals/uiss20<br>
• Policing and Society — An International Journal of Research and Policy<br>
https://www.tandfonline.com/journals/gpas20<br>
• Police Practice and Research — An International Journal<br>
https://www.tandfonline.com/journals/gppr20<br>
• Journal of Applied Security Research<br>
https://www.tandfonline.com/journals/wasr20<br>
• Information Systems Security<br>
https://www.tandfonline.com/journals/uiss19<br>
• Journal of Computer Information Systems<br>
https://www.tandfonline.com/journals/ucis20<br>
• Australian Journal of Forensic Sciences<br>
https://www.tandfonline.com/journals/tajf20<br>
• Advancing Technology, Research and Collaboration<br>
https://www.acm.org/conferences<br>
• The APWG Symposium on Electronic Crime Research (APWG eCrime)<br>
https://ecrimeresearch.org<br>
• Communications in Computer and Information Science — Springer<br>
https://www.springer.com/series/7899<br>
• IEEE Intelligence and Security Informatics (ISI)<br>
https://ieee-isi.org/<br>

<br>
</details>

<details>
<summary><b>Intelligence, Conflict, and Warfare Publications</b></summary>
<br>

• Taylor & Francis - Intelligence and National Security - Open access articles
https://www.tandfonline.com/action/showOpenAccess?journalCode=fint20
• The Journal of Intelligence, Conflict, and Warfare
https://journals.lib.sfu.ca/index.php/jicw/issue/archive
• CIA.gov - Center for the study of intelligence
https://www.cia.gov/resources/csi/studies-in-intelligence/
• DCAF - Geneva Centre for Security Sector Governance
https://www.dcaf.ch/resources?type=publications
• E-International Relations - Open access scholarly books 
https://www.e-ir.info/publications/

<br>
</details>

<details>
<summary><b>Law Publications</b></summary>
<br>

https://www.necessaryandproportionate.org<br>
https://www.fbi.gov<br>
https://www.justice.gov/news<br>
• Computer Crime Research Center - https://www.crime-research.org<br>
• Internet Crime Complaint Center (IC3) - https://www.ic3.gov/Home/AnnualReports<br>
https://www.justice.gov/criminal/cybercrime<br>
https://www.coe.int/en/web/cybercrime<br>
https://www.sherloc.unodc.org<br>
https://www.enisa.europa.eu<br>
https://csrc.nist.gov
https://openyls.law.yale.edu<br>
https://scholarship.law.duke.edu<br>
https://law.utexas.edu/transnational/foreign-law-translations<br>
∙ The IT Law Wiki - https://itlaw.fandom.com<br>

<br>
</details>

<!-- ################################ -->

<details>
<summary><b>YouTube Conferences</b></summary>
https://www.youtube.com/@BlackHatOfficialYT<br>
https://www.youtube.com/@DEFCONConference<br>
https://www.youtube.com/@DFRWS<br>
https://www.youtube.com/@SANSForensics<br>
https://www.youtube.com/@SANSOffensiveOperations<br>
https://www.youtube.com/@RSAConference<br>
https://www.youtube.com/@USENIXEnigmaConference<br>
https://www.youtube.com/@DebConfVideos<br>
https://www.youtube.com/@hitbsecconf<br>
https://www.youtube.com/@44contv<br>
https://www.youtube.com/@OffensiveCon<br>
https://www.youtube.com/@secwestnet<br>
https://www.youtube.com/@EkopartyConference<br>
https://www.youtube.com/@reconmtl<br>
https://www.youtube.com/@TROOPERScon<br>
https://www.youtube.com/@MCH2022NL<br>

<br>
</details>

<!-- ################################ -->

<details>
<summary><b>Others</b></summary>
<br>
• Computer Incident Response Center for Civil Society - https://www.civicert.org<br>
https://0x00sec.org<br>
https://csrc.nist.gov/projects<br>
https://malware.lu<br>
https://www.nsa.gov/ia/mitigation_guidance/security_configuration_guides/index.shtml<br>
https://oval.mitre.org<br>
https://www.w3.org/Security/Faq/www-security-faq.html<br>
https://www.nowsecure.com<br>
https://www.reddit.com/r/InfoSecNews<br>
https://www.reddit.com/r/digitalforensics<br>
https://www.reddit.com/r/computerforensics<br>
https://www.reddit.com/r/antiforensics<br>
https://www.reddit.com/r/Smartphoneforensics<br>
https://github.com/yeahhub/Hacking-Security-Ebooks<br>
https://github.com/InfoSecIITR/reading-material<br>

<br>
</details>

<!-- ################################ -->

<h3>REFERENCES</h3>

<table style="width:100%" cellspacing="0" cellpadding="0">
<thead>
  <tr>
  </tr>
</thead>
<tbody> 
<tr>
<td valign="top" style="width:50%">
https://dfrws.org/presentation<br>
https://issworldtraining.com<br>
https://sciencedirect.com/journal/forensic-science-international-digital-investigation<br>
https://sciencedirect.com/journal/computer-law-and-security-review<br>
https://github.com/MISP/misp-training<br>
https://github.com/ail-project/ail-training<br>
https://isc2.org/Certifications/CISSP<br>
https://github.com/connectans/awesome-CISSP-CCSP<br>
https://github.com/jefferywmoore/CISSP-Study-Resources<br>
https://github.com/Syslifters/OffSec-Reporting<br>
https://attack.mitre.org<br>
https://forensicfocus.com<br>
https://ecrimeresearch.org<br>
https://drivebadger.com<br>
https://cellebritelearningcenter.com<br>
https://public.cyber.mil<br>
</td>
<td valign="top" style="width:50%">
https://github.com/Cugu/awesome-forensics<br>
https://github.com/shadawck/awesome-anti-forensic<br>
https://github.com/Ignitetechnologies/Mindmap<br>
https://github.com/asiamina/A-Course-on-Digital-Forensics<br>
https://github.com/mikeroyal/Digital-Forensics-Guide<br>
https://github.com/forensicswiki/wiki<br>
https://github.com/Digital-Forensics-Discord-Server/LawEnforcementResources<br>
https://github.com/Digital-Forensics-Discord-Server/TheHitchhikersGuidetoDFIRExperiencesFromBeginnersandExperts<br>
https://github.com/Hack-with-Github/Awesome-Hacking<br>
https://github.com/enaqx/awesome-pentest<br>
https://github.com/onlurking/awesome-infosec<br>
https://github.com/504ensicsLabs<br>
</td>
</tr>
</tbody>
</table>

<!--################################### -->
<br>

<p align="right"> <a href="https://github.com/RENANZG/My-Forensics?tab=readme-ov-file#">Back to Top ⬆</a> </p>

<!--################################### -->

<div id="footer">

<br>
<br>
<br>

<p align="center">Made with ♥</p>
</div>

<!--################################### -->

</body>
</html>
