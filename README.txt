%%
%% Copyright (C) 2012 by Joseph Pan <cs.wzpan@gmail.com>
%%
%% This file may be distributed and/or modified under the
%% conditions of the LaTeX Project Public License, either version 1.3a
%% of this license or (at your option) any later version.
%% The latest version of this license is in:
%%
%% http://www.latex-project.org/lppl.txt
%%
%% and version 1.3a or later is part of all distributions of LaTeX
%% version 2004/10/01 or later.
%%

��Ҫ˵����
�������������������⣬��������ۿ�������scnuthesis.pdf�ļ����ʹ��˵����

* �򵥰�װ����
-------------------
1) ���ʹ�õ��� Windows
  1. ��װ CTeX��
  2. ʹ�� WinEdit �������ı��༭���� thesis.tex �ļ���
  3. ���ʹ�õ��� Windows Vista �� Windows 7���뽫��43�����ݸ�Ϊ��
           \documentclass[master,twoside,vista,ttf]{scnuthesis}
     ���ʹ�õ��� Windows XP������Ҫ���κθĶ���
  4. ˫��ģ��Ŀ¼�µ� makepdf.bat������ʾ�����ġ�

2) ���ʹ�õ��� Linux
  1. ��װ TexLive��
  2. �������壺�� Windows �µ� simsun.ttf, simhei.ttf, simkai.ttf��simli,ttf��simfang.ttf ������/usr/share/fonts/TTF�£�
     �ն�������
          sudo fc-cache
     ��ɺ�����
          fc-list :lang=zh
     �۲��б����Ƿ�������� Windows���壬���û�У�����Ҫcd��ȥ /usr/share/fonts/TTF Ŀ¼���ոտ�����ȥ�ļ��������ļ���Ȩ������Ϊ777��
	  cd /usr/share/fonts/TTF && chmod 777 *.ttf *.TTF
  3. ʹ��Emacs�������ı��༭����thesis.tex�ļ���
  4. ������忽������Դ��Windows Vista �� Windows 7���뽫��43�����ݸ�Ϊ��
      \documentclass[master,twoside,vista,ttf]{scnuthesis}
     �����Դ��Windows Vista��Windows 7������Ҫ���κθĶ���
  5. cd��ȥģ��Ŀ¼��Ȼ�������������
	  make
     ������ʾ�����ġ�

����ʹ�÷�����ο�������scnuthesis.pdf�ļ���

Happy Texing!
