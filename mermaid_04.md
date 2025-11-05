```mermaid
flowchart LR
 .gov[".gov"] -->|belongs to| government_organization["government organization"]
 .gov[".gov"] -->|located in| United_States["United States"]
 .gov[".gov"] -->|uses| HTTPS["HTTPS"]
 HTTPS["HTTPS"] -->|indicated by| lock_icon["lock icon"]
 lock_icon["lock icon"] -->|means safe connection to| .gov[".gov"]
 https://["https://"] -->|means safe connection to| .gov[".gov"]
 sensitive_information["sensitive information"] -->|should be shared only on| HTTPS["HTTPS"]
 sensitive_information["sensitive information"] -->|should be shared only on| .gov[".gov"]

 ```
