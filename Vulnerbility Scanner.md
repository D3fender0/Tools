# XSS Scanner
## XSSsuccessor 
```
python xssuccessor.py -d "https://domain.com/file.php?parameter=1234"

```
 It simulates real browser requests with custom advanced payloads, effectively bypassing cloud-based WAFs and protections.
 
Download: https://github.com/ronin-dojo/xssuccessor 

## XSStrike
```
python3 xsstrike.py -u https://yourdomain.com/
```
It Instead of injecting payloads and checking it works like all the other tools do, XSStrike analyses the response with multiple parsers and then crafts payloads that are guaranteed to work by context analysis integrated with a fuzzing engine .Download : https://github.com/s0md3v/XSStrike

