- print(<資料>)
  印出資料
	- print(<資料>, end='')
	  無換行
- open(<路徑>,  <開啟方法>)
  建立一個檔案物件
	- 開啟方法有r, rb, w, w+等
		- 常用r和w+，一個為只讀，一個為可讀可寫
- 資料型別
	- chr(<ASCII>)
	  ASCII轉char
	- int(<字串>)
	  字串轉數字
	- ord(<字元>)
	  char轉ASCII
	- str 字串
		- len(<字串>)
		  回傳字串長度
		- strip(<字元>)
		  刪除特定的字元
		- 裁切使用str = str[<啟始位置>:<結束位置>]
			- 結束位置會自動-1，因此使用len時不需在-1
<<<<<<< HEAD
=======
	- int(<字串>)
	  回傳字串轉數字
	- chr(<ASCII>)
	  回傳ASCII轉char
>>>>>>> 42ec4889e885b09864aa2121f9bc9baefc4a3f4a
- 流程控制
	- for
		- 計數使用 range(<範圍>)
- Pwn
	- from pwn import *
	  導入pwn函式庫
	- r = remote('<IP>', <Port>)
	  連線指令 ‘r‘ 為連線物件
	- 注意需decode()！
	  r.recvline() 
	  抄收一行，並回傳其值
	  r.recvlines(<行數>)
	  抄收指定行數，並回傳其值
	  r.recvuntil(<字串>)
	  抄收直到指定字串，並回傳其值
	- 注意需encode()！
	  r.send(<字串>)
	  發送字串
	  r.sendline(<字串>)
	  發送字串代\\n
- Hash
	- import hashlib
	  導入hashlib 函式庫
	- md5
		- m = hashlib.md5()
		  建立一個md5 hash物件
		- m.update(<字串>)
		  更新物件值
		  m.hexdigest()
		  回傳雜湊值