# Inf-pushing-scripts
This is a set of infinity pushing scripts that I made for 12h, 24h, 72h, and 192h runs.
Note that it may take multiple tries for the AI to not die.
In the "Start of pushing" script you MUST replace the ****imput time interval here (12h, 24h, 72h, 192h)**** in line 9 with the time you want DO NOT remove the "autopush".
Note that era floor should be on

Tower death protocol: 
```
FHRvd2VyIGRlYXRoIHByb3RvY29sAQAAAAVrZXkuMQAAAAANAAAAEWdlbmVyaWMud2FpdHVudGlsEWNvbXBhcmlzb24uZG91YmxlDHRvd2VyLmhlYWx0aAhjb25zdGFudAEACGNvbnN0YW50BAI9PQhjb25zdGFudAMAAAAAAAAAAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAAJEAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCDQAAABFjb21wYXJpc29uLmRvdWJsZQx0b3dlci5oZWFsdGgIY29uc3RhbnQBAAhjb25zdGFudAQCIT0IY29uc3RhbnQDAAAAAAAAAAAMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BBBzdGFydCBvZiBwdXNoaW5nDGdlbmVyaWMuc3RvcAhjb25zdGFudAQMMTJoIGF1dG9wdXNoDGdlbmVyaWMuc3RvcAhjb25zdGFudAQMMjRoIGF1dG9wdXNoDGdlbmVyaWMuc3RvcAhjb25zdGFudAQMNzJoIGF1dG9wdXNoDGdlbmVyaWMuc3RvcAhjb25zdGFudAQNMTkyaCBhdXRvcHVzaAxnZW5lcmljLnN0b3AIY29uc3RhbnQEDGVyYSBkaXNhYmxlcw1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A2ZmZmZmZuI/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A2ZmZmZmZtY/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEEHN0YXJ0IG9mIHB1c2hpbmcRZ2VuZXJpYy53YWl0dW50aWwRY29tcGFyaXNvbi5kb3VibGUMdG93ZXIuaGVhbHRoCGNvbnN0YW50AQAIY29uc3RhbnQEAiE9CGNvbnN0YW50AwAAAAAAAAAADGdlbmVyaWMuZ290bwhjb25zdGFudAIBAAAA
```

Era disables: 
```
DEVyYSBkaXNhYmxlcwAAAAAAAAAAEgAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A9nO91PjpdM/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3E9CtejcNU/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAgGhAEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A4GVQ4ts56s/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA5nZW5lcmljLnNsaWRlcghjb25zdGFudAUAANJCAABBQwhjb25zdGFudAMAAAAAAADwPwxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAA8D8NZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMrhxbZzvezPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANcj8L1KFzPPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAABRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABgY0ARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQD9ihcj8L12D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWxvY2FsLmludC5zZXQIY29uc3RhbnQECXdobyBjYXJlcw5hcml0aG1ldGljLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAl3aG8gY2FyZXMIY29uc3RhbnQEASsIY29uc3RhbnQCAQAAAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAA8D8NZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAM9CtejcD3KPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANcj8L1KFzrPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCCAAAAA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAl3aG8gY2FyZXMIY29uc3RhbnQEAjw9CGNvbnN0YW50AioAAAANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAM9CtejcD3KPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMfhetRuB7tPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCCAAAAA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAl3aG8gY2FyZXMIY29uc3RhbnQEAiE9CGNvbnN0YW50AlQAAAAMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAbKtADmdlbmVyaWMuc2xpZGVyCGNvbnN0YW50BQAA0kIAAEFDCGNvbnN0YW50AwAAAAAAAAAADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAgZEARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDO3DOiNLe2D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAADAY0ARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQD/tR46SYx5D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDGdlbmVyaWMuZ290bwhjb25zdGFudAIQAAAA
```

