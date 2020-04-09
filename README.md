# sm4-
sm4国密
blob_size = sm4_context_decrypt(bind_blob,&blob,bind_blob_size,brute_pass);
bind_blod,bind_blob_size:加密的数据块及其尺寸
brute_pass:口令
blob_size:解密数据块长度
序列化：内存数据结构转化为数据流（二进制流或者字符串流）
反序列化：数据流转化为数据结构 
序列化以后数据才能加密、存储、网络传输
序列化的数据需要在内存中使用，一般需要反序列化处理
一般容易定位的数据，不需要反序列化也可以访问
