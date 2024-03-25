Microsoft Office Language Pack
---

This section describes the design decisions associated with the Microsoft Office Language Pack.

Language packs add additional display, help and proofing tools to Microsoft Office. Multiple language packs can be installed to support specific user requirements. If additional language packs are installed it is also likely that keyboards other than US will be required.


| Decision Point      | Design Decision           | Justification                                                                                                                                                                                                                                               |
|---------------------|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Default Language    | English (UK) – AU Default | Required to support the Microsoft Office deployment and enable user productivity.<br>English (US) language pack is removed from the SOE as part of the English (UK) install. English (UK) contains the AU region language pack which is then set as default. |
| Additional Language | Not Configured            | Additional languages will be installed if required to meet organisation requirements.                                                                                                                                                                       |


### Related information

#### Security & Governance

* None identified

#### Design

* None identified

#### References

* [Add Microsoft 365 Apps to Windows 10/11 devices with Microsoft Intune](https://learn.microsoft.com/mem/intune/apps/apps-add-office365)
