=============================
#--CrossEntropy Assignment--#
=============================
1. ������
 1.1 hangulJamoDecoder.py ����
     : sejong.nov.train.txt, sejong.nov.test.txt, hani.test.txt�� �ڸ� �и� ���� ����
 
 1.2 hangulSyllablesDecoder.py ����
     : sejong.nov.train.txt, sejong.nov.test.txt, hani.test.txt�� ���� �и� ���� ����

 1.3 run.py ����
     : unigram�� bigram �� entropy�� cross_entropy ���
     *���� :bigram ��� �� �ð��� ���� �ɸ�



2. ������
 2-1. bigram ���� 
      : ���� �ڵ忡���� �ڸ�, ���� ������� bigram�� ����(ex.('��', '��'), ('��', '��'), ('��', '��'))
	������ �־��� �����Ϳ��� ������� �������� ���� bigram�� ���ٴ� ����(ex.��,��,��,��,��,none,��,��)
	�̷� ���� bigram �����͸� ����Ͽ� entropy�� cross_entropy�� ����� ���� ���ϴ� Ȯ�� p(bigram) ���� ���� 1�� �� ����
	
	������ �ڵ�� Ȯ���غ��� �ʹٸ�, 
	run.py���� vec_entropy, vec_cross_entropy���� �ּ�ó���� print������ �ּ������ϰ� �����ϸ� ��


 2-2. �ӵ� ����
      : �ӵ� ����� ����, for���� vector ������� ��� �ٲٷ��� �õ��� �Ͽ���
        �׷��� cross_entropy���� Ȯ���� ����� ��, type_list���� bigram�� ��ġ�� ����� �ʿ伺�� �߰��ϰ�,
	for�� �ϳ��� �߰��Ͽ��µ�, ��� �ð��� ����� ������

	vector ����� �ӵ� ����� Ȯ���ϰ� �ʹٸ�,
	## non_vectorization Vs. vectorization ## �� ���Ե� �ּ��� �����ϰ� �����ϸ� ��
	
	������ �䱸
	

 2-3. ����ġ�� ���� print��
      : run.py �� �κ��� ����, print���� = ���� �ʹ� ���� ���� �����
 
	����ϰ� ������ �䱸



3. �����
   : outcome.txt ���� ����

