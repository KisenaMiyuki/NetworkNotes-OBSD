# Concurrent Servers
服务器为了同时给多个客户端提供服务会采用多线程，这种也叫做**Concurrent Servers**。

这里服务器会分为Main Thread和Handler，Main Thread负责接待客户端的请求并创建Handler thread来为客户端提供服务。

> 例如银行一般都有大堂经理（Main Thread）来指引你到一个柜台（Handler thread）办理业务。