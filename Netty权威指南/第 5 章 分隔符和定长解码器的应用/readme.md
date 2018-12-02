##

TCP以流的方式进行数据传输，上层应用协议为了对消息进行区分，通常采用以下4中方式：

	消息长度固定，累计读取到长度综合为定长LEN的报文后，就认为读取到了一个完整的消息，将计数器置位，重新开始读取下一个数据报；
	将回车换行符作为消息结束符，例如FTP协议，这种方式在文本协议中应用比较广泛；
	将特殊的分隔符作为消息的结束标志，回车换行符就是一种特殊的分隔符；
	通过在消息头中定义长度字段来标识消息的总长度。
## DelimiterBasedFrameDecoder应用开发

### DelimiterBasedFrameDecoder服务端开发

### DelimiterBasedFrameDecoder客户端开发

### 运行DelimiterBasedFrameDecoder服务端和客户端程序

## FixedLengthFrameDecoder应用开发

### FixedLengthFrameDecoder服务端开发

### 利用telnet命令行测试EchoServer服务端

## 总结