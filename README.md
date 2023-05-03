# CA-Export
Tool to help save your CA policys as a html format. 

If not already connected the Script will connect MgGraph to the Beta Endpoint and use the Scopes documented below

```posh
Select-MgProfile -Name "beta"
Connect-MgGraph -Scopes 'Policy.Read.All', 'Directory.Read.All','Application.Read.All'
```

To run the Script use this Command

```posh
.\Export-CaPolicy.MSGraph.ps1
```

![Export-CaPolicy_01](Export-CaPolicy_01.jpg)
![Export-CaPolicy_02](Export-CaPolicy_02.jpg)
![Export-CaPolicy_03](Export-CaPolicy_03.jpg)


Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
