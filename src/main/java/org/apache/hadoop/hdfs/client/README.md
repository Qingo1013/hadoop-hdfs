# HDFS�ͻ���

HDFSĿǰ�ṩ�������ͻ��˽ӿ�: DistributedFileSystem��FsShell��DFSAdmin��
* DistributedFileSystemΪ�û���������HDFS��Ӧ�ó����ṩ��API;
* FsShell����ʹ�û�����ͨ��HDFS Shell����ִ�г����Ķ��ļ�ϵͳ���������紴���ļ���ɾ���ļ�������Ŀ¼��;
* DFSAdmin����ϵͳ����Ա�ṩ�˹���HDFS�Ĺ��ߣ�����ִ������������ȫģʽ�Ȳ�����

## DFSClientʵ��
DFSClient��һ������ʵ���˷ֲ�ʽ�ļ�ϵͳ�ͻ��˹��ܵ��࣬���û�ʹ��HDFS����ܵ���㡣DFSClient�����ӵ�HDFS��
�����ṩ�����ļ�/Ŀ¼����д�ļ��Լ�����������HDFSϵͳ�ȹ��ܡ�
���ڹ����ļ�/Ŀ¼�Լ�����������HDFSϵͳ���������ܣ�DFSClient������Ҫ��Datanode����������ֱ�ӵ���Զ�̽ӿ�ClientProtocol
����Namenode�ṩ�ķ��񼴿ɡ��������ļ���д���ܣ�DFSClient������Ҫ����ClientProtocol��Namenode�����⣬����Ҫͨ����ʽ
�ӿ�DataTransferProtocol��Datanode�����������ݡ�
