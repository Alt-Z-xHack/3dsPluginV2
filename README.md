# 3dsPluginV2 BY A.l.t.Z

=====How to Boot Plugin?=====

   3DS Select Button Press
         !EnJoy!

=============================

Plugin Google Form:

https://goo.gl/forms/aqlaPRI1duJXdg8C3

Discord ID:

TRC/A.l.t.Z/RMT#1724

Twitter:

https://twitter.com/AltZ76320635

YouTube:

https://www.youtube.com/channel/UCHZCL-bguGrgPvY3RkOwpsA

Plugin Source(Select):
===========================================================
void	A_l_t_Z_Code(void)
{
	offset = 0x08000000;
	WRITEU16(offset + 0x2345678, 0x00000810);
	offset = 0;
	data = 0;
}

void	A_l_t_Z_CodeTwo(void)
{
	offset = 0x08000000;
	WRITEU16(offset + 0x2345678, 0x00000019);
	offset = 0;
	data = 0;
}


===========================================================
Plugin Source(CTRPF):
===========================================================
void	A_l_t_Z_Code(MenuEntry *entry)
{
	offset = 0x08000000;
	Process::Write16(offset + 0x2345678, 0x00000810);
	offset = 0;
	data32 = 0;
	data16 = 0;
	data8 = 0;
}

void	A_l_t_Z_CodeTwo(MenuEntry *entry)
{
	offset = 0x08000000;
	Process::Write16(offset + 0x2345678, 0x00000019);
	offset = 0;
	data32 = 0;
	data16 = 0;
	data8 = 0;
}


===========================================================

Source By A.l.t.Z
