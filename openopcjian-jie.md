        OpenOPC通过安装zzzOpenOPCService服务，允许远程的TCP/IP链接传输OPC数据，从而越过DCOM来访问远程OPC服务器。这个网关协议将会安装在OPC服务器上，只要确保网关协议拥有正确的权限来访问本机上的OPC服务器就可以了。

        OpenOPC实现opcclient在opcserver上读取和写入数据\(opc.read\(item\),opc.write\(\[item,value\]\)\)

