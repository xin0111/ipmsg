======================================================================
        IP Messenger for Win �S�\�[�X ��舵��������    2011/06/27

                                               H.Shirouzu�i�����[�́j
                                               http://ipmsg.org
======================================================================

�ڎ�

  1. �T�v
  2. �g�p��̒���
  3. �T�|�[�g�ɂ���
  4. �R���p�C�����@�iVC6 �Łj
  5. �f�B���N�g���\��
  6. ���ȓW�J�C���X�g�[���`���ɂ���

�� 1. �T�v

�EIP Messenger for Win �̑S�\�[�X�R�[�h�ł��B

�EMFC/OWL ���g�p�����A�I���W�i���̊ȈՃN���X���g���Ă��܂��B
  �ȈՃN���X�����́Atlib.h �� t*.cpp �ɂȂ�܂��B
  �����ȃc�[���p�ɁA���p�ł��邩������܂���(^^;

�EVC++6 �ŃR���p�C�����Ă��܂��B�iVS2005�ȍ~ �ł��r���h�\�j

�E��`�Ȃ��n�̃G���[���ł鏈���n[VC5���H]�ɂ��āB
�@ipmsg.h ���� #ifdef �ɂ��A���̒�`�i���܂ރu���b�N�j��
�@����������Ă���͂��Ȃ̂ŁA����`�G���[�̏o���`������
�@���̃u���b�N����O�ɏo�����ƂŁA�R���p�C���\�ɂȂ�܂��B


�� 2. �g�p��̒���

�E�uIP Messenger for Win�v�͎��s�t�@�C���E�\�[�X�R�[�h����
  �u�i�v�Ɂv�t���[�\�t�g�E�F�A�ł��B

�E�A�[�J�C�u�̓]�ځE�Ĕz�z�͎��R�ł��B

�E���C�Z���X�͈ȉ��̒ʂ�ł��B

/* ==============================================================
  Copyright (c) 1996-2011 SHIROUZU Hiroaki  All rights reserved.

  �\�[�X�ƃo�C�i���`���̍Ĕz�z����юg�p�́A�u�ύX�̗L���A���p/
  �񏤗p�ɂ�����炸�v�A�ȉ��̏����𖞂����ꍇ�ɋ�����܂�:

  1. �\�[�X�R�[�h�̍Ĕz�z�́A��L�̒��쌠�\���A���̏����̃��X�g�A
     �����ĉ��L�̔۔F��������ێ����Ȃ���΂Ȃ�܂���B

  2. �o�C�i���`���̍Ĕz�z�́A��L�̒��쌠�\���A���̏����̃��X�g�A
     �����ĉ��L�̔۔F���������A�z�z���Ƌ��ɒ񋟂����A��������
     ��/�܂��͑��̎����Ƃ��ĕ������Ȃ���΂Ȃ�܂���B

  3. ����Җ����A�܂������Ȃ鋤���v���Җ����A���m�ɗD�悷�镶��
     �����ꂽ�������ɁA���̃\�t�g�E�G�A����h�����鐻�i�̕ۏ�
     ��̔����i�Ɏg���Ă͂Ȃ�܂���B

 �u���̃\�t�g�E�G�A�́A��҂ɂ��u���邪�܂܂̏�ԁv�Œ񋟂���A
   �����閾���I�܂��͈Öق̕ۏ؂�۔F���A�����Ȃ鑹�Q�ɑ΂��Ă�
   �ӔC�𕉂��܂���B�v

=============================================================== */


�� 3. �T�|�[�g�ɂ���

�E�T�|�[�g�͉��L��URL�ɋL�ڂ��Ă��� ipmsg-ML�i���C�y�ɂ��Q�����������j
  �ōs���Ă��܂��B�܂��A�����o�[�W�����֌����Ă̒�ĂȂǂ����}�ł��B
 �i�ŐV�ł͏�ɂ����ɂ���܂��j�B�ݏ��I�� BBS ������܂��B
    http://ipmsg.org/

�E���݃o�O�̎w�E��A���悢�\�[�X�R�[�h�ւ̃A�h�o�C�X�����}���܂��B


�� 4. �R���p�C�����@�iVC++6.0J�Łj

�Eipmsg.dsw �� VC++6.0 �Ŏ��s���܂��B
  VS2005�ȍ~�ł��r���h�\�ł��B
�EIPMsgv3.0�ȍ~�A���ߍ��݉摜(PNG)�p�ɁAzlib/lipng ���g���Ă��܂��B
  http://www.libpng.org/pub/png/libpng.html
  http://zlib.net/

�� 5. �f�B���N�g���\��

	IPMsg----+-IPMsg.dsw ... Project file for VC6
		|      IPMsg.sln ... Project file for VS2005�ȍ~
		|
		+-Src------+-ipmsg.cpp
		|          |     :
		|          +-install-+- install.cpp
		|                    |       :
		|
		+-External-+-Zlib---+-zlib.dsw
		|          |            :
		|          +-Libpng-+-libpng.dsw
		|                       :
		+-Release--+-
		|
		+-Obj------+-Release-+-
		           |
		           +-Debug---+-

�� 6. ���ȓW�J�C���X�g�[���`���ɂ���

�Ev3.10���A���ȓW�J�`���C���X�g�[�����T�|�[�g���Ă��܂��B
�@����̓\�[�X���r���h���ꂽ install.exe �̖����ɁA�ȉ��̂悤��
�@�t�H�[�}�b�g�ŁAipmsg.exe setup.exe ipmsg.chm ��t���������̂ł��B
�@ \n===(70��)===\n
�@ �t�@�C���T�C�Y �t�@�C����\n
�@ ZLIB���k�t�@�C��

�E��̓I�ɂ́A�ȉ��̂悤�� python script �ō쐬���Ă��܂��B

----------------------------------------------------
import sys, zlib

def add_file(f, fname):
	data = zlib.compress(open(fname, "rb").read())
	f.write("\n%s\n" % ("=" * 70))
	f.write("%d %s\n" % (len(data), fname))
	f.write(data)

def gen_inst(installer_name, installer_base, files):
	f = open(installer_name, "wb")
	f.write(open(installer_base, "rb").read())
	for i in files:
		add_file(f, i)
	f.close()

gen_inst("ipmsgXXX_installer.exe", "install.exe", ["ipmsg.exe", "ipmsg.chm", "setup.exe"])
----------------------------------------------------

