/*报文格式：8位长度$响应码$Tuxedo交易码$数据包$
   	    包头：  8位长度,不足时左补零
   	    包体：  $响应码$Tuxedo交易码$数据包$
   	    长度:   包体长度
   	    响应码: 0 通讯成功 1超时 2 tuxedo通讯失败 默认填9
*/
