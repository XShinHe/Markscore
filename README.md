# Markscore
A notation format of music scores and tabs in line text.

## 基础记号

```
节拍：
C--- 	全音符
C- 	二分之一音符
C	四分之一音符
C;	八分之一音符
C;;	十六分之一音符
C;;;	三十二分之一音符
.	附点音符

音符
音符与音符可以直接连接、推荐使用空格或Tab
单音符：
	绝对记号：
	\1C \1D \1E \1F \1G \1A \1B … \5C \5D \5E \5F \5G \5A \5B
	相对音：居中的：C D E D G A B
		升一个八度：^C ^D ^E ^F ^G ^A ^B => ^2C
		降一个八度：_C _D _E _F _G _A _B => _2C
	升半音：C'
	降半音：C,
	
多音符：()组合符号，[]追加符号（对于数字音程可以省略）
和弦缩写
C和弦	{Cmaj}{CEG}	说明Cmaj，对应的音为C、E、G，对应音程(1省略)一度、小三度、五度
	C[EG]
	C[3'5]
	C3'5
```
