fake_np���Խ����Լ���ISOαװ��PSN���صĸ�ʽ,������OFW��ֱ������,�������CFW.


����Ҫһ���Ϸ���PSN��Ϸ��Ϊ����.���PSN��Ϸ������һ��demo,Ҳ������һ���������Ϸ.��������һ��,�������ʱ��Ҫlicense�ļ�,��ôαװ�����ϷҲ��Ҫͬ����license�ļ�.fake_np����������demo������.

fake_np v1.0��������:
 - ֧��OFW 6.60
 - ֧������ѹ��
 - ���õ��������֧��1.1G(1197932544)��ISO
 - ��ʵ�õ������в���

ʹ�÷���:

fake_np [-b base_name] [-c] [-e] [iso_name] [pbp_name]
    -b base_name: ָ��һ��PSN��Ϸ��Ϊ����.���û��ָ��,ʹ�����õ�����
    -w          : ��[-b]һ��ʹ��,����һ����С�������ļ�.
    -c          : ��ѹ��֧��
    iso_name    : ��ϣ��αװ��ISO�ļ�. ���û��ָ��,Ĭ��Ϊ"NP.ISO".
    pbp_name    : αװ������. ���û��ָ��,Ĭ��Ϊ"EBOOT.PBP".

ע������:
1. �����ʾ"The EBOOT.BIN in iso is a ELF file", ��ô���ø�����seboot.exe�ȶ�EBOOT.BIN����ǩ��,�����ҵ�ԭ���EBOOT.BIN
2. ������fake_np -b xxx ����ʾ��Ϸ�������Ϣ.


Fake_NP v1.0 by tpu
  This program can put your ISO/homebrew into a PSN PBP file
  The faked PBP file can be load from OFW.

New features:
  support OFW 6.60
  support data compress
  support max ISO size of 1.1G

How to use:
  fake_np [-b base_name] [-c] [iso_name] [pbp_name]
    -b base_name: select a valid PSN game as base. if empty, use buitin base.
    -w          : work with -b, save a small header of game.
    -c          : compress data.
    iso_name    : the game you want to fake. if empty, default as "NP.ISO".
    pbp_name    : the fake result. if empty, default as "EBOOT.PBP".

Notes:
  If you get this message: "The EBOOT.BIN in iso is a ELF file",
  please sign your EBOOT.BIN first(use my seboot.exe), or find origin file.
  you can found the source code here:
    http://www.kusodev.org/hg/kirk_engine

Thanks:
CipherUpdate & kono for their NP Decryptor
Mathieulh, kgsws, SilverSpring, Davee and the peoples who worked on kirk research


