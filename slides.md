<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

### FACT demo
![](img/FACT_smaller.png)

<u>**F**</u>irmware <u>**A**</u>nalysis and <u>**C**</u>omparison <u>**T**</u>ool

[__`frak`__][1]`|2021-12-03`
[1]: https://github.com/frakman1


----  ----

## Project Page
Free & Open Source Software
<section style="text-align: left;"> Homepage: https://fkie-cad.github.io/FACT_core/index.html

Wiki: https://github.com/fkie-cad/FACT_core/wiki

Github: https://github.com/fkie-cad/FACT_core

----  ----

### Goal
Speed up firmware security analysis and vulnerability hunting via automation
<img src="img/FACT_Vulnerability_Hunting.png"/>





----  ----

### Challenge:    <span style="color:goldenrod">Firmware Extraction</span>

- Firmware extraction is time consuming
- Identify container format
- Use appropriate unpacker
- If none exist, use `binwalk` 
- Redo for multiple layers


----  ----

### Challenge:    <span style="color:goldenrod">Initial Firmware Analysis</span>

- Find out as much as possible to identify potential risks and vulnerabilities
- Software identification
  - Which OS is used?
  - Which programs are present?
  - Which versions are used?
  - Which services are started on boot?
  - Are there any well-known vulnerabilities? (CVEs)

----  ----

### Challenge:    <span style="color:goldenrod">Initial Firmware Analysis</span>

- Find login credentials, especially hard-coded passwords

- Crypto material detection
  - private keys
  - certificates

- Detect CPU architecture (needed for emulation and disassembling)
- Check if executable utilizing QEMU (needed for fuzzing and debugging)
- Look for implementation flaws (CWEs)

----  ----

### Challenge:    <span style="color:goldenrod">Initial Firmware Analysis</span>
<img src="img/fact_concept_initial_analysis.png"/>


----  ----

### Challenge:    <span style="color:goldenrod">Firmware Comparison</span>

- Confirm a fix is implemented between versions
- Identify changed / equal files
- Identify changed software versions

----  ----

### Challenge:    <span style="color:goldenrod">Firmware Comparison</span>
<img src="img/fact_concept_compare.png"/>


----  ----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Features / Plugins
<img src="img/features.png"/>


----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Main Page
<img src="img/01_main.png"/>


----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Upload Page
<img src="img/02_upload.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Firmware View 
<img src="img/03_firmware_view.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Users & Passwords
<img src="img/04_users_and_passwords.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### CVE Lookup Page
<img src="img/05_cve_lookup.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Binwalk Page
<img src="img/06_binwalk.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### QEMU exec Page
<img src="img/07_qemu_exec.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Compare Page
<img src="img/08_compare.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### System Page
<img src="img/09_system.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### User Management Page
<img src="img/10_user_management.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Advanced Search Page
<img src="img/11_advanced_search_result.png"/>


----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Yara Search Page
<img src="img/12_yara_search.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Radare
<img src="img/13_radare_main.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Radare
<img src="img/14_radare.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Radare
<img src="img/15_radare_hex.png"/>

----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
### Device Tree
<img src="img/16_device_tree.png"/>



----  ----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->
<!-- .element: data-background="https://miro.medium.com/max/500/0*XCS4g9J1TFAXHu04.gif"  -->
### 


----  ----


<!-- .element: data-background="img/thankyou.gif" data-state="frakbg"  -->
<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

# <span style="background-color:ggray; font-size:150%; color:tan">`return`&nbsp;</span><span style="background-color:ggray; font-size:150%; color:lightskyblue">`0`</span><span style="background-color:ggray; font-size:150%; color:white">`;`</span>

