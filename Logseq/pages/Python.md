- print(<資料>)
  印出資料
	- print(<資料>, end='')
	  無換行
- int(<字串>)
  字串轉數字
- chr(<ASCII>)
  ASCII轉char
- Pwn
	- from pwn import *
	  導入pwn函式庫
	- r = remote('<IP>', <Port>)
	  連線指令 ‘r‘ 為連線物件
	-
	- 注意需decode()！
	  r.recvline() 
	  抄收一行
	  r.recvlines(<行數>)
	  抄收指令行數
	  r.recvuntil(<字串>)
	  抄收直到指定字串
	-
	- 注意需encode()！
	  r.send(<字串>)
	  發送字串
	  r.sendline(<字串>)
	  發送字串代\n
	-
	-