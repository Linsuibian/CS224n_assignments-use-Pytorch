# CS224n_assignments
#### ��ѧ�ڿγ̱Ƚ϶࣬����������~~~~~~~~~~~~~~~^_\^
#### ��������γ�PJ�����Ժ�����ҵ����Ӧ�û��һ��ʱ�䣬ĿǰѧУ�Ŀ��Լ�������һ����֪�����½�����з��ࡣ�Լ������Ѿ���ȡ���ˣ����ڵ�ͬѧ������( T___T ) ��Ŀ��᳢�����ر�Ҷ˹���и���RNN�ĸ��ֱ��塣������һͬ������\ ( > < ) / 
#### ��Ƶ������Youtube�ϵ���Ƶ���о�Bվ�Ϸ���Ĳ�̫�á�By the way, Youtube�������һ�����п��Եĸ�ϰ�Σ�Ҳ������Ŷ��ѧ��ʱϰ֮~~~~
#### ѧϰ������鲻�ܼ�Ҫ�������������򲻴�Ŷp( ^ O ^ )q
## ˵��

- Դ��ʹ��Python2.7��д�����ڰ汾�ȽϹ�ʱ������ʹ�õ�3.x�汾(�����õ�3.6���������õ�3.5)���޸������е�һЩBUG��
- �Լ�û�в���tensorflow�Ŀ�ܣ�����ʹ�õ�Pytorch���Լ�Ҳ�Ǹոտ�ʼѧϰ�����ܡ�
- assignment one������̫���ˣ�����û�д���ʹ��shell�ű��Ϳ��Ի�á�
- **.log** �ļ��Ǵ����ڷ�����������ʱ��ӡ�������Ϣ�������˽�ģ�͵�����״̬��
- CS224n 2017��2018���п��Էǳ��м�ֵ

��Դ�� | ��Դ����
---|---
CS224n�ٷ�ҳ������(��start code��solution���и��ֲο�����) | [link](http://web.stanford.edu/class/cs224n/syllabus.html) 
Pytorch�̳� | [link](https://github.com/chenyuntc/pytorch-book)
�γ̱ʼ�(�����Ƽ�) | [link](https://github.com/stanfordnlp/cs224n-winter17-notes)
ԭ�汾�ο�����(Python2.7 & tensorflow) | [link](https://github.com/hankcs/CS224n)
���°���Ȼ���Դ�������(Speech and Language Processing)| [link](http://web.stanford.edu/~jurafsky/slp3/)
---


# assigment one

#### ˵��
- һЩ�����Ե��޸ģ�����print��������
- utils.treebank.py�µ�sentence��sent_lables���������޸ģ�ԭ���ǽ�������⡣�о��Լ��Ľ����ʽ�е㱩������������н�������ľ��Ӿ�����������и��õĽ����ʽ����ϵ�� ��)
- �Լ��Ĵ���д���е���ϣ����λ���ٲ�Ҫ���� %>_<%
### word2vec

![image](https://note.youdao.com/yws/api/personal/file/A4A10D2E3BC04B2D8659417E9AAF8C0C?method=download&shareKey=b0fdede89f787b2f28a17e89c0be3b41)

### sentiment
![image](https://note.youdao.com/yws/api/personal/file/9B76525F990648D78CF5672C35992152?method=download&shareKey=d83c7ac9cf477342337d25030f857470)
![image](https://note.youdao.com/yws/api/personal/file/8A6B212F21714221A723386CEBA67B21?method=download&shareKey=9ed57f92161aa7f825a3a22ebba71229)

# assigment two
#### ˵��
- �Լ��޸ĺ��ģ�͵��ļ����и�extention�ĺ�׺
- Դ����Ϊtensorflowд�ģ��Լ���pytorchȫ����д��
- utils�ļ��µĴ��룬ֻ����һ�����޸ģ���Ҫ��ת���������ͣ�����û��ʲô�仯��
- ������������⣬���ܽ���᲻̫һ�����������̫�ࡣ

### ���ս��
- .log���ļ��п���ԭʼģ�� test UAS: 89.40  
- �Լ��޸ĺ��ģ�� test UAS: 90.05
- �޸ĵ�ģ�ͣ��������һ�����㣬�������������������뵽����softmax��(��������� q2_parser_model_extension.py)
