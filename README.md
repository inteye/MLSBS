#MLSBS
MLSBS is the abbreviation of "My linux's bash script"!
��MLSBS���ǡ�My linux's bash script������д linux��ά������Ա�ճ���Ҫдһ�ѽű����򻯹���������MLSBS����Ŀ�ľ��ǰ����ճ���linux�µĹ���ͨ���ű����ϵ�һ����Ŀ�У���Ҫ��ʱ�򼸸�����Ϳ�����������ˡ�

����һ����ʱ�����ޣ�����������ά�ű����ϵĽ����е�������ʱ�ṩһ����װ������������Ĺ��ܡ� Ŀǰ�ű���Ŀ¼���£���������centos6.5 ��ubuntu12.04�²���ͨ������

�汾˵����
v0.1�汾��Ϊ��ʼ�汾��ֻ�ṩ�������ճ���ά����ļ򵥲����ܣ�Ŀǰ���кܶ�ű�û������������
����������֧������bash�ű�ģ�壬��������ͳ��õĽű�ģ�廯��������������cron����ģ��·����bashTemplate��
v0.2�汾������汾����Ϊ�˴����֣���ĳЩIT��ҵ������Ʒ�����2014��5��15�������﷢�����ѣ��Ա�v0.1�汾������Crontab�������ӹ��ܣ�Ŀǰ������������ű���ͬʱҲ�޸���mysql��10G����Ӳ�̰�װ���޷�������BUG��

Ŀ¼�ṹ��
mlsbs/
������ bashScript #����ʹ�õ�bash�ű�
��   ������ curl_url.sh
��   ������ mysqlclient.sh
��   ������ mysqlserver.sh
������ bashTemplate #Bash�ű�ģ��
��   ������ mysql_server.sh #����mysql���������ճ�����ű�
��   ������ ssh_backlist_deny.sh #ssh��������������ű�
��   ������ system_check.sh #Ӳ�̿ռ�������ű�
������ config#�ű������ļ�
������ function#�����õĺ���Ŀ¼
��   ������ config_python.sh
��   ������ create_cron.sh #�����ճ�����
��   ������ iptables_set.sh #���������iptables��������
��   ������ mysql_install.sh #mysqlԴ�����ݿⰲװ
��   ������ nginx_install.sh #nginxԴ�밲װ
��   ������ puppet_install.sh #puppet����˺Ϳͻ��˰�װ����
��   ������ report_system.sh
��   ������ system_base_set.sh #ϵͳ��������
��   ������ tomcat_install.sh #tomcat�Զ�����
��   ������ decryption_encryption.sh #���ܽ��ܳ���
������ LICENSE
������ myscript.sh #mainִ���ļ�
������ py2script #python2�ű�
��   ������ myconfig.conf
��   ������ myftp.py
��   ������ sendmail.py
������ README.md