# 1. 可以调节行间距的文字Demo效果 #
![](http://i.imgur.com/zSIGtGL.png)
# 2. gridView的单选和多选的联动效果 #
![](http://i.imgur.com/4HPuDnx.png)

> * 上面的条目只可以是单选的，下面的可以单选
> * 上面的选择状态变化，下面的会跟随清除






# 3. 使用ZXing的扫码效果 #
![](http://i.imgur.com/Cizh2qr.png)


<h2>下面的是ZXing中相应的效果设置<h2>


	 <cn.bingoogolapple.qrcode.zxing.ZXingView
	        android:id="@+id/zxingview" 
	        style="@style/MatchMatch"       //设置布局，匹配父元素
	        app:qrcv_animTime="1000"		//动画的执行时间
	        app:qrcv_barCodeTipText="将条码放入框内，即可自动扫描"  //扫码上方的文字
	        app:qrcv_barcodeRectHeight="180dp"					 //扫码框的高度
	        app:qrcv_borderColor="@android:color/white"			 //扫码边框的颜色
	        app:qrcv_borderSize="1dp"							 //扫码框的宽度
	        app:qrcv_cornerColor="@color/colorPrimaryDark"		 //扫码框的边角颜色
	        app:qrcv_cornerLength="20dp"						 //扫码框的长度
	        app:qrcv_cornerSize="3dp"							 //扫码框的宽度
	        app:qrcv_isBarcode="false"							 //扫码框是不是条码样式
	        app:qrcv_isScanLineReverse="true"					 //扫码框是不是带有条码背景
	        app:qrcv_isShowDefaultGridScanLineDrawable="true"	 //扫码框默认的网格样式
	        app:qrcv_isShowDefaultScanLineDrawable="false"		 //扫码框默认的线型
	        app:qrcv_isShowTipBackground="true"					 //
	        app:qrcv_isShowTipTextAsSingleLine="false"			 //
	        app:qrcv_isTipTextBelowRect="false"					 //
	        app:qrcv_maskColor="#99000000"						 //外周围蒙版色
	        app:qrcv_qrCodeTipText="将二维码/条码放入框内，即可自动扫描"     //提示文字
	        app:qrcv_rectWidth="280dp"							 //扫码框的宽度
	        app:qrcv_scanLineColor="@color/colorPrimaryDark"	 //扫描线的颜色
	        app:qrcv_scanLineMargin="0dp"						 // 
	        app:qrcv_scanLineSize="1dp"							 //扫码线的宽度	
	        app:qrcv_tipTextColor="@android:color/white"		 //提示文字的颜色
	        app:qrcv_tipTextSize="12sp"							 //提示文字的大小
	        app:qrcv_toolbarHeight="56dp"						 //上面的遮挡色块高度
	        app:qrcv_topOffset="90dp" />						 //顶边距