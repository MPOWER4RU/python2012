������ "��������"
������: ������ ���������, ������ ������� (������������� �� �������, � �� �� ���������� ;) )
karashevich@gmail.com, kirill.a.kononov@gmail.com

��� ������ � �������� ���������� ��������� �������������� ���� PostgreSQL (������������� 9.2) � 
��������� �� � ������������ python2012\Asteroid\Django\asteroid\settings.py. ����� ��������� ���� ������
� Parser.py  ��� ���������� ������ � ����� ������ ���������� ��������� ������� psycopg2, ��� ����� �������:
www.stickpeople.com/projects/python/win-psycopg/psycopg2-2.4.5.win-amd64-py2.7-pg9.1.3-release.exe

������ ������� 3� ������:
	- Parser.py - ������, ������� ������� *.proclog ����� � ������� ���������� � �� ���� ����������, 
		� ������ ��� ���������� � ���� ������ "asteroidb", ������� ����������� POstgreSQL.
	- �� "asterodb" � ��� �������� ��� ������������ ����������.
		"Image name" 		- ��� ����� �����������
		"Exposure"		- ����� ����������
		"CCD temperature		- ����������� ���-�������
		"Filter"			- ������������ ������
		"Mid-exposure time"	- ����� �������� ����������
		"Latitude"		- ������ ������������
		"Longitude"		- ������� ������������
		"Altitude"		- ������ ������������
		"Astrometric catalog"	- ���������������� ������� ��� ���������
		"Image center RA"		- ��������� �� alpha ������ �����
		"Image center DEC"	- ��������� �� delta ������ �����
	- Django ����, ��������� ������ ���� ���������� � ���� ������ � ���������� �� ������� �� ����������.
#########
��� ������ �������:
1) ���������� ��������� ��������� � ���������, ��� � python2012\Asteroid\Django\asteroid\settings.py 
� � python2012\Asteroid\Parser.py ����� ������� ��������� ��� "asteroidb".
2) ��������� ������ python2012\Asteroid\Parser.py - �� ������� � ���� ������� �� python2012\Asteroid\test\
3) ��������� ���� ���������  python2012\Asteroid\Django\manage.py runserver
4) ����� � �������� �� ���� localhost:8000
#########
��� ����� ���������� ��������� �������� ����� ������������ � ����� ������������.
	