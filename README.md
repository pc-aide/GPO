# GPO

## Acronyme
* ADMX : 
* ADML :
* GP - Group Policy

---

## URL
* https://admx.help/

---

## ADMX
### File reference
* ADMX & ADML
    * Central Store for GP admx files : `\\<forest.root>\SysVol<forest.root>\Policies\PolicyDefinitions\`
     * %Windir%\PolicyDefinitions\
          * AdmPwd.admx
          * en-US\AdmPwd.adml

### E.g.
* UE-V
    * [<img src="https://i.imgur.com/7bpCRwQg.png">](https://www.microsoft.com/en-us/download/details.aspx?id=55531)
    * MDOP_AMDX_Templates.cab
    * Extract file cab :
      * -F:Files Name of files to expand from a .CAB
      * expand `MDOP_AMDX_Templates.cab -F:* MDOP_ADMX_Template` :
      * [<img src="https://i.imgur.com/HFfJSvrg.png">](https://i.imgur.com/HFfJSvrg.png)
