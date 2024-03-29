# GPO

## Acronyme
* ADMX : 
* ADML :
* GP - Group Policy

---

## URL
* https://admx.help/

---

## Tools
1. [REGISTRY.POL](https://sdmsoftware.com/389932-gpo-freeware-downloads/registry-pol-viewer-utility/)

---

## ADMX
### File reference
* ADMX & ADML
    * Central Store for GP admx files :
       * Syntax : `\\forest.root\SYSVOL\forest.root\policies\`
       * Demo : `\\contoso.com\SYSVOL\contoso.com\policies\`
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
