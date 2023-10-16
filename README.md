# VMLTrace
Hyper-V troubleshooting tool; when the error is absolute garbage!

## How to Use
- Open a command prompt as administrator
- Browse to directory where `VmlTrace.exe` lives
- Start the trace with the following arguments: `VMLTrace.exe /m all /f all all /i /l LogFile.etl`
- Reproduce the problem
- Stop the tracer with `VmlTrace.exe /s`
- Convert it to human-friendly format with `netsh trace convert LogFile.etl`

## Available providers
- 51DDFA29-D5C8-4803-BE4B-2ECB715570FE (vmwp)
- 02F3A5E3-E742-4720-85A5-F64C4184E511 (vsconfig)
- 6066F867-7CA1-4418-85FD-36E3F9C0600C (vmms)
- 9193A773-E60D-4171-8468-05C000581B71 (vhdsvc)
- 0A18FF18-5362-4739-9671-78023D747B70 (nvspwmi)
- EDACD782-2564-4497-ADE6-7199377850F2 (synthstor)
- C29C4FB7-B60E-4FFF-9AF9-CF21F9B09A34 (synthnic)
- 09242393-1349-4F4D-9FD7-59CC79F553CE (emulatednic)
- 2B74A015-3873-4C56-9928-EA80C58B2787 (vmicheartbeat)
- 82D60869-5ADA-4D49-B76A-309B09666584 (vmickvpexchan
- BC714241-8EDC-4CE3-8714-AA0B51F98FDF (vmicshutdown)
- F152DC14-A3A0-4258-BECE-69A3EE4C2DE8 (vmictimesync)
- 67E605EE-A4D8-4C46-AE50-893F31E13963 (vmicvss)
- 64E92ABC-910C-4770-BD9C-C3C54699B8F9 (vmclusres)
- 5B621A17-3B58-4D03-94F0-314F4E9C79AE (synthfcvdev)
- 6357c13a-2eb3-4b91-b580-79682eb76986 (fcvspwmi)
- 2ab5188c-5915-4629-9f8f-b3b20c78d1b0 (vmphu)
