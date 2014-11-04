PyFuscator
========================

Based on my VBScript Obfuscation Script, allows python script random obfuscation with different outputs every time.


Script output (first run)
========================
```
C:\Projects\PyFuscator>python PyFuscate.py clean_script.py output.py
Converting char 112 => 4662-4550
Converting char 114 => 922602/8093
Converting char 105 => 9549-9444
Converting char 110 => -5795+5905
Converting char 116 => -4363+4479
Converting char 32 => 143040/4470
Converting char 34 => 191284/5626
Converting char 84 => -943+1027
Converting char 101 => 833351/8251
Converting char 115 => 128455/1117
Converting char 116 => 5272-5156
Converting char 34 => 15504/456
Done!
```

First output
========================
```
C:\Projects\PyFuscator>type output.py
exec(chr(4662-4550)+chr(922602/8093)+chr(9549-9444)+chr(-5795+5905)+chr(-4363+4479)+chr(143040/4470)+chr(191284/5626)+chr(-943+1027)+chr(833351/8251)+chr(128455/1117)+chr(5272-5156)+chr(15504/456))
```

Script output (second run)
========================
```
C:\Projects\PyFuscator>python PyFuscate.py clean_script.py output.py
Converting char 112 => 875952/7821
Converting char 114 => -4389+4503
Converting char 105 => 5135-5030
Converting char 110 => 1671-1561
Converting char 116 => 150452/1297
Converting char 32 => 107104/3347
Converting char 34 => 237932/6998
Converting char 84 => -9899+9983
Converting char 101 => 135037/1337
Converting char 115 => 9085-8970
Converting char 116 => -2607+2723
Converting char 34 => -1454+1488
Done!
```

Second output
========================
```
C:\Projects\PyFuscator>type output.py
exec(chr(875952/7821)+chr(-4389+4503)+chr(5135-5030)+chr(1671-1561)+chr(150452/1297)+chr(107104/3347)+chr(237932/6998)+chr(-9899+9983)+chr(135037/1337)+chr(9085-8970)+chr(-2607+2723)+chr(-1454+1488))
```

Obfuscated file execution (prints "Test")
========================
```
C:\Projects\PyFuscator>python output.py
Test

C:\Projects\PyFuscator>
```