Start of pushing: 
```
EHN0YXJ0IG9mIHB1c2hpbmcBAAAABWtleS4xAAAAAA8AAAAOZ2xvYmFsLmludC5zZXQIY29uc3RhbnQELW5vdGUgdGhpcyBzY3JpcHQgd29uJ3QgdXNlIGNyaXRpY2FsIHdhdmUganVtcAhjb25zdGFudAIAAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BDl5b3UgYWxzbyBuZWVkIHRvIGltcHV0IHRoZSBudW1iZXIgb2YgaG91cnMgeW91IHdhbnQgdG8gZ28IY29uc3RhbnQCAAAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQVYmVmb3JlIHRoZSAiYXV0b3B1c2giCGNvbnN0YW50AgAAAAAQdG93bi53aW5kb3cuc2hvdwhjb25zdGFudAQMdG93ZXJ0ZXN0aW5nCGNvbnN0YW50AQENZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAO8lpAPejbfPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPD9Shcj8LlPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAAAhADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQD9ihcj8L10D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDIO9VKxN+sT8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kEWdlbmVyaWMud2FpdHVudGlsEWNvbXBhcmlzb24uZG91YmxlDHRvd2VyLmhlYWx0aAhjb25zdGFudAEACGNvbnN0YW50BAIhPQhjb25zdGFudAMAAAAAAAAAABNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BDoqaW5zZXJ0IHRpbWUgaW50ZXJ2YWwgaGVyZSAoMTJoLCAyNGgsIDcyaCwgMTkyaCkqIGF1dG9wdXNoEWdlbmVyaWMud2FpdHVudGlsEWNvbXBhcmlzb24uZG91YmxlDHRvd2VyLmhlYWx0aAhjb25zdGFudAEACGNvbnN0YW50BAI9PQhjb25zdGFudAMAAAAAAAAAABB0b3duLndpbmRvdy5zaG93CGNvbnN0YW50BAx0b3dlcnRlc3RpbmcIY29uc3RhbnQBAQ1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3Noke18P9c/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3ctIR/0bOA/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A0jhehSuR9E/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A8P1KFyPwrU/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAACEAMZ2VuZXJpYy5nb3RvCGNvbnN0YW50AgEAAAA=
```

12h autopush: 
```
DDEyaCBhdXRvcHVzaAAAAAAAAAAAFgAAAA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEDGVyYSBkaXNhYmxlcwxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAMBM2EAMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BAxlcmEgZGlzYWJsZXMNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAABuQBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPNzMzMzMzkPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAHB2QBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOamZmZmZnpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQSZ2VuZXJpYy5zY3JvbGxyZWN0DnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A/YoXI/C9ew/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3E9CtejcN0/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZAhjb25zdGFudAMAAAAAAAAAAAhjb25zdGFudAMAAAAAAAAAAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAAFEANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DhPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMpXI/C9SjgPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAN7FK5H4XrsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPD9Shcj8LpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAA4tFADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAbkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDzczMzMzM5D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABwdkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDmpmZmZmZ6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kEmdlbmVyaWMuc2Nyb2xscmVjdA52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAP2KFyPwvXsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DdPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQIY29uc3RhbnQDAAAAAAAAAAAIY29uc3RhbnQDAAAAAAAAAAAMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAABRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDcT0K16Nw4T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDKVyPwvUo4D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDexSuR+F67D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDw/UoXI/C6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAOEARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDwOyePCzUqj8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAIQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA==
```

24h autopush: 
```
DDI0aCBhdXRvcHVzaAAAAAAAAAAAFgAAAA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEDGVyYSBkaXNhYmxlcwxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAMBM6EAMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BAxlcmEgZGlzYWJsZXMNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAABuQBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPNzMzMzMzkPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAHB2QBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOamZmZmZnpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQSZ2VuZXJpYy5zY3JvbGxyZWN0DnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A/YoXI/C9ew/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3E9CtejcN0/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZAhjb25zdGFudAMAAAAAAAAAAAhjb25zdGFudAMAAAAAAAAAAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAAFEANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DhPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMpXI/C9SjgPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAN7FK5H4XrsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPD9Shcj8LpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAACg4uFADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAbkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDzczMzMzM5D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABwdkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDmpmZmZmZ6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kEmdlbmVyaWMuc2Nyb2xscmVjdA52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAP2KFyPwvXsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DdPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQIY29uc3RhbnQDAAAAAAAAAAAIY29uc3RhbnQDAAAAAAAAAAAMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAABRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDcT0K16Nw4T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDKVyPwvUo4D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDexSuR+F67D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDw/UoXI/C6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAOEARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDwOyePCzUqj8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAIQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA==
```

