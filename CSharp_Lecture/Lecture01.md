# Step0

## Lecture01


### �ۑ�

#### �L�q���

1. ���O��ԂƂ͉����������Ȃ����B
2. �N���X�Ƃ͉����������Ȃ����B
3. �I�u�W�F�N�g�Ƃ͉����������Ȃ����B
4. �p���Ƃ͉����������Ȃ����B
5. ���\�b�h�Ƃ͉����������Ȃ����B
6. �A�N�Z�X�w��q�Ƃ͉����������Ȃ����BC#�ɂ͂ǂ�Ȏ�ނ����邩�����Ȃ����B(�Œ�4��)
7. �v���p�e�B�Ƃ͉����������Ȃ����B
8. �t�B�[���h�Ƃ͉����������Ȃ����B
9. �R���X�g���N�^�Ƃ͉����������Ȃ����B

�Q�l:

https://docs.microsoft.com/ja-jp/dotnet/csharp/

http://ufcpp.net/study/csharp/

https://qiita.com/toshi0607/items/801a0d37fb48313cbdbd


#### ���H���

C#�œd������Ȃ����B

�ȉ��̎d�l�̒ʂ�Ƃ��邱�ƁB

##### �O�����

- �R���\�[���A�v���P�[�V����(.NET Framework)�ō쐬���邱�ƁB
- .NET Framework�̃o�[�W������4.6.2�Ƃ���B
- Project����Calculator�Ƃ��邱�ƁB

##### �@�\�v��

�ȉ��̌v�Z���ł��邱�ƁB

1. �l�����Z
2. �����̌v�Z
3. ���[�g�̌v�Z
4. �ׂ���̌v�Z (�ׂ����͐��̐����Ƃ���)
5. �K��̌v�Z (���̐����̊K��ɑΉ����邱��)
6. �O�p�֐��̌v�Z(sin, cos, tan)
7. �t�B�{�i�b�`����̌v�Z (�Q�l�Fhttps://ja.wikipedia.org/wiki/%E3%83%95%E3%82%A3%E3%83%9C%E3%83%8A%E3%83%83%E3%83%81%E6%95%B0, https://www.studyplus.jp/445)
<ol style="background:#ffffff">
<img src="./FibonacciNumber0.gif" style="background:#ffffff"/><br />
<img src="./FibonacciNumber1.gif" style="background:#ffffff"/>
</ol>

8. history�R�}���h����͂�����A�R���\�[����ʏ�ɓ��͂��������Ƃ��̏o�͂��\������邱��
9. history�R�}���h�ɃI�v�V����--log����͂�����AExe�Ɠ��K�w��Log�t�H���_���쐬����A�R���\�[����ʏ�ɓ��͂��������Ƃ��̏o�͓��e��[yyyyMMddhhmmss].log�Ƃ����t�@�C�����쐬����邱��
    - ��̓I�ɂ́A> history --log �Ɠ��͂���Bhistory��--log�̊Ԃ�1�ȏ�̃X�y�[�X�������Ă����s����邱�ƁB
    - [yyyyMMddhhmmss]�́A���t������Format�Ƃ���

�������_�ȉ���3�ʂ܂Ő��x����������΂悢

�Ⴆ�΁A�ȉ��̒ʂ�̓�������邱�ƁB

````
> 1+1
2
> 5-1
4
> -5*4
20
> -5/4
-1.25

````


##### ��@�\�v��

1. �ێ琫�����߂邽�߁AUtility Class�Ȃǂ��쐬���A�@�\�v����1�`7�͌ʂ̊֐�(Method)���`���邱�ƁB
2. �v�Z�s�\�ȓ��͂��������Ƃ��Ă��A�A�v���P�[�V�����ŃG���[���b�Z�[�W��\�����A�A�v���P�[�V�����������I�ɏI�����邱�Ƃ��Ȃ��悤�ɂ���Btry,catch�Ȃǂ𗘗p���邱�ƁB(�p��)
3. �L�q���̊e���ڂɂ��Ď��H���Ŏ��������v���O�����ɃR�����g�A�E�g�łǂ̕����ɂ����邩�L�ڂ��Ȃ����B
    - ��: 2�̃N���X�Ȃ�ȉ��̒ʂ�Ƃ���

    ````
    public class Person {  //2. �N���X
        public string Name { get; set; }
    }
    ````
