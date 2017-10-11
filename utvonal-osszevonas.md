# Útvonal-összevonás
---

- 192.168.10.0/24
- 192.168.20.0/24
- 192.168.40.0/24

---

felírjuk a harmadik okteteket binárisban <br>
10 = 00|00 1010 <br>
20 = 00|01 0100 <br>
40 = 00|10 1000 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;^ eddig egyeznek

prefix = 8+8+2 = 18 <br>
összevont hálózat: 192.168.0.0/18

---

- 10.128.0.0/16
- 10.200.0.0/16
- 10.150.0.0/16

128 = 1|000 0000 <br>
200 = 1|100 1000 <br>
150 = 1|001 0110 <br>

új prefix = 9 <br>
összevont hálózat: 10.128.0.0/9
