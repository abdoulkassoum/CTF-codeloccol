#  Zoro
```
Level:  Basic , 50pts
```

# Description:

```
There is nothing to see here.

Or maybe .... ?

Flag: CTF_*
```

>We have a text file hackerlab.txt.

As we can see here there is a lot of invisible characters:

`$ xxd hackerlab.txt `
```
00000000: 5448 4520 4841 434b 4552 4c41 42e2 808c  THE HACKERLAB...
00000010: e280 8ce2 808c e280 8ce2 808d e280 8ce2  ................
00000020: 808c efbb bf20 3230 3232 e280 8ce2 808c  ..... 2022......
00000030: e280 8ce2 808c e280 8de2 808d e280 8de2  ................
00000040: 808c 2049 53e2 808c e280 8ce2 808c e280  .. IS...........
00000050: 8ce2 808d e280 8ce2 808d e280 ace2 808c  ................
00000060: e280 8ce2 808c e280 8ce2 808d e280 8def  ................
00000070: bbbf efbb bfe2 808c e280 8ce2 808c e280  ................
00000080: 8ce2 808d efbb bfe2 80ac e280 ac20 4120  ............. A 
00000090: 3438 20e2 808c e280 8ce2 808c e280 8ce2  48 .............
000000a0: 808c efbb bfe2 808c efbb bf48 4f55 5220  ...........HOUR 
000000b0: e280 8ce2 808c e280 8ce2 808c e280 8def  ................
000000c0: bbbf e280 8ce2 80ac 4e4f 4e2d e280 8ce2  ........NON-....
000000d0: 808c e280 8ce2 808c e280 8cef bbbf e280  ................
000000e0: 8ce2 808c 5354 4f50 2048 4143 4b49 4e47  ....STOP HACKING
000000f0: 2043 4f4d 5045 5449 5449 4f4e e280 8ce2   COMPETITION....
00000100: 808c e280 8ce2 808c e280 8def bbbf e280  ................
00000110: 8def bbbf 2e20 5448 4520 4649 4e41 4c20  ..... THE FINAL 
00000120: 5048 4153 4520 e280 8ce2 808c e280 8ce2  PHASE ..........
00000130: 808c e280 8cef bbbf e280 8ce2 808d 5749  ..............WI
00000140: 4c4c 2042 45e2 808c e280 8ce2 808c e280  LL BE...........
00000150: 8ce2 808d e280 ace2 808d e280 8c20 4845  ............. HE
00000160: 4c44 2049 4e20 5045 5253 4f4e 20e2 808c  LD IN PERSON ...
00000170: e280 8ce2 808c e280 8ce2 808d efbb bfe2  ................
00000180: 808d e280 8c46 524f 4d20 3130 204f 4354  .....FROM 10 OCT
00000190: 4f42 4552 e280 8ce2 808c e280 8ce2 808c  OBER............
000001a0: e280 8de2 80ac e280 ace2 808c 2032 3032  ............ 202
000001b0: 3220 e280 8ce2 808c e280 8ce2 808c e280  2 ..............
000001c0: 8cef bbbf e280 ace2 808d 544f 2031 3220  ..........TO 12 
000001d0: 4f43 544f 4245 52e2 808c e280 8ce2 808c  OCTOBER.........
000001e0: e280 8ce2 808c efbb bfe2 80ac e280 8de2  ................
000001f0: 808c e280 8ce2 808c e280 8ce2 808c efbb  ................
00000200: bfe2 808d e280 8c20 3230 3232 2049 4e20  ....... 2022 IN 
00000210: e280 8ce2 808c e280 8ce2 808c e280 8cef  ................
00000220: bbbf e280 8def bbbf e280 8ce2 808c e280  ................
00000230: 8ce2 808c e280 8cef bbbf e280 8cef bbbf  ................
00000240: 434f 544f 4e4f 5520 28e2 808c e280 8ce2  COTONOU (.......
00000250: 808c e280 8ce2 808c efbb bfe2 80ac e280  ................
00000260: 8d52 4550 5542 4c49 4320 4f46 e280 8ce2  .REPUBLIC OF....
00000270: 808c e280 8ce2 808c e280 8cef bbbf e280  ................
00000280: 8def bbbf 2042 454e 494e e280 8ce2 808c  .... BENIN......
00000290: e280 8ce2 808c e280 8cef bbbf e280 8de2  ................
000002a0: 808c 2920 5749 5448 2054 4845 e280 8ce2  ..) WITH THE....
000002b0: 808c e280 8ce2 808c e280 8cef bbbf e280  ................
000002c0: 8de2 808d 2046 4952 5354 2054 4541 4d53  .... FIRST TEAMS
000002d0: e280 8ce2 808c e280 8ce2 808c e280 8cef  ................
000002e0: bbbf e280 8ce2 808c 20e2 808c e280 8ce2  ........ .......
000002f0: 808c e280 8ce2 808c efbb bfe2 808c e280  ................
00000300: ac46 524f 4d20 e280 8ce2 808c e280 8ce2  .FROM ..........
00000310: 808c e280 8cef bbbf e280 8de2 808d 4541  ..............EA
00000320: 4348 20e2 808c e280 8ce2 808c e280 8ce2  CH .............
00000330: 808c efbb bfe2 808c e280 ac43 4f55 4e54  ...........COUNT
00000340: 5259 2057 484f 2048 4156 45e2 808c e280  RY WHO HAVE.....
00000350: 8ce2 808c e280 8ce2 808c efbb bfe2 80ac  ................
00000360: e280 8c20 5041 5353 4544 20e2 808c e280  ... PASSED .....
00000370: 8ce2 808c e280 8ce2 808c efbb bfe2 808c  ................
00000380: e280 8c54 4845 2050 5245 2d53 454c 4543  ...THE PRE-SELEC
00000390: 5449 4f4e e280 8ce2 808c e280 8ce2 808c  TION............
000003a0: e280 8cef bbbf e280 8ce2 80ac 2053 5441  ............ STA
000003b0: 4745 2ee2 808c e280 8ce2 808c e280 8ce2  GE..............
000003c0: 808c  

```

>It reminds me of Zero Width Space.  You're wondering how I know that, well it's not the first time I've come across it ☺️. I invite you to read this article to understand what it is 👉 [Be careful what you copy: Invisibly inserting usernames into text with Zero-Width Characters](https://medium.com/@umpox/be-careful-what-you-copy-invisibly-inserting-usernames-into-text-with-zero-width-characters-18b4e6f17b66)

>Google is your best friend  😃
a small search on google zero width space decoder and you find this site 😎 [Unicode Steganography with Zero-Width Characters](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjNpPCX7_P5AhWsS_EDHaHbDgQQFnoECAsQAQ&url=https%3A%2F%2F330k.github.io%2Fmisc_tools%2Funicode_steganography.html&usg=AOvVaw3ShU_Jb-nn0r6IBkk1TKer) 

>Let's go decode 

<img src="File/flag_zero.png">

```Flag:``` **CTF_z3r0w1dth9947397450252802** 