1.�}��virtual box�A�A�I��k�W�誺����u��A�I�i�D�������޲z���A
�b�����W�����إߡA�إ߷s�������d����A���k�䪺���e�A�N���q��אּ192.168.100.1/24�C
2.�I�索�W�����s�W�A��J�����W��-1�A�M��A�I��]�w�ȸ̭��������A��ܱҥ�
Host-only�����d�A�w�˦��\����A��Jinstall net-tools�ӤU��ifconfig�A�U���n����A
��Jifconfig enp0s8 192.168.100.100�A�A��Jifconfig�C
3.�A�̤W�z���覡�إߥt�~�@�ӵ��������A�W�٬�-2�A
�@�˦b�]�w�Ȫ��a��ҥ�Host-only�����d�A��Jinstall net-tools�ӤU��ifconfig�A
��Jifconfig en0s8 192.168.100.200�A�A��Jifconfig�C
4.���}-1�����������A��Jvi /etc/sysconfig/network-scripts/ifcfg-*�A
�M��bONBOOT=no���a��A��no�令yes�A�A�s�Wip��}IPADDR=192.168.100.100�C
���}-2�����������A��Jvi /etc/sysconfig/network-scripts/ifcfg-*�A
�M��bONBOOT=no���a��A��no�令yes�A�A�s�Wip��}IPADDR=192.168.100.200�C
5.���}-1�����������A��Jping 192.168.100.200�A�M��b-2������������Jping 192.168.100.100�A
�T�{�����O�_���q�C