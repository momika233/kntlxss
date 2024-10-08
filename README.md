```
                                  ,----,    ,--,                                              
       ,--.          ,--.       ,/   .`| ,---.'|                                              
   ,--/  /|        ,--.'|     ,`   .'  : |   | :     ,--,     ,--,    .--.--.      .--.--.    
,---,': / '    ,--,:  : |   ;    ;     / :   : |     |'. \   / .`|   /  /    '.   /  /    '.  
:   : '/ /  ,`--.'`|  ' : .'___,/    ,'  |   ' :     ; \ `\ /' / ;  |  :  /`. /  |  :  /`. /  
|   '   ,   |   :  :  | | |    :     |   ;   ; '     `. \  /  / .'  ;  |  |--`   ;  |  |--`   
'   |  /    :   |   \ | : ;    |.';  ;   '   | |__    \  \/  / ./   |  :  ;_     |  :  ;_     
|   ;  ;    |   : '  '; | `----'  |  |   |   | :.'|    \  \.'  /     \  \    `.   \  \    `.  
:   '   \   '   ' ;.    ;     '   :  ;   '   :    ;     \  ;  ;       `----.   \   `----.   \ 
|   |    '  |   | | \   |     |   |  '   |   |  ./     / \  \  \      __ \  \  |   __ \  \  | 
'   : |.  \ '   : |  ; .'     '   :  |   ;   : ;      ;  /\  \  \    /  /`--'  /  /  /`--'  / 
|   | '_\.' |   | '`--'       ;   |.'    |   ,/     ./__;  \  ;  \  '--'.     /  '--'.     /  
'   : |     '   : |           '---'      '---'      |   : / \  \  ;   `--'---'     `--'---'   
;   |,'     ;   |.'                                 ;   |/   \  ' |                           
'---'       '---'                                   `---'     `--`                            
``` 

**Version:** 1.0.0  
**Author:** btxcode  
**Supported By:** GOME Team

# XSS and SQLi Scanner

## Overview

This is a comprehensive security testing toolkit designed to automate the detection of XSS (Cross-Site Scripting) and SQL injection vulnerabilities. The toolkit includes reflection-based XSS scanning, stored XSS detection, and SQL injection testing, using a range of open-source tools combined in an efficient workflow.

The tools can be executed in parallel for faster results and include features like random user agent (RUA), advanced payload handling, and passive/active parameter discovery.

## Features

- **Reflected and Stored XSS Scanning**: Detects both reflected and stored XSS across multiple input vectors and forms.
- **Random User Agent (RUA)**: Automatically switches user agents to evade simple protection mechanisms.
- **Parallel Processing**: Tools such as Arjun, Katana, and Hakrawler are run in parallel for faster results.
- **Auto-Resume**: If a scan gets interrupted, the tool will automatically resume from where it left off by detecting existing files.
- **Port Stripping**: Automatically removes ports from URLs to ensure consistency in final results.

## Requirements

- **Operating System**: Linux (recommended: Kali Linux)
- **Dependencies**:
  - Python 3.x
  - Google Chrome (for Selenium-based tests)
    ```
    Downlaod :
    https://drive.google.com/file/d/15jfkq584QjJdSdpJsByLFgHi1vUeIIow/view?usp=drive_link
    ```
  - GF (TomNomNom's Gf Patterns)
  - Go language
  - Arjun, Waybackurls, Gau, Katana, Hakrawler

Usage:
```
cd kntlxss
chmod +x *
pip3 install -r requirements.txt
./kntlxss.sh
```

## License

This project is licensed under the MIT License.

### Credits

Thanks to all the amazing [community contributors for sending PRs](https://github.com/btxcode/kntlxss/graphs/contributors) and keeping this project updated. :heart:

If you have an idea or some kind of improvement, you are welcome to contribute and participate in the Project, feel free to send your PR.

<p align="center">
<a href="https://github.com/btxcode/kntlxss/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=btxcode/kntlxss&max=500">
</a>
</p>