72h autopush: 
```
DDcyaCBhdXRvcHVzaAAAAAAAAAAAFgAAAA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEDGVyYSBkaXNhYmxlcwxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAJg5AkEMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BAxlcmEgZGlzYWJsZXMNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAABuQBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPNzMzMzMzkPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAHB2QBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOamZmZmZnpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQSZ2VuZXJpYy5zY3JvbGxyZWN0DnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A/YoXI/C9ew/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3E9CtejcN0/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZAhjb25zdGFudAMAAAAAAAAAAAhjb25zdGFudAMAAAAAAAAAAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAAFEANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DhPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAOF61G4HoXrPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMpXI/C9SjgPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAN7FK5H4XrsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAPD9Shcj8LpPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAACA1PpADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAbkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDzczMzMzM5D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABwdkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDmpmZmZmZ6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kEmdlbmVyaWMuc2Nyb2xscmVjdA52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAP2KFyPwvXsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DdPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQIY29uc3RhbnQDAAAAAAAAAAAIY29uc3RhbnQDAAAAAAAAAAAMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAABRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDcT0K16Nw4T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDKVyPwvUo4D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDexSuR+F67D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDw/UoXI/C6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAOEARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDwOyePCzUqj8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAIQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Ax+F61G4HtE/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfhetQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA==
```

192h autopush: 
```
DTE5MkggYXV0b3B1c2gAAAAAAAAAABYAAAAPZ2VuZXJpYy5leGVjdXRlCGNvbnN0YW50BAxlcmEgZGlzYWJsZXMMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAADMTBhBDGdlbmVyaWMuc3RvcAhjb25zdGFudAQMZXJhIGRpc2FibGVzDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAAbkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDzczMzMzM5D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABwdkARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDmpmZmZmZ6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kEmdlbmVyaWMuc2Nyb2xscmVjdA52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAP2KFyPwvXsPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudANxPQrXo3DdPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQIY29uc3RhbnQDAAAAAAAAAAAIY29uc3RhbnQDAAAAAAAAAAAMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAABRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDcT0K16Nw4T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDhetRuB6F6z8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDKVyPwvUo4D8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDexSuR+F67D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDw/UoXI/C6T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kDGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAIOMRQQ1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAAG5AEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A83MzMzMzOQ/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAcHZAEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A5qZmZmZmek/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZBJnZW5lcmljLnNjcm9sbHJlY3QOdmVjLmZyb21Db29yZHMRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQD9ihcj8L17D8IY29uc3RhbnQEASoOc2NyZWVuLndpZHRoLmQRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDcT0K16Nw3T8IY29uc3RhbnQEASoPc2NyZWVuLmhlaWdodC5kCGNvbnN0YW50AwAAAAAAAAAACGNvbnN0YW50AwAAAAAAAAAADGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAUQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A4XrUbgehes/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3E9CtejcOE/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A4XrUbgehes/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50Aylcj8L1KOA/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A3sUrkfheuw/CGNvbnN0YW50BAEqDnNjcmVlbi53aWR0aC5kEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A8P1KFyPwuk/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAADhAEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50A8Dsnjws1Ko/CGNvbnN0YW50BAEqD3NjcmVlbi5oZWlnaHQuZAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAACEANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMfhetRuB7RPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAN7FK5H4XrUPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQNZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3JkcxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMfhetRuB7RPwhjb25zdGFudAQBKg5zY3JlZW4ud2lkdGguZBFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAN7FK5H4XrUPwhjb25zdGFudAQBKg9zY3JlZW4uaGVpZ2h0LmQ=
```

