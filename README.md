# strings
Best strings command line utility

```
Usage: strings macho_file [-u/--unicode-only] [-a/--ascii-only] [-q/--quiet] [-i/--imhex-output]
```

### Features

- [x] IDA Pro-like output
- [x] imhex compatible output
- [x] Mach-O support
- [ ] ELF support
- [ ] DEX support
- [ ] .tar viewer
- [ ] .zip/.apk/.ipa viewer
- [ ] Remove dependencies

### Dependencies
* radare2
* binutils

### Example output

```
XinaA15_1.1.6.2_patch λ find ./Payload/Xina.app/* | xargs -L 1 ./strings --unicode-only --quiet

./Payload/Xina.app/bins/bootstrap/usr/bin/dpkg-deb

Address                         Length        String
__ustring:0x0000000000007fac    0x00000058    参数:%�


./Payload/Xina.app/bins/bootstrap/usr/bin/jailbreakd

Address                         Length        String
__ustring:0x000000000019b410    0x000000d0    XPC连接无效，正在释放
__ustring:0x000000000019b4e0    0x00000168    xpc_get_kernel_all 失败�
__ustring:0x000000000019b648    0x00000120    瀀漀猀椀砀开猀瀀愀眀渀切ᥑ敖║搀
__ustring:0x000000000019b768    0x000001f0    瀀漀猀椀砀开猀瀀愀眀渀愀琀琀爀开搀攀猀琀爀漀礀 ᤀ敖║搀
__ustring:0x000000000019b958    0x00000130    愀琀琀挀栀洀攀�ஏ偺䤀䐀㨀 ─樀搀਀
__ustring:0x000000000019ba88    0x00000110    愀琀琀挀栀洀攀�ஏ杺䱢貈핛⁫─搀
__ustring:0x000000000019bb98    0x000001d0    愀琀琀挀栀洀攀�ஏꭺ䁓筧⁫戀礀 猀椀最渀愀氀 ─搀਀
__ustring:0x000000000019bd68    0x000001d0    愀琀琀挀栀洀攀�ஏꭺɓ督₍戀礀 猀椀最渀愀氀 ─搀਀
__ustring:0x000000000019bf38    0x00000140    愀琀琀挀栀洀攀�ஏ捺漀渀琀椀渀甀攀搀਀
__ustring:0x000000000019c078    0x000000f0    ൏๙瑔爀甀猀琀戀椀渀 ─䀀
__ustring:0x000000000019c168    0x00000070    縀ൻ㩔─猀਀
__ustring:0x000000000019c1d8    0x00000060    谀ၛ繢ൻ੔
__ustring:0x000000000019c238    0x00000120    ⼀ꡔ塒倀䌀ഀꅧㅒ╙斍爀爀漀爀㴀─䀀
__ustring:0x000000000019c358    0x00000150    ⼀ꡔ塒倀䌀蠀ѝٙ獴攀爀瘀椀挀攀 ─䀀
__ustring:0x000000000019c4a8    0x000000d0    �ꖏ獣攀爀瘀椀挀攀 ─䀀
__ustring:0x000000000019c578    0x000000d0    䤀蕻獟攀爀瘀椀挀攀 ─䀀
__ustring:0x000000000019c648    0x00000140    挀漀渀渀攀挀琀椀漀渀㴀─搀 관e�ꖏⅣ
__ustring:0x000000000019c788    0x00000120    挀漀渀渀攀挀琀椀漀渀㴀─搀 저找Ⅻ
__ustring:0x000000000019c8a8    0x00000130    㘀づ捒漀渀渀攀挀琀椀漀渀㴀─搀�ꖏⅣ
__ustring:0x000000000019c9d8    0x00000130    ⼀ꡔ慒琀琀挀栀洀攀䐀ꂖげ灒椀搀㴀─搀
__ustring:0x000000000019cb08    0x00000140    愀琀琀挀栀洀攀 瀀椀搀㴀─搀䐀ꂖ豒ၛⅢ
__ustring:0x000000000019cc48    0x000000f0    缀⡏瑵爀甀猀琀戀椀渀縀ൻ╔猀
__ustring:0x000000000019cd38    0x00000108    缀⡏摵攀昀愀甀氀琀⸀砀洀氀縀ൻ�
__ustring:0x000000000019ce40    0x00000078    升级权限文件�
__ustring:0x000000000019ceb8    0x000000b0    㥏㩥獎鍓蝞ⅎ਀
__ustring:0x000000000019cf68    0x000000a0    㥏㩥獎�ஏⅺ਀
__ustring:0x000000000019d008    0x00000160    猀椀最开愀瀀瀀开漀瀀攀渀 ─猀 蜀ㅎ╙↍
__ustring:0x000000000019d168    0x00000190    琀攀愀洀椀搀㴀䠀䄀䌀䬀䔀刀堀䤀一䄀Ⰰe춗纑ൻ੔
__ustring:0x000000000019d2f8    0x000000c0    ൏㩙獎摓礀氀椀戀਀
__ustring:0x000000000019d3b8    0x000001b0    琀攀愀洀椀搀㴀─猀 Ԁٮ捴猀开戀氀漀戀였ݑ쵙낑繥ൻ੔
__ustring:0x000000000019d568    0x00000190    琀攀愀洀椀搀㨀穎պٮ捴猀开戀氀漀戀였ݑ쵙낑繥ൻ੔
__ustring:0x000000000019d6f8    0x00000140    鼀쭓ꅙ६瑧攀愀洀椀搀㥏㩥獎�ஏⅺ਀
__ustring:0x000000000019d838    0x00000170    ἀၵ⁢渀攀眀 挀猀开戀氀漀戀 漀欀 ─氀砀਀
__ustring:0x000000000019d9a8    0x00000210     䘀开䄀䐀䐀匀䤀䜀匀縀ൻㅔ╙₍─猀 眀椀琀栀 攀爀爀渀漀㴀─搀਀


./Payload/Xina.app/bins/bootstrap/usr/bin/launchdhook

Address                         Length        String
__ustring:0x000000000000bcd2    0x00000088    忽略进程%s �
__ustring:0x000000000000bd5a    0x000000a0    ﴀ敟摵�ஏ╺猀 ਀
__ustring:0x000000000000bdfa    0x000001d0    �ஏz膗敬⁑椀㴀─搀 攀渀瘀㴀─瀀 攀渀瘀㴀─猀 ਀
__ustring:0x000000000000bfca    0x000002d0    䔀堀䌀开䈀䄀䐀开䄀䌀䌀䔀匀匀帀蕝塑ɛ㡟ⱞഀюٙ푴�䭖䔀刀一开䘀䄀䤀䰀唀刀䔀  ܀੎
__ustring:0x000000000000c29a    0x00000230    䔀堀䌀开匀伀䘀吀圀䄀刀䔀Ȁ㡟ⱞഀюٙ푴�䭖䔀刀一开䘀䄀䤀䰀唀刀䔀 ਀
__ustring:0x000000000000c4ca    0x000002f0    䔀堀䌀开匀夀匀䌀䄀䰀䰀Ȁ㡟ⱞഀюٙ푴�䭖䔀刀一开䘀䄀䤀䰀唀刀䔀 餀퉬ﵓ㚀偒䎋偧綖李䱢ઈ
__ustring:0x000000000000c7ba    0x00000150    氀굎륥⁰䔀堀䌀开䈀刀䔀䄀䬀倀伀䤀一吀਀
__ustring:0x000000000000c90a    0x00000130    挀栀攀挀欀开漀瘀攀爀琀椀洀攀 蔀Ⅵ
__ustring:0x000000000000ca3a    0x00000150    挀栀攀挀欀开漀瘀攀爀琀椀洀攀 က齢繒ൻ⅔
__ustring:0x000000000000cb8a    0x00000200    琀栀爀攀愀搀开挀漀渀瘀攀爀琀开琀栀爀攀愀搀开猀琀愀琀攀 ㄀╙↍
__ustring:0x000000000000cd8a    0x000000d8    堀倀䌀�ꖏ䡥౥揿⡫쩗㺑�
__ustring:0x000000000000ce62    0x00000080    XPC断开连接
__ustring:0x000000000000cee2    0x00000070    收到签名回复
__ustring:0x000000000000cf52    0x00000030    等待
__ustring:0x000000000000cf82    0x000000c0    收到getroot回复
__ustring:0x000000000000d042    0x00000070    收到回复错误
__ustring:0x000000000000d0b2    0x000000c0    收到fixproc回复


./Payload/Xina.app/bins/bootstrap/usr/bin/dpkg-query

Address                         Length        String
__ustring:0x0000000000007faa    0x00000058    参数:%�


./Payload/Xina.app/bins/bootstrap/usr/bin/jailbreakd_safe

Address                         Length        String
__ustring:0x000000000019f92e    0x00000118    posix_spawn出错退出%�
__ustring:0x000000000019fa46    0x000001f0    瀀漀猀椀砀开猀瀀愀眀渀愀琀琀爀开搀攀猀琀爀漀礀 ᤀ敖║搀
__ustring:0x000000000019fc36    0x00000130    愀琀琀挀栀洀攀�ஏ偺䤀䐀㨀 ─樀搀਀
__ustring:0x000000000019fd66    0x00000110    愀琀琀挀栀洀攀�ஏ杺䱢貈핛⁫─搀
__ustring:0x000000000019fe76    0x000001d0    愀琀琀挀栀洀攀�ஏꭺ䁓筧⁫戀礀 猀椀最渀愀氀 ─搀਀
__ustring:0x00000000001a0046    0x000001d0    愀琀琀挀栀洀攀�ஏꭺɓ督₍戀礀 猀椀最渀愀氀 ─搀਀
__ustring:0x00000000001a0216    0x00000140    愀琀琀挀栀洀攀�ஏ捺漀渀琀椀渀甀攀搀਀
__ustring:0x00000000001a0356    0x000000f0    ൏๙瑔爀甀猀琀戀椀渀 ─䀀
__ustring:0x00000000001a0446    0x00000070    縀ൻ㩔─猀਀
__ustring:0x00000000001a04b6    0x00000060    谀ၛ繢ൻ੔
__ustring:0x00000000001a0516    0x00000180    였ݑ⽙ꡔ橒愀椀氀戀爀攀愀欀搀开猀愀昀攀ഀꅧ⁒਀
__ustring:0x00000000001a0696    0x00000120    ⼀ꡔ塒倀䌀ഀꅧㅒ╙斍爀爀漀爀㴀─䀀
__ustring:0x00000000001a07b6    0x00000150    ⼀ꡔ塒倀䌀蠀ѝٙ獴攀爀瘀椀挀攀 ─䀀
__ustring:0x00000000001a0906    0x000000d0    �ꖏ獣攀爀瘀椀挀攀 ─䀀
__ustring:0x00000000001a09d6    0x000000d0    䤀蕻獟攀爀瘀椀挀攀 ─䀀
__ustring:0x00000000001a0aa6    0x00000140    挀漀渀渀攀挀琀椀漀渀㴀─搀 관e�ꖏⅣ
__ustring:0x00000000001a0be6    0x00000120    挀漀渀渀攀挀琀椀漀渀㴀─搀 저找Ⅻ
__ustring:0x00000000001a0d06    0x00000130    㘀づ捒漀渀渀攀挀琀椀漀渀㴀─搀�ꖏⅣ
__ustring:0x00000000001a0e36    0x00000130    ⼀ꡔ慒琀琀挀栀洀攀䐀ꂖげ灒椀搀㴀─搀
__ustring:0x00000000001a0f66    0x00000140    愀琀琀挀栀洀攀 瀀椀搀㴀─搀䐀ꂖ豒ၛⅢ
__ustring:0x00000000001a10a6    0x000000f0    缀⡏瑵爀甀猀琀戀椀渀縀ൻ╔猀
__ustring:0x00000000001a1196    0x00000108    缀⡏摵攀昀愀甀氀琀⸀砀洀氀縀ൻ�
__ustring:0x00000000001a129e    0x00000078    升级权限文件�
__ustring:0x00000000001a1316    0x000000b0    㥏㩥獎鍓蝞ⅎ਀
__ustring:0x00000000001a13c6    0x000000a0    㥏㩥獎�ஏⅺ਀
__ustring:0x00000000001a1466    0x00000160    猀椀最开愀瀀瀀开漀瀀攀渀 ─猀 蜀ㅎ╙↍
__ustring:0x00000000001a15c6    0x00000190    琀攀愀洀椀搀㴀䠀䄀䌀䬀䔀刀堀䤀一䄀Ⰰe춗纑ൻ੔
__ustring:0x00000000001a1756    0x000000c0    ൏㩙獎摓礀氀椀戀਀
__ustring:0x00000000001a1816    0x000001b0    琀攀愀洀椀搀㴀─猀 Ԁٮ捴猀开戀氀漀戀였ݑ쵙낑繥ൻ੔
__ustring:0x00000000001a19c6    0x00000190    琀攀愀洀椀搀㨀穎պٮ捴猀开戀氀漀戀였ݑ쵙낑繥ൻ੔
__ustring:0x00000000001a1b56    0x00000140    鼀쭓ꅙ६瑧攀愀洀椀搀㥏㩥獎�ஏⅺ਀
__ustring:0x00000000001a1c96    0x00000170    ἀၵ⁢渀攀眀 挀猀开戀氀漀戀 漀欀 ─氀砀਀
__ustring:0x00000000001a1e06    0x00000210     䘀开䄀䐀䐀匀䤀䜀匀縀ൻㅔ╙₍─猀 眀椀琀栀 攀爀爀渀漀㴀─搀਀


./Payload/Xina.app/bins/bootstrap/usr/bin/dash

Address                         Length        String
__ustring:0x0000000000007faa    0x00000058    参数:%�

```
