# ��-10.

## ����������

- [About](#about)
- [Usage](#usage)

## About <a name = "about"></a>

��-10. ����������� ������� ��������� ������


## Usage <a name = "usage"></a>

bulk_server <port> <bulk_size>
, ���
? port � ����� tcp ����� ��� �������� ����������. ���������� ������ ������������� � ������������ �����������
? bulk_size � ��� �������� ������ ����� ������.

������ ������� ������:
bulk_server 9000 3
�
seq 0 9 | nc localhost 9000
(��� �������� ������������ 10 ����� � ������� �� 0 �� 9 �� ������ ������ � ��������� �� �� ���� �� ��������� ���� 9000).